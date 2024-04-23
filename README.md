# Travel Sentinel: Empowering Safe Journeys with Personalized Travel Safety Alerts

## Authors
- Anupma Pandey (anupma23019@iiitd.ac.in)
- Dhananjay Sharma (dhananjay23033@iiitd.ac.in)
- Megha (megha23125@iiitd.ac.in)
- Parichay Madnani (parichay23054@iiitd.ac.in)
- Ritik Chhatwani (ritik23076@iiitd.ac.in)
- Ummeed Sinha (ummeed23101@iiitd.ac.in)

## 1. Problem Statement

There is a lack of readily accessible and comprehensive travel safety information for individuals planning or undertaking journeys. Travelers often face uncertainty on potential risks due to unpredictable weather conditions, unforeseen events, and limited access to up-to-date news and alerts relevant to their locations. This lack of real-time information can lead to compromised safety, inconvenience, and potentially hazardous situations while traveling, and it often overlooks the importance of enhancing users' travel experiences by highlighting opportunities for exploration and enjoyment. Therefore, an application is needed to consolidate and deliver timely updates empowering users to make informed decisions and take proactive measures to ensure their safety, enjoyment, and well-being during travel.

## 2. Background Motivation

The paper [1] talks about challenges faced by tourists in terms of advanced facilities, including a comprehensive warning system, precise and timely weather and safety information. There’s a lack of physical, individual, societal, and psychological safety information. This paper demands to develop a feature-rich mobile application providing all such vital information, specifically for tourist safety in warm and humid destinations. But this can be generalized to all kinds of destinations. Also, no such application is available for use/download on any application store/web.

### 2.1 Significance

- **Unexpected Events**: Natural disasters, political unrest, or unexpected events can occur in any location. Tourists may need help navigating these situations, and it can disrupt their travel plans.
- **Lack of Local Knowledge**: Tourists may not be aware of local customs, traditions, or local norms, which could lead to unintentional disrespect or misunderstanding.
- **Health and Medical Services**: Accessing healthcare services in an unfamiliar location may take time and effort. Understanding local medical facilities, obtaining necessary medications, or dealing with health issues can be stressful.
- **Safety Concerns**: Tourists might not be aware of local safety issues or areas to avoid. This lack of awareness can make them more susceptible to scams, theft, or other security-related concerns.
- **Cultural & Linguistic Differences**: Tourists may encounter cultural practices, norms, and etiquette that differ significantly from their own. Misunderstanding these cultural aspects can lead to unintentional disrespect or uncomfortable situations.

## 3. Proposed Approach & Methodology: Developing a Comprehensive Travel Safety Alert System

We propose a personalized application for individuals containing recent updates of their desired trip destination stating the current incidents, festivals, temperature, health recommendations, and many more details about their trip location. We tend to solve it by scraping the web (Apify API) for the information, classifying the search information, and giving it to the user in a simplified format for quick details of do’s and don'ts regarding that trip location. The do’s and don’ts would be classified by Sentiment analysis(Hugging face machine learning models)  on the data received by web scraping.

## 4. Novelty

The application would provide the following services:

- **Real-time Updates**: Destination-specific weather forecasts, unexpected happenings(Natural disasters, political unrest, etc.), Special events not to miss(concerts, festival celebrations, etc.)
- **Up-to-date News and Alerts**: Local news feeds(on crimes), Travel advisories, Safety tips and Resources
- **Health and Medical Services**: Emergency medical services

## 5. Metrics

- **Usability Testing**: Conducting usability testing sessions with a diverse group of users to assess the effectiveness and user-friendliness of the application interface. Gathering feedback on ease of navigation, clarity of safety alerts, and overall user experience.
- **Performance Testing**: Measuring the performance of the app in terms of response time for delivering safety alerts, accuracy of weather updates, and reliability of push notifications.
- **Accuracy Assessment**: Validating the accuracy of safety alerts and weather forecasts by comparing them with real-world data from reputable sources. Calculating metrics such as precision, recall, and F1-score, confusion matrix to quantify the app's accuracy in predicting safety risks.

## 6. Contributions:

- **Backend**: Parichay Madnani
- **Badminton**: Ritik Chhatwani
- **Frontend**: Ummeed Sinha
- **Web Scraping & API Implementation**: Dhananjay Sharma
- **Machine Learning(Sentiment Analysis)** : Megha, Anupma Pandey
- **Report**: Anupma, Dhananjay, Megha, Parichay, Ritik, Ummeed

## 7. References

[1] Dinkoksung, S.; Pitakaso, R.; Boonmee, C.; Srichok, T.; Khonjun, S.; Jirasirilerd, G.; Songkaphet, P.; Nanthasamroeng, N. A Mobile Solution for Enhancing Tourist Safety in Warm and Humid Destinations. Appl. Sci. 2023, 13, 9027. [Link](https://doi.org/10.3390/app13159027)

[2] Akter, Nadia & Newaz, Anisa Bente & Shakara, Amathul Hadi & Al-Mamun, Md. (2017). A Mobile Based Application for Journey Safety. IOSR Journal of Computer Engineering. 19. 39-45. [Link](10.9790/0661-1901023945)

[3] Țuclea, C.-E.; Vrânceanu, D.-M.; Năstase, C.-E. The Role of Social Media in Health Safety Evaluation of a Tourism Destination throughout the Travel Planning Process. Sustainability 2020, 12, 6661. [Link](https://doi.org/10.3390/su12166661)

[4]R. Sham et al., "An improved travel safety for urban commuters using an iTracks system," 2013 IEEE 3rd International Conference on System Engineering and Technology, Shah Alam, Malaysia, 2013, pp. 365-368, [Link](doi: 10.1109/ICSEngT.2013.6650201)

[5] Helai Huang, Yulu Wei, Chunyang Han, Jaeyoung Lee, Suyi Mao, Fan Gao, Travel route safety estimation based on conflict simulation, Accident Analysis 

## How to Run this Project

Install the required dependencies using pip package: 
  	pip install <package name>
	1. selenium
	2. pysentimiento
	3. webdriver_manager
	4. opencage

Once the packages are installed, in the working directory serve the flask file "app.py"

	python app.py #highlight

When the server finishes setting up with a message Running on localhost:port, click the link to start seeing the working app
