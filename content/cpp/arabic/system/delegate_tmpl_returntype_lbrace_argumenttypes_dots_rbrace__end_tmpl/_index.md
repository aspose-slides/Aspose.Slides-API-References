---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides لمرجع API C++
description: "يمثل مؤشرًا إلى دالة أو طريقة أو كائن دالة. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 287
url: /ar/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> فئة

يمثل مؤشرًا إلى دالة أو طريقة أو كائن دالة. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم [System::SmartPtr](../smartptr/) فئة لإدارة كائنات هذا النوع.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| ReturnType | نوع القيمة المرجعة لدالة أو طريقة أو كائن دالة يشير إليه المؤشر الذي تمثله الفئة |
| ArgumentTypes | قائمة الوسائط لدالة أو طريقة أو كائن دالة يشير إليه المؤشر الذي تمثله الفئة |

## الطرق

| الطريقة | الوصف |
| --- | --- |
|  [Delegate](./delegate/)() | باني افتراضي. ينشئ كائن delegate لا يشير إلى أي شيء. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | باني نسخة نقلية. يملك الكيان الذي يشير إليه delegate المحدد. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | باني. ينشئ كائن delegate من المؤشر المحدد إلى دالة حرة أو طريقة ثابتة. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | باني. ينشئ delegate من المؤشر المحدد إلى كائن الدالة الناتج عن std::bind(). |
|  [Delegate](./delegate/)(int, T\&) | باني. ينشئ delegate من كائن الدالة المحدد. |
|  [Delegate](./delegate/)(long, T\&&) | باني نقل. ينشئ delegate من كائن الدالة المحدد. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | باني. ينشئ delegate يشير إلى الطريقة غير الثابتة المحددة في الكائن المحدد. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | باني. ينشئ delegate يشير إلى الطريقة غير الثابتة المحددة في الكائن المحدد. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | ينشئ كائن delegate يشير إلى كائن دالة std::function. |
| **bool** [Empty](./empty/)() const | يحدد ما إذا كان كائن delegate الحالي فارغًا، أي لا يشير إلى أي كيان. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | يستدعي دالة أو طريقة أو كائن دالة يشير إليه كائن delegate الحالي. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | عامل تعيين نقل. يملك الكيان الذي يشير إليه delegate المحدد. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | يقارن كائنين delegate للتحقق مما إذا كانا يشيران إلى نفس الكيان. |

## ملاحظات

```cpp
#include "system/delegate.h"
#include <iostream"

// إعلان الـ delegate.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // تعيين عنوان الدالة PrintMessage إلى المتغير.
  Message mes = Message(&PrintMessage);

  // استدعاء الدالة.
  mes();

  return 0;
}
/*
مثال الشيفرة هذا ينتج المخرجات التالية:
Hello, world!
*/
```

## راجع أيضًا

* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)