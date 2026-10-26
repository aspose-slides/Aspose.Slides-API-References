---
title: BlobManagementOptions class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions क्लास

BLOB हैंडलिंग नियमों और अन्य BLOB सेटिंग्स को प्रबंधित करने के लिए उपयोग किए जा सकने वाले विकल्पों का प्रतिनिधित्व करता है।

BlobManagementOptions प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## निर्माता

| निर्माता | विवरण |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hi/aspose.slides/blobmanagementoptions/__init__/#) | नया डिफ़ॉल्ट ब्लॉब प्रबंधन विकल्प बनाता है। |

## गुण

| गुण | विवरण |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/hi/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | यह गुण निर्धारित करता है कि Presentation क्लास का एक उदाहरण स्रोत-फ़ाइल <br/>            या स्ट्रीम का मालिक हो सकता है या नहीं, उदाहरण के जीवनकाल के दौरान। यदि उदाहरण मालिक है, तो यह स्रोत को लॉक कर देता है। यह BLOBs के साथ काम करते समय मेमोरी खपत और प्रदर्शन को सुधारने में मदद करता है, लेकिन प्रस्तुति के उदाहरण के जीवनकाल के दौरान स्रोत (स्ट्रीम या फ़ाइल) को बदला नहीं जा सकता। |
| [`is_temporary_files_allowed`](/slides/python-net/hi/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | यह गुण निर्धारित करता है कि BLOBs के साथ काम करते समय अस्थायी फ़ाइलें बनाई जा सकती हैं या नहीं, जो मेमोरी खपत को काफी घटाता है लेकिन फ़ाइलें बनाने की अनुमति की आवश्यकता होती है।<br/>            सभी फ़ाइलें प्रस्तुति के साथ कार्य समाप्त होने के बाद हटा दी जाएंगी। |
| [`temp_files_root_path`](/slides/python-net/hi/aspose.slides/blobmanagementoptions/temp_files_root_path/) | वह मूल पथ जहाँ अस्थायी फ़ाइलें बनाई जाएँगी। डिफ़ॉल्ट रूप से सिस्टम अस्थायी निर्देशिका उपयोग की जाएगी। <br/>            होस्टिंग प्रक्रिया के पास वहाँ फ़ाइलें और फ़ोल्डर बनाने की अनुमति होनी चाहिए। |
| [`max_blobs_bytes_in_memory`](/slides/python-net/hi/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | मेमोरी में सभी BLOBs द्वारा कब्जा किया जा सकने वाला अधिकतम कुल आकार (बाइट्स में) निर्धारित करता है। डिफ़ॉल्ट रूप से, सभी BLOBs मेमोरी में लोड होते हैं; केवल जब यह सीमा पहुँच जाती है तो वैकल्पिक तंत्र (जैसे अस्थायी फ़ाइलें) प्रयोग में लाए जाते हैं। BLOBs को मेमोरी में रखने से प्रदर्शन अधिकतम होता है लेकिन उच्च मेमोरी उपयोग हो सकता है। इस गुण का उपयोग अपने वातावरण या आवश्यकताओं के अनुसार व्यवहार को अनुकूलित करने के लिए करें। |


### संबंधित देखें
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)