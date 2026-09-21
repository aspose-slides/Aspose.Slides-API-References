---
title: add_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

### रिटर्न मान

नव निर्मित [`IOleObjectFrame`](/slides/python-net/hi/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| परामीटर | टाइप | विवरण |
| :- | :- | :- |
| x | **float** | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo) | एम्बेडेड OLE डेटा ([`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo)) के बारे में जानकारी। |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे आकार संग्रह के अंत में जोड़ता है।

### रिटर्न मान

नव निर्मित [`IOleObjectFrame`](/slides/python-net/hi/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| परामीटर | टाइप | विवरण |
| :- | :- | :- |
| x | **float** | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| class_name | **str** | OLE ऑब्जेक्ट का क्लास नाम। |
| path | **str** | लिंक्ड फ़ाइल का पथ। <br/><br/>यह पथ प्रस्तुति में जैसा का जैसा संग्रहीत किया जाता है।<br/><br/>यदि एक रिलेटिव पथ निर्दिष्ट किया जाता है, तो विभिन्न डायरेक्टरी से प्रस्तुति खोलने पर फ़ाइल अभिगम्य नहीं रहेगी। |



### संबंधित देखें
* क्लास [`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo)
* क्लास [`IOleObjectFrame`](/slides/python-net/hi/aspose.slides/ioleobjectframe)
* क्लास [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)