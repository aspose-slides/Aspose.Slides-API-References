---
title: remove_node method
second_title: Aspose.Slides for Python के लिए .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
इंडेक्स द्वारा नोड या उप-नोड हटाएँ।

```python
def remove_node(self, index):
    ...
```

| परिमाप | प्रकार | विवरण |
| :- | :- | :- |
| index | **int** | नोड का शून्य-आधारित इंडेक्स |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | इंडेक्स 0 से कम है। -या- इंडेक्स sibling की गणना के बराबर या उससे अधिक है। |

## remove_node(self, node_obj) {#ismartartnode}
नोड या उप-नोड हटाएँ।

```python
def remove_node(self, node_obj):
    ...
```

| परिमाप | प्रकार | विवरण |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/hi/aspose.slides.smartart/ismartartnode) | हटाने के लिए नोड। |

### देखें
* क्लास [`ISmartArtNode`](/slides/python-net/hi/aspose.slides.smartart/ismartartnode)
* क्लास [`ISmartArtNodeCollection`](/slides/python-net/hi/aspose.slides.smartart/ismartartnodecollection)
* मॉड्यूल [`aspose.slides.smartart`](/slides/python-net/hi/aspose.slides.smartart)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)