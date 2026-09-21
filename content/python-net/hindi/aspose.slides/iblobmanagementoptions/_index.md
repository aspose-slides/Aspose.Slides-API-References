---
title: IBlobManagementOptions class
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions क्लास

एक बाइनरी बड़ा ऑब्जेक्ट (BLOB) बाइनरी डेटा है जो एक ही इकाई के रूप में संग्रहीत होता है - यानी BLOB ऑडियो, वीडियो या प्रस्तुति स्वयं हो सकता है। 
            एक संख्या में तकनीकों का उपयोग मेमोरी उपयोग को अनुकूलित करने के लिए किया जाता है 
            जब BLOBs के साथ काम किया जाता है - जो पहले से प्रस्तुति में संग्रहीत था या प्रोग्रामेटिक रूप से बाद में जोड़ा जा सकता है। 
            [`IBlobManagementOptions`](/slides/python-net/hi/aspose.slides/iblobmanagementoptions) का उपयोग करके आप [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) इंस्टेंस जीवनकाल के लिए BLOBs हैंडलिंग से संबंधित विभिन्न व्यवहार पहलुओं को बदल सकते हैं। 

IBlobManagementOptions प्रकार निम्नलिखित सदस्यों को प्रदर्शित करता है:

## गुण

| Property | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/hi/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | यह प्रॉपर्टी निर्धारित करती है कि Presentation क्लास का एक उदाहरण स्रोत - फ़ाइल <br/>            या स्ट्रीम का मालिक हो सकता है या नहीं, इंस्टेंस जीवनकाल के दौरान। यदि उदाहरण मालिक है, तो यह स्रोत को लॉक कर देता है। यह मदद करता है <br/>            मेमोरी उपयोग और प्रदर्शन को सुधारने में जब BLOBs के साथ काम किया जाता है, लेकिन स्रोत (स्ट्रीम या फ़ाइल) <br/>            को Presentation के इंस्टेंस जीवनकाल के दौरान बदला नहीं जा सकता। यह एक उदाहरण है: |
| [`is_temporary_files_allowed`](/slides/python-net/hi/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | यह प्रॉपर्टी निर्धारित करती है कि BLOBs के साथ काम करने के दौरान अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जो मेमोरी उपयोग को काफी <br/>            कम करती है लेकिन फ़ाइलें बनाने के लिए अनुमति की आवश्यकता होती है।<br/>            सभी फ़ाइलों को प्रस्तुतिकरण के साथ काम समाप्त होने के बाद हटा दिया जाएगा। |
| [`temp_files_root_path`](/slides/python-net/hi/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | अस्थायी फ़ाइलों के निर्माण की मूल पथ। डिफ़ॉल्ट रूप से सिस्टम अस्थायी निर्देशिका उपयोग की जाएगी। <br/>            होस्टिंग प्रक्रिया को वहाँ फ़ाइलें और फ़ोल्डर बनाने की अनुमति होनी चाहिए। |
| [`max_blobs_bytes_in_memory`](/slides/python-net/hi/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | सभी BLOBs द्वारा मेमोरी में ली जा सकने वाले अधिकतम कुल आकार (बाइट्स में) को निर्धारित करता है। डिफ़ॉल्ट रूप से, सभी BLOBs<br/>            मेमोरी में लोड हो जाते हैं; केवल जब यह सीमा पहुँच जाती है तब वैकल्पिक तंत्र (जैसे अस्थायी<br/>            फ़ाइलें) उपयोग किए जाते हैं। BLOBs को मेमोरी में रखने से प्रदर्शन अधिकतम होता है लेकिन उच्च मेमोरी उपयोग हो सकता है। इस प्रॉपर्टी का उपयोग करके आप अपने पर्यावरण या आवश्यकताओं के अनुसार व्यवहार को अनुकूलित कर सकते हैं। |


### संबंधित देखें
* क्लास [`IBlobManagementOptions`](/slides/python-net/hi/aspose.slides/iblobmanagementoptions)
* क्लास [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)