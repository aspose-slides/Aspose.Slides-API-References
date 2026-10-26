---
title: SortedSetPtr
second_title: Aspose.Slides برای C++ مرجع API
description: اشاره‌گری برای نگه داشتن مراجع SortedSet. این نوع یک اشاره‌گر برای مدیریت حذف اشیای دیگر است. باید روی پشته تخصیص داده شود و به توابع یا به صورت مقدار یا به صورت ارجاع const پاس داده شود.
type: docs
weight: 586
url: /fa/system.collections.generic/sortedsetptr/
---
## SortedSetPtr کلاس

Pointer to keep [SortedSet](../sortedset/) references. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class SortedSetPtr : public System::SmartPtr<SortedSet<T>>
```

## متدها

| متد | توضیح |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | دسترس‌گر برای [begin()](../../system/smartptr/begin/) متد از یک مجموعه زیرساختی. فقط زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با [begin()](../../system/smartptr/begin/) متد باشد. |
| auto [begin](../../system/smartptr/begin/)() const | دسترس‌گر برای [begin()](../../system/smartptr/begin/) متد از یک مجموعه زیرساختی. فقط زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با [begin()](../../system/smartptr/begin/) متد باشد. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به همان نوع خودش تبدیل می‌کند. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع پایه با استفاده از static_cast تبدیل می‌کند. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق‌شده با dynamic_cast تبدیل می‌کند. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق‌شده با dynamic_cast تبدیل می‌کند. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | دسترس‌گر برای [cbegin()](../../system/smartptr/cbegin/) متد از یک مجموعه زیرساختی. فقط زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با [cbegin()](../../system/smartptr/cbegin/) متد باشد. |
| auto [cend](../../system/smartptr/cend/)() const | دسترس‌گر برای [cend()](../../system/smartptr/cend/) متد از یک مجموعه زیرساختی. فقط زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با [cend()](../../system/smartptr/cend/) متد باشد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از const_cast بر روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از dynamic_cast بر روی شیء اشاره‌شده تبدیل می‌کند. |
| auto [end](../../system/smartptr/end/)() | دسترس‌گر برای [end()](../../system/smartptr/end/) متد از یک مجموعه زیرساختی. فقط زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با [end()](../../system/smartptr/end/) متد باشد. |
| auto [end](../../system/smartptr/end/)() const | دسترس‌گر برای [end()](../../system/smartptr/end/) متد از یک مجموعه زیرساختی. فقط زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با [end()](../../system/smartptr/end/) متد باشد. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | شیء اشاره‌شده را دریافت می‌کند. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | حالت اشاره‌گر را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | شیء اشاره‌شده را دریافت می‌کند، اما اطمینان می‌دهد که اشاره‌گر در حالت اشتراکی است. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | تعداد اشاره‌گرهای اشتراکی موجود به شیء ارجاع‌شده را، شامل اشاره‌گر فعلی، دریافت می‌کند. اطمینان می‌دهد که اشاره‌گر فعلی در حالت اشتراکی است. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | متد [GetHashCode()](../../system/smartptr/gethashcode/) را بر روی شیء اشاره‌شده فراخوانی می‌کند. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | شیء ارجاع‌شده فعلی (در صورت وجود) را دریافت می‌کند یا خطا می‌اندازد. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | شیء اشاره‌شده (در صورت وجود) را دریافت می‌کند یا nullptr. مشابه [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | شیء ارجاع‌شده را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | شیء اشاره‌شده (در صورت وجود) را دریافت می‌کند یا nullptr. مشابه [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء اشاره‌شده از نوع خاص یا نوع فرزند آن است. از semantics 'is' در C# پیروی می‌کند. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | بررسی می‌کند که آیا اشاره‌گر به شیء دیگری غیر از مالك (ایجاد شده توسط سازنده aliasing) اشاره دارد. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت اشتراکی است. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت ضعیف (weak) است. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | بررسی می‌کند که آیا اشاره‌گر مقدار null ندارد. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | بررسی می‌کند که آیا اشاره‌گر null است. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | مرجع به شیء اشاره‌شده را دریافت می‌کند. اطمینان می‌دهد که اشاره‌گر null نیست. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | دسترسی به اعضای شیء ارجاع‌شده را فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | semantics مقایسه کمتر را برای کلاس [SmartPtr](../../system/smartptr/) فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | semantics مقایسه کمتر را برای کلاس [SmartPtr](../../system/smartptr/) فراهم می‌کند. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | به‌صورت Move-assign شیء [SmartPtr](../../system/smartptr/) را مقداردهی می‌کند. x غیرقابل استفاده می‌شود. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | به‌صورت Copy-assign شیء [SmartPtr](../../system/smartptr/) را مقداردهی می‌کند. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | به‌صورت Copy-assign شیء [SmartPtr](../../system/smartptr/) را مقداردهی می‌کند. تبدیل‌های نوع لازم را انجام می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | اشاره‌گر خام را به شیء [SmartPtr](../../system/smartptr/) اختصاص می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | مقدار اشاره‌گر را به nullptr تنظیم می‌کند. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | بررسی می‌کند که آیا اشاره‌گر به nullptr اشاره دارد. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | aliasing (ایجاد شده توسط سازنده aliasing) را از اشاره‌گر حذف می‌کند و اطمینان می‌دهد که در حالت shared مدیریت می‌کند یا در حالت weak ردیابی می‌کند همان شیء‌ای که به آن اشاره دارد. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | شیء اشاره‌شده را تنظیم می‌کند. |
| void [reset](../../system/smartptr/reset/)() | اشاره‌گر را طوری تنظیم می‌کند که به nullptr اشاره داشته باشد. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | حالت اشاره‌گر را تنظیم می‌کند. ممکن است شمارنده‌های مرجع شیء ارجاع‌شده را تغییر دهد. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | متد SetTemplateWeakPtr() را بر روی شیء اشاره‌شده (در صورت وجود) فراخوانی می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) با حالت مورد نیاز را ایجاد می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) null-pointer با حالت مورد نیاز را ایجاد می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را که به شیء مشخص اشاره می‌کند ایجاد می‌کند، یا اشاره‌گر خام را به [SmartPtr](../../system/smartptr/) تبدیل می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت copy ساخت می‌کند. هر دو اشاره‌گر پس از آن به یک شیء اشاره می‌کنند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت copy ساخت می‌کند. هر دو اشاره‌گر پس از آن به یک شیء اشاره می‌کنند. در صورت امکان تبدیل نوع را انجام می‌دهد. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت move ساخت می‌کند. عملاً دو اشاره‌گر را اگر هر دو از یک حالت باشند تعویض می‌کند. x ممکن است پس از فراخوانی غیرقابل استفاده باشد. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | نوع آرایه ارجاع‌شده را با ایجاد آرایه‌ای از نوع متفاوت تبدیل می‌کند. مفید است اگر در C# تبدیل نوع آرایه‌ای وجود داشته باشد که در C++ پشتیبانی نشود. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | یک آرایه خالی را مقداردهی می‌کند. برای ترجمه برخی سازه‌های کد C# استفاده می‌شود. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | یک [SmartPtr](../../system/smartptr/) را می‌سازد که اطلاعات مالکیت را با مقدار اولیه ptr به اشتراک می‌گذارد، اما یک اشاره‌گر نامرتبط و بدون مدیریت p را نگه می‌دارد. |
|  [SortedSetPtr](./sortedsetptr/)() | سازنده اشاره‌گر null. |
|  [SortedSetPtr](./sortedsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[SortedSet](../sortedset/)\<T\>\>\&) | سازنده کپی. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از static_cast بر روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | هر نوع اشاره‌گری را به اشاره‌گر به [Object](../../system/object/) تبدیل می‌کند. نیازی به کامل بودن نوع Pointee_ نیست. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | میان‌بر برای دریافت شیء [System::TypeInfo](../../system/typeinfo/) برای نوع Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | شیء [SmartPtr](../../system/smartptr/) را از بین می‌برد. در صورت نیاز شمارنده مرجع شیء اشاره‌شده را کاهش می‌دهد و شیء را حذف می‌کند. |

## مراجع

* کلاس [SmartPtr](../../system/smartptr/)
* فضای‌نام [System::Collections::Generic](../)
* کتابخانه [Aspose.Slides](../../)