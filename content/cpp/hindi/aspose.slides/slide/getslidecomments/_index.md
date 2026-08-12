---
title: GetSlideComments()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट लेखक द्वारा जोड़ी गई सभी स्लाइड टिप्पणियों को लौटाता है।
type: docs
weight: 209
url: /hi/aspose.slides/slide/getslidecomments/
---
## Slide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) विधि

निर्दिष्ट लेखक द्वारा जोड़े गए सभी स्लाइड टिप्पणियों को वापस करता है।

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::Slide::GetSlideComments(System::SharedPtr<ICommentAuthor> author) override
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | टिप्पणी खोजने के लिए लेखक या सभी टिप्पणियों को वापस करने के लिए null। |

### वापसी मान

ऐरे ऑफ [Comment](../../comment/).

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IComment](../../icomment/)
* क्लास [ICommentAuthor](../../icommentauthor/)
* क्लास [Slide](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)