---
title: insert_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

### Returns
नया बनाया गया [`IOleObjectFrame`](/slides/python-net/hi/aspose.slides/ioleobjectframe)।

```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | शून्य-आधारित इंडेक्स जहाँ OLE ऑब्जेक्ट फ्रेम सम्मिलित किया जाता है। |
| x | **float** | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo) | संलग्न OLE डेटा जानकारी ([`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo))। |

## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
एक नया OLE ऑब्जेक्ट फ्रेम बनाता है और इसे निर्दिष्ट इंडेक्स पर shape संग्रह में सम्मिलित करता है।

### Returns
नया बनाया गया OLE ऑब्जेक्ट फ्रेम।

```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | शून्य-आधारित इंडेक्स जहाँ OLE ऑब्जेक्ट फ्रेम सम्मिलित किया जाता है। |
| x | **float** | नए OLE फ्रेम का x-निर्देशांक, पॉइंट्स में। |
| y | **float** | नए OLE फ्रेम का y-निर्देशांक, पॉइंट्स में। |
| width | **float** | नए OLE फ्रेम की चौड़ाई, पॉइंट्स में। |
| height | **float** | नए OLE फ्रेम की ऊँचाई, पॉइंट्स में। |
| class_name | **str** | OLE ऑब्जेक्ट का क्लास नाम। |
| path | **str** | लिंक्ड फ़ाइल का पथ। <br/><br/>यह पथ प्रस्तुति में जैसा है वैसा ही संग्रहीत किया जाता है।<br/><br/>यदि सापेक्ष पथ निर्दिष्ट किया गया है, तो फ़ाइल विभिन्न निर्देशिका से प्रस्तुति खोलते समय असुलभ होगी। |

### See Also
* क्लास [`IOleEmbeddedDataInfo`](/slides/python-net/hi/aspose.slides/ioleembeddeddatainfo)
* क्लास [`IOleObjectFrame`](/slides/python-net/hi/aspose.slides/ioleobjectframe)
* क्लास [`ShapeCollection`](/slides/python-net/hi/aspose.slides/shapecollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)