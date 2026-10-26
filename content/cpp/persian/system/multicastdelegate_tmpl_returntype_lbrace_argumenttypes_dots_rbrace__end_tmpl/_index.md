---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides برای C++ مرجع API
description: "نمایش دهنده یک مجموعه از نمایندگان است. این نوع باید روی پشته تخصیص داده شود و به توابع به صورت مقدار یا مرجع پاس داده شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 1093
url: /fa/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> کلاس

نمایش دهنده یک مجموعه از نمایندگان. این نوع باید روی پشته تخصیص داده شود و به توابع به صورت مقدار یا مرجع پاس داده شود. هرگز از کلاس [System::SmartPtr](../smartptr/) برای مدیریت اشیاء این نوع استفاده نکنید.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| ReturnType | نوع بازگشتی موجودیت‌های قابل فراخوانی که توسط هر نماینده در مجموعه اشاره می‌شود |
| ArgumentTypes | فهرست آرگومان‌های موجودیت‌های قابل فراخوانی که توسط هر نماینده در مجموعه اشاره می‌شود |

## متدها

| متد | توضیح |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | پیاده‌سازی نشده. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | نمایندهٔ مشخص‌شده را به مجموعه اضافه می‌کند. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | تابع شیء مشخص‌شده را به مجموعه نمایندگان اضافه می‌کند. شیء تابع قبل از افزودن به مجموعه به نوع نماینده Callback تبدیل می‌شود. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | شیء MulticastDelegate مشخص‌شده را به مجموعه نمایندگان اضافه می‌کند. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | متد غیر‌استاتیک مشخص‌شده از شیء مشخص‌شده را به مجموعه نمایندگان اضافه می‌کند. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | متد غير‌استاتیک مشخص‌شده از شیء مشخص‌شده را به مجموعه نمایندگان اضافه می‌کند. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | نمایندهٔ مشخص‌شده را از مجموعه نمایندگان حذف می‌کند. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | متد غیر‌استاتیک مشخص‌شده از شیء مشخص‌شده را از مجموعه نمایندگان حذف می‌کند. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | متد غیر‌استاتیک مشخص‌شده از شیء مشخص‌شده را از مجموعه نمایندگان حذف می‌کند. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | شیء MulticastDelegate مشخص‌شده را از مجموعه نمایندگان حذف می‌کند. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | تمام نمایندگان را از مجموعه نمایندگان حذف می‌کند. |
| **bool** [empty](./empty/)() const | تعیین می‌کند که آیا مجموعه نمایندگان خالی است یا خیر. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | پیاده‌سازی نشده. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | تمام نمایندگان موجود در مجموعه نمایندگان را فراخوانی می‌کند. نمایندگان به همان ترتیب که به مجموعه افزوده شدند، فراخوانی می‌شوند. این متد تا پایان اجرای نمایندگان مسدود می‌شود. |
| **bool** [IsNull](./isnull/)() const | تعیین می‌کند که آیا مجموعه نمایندگان خالی است یا خیر. |
|  [MulticastDelegate](./multicastdelegate/)() | یک مجموعهٔ خالی ساختار می‌دهد. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | معادل سازندهٔ پیش‌فرض. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | کپی سطحی از مجموعه نمایندگان را انجام می‌دهد. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | سازندهٔ انتقال. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | یک نمونه می‌سازد و نمایندهٔ مشخص‌شده را به مجموعه نمایندگان اضافه می‌کند. |
|  [MulticastDelegate](./multicastdelegate/)(T) | یک نمونه می‌سازد و مقدار مشخص‌شده را به مجموعه نمایندگان اضافه می‌کند. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | یک نمونه می‌سازد و مقدار مشخص‌شده را به مجموعه نمایندگان اضافه می‌کند. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | تعیین می‌کند که آیا مجموعه نمایندگان خالی نیست. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | تعیین می‌کند که آیا دو نمونهٔ MulticastDelegate — شیء جاری و شیء مشخص‌شده — برابر نیستند. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | تمام نمایندگان موجود در مجموعه نمایندگان را فراخوانی می‌کند. نمایندگان به همان ترتیبی که به مجموعه افزوده شدند، فراخوانی می‌شوند. عملگر تا پایان اجرای نمایندگان مسدود می‌شود. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | نمایندهٔ مشخص‌شده را به مجموعه اضافه می‌کند. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | نمایندهٔ مشخص‌شده را از مجموعه نمایندگان حذف می‌کند. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | مجموعهٔ نمایندگان نمایندهٔ شیء مشخص‌شده را به شیء جاری اختصاص می‌دهد. در نتیجه هر دو شیء به همان مجموعهٔ نمایندگان اشاره می‌کنند. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | عملگر انتساب انتقال. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | تعیین می‌کند که آیا مجموعه نمایندگان خالی است. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | تعیین می‌کند که آیا دو نمونهٔ MulticastDelegate — شیء جاری و شیء مشخص‌شده — برابر هستند. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | کال‌بک‌های خالی (که در واقع هیچ‌چیزی را فراخوانی نمی‌کنند) را پاک می‌کند. |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | مرجعی به شیء [TypeInfo](../typeinfo/) که اطلاعات نوع کلاس MulticastDelegate را نشان می‌دهد، برمی‌گرداند. |
|  [~MulticastDelegate](./~multicastdelegate/)() | تخریبی. |

## تعریف‌های نوع

| تعریف نوع | توضیح |
| --- | --- |
| [Callback](./callback/) | نوع نمایندگان که توسط کلاس MulticastDelegate نمایانده می‌شود. |
| [Function](./function/) | نوع تابع مرتبط با امضای نماینده. |

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)