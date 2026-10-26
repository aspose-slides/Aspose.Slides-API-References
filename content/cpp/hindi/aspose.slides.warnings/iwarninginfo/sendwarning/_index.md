---
title: SendWarning()
second_title: Aspose.Slides for C++ API संदर्भ
description: यदि receiver null नहीं है तो निर्दिष्ट प्राप्तकर्ता को चेतावनी समाप्त करता है और यदि receiver ने ऑपरेशन को रोकने का निर्णय लिया तो AbortRequestedException फेंकता है।
type: docs
weight: 27
url: /hi/aspose.slides.warnings/iwarninginfo/sendwarning/
---
## IWarningInfo::SendWarning(System::SharedPtr\<IWarningCallback\>) विधि


यदि receiver null नहीं है तो निर्दिष्ट प्राप्तकर्ता को चेतावनी समाप्त करता है और यदि receiver ने ऑपरेशन को रोकने का निर्णय लिया तो AbortRequestedException फेंकता है।

```cpp
virtual void Aspose::Slides::Warnings::IWarningInfo::SendWarning(System::SharedPtr<IWarningCallback> receiver)=0
```


### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| receiver | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningCallback](../../iwarningcallback/)\> | Receiver ऑब्जेक्ट [IWarningCallback](../../iwarningcallback/) |

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWarningCallback](../../iwarningcallback/)
* Class [IWarningInfo](../)
* Namespace [Aspose::Slides::Warnings](../../)
* Library [Aspose.Slides](../../../)