---
title: Func
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "مفوض الدالة. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم الفئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 859
url: /ar/system/func/
---
## Func فئة


مفوض الدالة. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](../smartptr/) لإدارة كائنات هذا النوع.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```


### معلمات القالب

| معاملة | وصف |
| --- | --- |
| Args | معاملات الاستدعاء، ثم نوع الإرجاع الإلزامي. |
## طرق

| طريقة | وصف |
| --- | --- |
|  [Func](./func/)() | منشئ افتراضي ينشئ null-Func. |
|  [Func](./func/)(T\&&) | منشئ ينشئ كائن [Func](./) ويعيّن القيمة (إما رد الاتصال الفعلي أو nullptr) له. |
|  [Func](./func/)(const [Func](./)\&) | منشئ النسخ. |
|  [Func](./func/)([Func](./)\&&) | منشئ النقل. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | إسناد النسخ. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | إسناد النقل. |
|  [~Func](./~func/)() | المدمر. |
## ملاحظات



```cpp
#include "system/func.h"
#include <iostream"

// هذه الدالة تقبل مثيلاً من مفوض System::Func كمعامل.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // إنشاء مثيل من مفوض System::Func.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // تمرير المثيل المُنشأ كمعامل للدالة.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
هذا المثال البرمجي ينتج المخرجات التالية:
1
4
9
*/
```

## راجع أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)