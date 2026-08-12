---
title: BothArrayOrList
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जाँचता है कि दोनों टाइप तर्क arrays या lists हैं। यदि ऐसा है, तो value member को true सेट किया जाता है, अन्यथा इसे false सेट किया जाता है।
type: docs
weight: 131
url: /hi/system.testpredicates.typetraits/botharrayorlist/
---
## BothArrayOrList टाइपडिफ़


जाँचता है कि दोनों प्रकार के तर्क arrays या lists हैं। यदि सत्य है, तो value member को true सेट किया जाता है, अन्यथा इसे false सेट किया जाता है।

```cpp
using System::TestPredicates::TypeTraits::BothArrayOrList = typedef std::integral_constant<bool, (IsArray<T1>::value || IsList<T1>::value) && (IsArray<T2>::value || IsList<T2>::value)>
```


## देखें

* नामस्थान [System::TestPredicates::TypeTraits](../)
* लाइब्रेरी [Aspose.Slides](../../)