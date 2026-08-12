---
title: AreFPandArithmetic
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जाँचता है कि T1 अंकगणितीय है और T2 फ्लोटिंग पॉइंट है, या इसके विपरीत। यदि ऐसा है, तो value सदस्य को true सेट करता है, अन्यथा यह false रहता है।
type: docs
weight: 79
url: /hi/system.testpredicates.typetraits/arefpandarithmetic/
---
## AreFPandArithmetic टाइपडैफ़

Checks that **T1** is arithmetic and **T2** is floating point, or vice versa. If so, sets value member to true, otherwise it is false.

```cpp
using System::TestPredicates::TypeTraits::AreFPandArithmetic = typedef std::integral_constant<bool, (std::is_floating_point<T1>::value && std::is_arithmetic<T2>::value) || (std::is_arithmetic<T1>::value && std::is_floating_point<T2>::value) >
```

## संबंधित देखें

* नेमस्पेस [System::TestPredicates::TypeTraits](../)
* लाइब्रेरी [Aspose.Slides](../../)