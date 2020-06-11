# IN A NUTSHELL
In our everyday lives it is common to be faced with the need to summarize information. Whether we are studying for a test, trying to catch up with news, or reading blogs and articles on the internet it would be very helpful if we could compress all that information into just a few paragraphs without losing meaning or context. Furthermore, with all the information we are overwhelmed with on a daily basis, we would find a summarizing tool to be valuable in helping us grasp the gist of huge source of text.

 Nutshell is a mobile application that leverages on device machine learning to accurately summarize information. Users can import a document or copy paste text into the Nutshell text summarizer and the app will deliver an accurate summary in a compressed form.
With support of over 100 languages, Nutshell helps you shorten a set of paragraphs to the most relevant sentences containing key points you should be aware of. It is as simple as it sounds, copy text from your favorite source or copy the link directly, open the app and start reading!
All summarization happens on-device and doesn't require internet access, unless you're using the link to summarize, then you need internet just to get the text.

The app uses abstractive summary to achieve its goals. Firstly, we will perform data processing which will aid in filtering unnecessary characters or sentences from the data set, tokenizing articles into words and creating word embedding’s using Tensorflow lite to represent the words in a numeric manner. The architecture of the model will involve a sequence to sequence model which is available on Tensor flow lite. The data will then be trained and tested on google cloud AI platform.

<img src="images/nutshell.PNG" width=200 height =300>     <img src="images/Screenshot_2019-12-03-01-32-26.png" width=200 height =300>             <img src="images/summary.PNG" width=200 height =300>




