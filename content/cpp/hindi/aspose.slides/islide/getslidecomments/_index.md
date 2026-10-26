---
title: GetSlideComments()
second_title: Aspose.Slides for C++ API संदर्भ
description: विशिष्ट लेखक द्वारा जोड़ी गई सभी स्लाइड टिप्पणियों को लौटाता है।
type: docs
weight: 118
url: /hi/aspose.slides/islide/getslidecomments/
---
## ISlide::GetSlideComments(System::SharedPtr\<ICommentAuthor\>) मेथड

निर्दिष्ट लेखक द्वारा जोड़े गए सभी स्लाइड टिप्पणियों को लौटाता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ISlide::GetSlideComments(System::SharedPtr<ICommentAuthor> author)=0
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| author | [System::SharedPtr](../../../system/sharedptr/)\<[ICommentAuthor](../../icommentauthor/)\> | खोजने के लिए टिप्पणियों का लेखक या सभी टिप्पणियों को लौटाने के लिए null। |

### वापसी मान

[IComment](../../icomment/) की सरणी।

## देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IComment](../../icomment/)
* क्लास [ICommentAuthor](../../icommentauthor/)
* क्लास [ISlide](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)