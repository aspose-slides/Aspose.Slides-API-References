---
title: add_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है।

### रिटर्न
नया बनाया गया [`IOleObjectFrame`](/slides/python-net/hi/aspose.slides/ioleobjectframe)।

```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | **float** | नया OLE फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | **float** | नया OLE फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |
| width | **float** | नया OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नया OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo) | एम्बेडेड OLE डेटा जानकारी ([`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo))। |

## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे शेप संग्रह के अंत में जोड़ता है।

### रिटर्न
नया बनाया गया [`IOleObjectFrame`](/slides/python-net/hi/aspose.slides/ioleobjectframe)।

```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | **float** | नया OLE फ्रेम का x-कोऑर्डिनेट, पॉइंट्स में। |
| y | **float** | नया OLE फ्रेम का y-कोऑर्डिनेट, पॉइंट्स में। |
| width | **float** | नया OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नया OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| class_name | **str** | OLE ऑब्जेक्ट का क्लास नाम। |
| path | **str** | लिंक्ड फ़ाइल का पथ। <br/><br/>यह पथ प्रस्तुति में वैसा ही संग्रहीत किया जाता है।<br/><br/>यदि एक सापेक्ष पथ निर्दिष्ट किया गया है, तो फ़ाइल विभिन्न निर्देशिका से प्रस्तुति खोलने पर पहुँच योग्य नहीं होगी। |

### देखें
* class [`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo)
* class [`IOleObjectFrame`](/slides/python-net/hi/aspose.slides/ioleobjectframe)
* class [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)