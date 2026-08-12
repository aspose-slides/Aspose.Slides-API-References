---
title: Warning()
second_title: Aspose.Slides for C++ API संदर्भ
description: कोलबैक मेथड जो चेतावनी प्राप्त करता है और तय करता है कि ऑपरेशन को रद्द किया जाना चाहिए या नहीं।
type: docs
weight: 1
url: /hi/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) मेथड

कोलबैक मेथड जो चेतावनी प्राप्त करता है और तय करता है कि ऑपरेशन को रद्द किया जाना चाहिए या नहीं।

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | प्रोसेस करने के लिए चेतावनी। |

### वापसी मान

रद्दीकरण निर्णय [ReturnAction](../../returnaction/)।

## संबंधित देखें

* Enum [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IWarningInfo](../../iwarninginfo/)
* क्लास [IWarningCallback](../)
* नामस्थान [Aspose::Slides::Warnings](../../)
* Library [Aspose.Slides](../../../)