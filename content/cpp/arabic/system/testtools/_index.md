---
title: TestTools
second_title: مرجع API لـ Aspose.Slides للغة C++
description: توفر مجموعة من الطرق المفيدة التي تتحقق من بعض الخصائص الأساسية لأنواع مختلفة والوظائف.
type: docs
weight: 1925
url: /ar/system/testtools/
---
## TestTools بنية

توفر مجموعة من الطرق المفيدة التي تتحقق من بعض الخصائص الأساسية لأنواع مختلفة والوظائف.

```cpp
class TestTools
```

## طرق

| الطريقة | الوصف |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | يتحقق مما إذا كانت الدالة تُرمِّس استثناءً من أي نوع. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | يتحقق مما إذا كانت السلسلة فارغة. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | يتحقق مما إذا كانت المجموعة فارغة. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | يتحقق مما إذا كانت القيمة المحددة فارغة. [Version](../version/) لأنواع arithmetic و enum. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | يتحقق مما إذا كانت القيمة المحددة فارغة. [Version](../version/) لأنواع القيمة غير arithmetic وغير enum. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | يتحقق مما إذا كانت القيمة المحددة فارغة. [Version](../version/) لأنواع القيمة غير arithmetic. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | يتحقق مما إذا كانت القيمة المحددة فارغة. [Version](../version/) لأزواج المفتاح-القيمة. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | يتحقق مما إذا كانت السلسلة فارغة. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | يتحقق مما إذا كانت المجموعة غير موجودة أو فارغة. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | يتحقق مما إذا كانت السلسلة غير موجودة أو فارغة. |
## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)