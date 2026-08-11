---
title: StringCollectionPtr
second_title: Aspose.Slides برای مرجع API C++
description: مجموعه رشته‌ای با عملگر دسترسی.
type: docs
weight: 40
url: /fa/system.collections.specialized/stringcollectionptr/
---
## StringCollectionPtr کلاس

مجموعه رشته‌ای با عملگر دسترسی.

```cpp
class StringCollectionPtr : public System::SmartPtr<StringCollection>
```

## متدها

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | دسترس‌پذیر برای متد [begin()](../../system/smartptr/begin/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد. |
| auto [begin](../../system/smartptr/begin/)() const | دسترس‌پذیر برای متد [begin()](../../system/smartptr/begin/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | نوع اشاره‌گر را به خود نوعش تبدیل می‌کند. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع پایه با استفاده از static_cast تبدیل می‌کند. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق‌شده با dynamic_cast تبدیل می‌کند. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق‌شده با dynamic_cast تبدیل می‌کند. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | دسترس‌پذیر برای متد [cbegin()](../../system/smartptr/cbegin/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [cbegin()](../../system/smartptr/cbegin/) باشد. |
| auto [cend](../../system/smartptr/cend/)() const | دسترس‌پذیر برای متد [cend()](../../system/smartptr/cend/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [cend()](../../system/smartptr/cend/) باشد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | اشاره‌گر را به نوع دیگری با استفاده از const_cast بر روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | اشاره‌گر را به نوع دیگری با استفاده از dynamic_cast بر روی شیء اشاره‌شده تبدیل می‌کند. |
| auto [end](../../system/smartptr/end/)() | دسترس‌پذیر برای متد [end()](../../system/smartptr/end/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد. |
| auto [end](../../system/smartptr/end/)() const | دسترس‌پذیر برای متد [end()](../../system/smartptr/end/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | شیء اشاره‌شده را دریافت می‌کند. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | حالت اشاره‌گر را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | شیء اشاره‌شده را دریافت می‌کند، اما اطمینان می‌دهد که اشاره‌گر در حالت مشترک است. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | تعداد اشاره‌گرهای مشترکی که به شیء مرجع وجود دارند را به‌همراه اشاره‌گر فعلی برمی‌گرداند. اطمینان می‌دهد که اشاره‌گر فعلی در حالت مشترک است. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | متد [GetHashCode()](../../system/smartptr/gethashcode/) را روی شیء اشاره‌شده فراخوانی می‌کند. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | شیء مرجع فعلی را (اگر وجود داشته باشد) دریافت می‌کند یا استثنا می‌افکند. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | شیء اشاره‌شده را (اگر وجود داشته باشد) یا nullptr برمی‌گرداند. مشابه [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | شیء مرجع را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | شیء اشاره‌شده را (اگر وجود داشته باشد) یا nullptr برمی‌گرداند. مشابه [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء اشاره‌شده از نوع خاصی یا نوع فرزند آن است. مطابق معنای 'is' در C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | بررسی می‌کند که آیا اشاره‌گر به شیء دیگری غیر از مالک خود اشاره دارد (توسط سازنده aliasing ایجاد شده). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت مشترک است. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت ضعیف (weak) است. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | بررسی می‌کند که آیا اشاره‌گر null نیست. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | بررسی می‌کند که آیا اشاره‌گر null است. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | مرجع به شیء اشاره‌شده را دریافت می‌کند. اطمینان می‌دهد که اشاره‌گر null نیست. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | دسترسی به اعضای شیء مرجع را فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | معنای مقایسه کمتر را برای کلاس [SmartPtr](../../system/smartptr/) فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | معنای مقایسه کمتر را برای کلاس [SmartPtr](../../system/smartptr/) فراهم می‌کند. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | به‌صورت Move-assign شیء [SmartPtr](../../system/smartptr/) را اختصاص می‌دهد. x قابل استفاده نیست. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | به‌صورت Copy-assign شیء [SmartPtr](../../system/smartptr/) را اختصاص می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | به‌صورت Copy-assign شیء [SmartPtr](../../system/smartptr/) را اختصاص می‌دهد. تبدیل‌های نوع مورد نیاز را انجام می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | اشاره‌گر خام را به شیء [SmartPtr](../../system/smartptr/) اختصاص می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | مقدار اشاره‌گر را به nullptr تنظیم می‌کند. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | بررسی می‌کند که آیا اشاره‌گر به nullptr اشاره دارد. |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) const | تابع دسترسی. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | امکانات aliasing (ایجاد شده توسط سازنده aliasing) را از اشاره‌گر حذف می‌کند و اطمینان می‌دهد که همان شیء را (اگر مشترک باشد) مدیریت یا (اگر ضعیف باشد) ردیابی می‌کند. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | شیء اشاره‌شده را تنظیم می‌کند. |
| void [reset](../../system/smartptr/reset/)() | اشاره‌گر را به nullptr تنظیم می‌کند. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | حالت اشاره‌گر را تنظیم می‌کند. ممکن است شمارش مراجع شیء مرجع را تغییر دهد. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | متد SetTemplateWeakPtr() را بر روی شیء اشاره‌شده (اگر موجود باشد) فراخوانی می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) با حالت مورد نیاز را ایجاد می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) با اشاره‌گر null و حالت مورد نیاز را ایجاد می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را که به شیء مشخص اشاره دارد ایجاد می‌کند، یا اشاره‌گر خام را به [SmartPtr](../../system/smartptr/) تبدیل می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت کپی ساخت می‌کند. هر دو اشاره‌گر پس از آن به همان شیء اشاره می‌کنند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت کپی ساخت می‌کند. هر دو اشاره‌گر پس از آن به همان شیء اشاره می‌کنند. در صورت امکان تبدیل نوع انجام می‌دهد. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت Move ساخت می‌کند. عملاً دو اشاره‌گر را اگر هر دو در یک حالت باشند جابجا می‌کند. x ممکن است پس از فراخوانی غیرقابل استفاده باشد. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | نوع آرایه مرجع را با ایجاد آرایه‌ای جدید از نوع متفاوت تبدیل می‌کند. مفید است وقتی در C# تبدیل نوع آرایه‌ای وجود دارد که در C++ پشتیبانی نمی‌شود. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | آرایه خالی را مقداردهی اولیه می‌کند. برای ترجمه برخی ساختارهای کد C# استفاده می‌شود. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را می‌سازد که اطلاعات مالکیت را با مقدار اولیه ptr به اشتراک می‌گذارد، اما یک اشاره‌گر نامرتبط و بدون مدیریت p را نگه می‌دارد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | اشاره‌گر را به نوع دیگری با استفاده از static_cast بر روی شیء اشاره‌شده تبدیل می‌کند. |
|  [StringCollectionPtr](./stringcollectionptr/)() | اشاره‌گر null را می‌سازد. |
|  [StringCollectionPtr](./stringcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[StringCollection](../stringcollection/)\>\&) | اشاره‌گر به مجموعه خاصی را می‌سازد. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | هر نوع اشاره‌گری را به اشاره‌گر به [Object](../../system/object/) تبدیل می‌کند. نیازی به کامل بودن نوع Pointee_ نیست. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | میان‌بر برای دریافت شیء [System::TypeInfo](../../system/typeinfo/) برای نوع Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | شیء [SmartPtr](../../system/smartptr/) را از بین می‌برد. در صورت نیاز شمارنده مرجع شیء اشاره‌شده را کاهش می‌دهد و شیء را حذف می‌کند. |
## موارد مرتبط

* Class [SmartPtr](../../system/smartptr/)
* Namespace [System::Collections::Specialized](../)
* Library [Aspose.Slides](../../)