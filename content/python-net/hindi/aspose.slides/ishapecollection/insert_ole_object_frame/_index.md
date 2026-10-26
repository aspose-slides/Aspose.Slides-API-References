---
title: insert_ole_object_frame method
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर शेप कलेक्शन में इसे सम्मिलित करता है।

### वापसी मान

नव निर्मित [`IOleObjectFrame`](/slides/python-net/hi/aspose.slides/ioleobjectframe)।

```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | शून्य-आधारित इंडेक्स जहाँ OLE ऑब्जेक्ट फ्रेम को सम्मिलित किया जाएगा। |
| x | **float** | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo) | एम्बेडेड OLE डेटा सूचना ([`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo))। |

## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और निर्दिष्ट इंडेक्स पर शेप कलेक्शन में इसे सम्मिलित करता है।

### वापसी मान

नव निर्मित [`IOleObjectFrame`](/slides/python-net/hi/aspose.slides/ioleobjectframe)।

```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | शून्य-आधारित इंडेक्स जहाँ OLE ऑब्जेक्ट फ्रेम को सम्मिलित किया जाएगा। |
| x | **float** | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| class_name | **str** | OLE ऑब्जेक्ट का क्लास नाम। |
| path | **str** | लिंक्ड फ़ाइल का पथ। <br/><br/>यह पथ प्रस्तुति में जैसा है वैसा संग्रहीत किया जाता है।<br/><br/>यदि रिलेटिव पथ निर्दिष्ट किया जाता है, तो जब प्रस्तुति को किसी अलग डिरेक्टरी से खोलेंगे तो फ़ाइल अप्राप्य होगी। |

### देखें भी
* class [`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo)
* class [`IOleObjectFrame`](/slides/python-net/hi/aspose.slides/ioleobjectframe)
* class [`IShapeCollection`](/slides/python-net/hi/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)