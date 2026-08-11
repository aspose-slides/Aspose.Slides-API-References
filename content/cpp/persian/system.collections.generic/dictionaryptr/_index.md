---
title: DictionaryPtr
second_title: مرجع API Aspose.Slides برای C++
description: کلاس اشاره‌گر دیکشنری با بارگذاری مجدد عملگرها. این نوع یک اشاره‌گر برای مدیریت حذف شیء دیگر است. باید بر روی پشته تخصیص داده شود و به توابع یا به صورت مقدار یا به صورت ارجاع ثابت پاس داده شود.
type: docs
weight: 170
url: /fa/system.collections.generic/dictionaryptr/
---
## DictionaryPtr کلاس

[Dictionary](../dictionary/) کلاس اشاره‌گر با بارگذاری اپراتورها. این نوع یک اشاره‌گر برای مدیریت حذف شیء دیگر است. باید بر روی پشته تخصیص یابد و به توابع به صورت مقدار یا به‌صورت ارجاع ثابت پاس داده شود.

```cpp
template<typename T,typename V>class DictionaryPtr : public System::SmartPtr<Dictionary<T, V>>
```

### پارامترهای قالب

| پارامتر | توصیف |
| --- | --- |
| T | نوع کلید. |
| V | نوع مقدار. |

## متدها

