---
title: get_InterruptionToken()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: विच्छेदन अनुरोधों की निगरानी करने के लिए टोकन।
type: docs
weight: 235
url: /hi/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() विधि


विच्छेदन अनुरोधों की निगरानी करने के लिए टोकन।

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## टिप्पणियां


यह टोकन पूरे [IPresentation](../../ipresentation/) इंस्टेंस के जीवनकाल का प्रबंधन करता है। कोई भी लंबी अवधि की प्रक्रिया, जैसे प्रस्तुति लोड करना या सहेजना, [IInterruptionTokenSource](../../iinterruptiontokensource/) के [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) विधि को कॉल करने से बाधित हो जाएगी। 
## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInterruptionToken](../../iinterruptiontoken/)
* Class [ILoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)