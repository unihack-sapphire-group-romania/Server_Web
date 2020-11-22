# COVID-Z

# Inspiration
Like most people in the world right now, we are genuinely concerned about COVID-19. One of the biggest problems with this new virus is the fact that it's impossible to know if you are infected without a test, and that “not knowing” is what makes this situation so scary for most of the people. COVID-19 tests are difficult to find because they are simply not enough and cannot be manufactured quickly enough, which is causing panic. Due to this fact, we will have to rely on other diagnostic techniques.

In order to solve this problem we thought about using X-Ray images as doctors frequently use X-rays and CT scans to diagnose pneumonia, lung inflammation, abscesses, etc. Since this virus attacks our respiratory tract, we can use X-rays to analyze the health of a patient’s lungs. And given that most of the hospitals have X-Ray imaging machines, it could be possible to use X-rays to diagnose COVID-19 without the dedicated test kits. A disadvantage is that the analysis of X-Ray images requires a radiology expert and takes significant time.

Here comes our possible solution namely the development of an automated analysis system based on artificial intelligence that can save medical professionals valuable time.

As the number of cases has grown very rapidly lately, the authorities have been taken by surprise, which has led to the overcrowding of hospitals. To prevent this in the future, our platform also provides future cases predictions in each county based on previous data from datelazi.ro

We choose to develop this app only for Romania because we couldn't find something similar for our country and we believe that it will really help in the current situation.

# What it does
The system consists of an web application in which the doctor uploads the patient's X-ray and the artificial intelligence algorithm from behind returns a percentage that refers to the patient's condition (infected or healthy).

The website also shows realtime statistics about the pandemic in Romania, a future cases forecast and provides useful information for prevention and protection against the virus.

# How we built it
Front-end: HTML, CSS, Javascript, Boostrap 
Back-end: Python Flask
Machine learning: Tensorflow and Keras frameworks
