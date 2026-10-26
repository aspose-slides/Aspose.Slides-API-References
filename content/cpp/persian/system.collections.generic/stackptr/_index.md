---
title: StackPtr
second_title: مستندات API Aspose.Slides برای C++
description: اشاره‌گر استک. این نوع یک اشاره‌گر برای مدیریت حذف شیء دیگر است. باید روی استک تخصیص یابد و به توابع یا به صورت مقدار یا به صورت ارجاع ثابت پاس داده شود.
type: docs
weight: 612
url: /fa/system.collections.generic/stackptr/
---
## StackPtr کلاس

[Stack](../stack/) اشاره‌گر. این نوع یک اشاره‌گر برای مدیریت حذف شیء دیگر است. باید روی استک تخصیص یابد و به توابع یا به صورت مقدار یا به صورت ارجاع ثابت پاس داده شود.

```cpp
template<typename T>class StackPtr : public System::SmartPtr<Stack<T>>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عنصر. |

## متدها

| متد | توضیح |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | دسترس‌پذیر برای متد [begin()](../../system/smartptr/begin/) یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ از نوع خاصی باشد که متد [begin()](../../system/smartptr/begin/) را داشته باشد. |
| auto [begin](../../system/smartptr/begin/)() const | دسترس‌پذیر برای متد [begin()](../../system/smartptr/begin/) یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ از نوع خاصی باشد که متد [begin()](../../system/smartptr/begin/) را داشته باشد. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع خودش تبدیل می‌کند. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع پایه با استفاده از static_cast تبدیل می‌کند. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق با dynamic_cast تبدیل می‌کند. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق با dynamic_cast تبدیل می‌کند. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | دسترس‌پذیر برای متد [cbegin()](../../system/smartptr/cbegin/) یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ از نوع خاصی باشد که متد [cbegin()](../../system/smartptr/cbegin/) را داشته باشد. |
| auto [cend](../../system/smartptr/cend/)() const | دسترس‌پذیر برای متد [cend()](../../system/smartptr/cend/) یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ از نوع خاصی باشد که متد [cend()](../../system/smartptr/cend/) را داشته باشد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | اشاره‌گر را به نوع مختلف با استفاده از const_cast روی شیء اشاره شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | اشاره‌گر را به نوع مختلف با dynamic_cast روی شیء اشاره شده تبدیل می‌کند. |
| auto [end](../../system/smartptr/end/)() | دسترس‌پذیر برای متد [end()](../../system/smartptr/end/) یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ از نوع خاصی باشد که متد [end()](../../system/smartptr/end/) را داشته باشد. |
| auto [end](../../system/smartptr/end/)() const | دسترس‌پذیر برای متد [end()](../../system/smartptr/end/) یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ از نوع خاصی باشد که متد [end()](../../system/smartptr/end/) را داشته باشد. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | شیء اشاره شده را دریافت می‌کند. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | حالت اشاره‌گر را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | شیء اشاره شده را دریافت می‌کند، اما صحت حالت اشتراک‌گذاری اشاره‌گر را تأیید می‌کند. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | تعداد اشاره‌گرهای اشتراک‌گذاری موجود به شیء مرجع را (از جمله این اشاره‌گر) بر می‌گرداند. صحت حالت اشتراک‌گذاری اشاره‌گر جاری را تأیید می‌کند. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | متد [GetHashCode()](../../system/smartptr/gethashcode/) را روی شیء اشاره شده فراخوانی می‌کند. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | شیء مرجع فعلی را (در صورت وجود) دریافت می‌کند یا استثنا می‌اندازد. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | شیء اشاره شده را (در صورت وجود) دریافت می‌کند یا nullptr برمی‌گرداند. همانند [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | شیء مرجع را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | شیء اشاره شده را (در صورت وجود) دریافت می‌کند یا nullptr برمی‌گرداند. همانند [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء اشاره شده از نوع خاص یا نوع فرزند آن است. مطابق معناشناسی 'is' در C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | بررسی می‌کند آیا اشاره‌گر به شیء متفاوتی از شیء صاحب (ساخته‌شده توسط سازنده aliasing) اشاره دارد. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | بررسی می‌کند آیا اشاره‌گر در حالت اشتراک‌گذاری است. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | بررسی می‌کند آیا اشاره‌گر در حالت ضعیف (weak) است. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | بررسی می‌کند آیا اشاره‌گر تهی نیست. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | بررسی می‌کند آیا اشاره‌گر تهی است. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | مرجع به شیء اشاره شده را بر می‌گرداند. صحت عدم تهی بودن اشاره‌گر را تأیید می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | اجازه دسترسی به اعضای شیء مرجع را می‌دهد. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | معنایی مقایسه کمتر برای کلاس [SmartPtr](../../system/smartptr/) فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | معنایی مقایسه کمتر برای کلاس [SmartPtr](../../system/smartptr/) فراهم می‌کند. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | به‌صورت Move-assign شیء [SmartPtr](../../system/smartptr/) را تخصیص می‌دهد. x غیرقابل استفاده می‌شود. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | به‌صورت Copy-assign شیء [SmartPtr](../../system/smartptr/) را تخصیص می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | به‌صورت Copy-assign شیء [SmartPtr](../../system/smartptr/) را تخصیص می‌دهد. تبدیل نوع‌های مورد نیاز را انجام می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | اشاره‌گر خام را به شیء [SmartPtr](../../system/smartptr/) اختصاص می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | مقدار اشاره‌گر را به nullptr تنظیم می‌کند. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | بررسی می‌کند آیا اشاره‌گر به nullptr اشاره دارد. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | از اشاره‌گر aliasing (ساخته‌شده توسط سازنده aliasing) را حذف می‌کند و اطمینان می‌دهد که همان شیء را (اگر اشتراک‌گذاری باشد مدیریت یا اگر ضعیف باشد ردیابی) می‌کند. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | شیء اشاره شده را تنظیم می‌کند. |
| void [reset](../../system/smartptr/reset/)() | اشاره‌گر را به nullptr تنظیم می‌کند. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | حالت اشاره‌گر را تنظیم می‌کند. ممکن است شمارش مرجع شیء مرجع را تغییر دهد. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | متد SetTemplateWeakPtr() را روی شیء اشاره شده (در صورت وجود) فراخوانی می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را با حالت مورد نیاز ایجاد می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) تهی با حالت مورد نیاز را ایجاد می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را که به شیء مشخص اشاره دارد ایجاد می‌کند، یا اشاره‌گر خام را به [SmartPtr](../../system/smartptr/) تبدیل می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت Copy-construct می‌سازد. پس از آن هر دو اشاره‌گر به یک شیء اشاره می‌کنند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت Copy-construct می‌سازد. پس از آن هر دو اشاره‌گر به یک شیء اشاره می‌کنند. در صورت امکان تبدیل نوع انجام می‌دهد. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت Move-construct می‌سازد. به‌طور مؤثر دو اشاره‌گر را جابجا می‌کند، اگر هر دو در همان حالت باشند. x ممکن است پس از فراخوانی غیرقابل استفاده باشد. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | نوع آرایه مرجع را با ایجاد آرایه‌ای از نوع متفاوت تبدیل می‌کند. مفید است وقتی در C# تبدیل نوع آرایه‌ای وجود دارد که در C++ پشتیبانی نمی‌شود. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | آرایه خالی را مقداردهی اولیه می‌کند. برای ترجمه برخی ساختارهای کد C# استفاده می‌شود. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را می‌سازد که اطلاعات مالکیت را با مقدار اولیه ptr به اشتراک می‌گذارد، اما یک اشاره‌گر مستقل و غیرمدیریت‌شده p را نگه می‌دارد. |
|  [StackPtr](./stackptr/)() | اشاره‌گر تهی را می‌سازد. |
|  [StackPtr](./stackptr/)(const [SharedPtr](../../system/sharedptr/)\<[Stack](../stack/)\<T\>\>\&) | اشاره‌گری را می‌سازد که به پشته خاصی ارجاع می‌دهد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | اشاره‌گر را به نوع متفاوت با استفاده از static_cast روی شیء اشاره شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | هر نوع اشاره‌گری را به اشاره‌گر به [Object](../../system/object/) تبدیل می‌کند. نیازی به کامل بودن نوع Pointee_ نیست. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | راه‌حلی برای دریافت شیء [System::TypeInfo](../../system/typeinfo/) برای نوع Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | شیء [SmartPtr](../../system/smartptr/) را از بین می‌برد. در صورت نیاز، شمارنده مرجع شیء اشاره شده را کاهش داده و شیء را حذف می‌کند. |

## موارد مرتبط

* کلاس [SmartPtr](../../system/smartptr/)
* فضای‌نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)