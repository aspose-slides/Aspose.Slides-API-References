---
title: HashSetPtr
second_title: مرجع API Aspose.Slides برای C++
description: اشاره‌گری برای نگهداری ارجاعات HashSet. این نوع یک اشاره‌گر برای مدیریت حذف شیء دیگر است. باید بر روی پشته تخصیص یابد و به توابع یا به‌صورت مقدار یا به‌صورت مرجع ثابت پاس داده شود.
type: docs
weight: 235
url: /fa/system.collections.generic/hashsetptr/
---
## کلاس HashSetPtr

Pointer to keep [HashSet](../hashset/) references. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class HashSetPtr : public System::SmartPtr<HashSet<T>>
```

## متدها

| متد | توضیح |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | دسترسی به متد [begin()](../../system/smartptr/begin/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد. |
| auto [begin](../../system/smartptr/begin/)() const | دسترسی به متد [begin()](../../system/smartptr/begin/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع خودش تبدیل می‌کند. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع پایه با استفاده از static_cast تبدیل می‌کند. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق‌شده با dynamic_cast تبدیل می‌کند. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق‌شده با dynamic_cast تبدیل می‌کند. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | دسترسی به متد [cbegin()](../../system/smartptr/cbegin/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [cbegin()](../../system/smartptr/cbegin/) باشد. |
| auto [cend](../../system/smartptr/cend/)() const | دسترسی به متد [cend()](../../system/smartptr/cend/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [cend()](../../system/smartptr/cend/) باشد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | اشاره‌گر را به نوع متفاوت با استفاده از const_cast روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | اشاره‌گر را به نوع متفاوت با استفاده از dynamic_cast روی شیء اشاره‌شده تبدیل می‌کند. |
| auto [end](../../system/smartptr/end/)() | دسترسی به متد [end()](../../system/smartptr/end/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد. |
| auto [end](../../system/smartptr/end/)() const | دسترسی به متد [end()](../../system/smartptr/end/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | شیء اشاره‌شده را دریافت می‌کند. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | حالت اشاره‌گر را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | شیء اشاره‌شده را دریافت می‌کند، اما اطمینان می‌دهد که اشاره‌گر در حالت مشترک است. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | تعداد اشاره‌گرهای مشترکی که به شیء ارجاع‌شده وجود دارند، شامل اشاره‌گر جاری، را دریافت می‌کند. اطمینان می‌دهد که اشاره‌گر جاری در حالت مشترک است. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | متد [GetHashCode()](../../system/smartptr/gethashcode/) را بر روی شیء اشاره‌شده فراخوانی می‌کند. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | شیء ارجاع‌شده کنونی (اگر وجود داشته باشد) را دریافت می‌کند یا استثنا پرتاب می‌کند. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | شیء اشاره‌شده (اگر وجود داشته باشد) را دریافت می‌کند یا nullptr برمی‌گرداند. مشابه [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | شیء ارجاع‌شده را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | شیء اشاره‌شده (اگر وجود داشته باشد) را دریافت می‌کند یا nullptr برمی‌گرداند. مشابه [get()](../../system/smartptr/get/). |
|  [HashSetPtr](./hashsetptr/)() | سازندهٔ اشاره‌گر تهی. |
|  [HashSetPtr](./hashsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[HashSet](../hashset/)\<T\>\>\&) | سازندهٔ کپی. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء اشاره‌شده از نوع خاصی یا نوع فرزند آن است. منطق 'is' زبان C# را دنبال می‌کند. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | بررسی می‌کند که آیا اشاره‌گر به شیء دیگری غیر از مالکش (ایجادشده توسط سازندهٔ aliasing) اشاره دارد. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت مشترک است. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت ضعیف (weak) است. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | بررسی می‌کند که آیا اشاره‌گر خالی نیست. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | بررسی می‌کند که آیا اشاره‌گر خالی است. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | مرجع به شیء اشاره‌شده را دریافت می‌کند. اطمینان می‌دهد که اشاره‌گر خالی نیست. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | امکان دسترسی به اعضای شیء ارجاع‌شده را می‌دهد. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | منطق مقایسهٔ کمتر (less) را برای کلاس [SmartPtr](../../system/smartptr/) فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | منطق مقایسهٔ کمتر (less) را برای کلاس [SmartPtr](../../system/smartptr/) فراهم می‌کند. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | انتساب جابجایی به شیء [SmartPtr](../../system/smartptr/). x غیرقابل استفاده می‌شود. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | انتساب کپی به شیء [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | انتساب کپی به شیء [SmartPtr](../../system/smartptr/). تبدیل‌های نوع مورد نیاز را انجام می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | اشاره‌گر خام را به شیء [SmartPtr](../../system/smartptr/) اختصاص می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | مقدار اشاره‌گر را به nullptr تنظیم می‌کند. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | بررسی می‌کند که آیا اشاره‌گر به nullptr اشاره دارد. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | الایاسینگ (ایجادشده توسط سازندهٔ aliasing) را از اشاره‌گر حذف می‌کند و اطمینان می‌دهد که همان شیء را مدیریت (در حالت مشترک) یا دنبال می‌کند (در حالت ضعیف) که به آن اشاره دارد. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | شیء اشاره‌شده را تنظیم می‌کند. |
| void [reset](../../system/smartptr/reset/)() | اشاره‌گر را به سمت nullptr تنظیم می‌کند. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | حالت اشاره‌گر را تنظیم می‌کند. ممکن است شمارنده‌های ارجاع شیء ارجاع‌شده را تغییر دهد. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | متد SetTemplateWeakPtr() را بر روی شیء اشاره‌شده (در صورت وجود) فراخوانی می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) با حالت مورد نیاز را ایجاد می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) با مقدار nullptr و حالت مورد نیاز را ایجاد می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) که به شیء مشخص اشاره می‌کند ایجاد می‌کند یا اشاره‌گر خام را به [SmartPtr](../../system/smartptr/) تبدیل می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را با کپی ساخت می‌کند. پس از آن هر دو اشاره‌گر به یک شیء یکسان اشاره می‌کنند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را با کپی ساخت می‌کند. پس از آن هر دو اشاره‌گر به یک شیء یکسان اشاره می‌کنند. در صورت امکان تبدیل نوع انجام می‌دهد. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را با جابجایی ساخت می‌کند. در عمل دو اشاره‌گر که هر دو از یک حالت هستند تعویض می‌کند. x ممکن است پس از فراخوانی غیرقابل استفاده باشد. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | نوع آرایهٔ ارجاع‌شده را با ایجاد آرایه‌ای جدید از نوع متفاوت تبدیل می‌کند. مفید است وقتی در C# تبدیل نوع آرایه‌ای وجود دارد که در C++ پشتیبانی نمی‌شود. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | آرایهٔ خالی را مقداردهی اولیه می‌کند. برای ترجمهٔ برخی ساختارهای کد C# استفاده می‌شود. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | یک [SmartPtr](../../system/smartptr/) را می‌سازد که اطلاعات مالکیت را با مقدار اولیهٔ ptr به اشتراک می‌گذارد، اما یک اشاره‌گر نامرتبط و غیرمدیریت‌شده p را نگه می‌دارد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | اشاره‌گر را به نوع متفاوت با استفاده از static_cast روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | هر نوع اشاره‌گری را به اشاره‌گر به [Object](../../system/object/) تبدیل می‌کند. نیازی به کامل بودن نوع Pointee_ ندارد. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | میان‌گیر برای دریافت شیء [System::TypeInfo](../../system/typeinfo/) برای نوع Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | شیء [SmartPtr](../../system/smartptr/) را از بین می‌برد. در صورت لزوم، شمارندهٔ ارجاع شیء اشاره‌شده را کاهش داده و شیء را حذف می‌کند. |

## موارد مرتبط

* کلاس [SmartPtr](../../system/smartptr/)
* فضای‌نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)