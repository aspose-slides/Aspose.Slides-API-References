---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: مرجع API Aspose.Slides برای C++
description: "یک اشاره‌گر به تابع، متد یا شیء تابع را نشان می‌دهد. این نوع باید روی پشته تخصیص یابد و به توابع به صورت مقدار یا مرجع پاس داده شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 287
url: /fa/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> کلاس

یک اشاره‌گر به تابع، متد یا شیء تابع را نشان می‌دهد. این نوع باید روی پشته تخصیص یابد و به توابع به صورت مقدار یا مرجع پاس داده شود. هرگز از کلاس [System::SmartPtr](../smartptr/) برای مدیریت اشیاء این نوع استفاده نکنید.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ReturnType | نوع بازگشتی تابع، متد یا اشاره‌گری به شیء تابع که توسط کلاس نمایان می‌شود |
| ArgumentTypes | لیست آرگومان‌های تابع، متد یا اشاره‌گری به شیء تابع که توسط کلاس نمایان می‌شود |

## متدها

| متد | توضیح |
| --- | --- |
|  [Delegate](./delegate/)() | سازنده پیش‌فرض. شی delegate را می‌سازد که به هیچ‌چیزی اشاره نمی‌کند. |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | سازنده کپی انتقالی. مالکیت موجودیتی را که توسط delegate مشخص شده اشاره شده است، به‌دست می‌آورد. |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | سازنده. یک شی delegate را از اشاره‌گر مشخص شده به تابع آزاد یا متد استاتیک می‌سازد. |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | سازنده. یک delegate را از اشاره‌گر مشخص شده به شیء تابعی که توسط std::bind() تولید شده است، می‌سازد. |
|  [Delegate](./delegate/)(int, T\&) | سازنده. یک delegate را از شیء تابعی که مشخص شده است می‌سازد. |
|  [Delegate](./delegate/)(long, T\&&) | سازنده انتقالی. یک delegate را از شیء تابعی که مشخص شده است می‌سازد. |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | سازنده. یک delegate می‌سازد که به متد غیر‌استاتیک مشخص شده از شیء مشخص شده اشاره می‌کند. |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | سازنده. یک delegate می‌سازد که به متد غیر‌استاتیک مشخص شده از شیء مشخص شده اشاره می‌کند. |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | یک شی delegate می‌سازد که به یک شیء تابع std::function اشاره می‌کند. |
| **bool** [Empty](./empty/)() const | تشخیص می‌دهد که آیا شی delegate جاری خالی است، مثلاً به هیچ‌موجودیتی اشاره نمی‌کند. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | یک تابع، متد یا شیء تابعی که توسط شی delegate جاری اشاره شده است را فراخوانی می‌کند. |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | عملگر تخصیص انتقالی. مالکیت موجودیتی را که توسط delegate مشخص شده اشاره شده است، به‌دست می‌آورد. |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | دو شیء delegate را مقایسه می‌کند تا ببیند آیا به همان موجودیت اشاره می‌کنند یا خیر. |

## توضیحات

```cpp
#include "system/delegate.h"
#include <iostream"

// اعلان delegate.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // مقداردهی متغیر با آدرس تابع PrintMessage.
  Message mes = Message(&PrintMessage);

  // فراخوانی تابع.
  mes();

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
Hello, world!
*/
```

## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)