---
title: ILinkEmbedController class
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController क्लास

सेविंग के दौरान ऑब्जेक्ट को कैसे प्रोसेस किया जाना चाहिए, यह निर्धारित करने के लिए उपयोग किया जाने वाला कॉलबैक इंटरफ़ेस।

ILinkEmbedController प्रकार निम्नलिखित सदस्य उजागर करता है:

## विधियां

| मेथड | विवरण |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/hi/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | निर्धारित करता है कि ऑब्जेक्ट कहां संग्रहीत किया जाना चाहिए।<br/>            यह मेथड प्रत्येक ऑब्जेक्ट आईडी के लिए एक बार कॉल किया जाता है।<br/>            यह गारंटी नहीं देता कि समान डेटा, semanticName और contentType वाले दो ऑब्जेक्ट्स अलग-अलग आईडी के साथ नहीं होंगे। |
| [`get_url(self, id, referrer)`](/slides/python-net/hi/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | एक बाहरी ऑब्जेक्ट के लिए URL लौटाता है।<br/>            यह मेथड तभी हमेशा कॉल किया जाता है जब **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** ने [`LinkEmbedDecision.LINK`](/slides/python-net/hi/aspose.slides.export/linkembeddecision/LINK) लौटाया हो और जब **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** ने [`LinkEmbedDecision.EMBED`](/slides/python-net/hi/aspose.slides.export/linkembeddecision/EMBED) लौटाया हो लेकिन एम्बेडिंग असम्भव है।<br/>            इसे उसी ऑब्जेक्ट आईडी के लिए कई बार कॉल किया जा सकता है। |
| [`save_external(self, id, entity_data)`](/slides/python-net/hi/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | बाहरी ऑब्जेक्ट को सहेजता है। |


### देखें
* मॉड्यूल [`aspose.slides.export`](/slides/python-net/hi/aspose.slides.export)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)