---
title: remove method
second_title: Python के लिए Aspose.Slides via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/commentcollection/remove/
weight: 70
---
## remove(self, comment) {#icomment}
संग्रह में निर्दिष्ट टिप्पणी की पहली उपस्थिति को हटाता है।

```python
def remove(self, comment):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| comment | [`IComment`](/slides/python-net/hi/aspose.slides/icomment) | संग्रह से हटाने के लिए टिप्पणी। |

### अपवाद

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | यदि टिप्पणी `None` है |
| [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception) | यदि टिप्पणी पहले ही हटाई जा चुकी है तो फेंका जाता है। |

### देखें
* class [`CommentCollection`](/slides/python-net/hi/aspose.slides/commentcollection)
* class [`IComment`](/slides/python-net/hi/aspose.slides/icomment)
* class [`PptxEditException`](/slides/python-net/hi/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)