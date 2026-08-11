---
title: ListPtr
second_title: مرجع API Aspose.Slides برای C++
description: اشاره‌گر فهرست با عملگرهای دسترسی. این نوع یک اشاره‌گر برای مدیریت حذف شیء دیگر است. باید بر روی پشته تخصیص یافته و به توابع یا به صورت مقدار یا توسط ارجاع ثابت پاس داده شود.
type: docs
weight: 456
url: /fa/system.collections.generic/listptr/
---
## ListPtr کلاس

[List](../list/) اشاره‌گر با عملگرهای دسترسی. این نوع یک اشاره‌گر برای مدیریت حذف شیء دیگری است. باید بر روی پشته تخصیص یافته و به توابع یا به صورت مقدار یا توسط ارجاع ثابت پاس داده شود.
```cpp
template<typename T>class ListPtr : public System::SmartPtr<List<T>>
```

## متدها

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | دسترس‌پذیر برای متد [begin()](../../system/smartptr/begin/) یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد. |
| auto [begin](../../system/smartptr/begin/)() const | دسترس‌پذیر برای متد [begin()](../../system/smartptr/begin/) یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به خودش تبدیل می‌کند. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع پایه با استفاده از static_cast تبدیل می‌کند. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق با dynamic_cast تبدیل می‌کند. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق با dynamic_cast تبدیل می‌کند. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | دسترس‌پذیر برای متد [cbegin()](../../system/smartptr/cbegin/) یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [cbegin()](../../system/smartptr/cbegin/) باشد. |
| auto [cend](../../system/smartptr/cend/)() const | دسترس‌پذیر برای متد [cend()](../../system/smartptr/cend/) یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [cend()](../../system/smartptr/cend/) باشد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از const_cast بر روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از dynamic_cast بر روی شیء اشاره‌شده تبدیل می‌کند. |
| auto [end](../../system/smartptr/end/)() | دسترس‌پذیر برای متد [end()](../../system/smartptr/end/) یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد. |
| auto [end](../../system/smartptr/end/)() const | دسترس‌پذیر برای متد [end()](../../system/smartptr/end/) یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | شیء اشاره‌شده را دریافت می‌کند. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | حالت اشاره‌گر را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | شیء اشاره‌شده را دریافت می‌کند، اما اطمینان می‌دهد که اشاره‌گر در حالت اشتراکی است. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | تعداد اشاره‌گرهای اشتراکی موجود به شیء مرجع را (از جمله اشاره‌گر فعلی) دریافت می‌کند. اطمینان می‌دهد که اشاره‌گر فعلی در حالت اشتراکی است. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | متد [GetHashCode()](../../system/smartptr/gethashcode/) را بر روی شیء اشاره‌شده فراخوانی می‌کند. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | شیء مرجع فعلی را دریافت می‌کند (در صورت وجود) یا استثنا می‌اندازد. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | شیء اشاره‌شده را (در صورت وجود) یا nullptr دریافت می‌کند. مشابه [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | شیء مرجع را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | شیء اشاره‌شده را (در صورت وجود) یا nullptr دریافت می‌کند. مشابه [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء اشاره‌شده از نوع مشخص یا نوع فرزند آن است. از معنای 'is' در C# پیروی می‌کند. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | بررسی می‌کند که آیا اشاره‌گر به شیء دیگری غیر از شیء مالک (ایجاد شده توسط سازنده aliasing) اشاره دارد. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت اشتراکی است. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت ضعیف (weak) است. |
| [ListPtr](./listptr/)(std::nullptr_t) | یک اشاره‌گر تهی را مقداردهی اولیه می‌کند. |
| [ListPtr](./listptr/)(const [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\>\&) | اشاره‌گر را به فهرست مشخص مقداردهی اولیه می‌کند. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | بررسی می‌کند که اشاره‌گر تهی نیست. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | بررسی می‌کند که اشاره‌گر تهی است. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | مرجع به شیء اشاره‌شده را دریافت می‌کند. اطمینان می‌دهد که اشاره‌گر تهی نیست. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | دسترسی به اعضای شیء مرجع را فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | ویژگی مقایسه کمتر برای کلاس [SmartPtr](../../system/smartptr/) را فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | ویژگی مقایسه کمتر برای کلاس [SmartPtr](../../system/smartptr/) را فراهم می‌کند. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | انتساب حرکتی به شیء [SmartPtr](../../system/smartptr/) را انجام می‌دهد. x غیرقابل استفاده می‌شود. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | کپی انتساب به شیء [SmartPtr](../../system/smartptr/) را انجام می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | کپی انتساب به شیء [SmartPtr](../../system/smartptr/) را انجام می‌دهد. تبدیل‌های نوع مورد نیاز را انجام می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | اشاره‌گر خام را به شیء [SmartPtr](../../system/smartptr/) اختصاص می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | مقدار اشاره‌گر را به nullptr تنظیم می‌کند. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | بررسی می‌کند که آیا اشاره‌گر [List](../list/) تهی است. |
| std::vector\<T\>::reference [operator[]](./operator[]/)(int) | دسترس‌پذیر. |
| std::vector\<T\>::const_reference [operator[]](./operator[]/)(int) const | دسترس‌پذیر. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | حذف aliasing (ایجاد شده توسط سازنده aliasing) از اشاره‌گر را انجام می‌دهد و اطمینان می‌دهد که در حالت اشتراکی مدیریت می‌کند یا در حالت ضعیف ردیابی می‌کند همان شیء که به آن اشاره دارد. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | شیء اشاره‌شده را تنظیم می‌کند. |
| void [reset](../../system/smartptr/reset/)() | اشاره‌گر را به nullptr تنظیم می‌کند. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | حالت اشاره‌گر را تنظیم می‌کند. ممکن است شمارش‌های مرجع شیء مرجع را تغییر دهد. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | متد SetTemplateWeakPtr() را بر روی شیء اشاره‌شده (در صورت وجود) فراخوانی می‌کند. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) با حالت مورد نیاز را ایجاد می‌کند. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) اشاره‌گر تهی با حالت مورد نیاز را ایجاد می‌کند. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | یک شیء [SmartPtr](../../system/smartptr/) ایجاد می‌کند که به شیء مشخص اشاره می‌کند، یا اشاره‌گر خام را به [SmartPtr](../../system/smartptr/) تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به صورت کپی می‌سازد. پس از آن هر دو اشاره‌گر به یک شیء اشاره می‌کنند. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به صورت کپی می‌سازد. پس از آن هر دو اشاره‌گر به یک شیء اشاره می‌کنند. در صورت امکان تبدیل نوع انجام می‌دهد. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به صورت حرکتی می‌سازد. به طور مؤثر دو اشاره‌گر را که هر دو در یک حالت هستند، جابجا می‌کند. x ممکن است پس از فراخوانی غیرقابل استفاده باشد. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | نوع آرایه مرجع را با ایجاد آرایه‌ای جدید از نوع متفاوت تبدیل می‌کند. مفید است اگر در C# تبدیل نوع آرایه‌ای وجود داشته باشد که در C++ پشتیبانی نمی‌شود. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | آرایه خالی را مقداردهی اولیه می‌کند. برای ترجمه برخی ساختارهای کد C# استفاده می‌شود. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | یک شیء [SmartPtr](../../system/smartptr/) می‌سازد که اطلاعات مالکیت را با مقدار اولیه ptr به اشتراک می‌گذارد، اما یک اشاره‌گر نامرتبط و بدون مدیریت p را نگه می‌دارد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از static_cast بر روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | هر نوع اشاره‌گری را به اشاره‌گر به [Object](../../system/object/) تبدیل می‌کند. نیازی به کامل بودن نوع Pointee_ نیست. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | میان‌بر برای دریافت شیء [System::TypeInfo](../../system/typeinfo/) برای نوع Pointee_. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | شیء [SmartPtr](../../system/smartptr/) را از بین می‌برد. در صورت نیاز، شمارش مرجع شیء اشاره‌شده را کاهش داده و شیء را حذف می‌کند. |

## مراجع

* کلاس [SmartPtr](../../system/smartptr/)
* فضای نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)