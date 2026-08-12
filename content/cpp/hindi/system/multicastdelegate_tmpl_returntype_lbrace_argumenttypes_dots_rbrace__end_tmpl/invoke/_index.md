---
title: invoke()
second_title: Aspose.Slides for C++ API संदर्भ
description: डेलीगेट्स संग्रह में वर्तमान में मौजूद सभी डेलीगेट्स को बुलाता है। डेलीगेट्स को उसी क्रम में बुलाया जाता है जैसा कि उन्हें संग्रह में जोड़ा गया था। मेथड डेलीगेट्स के निष्पादन के दौरान ब्लॉक हो जाता है।
type: docs
weight: 222
url: /hi/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes...) const मेथड

डेलीगेट्स कलेक्शन में वर्तमान में मौजूद सभी डेलीगेट्स को बुलाता है। डेलीगेट्स को उसी क्रम में बुलाया जाता है जैसे उन्हें कलेक्शन में जोड़ा गया था। डेलीगेट्स के निष्पादन के दौरान मेथड ब्लॉक हो जाता है।

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| args | ArgumentTypes... | डेलीगेट्स को पास करने के लिए आर्ग्युमेंट्स जिन्हें बुलाया जाना है |

## रिटर्न वैल्यू

आखिरी बुलाए गए डेलीगेट का रिटर्न वैल्यू

## संबंधित

* क्लास [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)