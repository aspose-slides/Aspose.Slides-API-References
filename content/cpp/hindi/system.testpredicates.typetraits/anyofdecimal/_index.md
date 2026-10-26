---
title: AnyOfDecimal
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "जाँचता है कि टाइप तर्कों में से कम से कम एक System::Decimal है। यदि ऐसा है, तो value सदस्य को true सेट करता है, अन्यथा यह false रहता है।"
type: docs
weight: 92
url: /hi/system.testpredicates.typetraits/anyofdecimal/
---
## AnyOfDecimal typedef

जाँचता है कि कम से कम एक टाइप तर्क [System::Decimal](../../system/decimal/) है। यदि ऐसा है, तो value सदस्य को true सेट करता है, अन्यथा यह false होता है।

```cpp
using System::TestPredicates::TypeTraits::AnyOfDecimal = typedef std::integral_constant<bool, std::is_same<T1, System::Decimal>::value || std::is_same<T2, System::Decimal>::value>
```

## संबंधित देखें

* नामस्थान [System::TestPredicates::TypeTraits](../)
* लाइब्रेरी [Aspose.Slides](../../)