---
title: Nullable
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides لـ C++
description: إعلان مسبق.
type: docs
weight: 1106
url: /ar/system/nullable/
---
## فئة Nullable

Forward declaration.

```cpp
template<typename T>class Nullable
```

### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | The underlying value type which is extended by the [Nullable](./) class |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي مساوية للقيمة التي يمثلها الكائن [Nullable](./) المحدد. |
| **bool** [get_HasValue](./get_hasvalue/)() const | يحدّد ما إذا كان الكائن الحالي يمثل أي قيمة. |
| T [get_Value](./get_value/)() const | يرجع نسخة من القيمة التي يمثلها الكائن الحالي. |
| int [GetHashCode](./gethashcode/)() const | يرجع رمز تجزئة (hash code) للكائن الحالي. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | يرجع القيمة التي يمثلها الكائن الحالي أو القيمة المحددة إذا كانت القيمة التي يمثلها الكائن الحالي فارغة (null). |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | يحدّد ما إذا كان الكائن الحالي يمثل قيمة فارغة (null). |
|  [Nullable](./nullable/)() | ينشئ مثالاً يمثل قيمة فارغة. |
|  [Nullable](./nullable/)(std::nullptr_t) | ينشئ مثالاً يمثل null. |
|  [Nullable](./nullable/)(const T1\&) | ينشئ مثلاً من الفئة [Nullable](./) يمثل القيمة المحددة بعد تحويلها (إذا لزم الأمر) إلى نوع القيمة الأساسي T. |
|  [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | ينشئ مثلاً يمثل قيمة ممثلة بواسطة الكائن [Nullable](./) المحدد. قد يمثل الكائن القابل للاختلاف نوعًا مختلفًا عن النوع الأساسي للمثال المُنشأ، وفي هذه الحالة يتم تحويل القيمة إلى النوع T. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | دالة مساعدة للتحقق مما إذا كان هذا و **آخر** كلاهما غير فارغين وتستدعي دالة lambda إذا كان كذلك. تُستعمل في التنفيذ. |
|  [operator const T &](./operator_const_t__and/)() const | يرجع مرجعًا ثابتًا إلى القيمة التي يمثلها الكائن الحالي. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي ليست null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي غير مساوية للقيمة المحددة. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي غير مساوية للقيمة التي يمثلها الكائن [Nullable](./) المحدد. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | يطبق [operator&=()](./operator_and_equal/) على القيمة التي يمثلها الكائن الحالي باستخدام القيمة المحددة كمعامل يميني. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | يرجع مثلاً تم إنشاؤه افتراضيًا من فئة Nullable<T>. |
| auto [operator+](./operator_plus/)(const T1\&) const | يجمع القيم القابلة للاختبار والقيم غير القابلة للاختبار. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | يجمع القيم القابلة للاختبار. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | يعيد تعيين الكائن الحالي ليصبح يمثل قيمة فارغة (null). |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | يطبق [operator+=()](./operator_plus_equal/) على القيمة التي يمثلها الكائن الحالي باستخدام القيمة المحددة كمعامل يميني. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | يطبق [operator+=()](./operator_plus_equal/) على القيمة التي يمثلها الكائن الحالي باستخدام القيمة التي يمثلها الكائن [Nullable](./) المحدد كمعامل يميني. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | يطرح القيم القابلة للاختبار والقيم ذات المؤشر الفارغ. |
| auto [operator-](./operator_minus/)(const T1\&) const | يطرح القيم القابلة للاختبار والقيم غير القابلة للاختبار. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | يطرح القيم القابلة للاختبار. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | يرجع مثلاً من الفئة [Nullable](./) يمثل قيمة فارغة (null). |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | يطبق [operator-=()](./operator_minus_equal/) على القيمة التي يمثلها الكائن الحالي باستخدام القيمة المحددة كمعامل يميني. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | يطبق [operator-=()](./operator_minus_equal/) على القيمة التي يمثلها الكائن الحالي باستخدام القيمة التي يمثلها الكائن [Nullable](./) المحدد كمعامل يميني. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | دائمًا ما يرجع false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي أصغر من القيمة المحددة عبر تطبيق [operator<()](./operator_less/) على هاتين القيمتين. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي أصغر من القيمة التي يمثلها الكائن [Nullable](./) المحدد عبر تطبيق [operator<()](./operator_less/) على هاتين القيمتين. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | دائمًا ما يرجع false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي أصغر أو مساوية للقيمة المحددة عبر تطبيق [operator<=()](./operator_less_equal/) على هاتين القيمتين. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي أصغر أو مساوية للقيمة التي يمثلها الكائن [Nullable](./) المحدد عبر تطبيق [operator<=()](./operator_less_equal/) على هاتين القيمتين. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | يعين null للكائن الحالي. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | يستبدل القيمة الحالية الممثلة للكائن بالقيمة المحددة. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | يستبدل القيمة الحالية الممثلة للكائن بالقيمة المحددة. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي هي null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي مساوية للقيمة المحددة. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي مساوية للقيمة التي يمثلها الكائن [Nullable](./) المحدد. |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | دائمًا ما يرجع false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي أكبر من القيمة المحددة عبر تطبيق [operator>()](./operator_greater/) على هاتين القيمتين. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي أكبر من القيمة التي يمثلها الكائن [Nullable](./) المحدد عبر تطبيق [operator>()](./operator_greater/) على هاتين القيمتين. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | دائمًا ما يرجع false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي أكبر أو مساوية للقيمة التي يمثلها الكائن المحدد عبر تطبيق [operator>=()](./operator_greater_equal/) على هاتين القيمتين. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | يحدّد ما إذا كانت القيمة التي يمثلها الكائن الحالي أكبر أو مساوية للقيمة التي يمثلها الكائن [Nullable](./) المحدد عبر تطبيق [operator>=()](./operator_greater_equal/) على هاتين القيمتين. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | يطبق [operator|=()](./operator_or_equal/) على القيمة التي يمثلها الكائن الحالي باستخدام القيمة المحددة كمعامل يميني. |
| void [reset](./reset/)() | يضبط القيمة الحالية الممثلة إلى null. |
| void [set_Value](./set_value/)(const T\&) | يضبط قيمة جديدة للكائن القابل للاختبار. |
| [String](../string/) [ToString](./tostring/)() const | يحوّل القيمة التي يمثلها الكائن الحالي إلى سلسلة نصية. |
## التعريفات

| التعريف | الوصف |
| --- | --- |
| [ValueType](./valuetype/) | اسم مستعار لنوع القيمة التي يمثلها هذا الصف. |
## ملاحظات

يمثل قيمة من النوع المحدد يمكن تعيينها إلى null. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبداً الفئة [System::SmartPtr](../smartptr/) لإدارة كائنات هذا النوع.

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)