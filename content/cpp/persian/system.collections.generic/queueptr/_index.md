---
title: QueuePtr
second_title: مرجع API Aspose.Slides برای C++
description: اشاره‌گر صف. این نوع یک اشاره‌گر برای مدیریت حذف شیء دیگر است. باید در پشته تخصیص یابد و به توابع یا به صورت مقدار یا به صورت مرجع const منتقل شود.
type: docs
weight: 482
url: /fa/system.collections.generic/queueptr/
---
## QueuePtr کلاس

[Queue](../queue/) اشاره‌گر. این نوع اشاره‌گر برای مدیریت حذف شیء دیگر استفاده می‌شود. باید در پشته تخصیص یابد و به توابع یا به صورت مقدار یا به صورت مرجع const منتقل شود.

```cpp
template<typename T>class QueuePtr : public System::SmartPtr<Queue<T>>
```

## متدها

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | دسترس‌پذیر برای متد [begin()](../../system/smartptr/begin/) از یک مجموعه‌ی زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد. |
| auto [begin](../../system/smartptr/begin/)() const | دسترس‌پذیر برای متد [begin()](../../system/smartptr/begin/) از یک مجموعه‌ی زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به همان نوع خود تبدیل می‌کند. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع پایه با استفاده از static_cast تبدیل می‌کند. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق شده با dynamic_cast تبدیل می‌کند. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق شده با dynamic_cast تبدیل می‌کند. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | دسترس‌پذیر برای متد [cbegin()](../../system/smartptr/cbegin/) از یک مجموعه‌ی زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [cbegin()](../../system/smartptr/cbegin/) باشد. |
| auto [cend](../../system/smartptr/cend/)() const | دسترس‌پذیر برای متد [cend()](../../system/smartptr/cend/) از یک مجموعه‌ی زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [cend()](../../system/smartptr/cend/) باشد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از const_cast روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از dynamic_cast روی شیء اشاره‌شده تبدیل می‌کند. |
| auto [end](../../system/smartptr/end/)() | دسترس‌پذیر برای متد [end()](../../system/smartptr/end/) از یک مجموعه‌ی زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد. |
| auto [end](../../system/smartptr/end/)() const | دسترس‌پذیر برای متد [end()](../../system/smartptr/end/) از یک مجموعه‌ی زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | شیء اشاره‌شده را دریافت می‌کند. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | حالت اشاره‌گر را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | شیء اشاره‌شده را دریافت می‌کند، اما اطمینان می‌یابد که اشاره‌گر در حالت مشترک است. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | تعداد اشاره‌گرهای مشترکی که به شیء ارجاع‌شده وجود دارد (از جمله فعلی) را دریافت می‌کند. اطمینان می‌یابد که اشاره‌گر فعلی در حالت مشترک است. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | متد [GetHashCode()](../../system/smartptr/gethashcode/) را روی شیء اشاره‌شده فراخوانی می‌کند. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | شیء ارجاع‌شده فعلی را (در صورت وجود) دریافت می‌کند یا استثنا می‌اندازد. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | شیء اشاره‌شده را (در صورت وجود) یا nullptr دریافت می‌کند. مشابه [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | شیء ارجاع‌شده را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | شیء اشاره‌شده را (در صورت وجود) یا nullptr دریافت می‌کند. مشابه [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء اشاره‌شده از نوع خاصی یا نوع فرزند آن است. از معنای 'is' در C# پیروی می‌کند. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | بررسی می‌کند که آیا اشاره‌گر به شیء دیگری به‌جز مالک خود (ایجاد شده توسط سازنده aliasing) اشاره می‌کند. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت مشترک است. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت ضعیف (weak) است. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | بررسی می‌کند که آیا اشاره‌گر مقدار null ندارد. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | بررسی می‌کند که آیا اشاره‌گر مقدار null است. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | مرجع به شیء اشاره‌شده را دریافت می‌کند. اطمینان می‌یابد که اشاره‌گر null نیست. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | امکان دسترسی به اعضای شیء ارجاع‌شده را فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | معنای مقایسه کمتر برای کلاس [SmartPtr](../../system/smartptr/) را فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | معنای مقایسه کمتر برای کلاس [SmartPtr](../../system/smartptr/) را فراهم می‌کند. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت Move-assign می‌کند. x قابل استفاده نیست. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت Copy-assign می‌کند. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت Copy-assign می‌کند. تبدیل‌های نوع مورد نیاز را انجام می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | اشاره‌گر خام را به شیء [SmartPtr](../../system/smartptr/) اختصاص می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | مقدار اشاره‌گر را به nullptr تنظیم می‌کند. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | بررسی می‌کند که آیا اشاره‌گر به nullptr اشاره می‌کند. |
| [QueuePtr](./queueptr/)() | یک اشاره‌گر null می‌سازد. |
| [QueuePtr](./queueptr/)(const [SharedPtr](../../system/sharedptr/)\<[Queue](../queue/)\<T\>\>\&) | یک اشاره‌گر به صف خاص می‌سازد. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Aliasing (ایجاد شده توسط سازنده aliasing) را از اشاره‌گر حذف می‌کند و اطمینان می‌دهد که (اگر مشترک باشد) مدیریت می‌کند یا (اگر ضعیف باشد) ردیابی می‌کند همان شیء که به آن اشاره دارد. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | شیء اشاره‌شده را تنظیم می‌کند. |
| void [reset](../../system/smartptr/reset/)() | اشاره‌گر را به nullptr تنظیم می‌کند. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | حالت اشاره‌گر را تنظیم می‌کند. ممکن است شمارنده‌های ارجاع شیء ارجاع‌شده را تغییر دهد. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | متد SetTemplateWeakPtr() را روی شیء اشاره‌شده (در صورت وجود) فراخوانی می‌کند. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) با حالت مورد نیاز ایجاد می‌کند. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) با اشاره‌گر null و حالت مورد نیاز ایجاد می‌کند. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) که به شیء مشخص اشاره می‌کند ایجاد می‌کند یا اشاره‌گر خام را به [SmartPtr](../../system/smartptr/) تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت Copy-construct می‌کند. پس از آن هر دو اشاره‌گر به همان شیء اشاره می‌کنند. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت Copy-construct می‌کند. پس از آن هر دو اشاره‌گر به همان شیء اشاره می‌کنند. اگر اجازه باشد تبدیل نوع انجام می‌شود. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت Move-construct می‌کند. به‌طور موثری دو اشاره‌گر را، اگر هر دو در همان حالت باشند، جابجا می‌کند. x پس از فراخوانی ممکن است قابل استفاده نباشد. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | نوع آرایه ارجاع‌شده را با ایجاد آرایه‌ای جدید از نوع متفاوت تبدیل می‌کند. مفید است اگر در C# تبدیل نوع آرایه‌ای وجود داشته باشد که در C++ پشتیبانی نمی‌شود. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | آرایه خالی را مقداردهی اولیه می‌کند. برای ترجمه برخی ساختارهای کد C# استفاده می‌شود. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | یک [SmartPtr](../../system/smartptr/) را می‌سازد که اطلاعات مالکیت را با مقدار اولیه ptr به اشتراک می‌گذارد، اما یک اشاره‌گر نامرتبط و بدون مدیریت p را نگه می‌دارد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از static_cast روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | هر نوع اشاره‌گری را به اشاره‌گر به [Object](../../system/object/) تبدیل می‌کند. نیازی به کامل بودن نوع Pointee_ نیست. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | میان‌بر برای دریافت شیء [System::TypeInfo](../../system/typeinfo/) برای نوع Pointee_. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | شیء [SmartPtr](../../system/smartptr/) را از بین می‌برد. در صورت نیاز، شمارنده ارجاع شیء اشاره‌شده را کاهش می‌دهد و شیء را حذف می‌کند. |

## همچنین ببینید

* کلاس [SmartPtr](../../system/smartptr/)
* فضای‌نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)