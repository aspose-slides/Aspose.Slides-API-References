---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: "يمثل تجميعة من المفوضين. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة System::SmartPtr أبداً لإدارة كائنات هذا النوع."
type: docs
weight: 1093
url: /ar/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> فئة

يمثل تجميعة من المفوضين. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](../smartptr/) أبداً لإدارة كائنات هذا النوع.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| ReturnType | Return type of the invokable entities pointed to by each delegate in the collection |
| ArgumentTypes | Argument list of the invokable entities pointed to by each delegate in the collection |

## الطرق

| Method | Description |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | NOT IMPLEMENTED. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | يضيف المفوض المحدد إلى التجميعة. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | يضيف كائن الدالة المحدد إلى تجميعة المفوضين. يتم تحويل كائن الدالة إلى نوع مفوض Callback قبل إضافته إلى التجميعة. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | يضيف كائن MulticastDelegate المحدد إلى تجميعة المفوضين. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | يضيف الطريقة غير الساكنة المحددة للكائن المحدد إلى تجميعة المفوضين. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | يضيف الطريقة غير الساكنة المحددة للكائن المحدد إلى تجميعة المفوضين. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | يزيل المفوض المحدد من تجميعة المفوضين. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | يزيل الطريقة غير الساكنة المحددة للكائن المحدد من تجميعة المفوضين. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | يزيل الطريقة غير الساكنة المحددة للكائن المحدد من تجميعة المفوضين. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | يزيل كائن MulticastDelegate المحدد من تجميعة المفوضين. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | يزيل جميع المفوضين من تجميعة المفوضين. |
| **bool** [empty](./empty/)() const | يحدد ما إذا كانت تجميعة المفوضين فارغة. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | NOT IMPLEMENTED. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | يستدعي جميع المفوضين الموجودين حالياً في تجميعة المفوضين. يتم استدعاء المفوضين بنفس الترتيب الذي أضيفوا به إلى التجميعة. تحجب الطريقة التنفيذ حتى انتهاء تشغيل المفوضين. |
| **bool** [IsNull](./isnull/)() const | يحدد ما إذا كانت تجميعة المفوضين فارغة. |
|  [MulticastDelegate](./multicastdelegate/)() | يُنشئ تجميعة فارغة. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | مكافئ للمنشئ الافتراضي. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | ينفّذ نسخة سطحية من تجميعة المفوضين. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | منشئ النقل. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | يُنشئ نسخة ويضع المفوض المحدد في تجميعة المفوضين. |
|  [MulticastDelegate](./multicastdelegate/)(T) | يُنشئ نسخة ويضع القيمة المحددة في تجميعة المفوضين. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | يُنشئ نسخة ويضع القيمة المحددة في تجميعة المفوضين. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | يحدد ما إذا كانت تجميعة المفوضين غير فارغة. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | يحدد ما إذا كان كائنان من MulticastDelegate - الكائن الحالي والكائن المحدد - غير متساويين. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | يستدعي جميع المفوضين الموجودين حالياً في تجميعة المفوضين. يتم استدعاء المفوضين بنفس الترتيب الذي أضيفوا به إلى التجميعة. المشغل يحجب التنفيذ حتى انتهاء تشغيل المفوضين. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | يضيف المفوض المحدد إلى التجميعة. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | يزيل المفوض المحدد من تجميعة المفوضين. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | يعيّن تجميعة المفوضين التي يمثلها الكائن المحدد إلى الكائن الحالي. نتيجةً لذلك، يشير كلا الكائنين إلى نفس تجميعة المفوضين. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | عامل الإسناد بالنقل. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | يحدد ما إذا كانت تجميعة المفوضين فارغة. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | يحدد ما إذا كان كائنان من MulticastDelegate - الكائن الحالي والكائن المحدد - متساويين. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | يُنظّف النداءات المرتجعة الفارغة (التي لا تستدعي أي شيء فعلياً). |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | يُرجع إشارة إلى كائن [TypeInfo](../typeinfo/) الذي يمثل معلومات نوع الفئة MulticastDelegate. |
|  [~MulticastDelegate](./~multicastdelegate/)() | المُدمّر. |

## تعريفات الأنواع

| Typedef | Description |
| --- | --- |
| [Callback](./callback/) | نوع المفوضين الذين تمثلهم فئة MulticastDelegate. |
| [Function](./function/) | نوع الدالة المتعلق بتوقيع المفوض. |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)