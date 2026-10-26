---
title: get_object_storing_location method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
ऑब्जेक्ट को कहाँ संग्रहीत किया जाना चाहिए, यह निर्धारित करता है।  
यह मेथड प्रत्येक ऑब्जेक्ट id के लिए एक बार बुलाया जाता है।  
यह गारंटी नहीं दी जा सकती कि समान डेटा, semanticName और contentType वाले दो ऑब्जेक्ट नहीं होंगे, लेकिन अलग id हो सकते हैं।

### रिटर्न

निर्णय



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| id | **int** | ऑब्जेक्ट id। यह id संचालन-व्यापी अद्वितीय है। |
| entity_data | **bytes** | ऑब्जेक्ट बाइनरी डेटा। यह पैरामीटर None हो सकता है, यदि ऑब्जेक्ट बाइनरी डेटा अभी तक उत्पन्न नहीं हुआ है। |
| semantic_name | **str** | ऑब्जेक्ट का अर्थ वर्णित करने वाला कुछ छोटा पाठ। Controller इसको बाहरी ऑब्जेक्ट नाम के हिस्से के रूप में उपयोग कर सकता है, लेकिन यह dispatcher पर निर्भर करता है कि नाम अद्वितीय हों और केवल अनुमत अक्षरों को शामिल करें। |
| content_type | **str** | ऑब्जेक्ट का MIME प्रकार। |
| recomended_extension | **str** | फ़ाइल नाम एक्सटेंशन, इस MIME प्रकार के लिए अनुशंसित। |



### देखें
* क्लास [`ILinkEmbedController`](/slides/python-net/hi/aspose.slides.export/ilinkembedcontroller)
* एन्युमरेशन [`LinkEmbedDecision`](/slides/python-net/hi/aspose.slides.export/linkembeddecision)
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)