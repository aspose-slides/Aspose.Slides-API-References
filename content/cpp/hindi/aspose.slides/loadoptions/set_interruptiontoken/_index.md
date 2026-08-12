---
title: set_InterruptionToken()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: रोकथाम अनुरोधों की निगरानी के लिए टोकन।
type: docs
weight: 248
url: /hi/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) विधि

रोकने के अनुरोधों की निगरानी के लिए टोकन।

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## टिप्पणियाँ

यह टोकन पूरे [IPresentation](../../ipresentation/) इंस्टेंस के लाइफ़टाइम का प्रबंधन करता है। कोई भी दीर्घकालिक संचालन, जैसे प्रस्तुति का लोड करना या सहेजना, [InterruptionTokenSource](../../interruptiontokensource/) के [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) विधि को कॉल करके बाधित किया जाएगा।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IInterruptionToken](../../iinterruptiontoken/)
* क्लास [LoadOptions](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)