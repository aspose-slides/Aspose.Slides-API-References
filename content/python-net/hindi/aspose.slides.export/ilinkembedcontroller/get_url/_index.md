---
title: get_url method
second_title: Aspose.Slides Python के लिए .NET API रेफ़रेंस
description: 
type: docs
url: /hi/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
बाहरी वस्तु के लिए एक URL लौटाता है।
            यह विधि हमेशा तब कॉल की जाती है जब **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** ने [`LinkEmbedDecision.LINK`](/slides/python-net/hi/aspose.slides.export/linkembeddecision/LINK) लौटाया हो और जब **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** ने [`LinkEmbedDecision.EMBED`](/slides/python-net/hi/aspose.slides.export/linkembeddecision/EMBED) लौटाया हो तब भी कॉल की जा सकती है लेकिन एम्बेडिंग असम्भव है।
            इसे समान वस्तु id के लिए कई बार कॉल किया जा सकता है।

### Returns

बाहरी वस्तु का Url या None यदि इस वस्तु को अनदेखा किया जाना चाहिए।



```python
def get_url(self, id, referrer):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| id | **int** | वस्तु id। यह id संचालन-व्यापी अद्वितीय है। |
| referrer | **int** | संदर्भ देने वाली वस्तु का id या 0, यदि वस्तु मूल दस्तावेज़ द्वारा संदर्भित है। सापेक्ष लिंक बनाने के लिए उपयोग किया जा सकता है। |



### देखें
* क्लास [`ILinkEmbedController`](/slides/python-net/hi/aspose.slides.export/ilinkembedcontroller)
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)