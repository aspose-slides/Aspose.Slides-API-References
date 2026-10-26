---
title: set_InterruptionToken()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: विच्छेदन अनुरोधों की निगरानी के लिए टोकन।
type: docs
weight: 248
url: /hi/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) विधि

विच्छेदन अनुरोधों की निगरानी के लिए टोकन।

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## टिप्पणियाँ

यह टोकन पूरे [IPresentation](../../ipresentation/) इंस्टेंस जीवनकाल का प्रबंध करता है। कोई भी लंबी-चलने वाली प्रक्रिया, जैसे प्रस्तुति लोड करना या सहेजना, [IInterruptionTokenSource](../../iinterruptiontokensource/) की [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) विधि को कॉल करके बाधित की जाएगी।

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IInterruptionToken](../../iinterruptiontoken/)
* क्लास [ILoadOptions](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)