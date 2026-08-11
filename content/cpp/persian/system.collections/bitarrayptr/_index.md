---
title: BitArrayPtr
second_title: Aspose.Slides برای C++ مرجع API
description: اشاره‌گر به BitArray. این نوع یک اشاره‌گر برای مدیریت حذف شیء دیگر است. باید در پشته تخصیص یابد و به توابع یا به صورت مقدار یا به صورت ارجاع ثابت پاس داده شود.
type: docs
weight: 14
url: /fa/system.collections/bitarrayptr/
---
## BitArrayPtr کلاس

Pointer to [BitArray](../bitarray/). این نوع یک اشاره‌گر برای مدیریت حذف شیء دیگر است. باید بر روی پشته تخصیص یابد و به توابع یا به‌صورت مقدار یا به‌صورت ارجاع ثابت پاس داده شود.

```cpp
class BitArrayPtr : public System::SmartPtr<BitArray>
```

## متدها

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | دسترس‌کننده برای متد [begin()](../../system/smartptr/begin/) از یک مجموعه زیرین. فقط در صورتی که SmartPtr_ یک نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد، کامپایل می‌شود. |
| auto [begin](../../system/smartptr/begin/)() const | دسترس‌کننده برای متد [begin()](../../system/smartptr/begin/) از یک مجموعه زیرین. فقط در صورتی که SmartPtr_ یک نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد، کامپایل می‌شود. |
|  [BitArrayPtr](./bitarrayptr/)() | اشاره‌گر را به مقدار null مقداردهی می‌کند. |
|  [BitArrayPtr](./bitarrayptr/)(const [SharedPtr](../../system/sharedptr/)\<[BitArray](../bitarray/)\>\&) | سازنده تبدیل. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به همان نوع خود تبدیل می‌کند. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع پایه با استفاده از static_cast تبدیل می‌کند. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق شده با استفاده از dynamic_cast تبدیل می‌کند. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق شده با استفاده از dynamic_cast تبدیل می‌کند. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | دسترس‌کننده برای متد [cbegin()](../../system/smartptr/cbegin/) از یک مجموعه زیرین. فقط در صورتی که SmartPtr_ یک نوع تخصصی با متد [cbegin()](../../system/smartptr/cbegin/) باشد، کامپایل می‌شود. |
| auto [cend](../../system/smartptr/cend/)() const | دسترس‌کننده برای متد [cend()](../../system/smartptr/cend/) از یک مجموعه زیرین. فقط در صورتی که SmartPtr_ یک نوع تخصصی با متد [cend()](../../system/smartptr/cend/) باشد، کامپایل می‌شود. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از const_cast روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از dynamic_cast روی شیء اشاره‌شده تبدیل می‌کند. |
| auto [end](../../system/smartptr/end/)() | دسترس‌کننده برای متد [end()](../../system/smartptr/end/) از یک مجموعه زیرین. فقط در صورتی که SmartPtr_ یک نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد، کامپایل می‌شود. |
| auto [end](../../system/smartptr/end/)() const | دسترس‌کننده برای متد [end()](../../system/smartptr/end/) از یک مجموعه زیرین. فقط در صورتی که SmartPtr_ یک نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد، کامپایل می‌شود. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | شیء اشاره‌شده را دریافت می‌کند. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | حالت اشاره‌گر را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | شیء اشاره‌شده را دریافت می‌کند، اما تضمین می‌کند که اشاره‌گر در حالت به‌اشتراک‌گذاری است. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | تعداد اشاره‌گرهای به‌اشتراک‌گذاری موجود به شیء مرجع را به‌همراه اشاره‌گر کنونی بازمی‌گرداند. تضمین می‌کند که اشاره‌گر کنونی در حالت به‌اشتراک‌گذاری باشد. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | [GetHashCode()](../../system/smartptr/gethashcode/) را بر روی شیء اشاره‌شده فراخوانی می‌کند. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | شیء مرجع فعلی (در صورت وجود) را دریافت می‌کند یا استثنا پرتاب می‌کند. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | شیء اشاره‌شده (در صورت وجود) را دریافت می‌کند یا nullptr برمی‌گرداند. معادل [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | شیء مرجع را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | شیء اشاره‌شده (در صورت وجود) را دریافت می‌کند یا nullptr برمی‌گرداند. معادل [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء اشاره‌شده از نوع خاص یا نوع فرزند آن است. رفتار مشابه عملگر 'is' در C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | بررسی می‌کند که آیا اشاره‌گر به شیئی به‌جز شیء مالک (ساخته شده توسط سازندهٔ aliasing) اشاره دارد. |
| **bool** [IsNull](./isnull/)() const | بررسی می‌کند که آیا مقدار خاص null است. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت به‌اشتراک‌گذاری است. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت ضعیف (weak) است. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | بررسی می‌کند که آیا اشاره‌گر null نیست. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | بررسی می‌کند که آیا اشاره‌گر null است. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | مرجع به شیء اشاره‌شده را دریافت می‌کند. تضمین می‌کند که اشاره‌گر null نیست. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | امکان دسترسی به اعضای شیء مرجع را فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | معنای مقایسه کمتر برای کلاس [SmartPtr](../../system/smartptr/) فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | معنای مقایسه کمتر برای کلاس [SmartPtr](../../system/smartptr/) فراهم می‌کند. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت move-assign می‌کند. x غیرقابل استفاده می‌شود. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت copy-assign می‌کند. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت copy-assign می‌کند. تبدیل‌های نوع مورد نیاز را انجام می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | اشاره‌گر خام را به شیء [SmartPtr](../../system/smartptr/) اختصاص می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | مقدار اشاره‌گر را به nullptr تنظیم می‌کند. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | بررسی می‌کند که آیا اشاره‌گر به nullptr اشاره دارد. |
| **BitArray::Reference** [operator[]](./operator[]/)(int) const | دسترس‌کنندهٔ بیت. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | aliasing ساخته شده توسط سازندهٔ aliasing را از اشاره‌گر حذف می‌کند و اطمینان می‌دهد که (در حالت به‌اشتراک‌گذاری) یا (در حالت ضعیف) همان شیء را مدیریت یا ردیابی می‌کند. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | شیء اشاره‌شده را تنظیم می‌کند. |
| void [reset](../../system/smartptr/reset/)() | اشاره‌گر را به nullptr تنظیم می‌کند. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | حالت اشاره‌گر را تنظیم می‌کند. ممکن است شمارش‌های مرجع شیء مرجع را تغییر دهد. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | متد SetTemplateWeakPtr() را بر روی شیء اشاره‌شده (در صورت وجود) فراخوانی می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) با حالت مورد نیاز را می‌سازد. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) null-pointer با حالت مورد نیاز را می‌سازد. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را که به شیء مشخص اشاره می‌کند می‌سازد، یا اشاره‌گر خام را به [SmartPtr](../../system/smartptr/) تبدیل می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت copy می‌سازد. هر دو اشاره‌گر پس از آن به همان شیء اشاره می‌کنند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت copy می‌سازد. هر دو اشاره‌گر پس از آن به همان شیء اشاره می‌کنند. در صورت امکان تبدیل نوع انجام می‌دهد. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت move می‌سازد. عملاً دو اشاره‌گر را تعویض می‌کند، اگر هر دو در همان حالت باشند. x ممکن است پس از فراخوانی غیرقابل استفاده شود. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | نوع آرایه مرجع را با ایجاد آرایه‌ای جدید از نوع متفاوت تبدیل می‌کند. مفید است وقتی در C# تبدیل نوع آرایه‌ای وجود دارد که در C++ پشتیبانی نمی‌شود. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | آرایهٔ خالی را مقداردهی اولیه می‌کند. برای ترجمهٔ برخی سازه‌های کد C# استفاده می‌شود. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | یک [SmartPtr](../../system/smartptr/) می‌سازد که اطلاعات مالکیت را با مقدار اولیهٔ ptr به‌اشتراک می‌گذارد، اما اشاره‌گر نامرتبط و بدون مدیریت p را نگه می‌دارد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از static_cast روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | هر نوع اشاره‌گری را به اشاره‌گر به [Object](../../system/object/) تبدیل می‌کند. نیازی به این نیست که نوع Pointee_ کامل باشد. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | میان‌راهی برای دریافت شیء [System::TypeInfo](../../system/typeinfo/) برای نوع Pointee_ است. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | شیء [SmartPtr](../../system/smartptr/) را نابود می‌کند. در صورت نیاز، شمارندهٔ مرجع شیء اشاره‌شده را کاهش داده و شیء را حذف می‌کند. |
## مراجع

* کلاس [SmartPtr](../../system/smartptr/)
* فضای نام [System::Collections](../)
* کتابخانه [Aspose.Slides](../../)