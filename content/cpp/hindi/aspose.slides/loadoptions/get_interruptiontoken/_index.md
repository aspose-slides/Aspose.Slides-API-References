---
title: get_InterruptionToken()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: बाधा अनुरोधों की निगरानी के लिए टोकन।
type: docs
weight: 235
url: /hi/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() विधि

इस टोकन को बाधा अनुरोधों की निगरानी के लिए उपयोग किया जाता है।

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## टिप्पणियाँ

यह टोकन पूरे [IPresentation](../../ipresentation/) उदाहरण के जीवनकाल को प्रबंधित करता है। कोई भी लंबी चलने वाली प्रक्रिया, जैसे प्रस्तुति का लोडिंग या सहेजना, [InterruptionTokenSource](../../interruptiontokensource/) की [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) विधि को कॉल करके बाधित की जाएगी।

## संबंधित देखें

* टाइपडेफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IInterruptionToken](../../iinterruptiontoken/)
* क्लास [LoadOptions](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)