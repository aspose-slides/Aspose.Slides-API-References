---
title: ToArray()
second_title: Aspose.Slides for C++ API संदर्भ
description: सभी टिप्पणियों के साथ एक ऐरे बनाता है और उसे लौटाता है।
type: docs
weight: 105
url: /hi/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() विधि


सभी टिप्पणियों के साथ एक ऐरे बनाता है और उसे लौटाता है।

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```


### रिटर्न वैल्यू

[Comment](../../comment/) का ऐरे।

## CommentCollection::ToArray(int32_t, int32_t) विधि


निर्दिष्ट सीमा से सभी टिप्पणियों के साथ एक ऐरे बनाता है और उसे लौटाता है।

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startIndex | **int32_t** | पहली टिप्पणी को लौटाने के लिए एक सूचकांक। |
| count | **int32_t** | लौटाने के लिए टिप्पणियों की संख्या। |

### रिटर्न वैल्यू

[Comment](../../comment/) का ऐरे।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IComment](../../icomment/)
* क्लास [CommentCollection](../)
* नेमस्पेस [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)