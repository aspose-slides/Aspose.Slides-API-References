---
title: operator()()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: डेलीगेट्स संग्रह में वर्तमान में मौजूद सभी डेलीगेट्स को बुलाता है। डेलीगेट्स को उसी क्रम में बुलाया जाता है जैसा कि वे संग्रह में जोड़े गए थे। ऑपरेटर डेलीगेट्स के निष्पादित होने तक ब्लॉक करता है।
type: docs
weight: 235
url: /hi/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const विधि

Invokes all delegates currently present in the delegates collection. Delegates are invoked in the same order as they were added to the collection. The operator blocks while the delegates are executed.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| args | ArgumentTypes... | आर्ग्युमेंट्स जिन्हें बुलाए जाने वाले डेलीगेट्स को पास किया जाता है |

## वापसी मान

आखिरी बुलाए गए डेलीगेट का रिटर्न वैल्यू

## संबंधित

* क्लास [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)