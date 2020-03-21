# Preface

The main objective of this thesis is to gather the general sentiment of visitors in Athens by exploiting tourism content shared on online platforms. The idea comprises the study of real data about tourism, the discovery of sentiment and insights from them and finally, their visualization. The steps of the research include the data collection (reviews/posts), the data preprocessing and transformation and the algorithms’ application (i.e. topic modeling and sentiment analysis algorithms) on the refined data. A combination of tools and algorithms is used in order to intersect the output and to approach more realistic results. Finally, the outcome is visualised with diagrams and maps. The graphs provide answers to a series of questions and depict the satisfaction of visitors in Athens.

# Dev environment and Tools
The project is implemented on Python 3.7.3  with the use of python libraries. Google Places, python-twitter and foursquare are wrappers that provide a pure Python interface for the corresponding APIs. During the preprocessing stage, [langdetect](https://pypi.org/project/langdetect/), [ast](https://docs.python.org/3/library/ast.html), [re](https://docs.python.org/3/library/re.html), [stop_words](https://pypi.org/project/stop-words/) and [nltk](https://www.nltk.org/) libraries eliminate non-english and redundant elements. As far as algorithms are concerned, topic modeling utilises [gensim](https://pypi.org/project/gensim/) modules and sentiment analysis combines  [nltk.sentiment.vader](https://www.nltk.org/_modules/nltk/sentiment/vader.html) (ready sentiment analysis tool) and [sklearn](https://scikit-learn.org/stable/index.html) (library with custom vectorizers and classifiers). A library of offline reverse geocoding ([reverse_geocoder](https://github.com/thampiman/reverse-geocoder))  and a service that uses third-party geocoders ([geopy](https://github.com/geopy/geopy)) are responsible for the conversion of coordinates to districts. The third-party geocoder in this case is [Nominatim](https://nominatim.openstreetmap.org/), a geocoder for open source OpenStreetMap data. The visualization process is also achieved using python libraries. A word cloud generator ([word_cloud](https://github.com/amueller/word_cloud)), a data visualization library ([seaborn](https://seaborn.pydata.org/)), a tool that creates JS Leaflet maps ([folium](https://python-visualization.github.io/folium/)) and a 2D plotting library ([matplotlib](https://matplotlib.org/)) are used to form the diagrams and the plots.
Despite the essential components, many helping functions and modules were used. [CSV](https://docs.python.org/3/library/csv.html), [JSON](https://docs.python.org/3/library/json.html) and [pickle](https://docs.python.org/3/library/pickle.html) libraries manage the generated files, while [pandas](https://pandas.pydata.org/docs/user_guide/index.html), [collections](https://docs.python.org/3/library/collections.html) and [operator](https://docs.python.org/3.4/library/operator.html) handle the data structures. Python system libraries (sys, os, time) complete the project’s environment. 


_The current thesis was conducted at the Department of Informatics and Telecommunications of the National and Kapodistrian University of Athens from May 2019 to February 2020 and was supervised by Assistant Professor Maria Roussou and Instructional Lab. Personnel Ms. Athanasia Kolovou._