| متد | توضیح |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | دسترس برای متد [begin()](../../system/smartptr/begin/) از یک مجموعه زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد. |
| auto [begin](../../system/smartptr/begin/)() const | دسترس برای متد [begin()](../../system/smartptr/begin/) از یک مجموعه زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به همان نوع خودش تبدیل می‌کند. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع پایه با استفاده از static_cast تبدیل می‌کند. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق‌شده با dynamic_cast تبدیل می‌کند. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق‌شده با dynamic_cast تبدیل می‌کند. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | دسترس برای متد [cbegin()](../../system/smartptr/cbegin/) از یک مجموعه زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [cbegin()](../../system/smartptr/cbegin/) باشد. |
| auto [cend](../../system/smartptr/cend/)() const | دسترس برای متد [cend()](../../system/smartptr/cend/) از یک مجموعه زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [cend()](../../system/smartptr/cend/) باشد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از const_cast بر روی شیء اشاره‌شده تبدیل می‌کند. |
|  [DictionaryPtr](./dictionaryptr/)() | یک اشاره‌گر تهی را مقداردهی اولیه می‌کند. |
|  [DictionaryPtr](./dictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[Dictionary](../dictionary/)\<T, V\>\>\&) | نوع اشاره‌گر را تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از dynamic_cast بر روی شیء اشاره‌شده تبدیل می‌کند. |
| auto [end](../../system/smartptr/end/)() | دسترس برای متد [end()](../../system/smartptr/end/) از یک مجموعه زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد. |
| auto [end](../../system/smartptr/end/)() const | دسترس برای متد [end()](../../system/smartptr/end/) از یک مجموعه زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | شیء اشاره‌شده را دریافت می‌کند. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | حالت اشاره‌گر را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | شیء اشاره‌شده را دریافت می‌کند، اما اطمینان می‌دهد که اشاره‌گر در حالت اشتراکی است. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | تعداد اشاره‌گرهای اشتراکی موجود به شیء ارجاع‌شده را (از جمله این اشاره‌گر) دریافت می‌کند. اطمینان می‌دهد که اشاره‌گر در حالت اشتراکی است. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | متد [GetHashCode()](../../system/smartptr/gethashcode/) را بر روی شیء اشاره‌شده فراخوانی می‌کند. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | شیء ارجاع‌شده فعلی را (در صورت وجود) دریافت می‌کند یا استثناء می‌اندازد. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | شیء اشاره‌شده را (در صورت وجود) یا nullptr دریافت می‌کند. مشابه [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | شیء ارجاع‌شده را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | شیء اشاره‌شده را (در صورت وجود) یا nullptr دریافت می‌کند. مشابه [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء اشاره‌شده از نوع خاص یا نوع فرزند آن است. مطابق معناشناسی 'is' در C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | بررسی می‌کند آیا اشاره‌گر به شیء دیگری به‌جز شیء مالک (ایجاد شده توسط سازنده aliasing) اشاره دارد. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | بررسی می‌کند آیا اشاره‌گر در حالت اشتراکی است. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | بررسی می‌کند آیا اشاره‌گر در حالت ضعیف (weak) است. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | بررسی می‌کند آیا اشاره‌گر تهی نیست. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | بررسی می‌کند آیا اشاره‌گر تهی است. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | مرجع به شیء اشاره‌شده را دریافت می‌کند. اطمینان می‌دهد که اشاره‌گر تهی نیست. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | امکان دسترسی به اعضای شیء ارجاع‌شده را فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | معانی مقایسه کمتر برای کلاس [SmartPtr](../../system/smartptr/) را فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | معانی مقایسه کمتر برای کلاس [SmartPtr](../../system/smartptr/) را فراهم می‌کند. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Move-assigns شیء [SmartPtr](../../system/smartptr/). x غیرقابل استفاده می‌شود. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Copy-assigns شیء [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Copy-assigns شیء [SmartPtr](../../system/smartptr/). تبدیل‌های نوع مورد نیاز را انجام می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | اشاره‌گر خام را به شیء [SmartPtr](../../system/smartptr/) اختصاص می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | مقدار اشاره‌گر را به nullptr تنظیم می‌کند. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | بررسی می‌کند آیا اشاره‌گر به nullptr اشاره دارد. |
| V\& [operator[]](./operator[]/)(const X\&) const | اپراتور دسترسی برای کار با تبدیل نوع کلید. |
| V\& [operator[]](./operator[]/)(const T\&) const | اپراتور دسترسی. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Aliasینگ (ایجاد شده توسط سازنده aliasing) را از اشاره‌گر حذف می‌کند و اطمینان می‌دهد که (در صورت اشتراکی) یا (در صورت ضعیف) همان شیء را مدیریت یا پیگیری می‌کند. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | شیء اشاره‌شده را تنظیم می‌کند. |
| void [reset](../../system/smartptr/reset/)() | اشاره‌گر را به nullptr تنظیم می‌کند. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | حالت اشاره‌گر را تنظیم می‌کند. ممکن است شمارنده‌های مرجع شیء ارجاع‌شده را تغییر دهد. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | متد SetTemplateWeakPtr() را بر روی شیء اشاره‌شده (در صورت وجود) فراخوانی می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) با حالت مورد نیاز را ایجاد می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) تهی با حالت مورد نیاز را ایجاد می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به شیء مشخص اشاره می‌کند یا اشاره‌گر خام را به [SmartPtr](../../system/smartptr/) تبدیل می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به صورت کپی ساختار می‌کند. پس از آن هر دو اشاره‌گر به یک شیء اشاره می‌کنند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به صورت کپی ساختار می‌کند. هر دو اشاره‌گر پس از آن به یک شیء اشاره می‌کنند. در صورت امکان تبدیل نوع را انجام می‌دهد. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به صورت Move ساختار می‌کند. در اصل دو اشاره‌گر را اگر هر دو در یک حالت باشند، جابجا می‌کند. x ممکن است پس از فراخوانی غیرقابل استفاده باشد. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | نوع آرایه ارجاع‌شده را با ایجاد آرایه‌ای از نوع دیگر تبدیل می‌کند. مفید اگر در C# تبدیل نوع آرایه‌ای وجود داشته باشد که در C++ پشتیبانی نمی‌شود. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | آرایه خالی را مقداردهی اولیه می‌کند. برای ترجمه برخی ساختارهای کد C# استفاده می‌شود. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | یک [SmartPtr](../../system/smartptr/) می‌سازد که اطلاعات مالکیت را با مقدار اولیه ptr به اشتراک می‌گذارد، اما اشاره‌گر نامرتبط و بدون مدیریت p را نگهداری می‌کند. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از static_cast بر روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | هر نوع اشاره‌گری را به اشاره‌گر به [Object](../../system/object/) تبدیل می‌کند. نیازی به اینکه نوع Pointee_ کامل باشد نیست. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | میانبر برای دریافت شیء [System::TypeInfo](../../system/typeinfo/) برای نوع Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | شیء [SmartPtr](../../system/smartptr/) را از بین می‌برد. در صورت نیاز، شمارنده مرجع شیء اشاره‌شده را کاهش داده و شیء را حذف می‌کند. |

## مراجع

* کلاس [SmartPtr](../../system/smartptr/)
* فضای نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)