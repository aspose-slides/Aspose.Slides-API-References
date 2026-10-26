---
title: X509Certificate2CollectionPtr
second_title: مرجع API Aspose.Slides برای C++
description: اشاره‌گری به مجموعه‌ای از گواهینامه‌های X509. این نوع یک اشاره‌گر برای مدیریت حذف شیء دیگر است. باید روی پشته تخصیص یابد و به توابع یا به صورت مقدار یا به صورت ارجاع ثابت پاس شود.
type: docs
weight: 66
url: /fa/system.security.cryptography.x509certificates/x509certificate2collectionptr/
---
## X509Certificate2CollectionPtr کلاس

اشاره‌گر به مجموعه‌ای از گواهینامه‌های X509. این نوع یک اشاره‌گر است برای مدیریت حذف شیء دیگر. باید روی پشته تخصیص یابد و به توابع یا به صورت مقدار یا به صورت ارجاع ثابت پاس شود.

```cpp
class X509Certificate2CollectionPtr : public System::SmartPtr<X509Certificate2Collection>
```

## متدها

| متد | توضیح |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | دسترس‌دهنده برای متد [begin()](../../system/smartptr/begin/) یک مجموعه زیرین. تنها در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد. |
| auto [begin](../../system/smartptr/begin/)() const | دسترس‌دهنده برای متد [begin()](../../system/smartptr/begin/) یک مجموعه زیرین. تنها در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع خودش تبدیل می‌کند. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع پایه با استفاده از static_cast تبدیل می‌کند. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق با dynamic_cast تبدیل می‌کند. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به نوع مشتق با dynamic_cast تبدیل می‌کند. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | دسترس‌دهنده برای متد [cbegin()](../../system/smartptr/cbegin/) یک مجموعه زیرین. تنها در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [cbegin()](../../system/smartptr/cbegin/) باشد. |
| auto [cend](../../system/smartptr/cend/)() const | دسترس‌دهنده برای متد [cend()](../../system/smartptr/cend/) یک مجموعه زیرین. تنها در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [cend()](../../system/smartptr/cend/) باشد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | اشاره‌گر را با استفاده از const_cast بر روی شیء اشاره‌شده به نوع متفاوت تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | اشاره‌گر را با استفاده از dynamic_cast بر روی شیء اشاره‌شده به نوع متفاوت تبدیل می‌کند. |
| auto [end](../../system/smartptr/end/)() | دسترس‌دهنده برای متد [end()](../../system/smartptr/end/) یک مجموعه زیرین. تنها در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد. |
| auto [end](../../system/smartptr/end/)() const | دسترس‌دهنده برای متد [end()](../../system/smartptr/end/) یک مجموعه زیرین. تنها در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | شیء اشاره‌شده را دریافت می‌کند. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | حالت اشاره‌گر را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | شیء اشاره‌شده را دریافت می‌کند، اما اطمینان می‌دهد که اشاره‌گر در حالت اشتراک‌گذاری است. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | تعداد اشاره‌گرهای اشتراکی موجود به شیء مرجع را دریافت می‌کند، شامل اشاره‌گر جاری. اطمینان می‌شود که اشاره‌گر جاری در حالت اشتراک‌گذاری است. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | متد [GetHashCode()](../../system/smartptr/gethashcode/) را بر روی شیء اشاره‌شده فراخوانی می‌کند. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | شیء مرجع فعلی را دریافت می‌کند (اگر موجود باشد) یا استثنا می‌اندازد. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | شیء اشاره‌شده را دریافت می‌کند (اگر موجود باشد) یا nullptr. همانند [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | شیء مرجع را دریافت می‌کند. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | شیء اشاره‌شده را دریافت می‌کند (اگر موجود باشد) یا nullptr. همانند [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء اشاره‌شده از نوع خاص یا نوع فرزند آن است. از معانی «is» در C# پیروی می‌کند. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | بررسی می‌کند که آیا اشاره‌گر به شیء دیگری غیر از مالک خود اشاره دارد (ایجاد شده توسط سازنده aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت اشتراک‌گذاری است. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت ضعیف (weak) است. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | بررسی می‌کند که آیا اشاره‌گر null نیست. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | بررسی می‌کند که آیا اشاره‌گر null است. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | مرجع به شیء اشاره‌شده را دریافت می‌کند. اطمینان می‌شود که اشاره‌گر null نیست. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | امکان دسترسی به اعضای شیء مرجع را فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | معنای مقایسه‌ای کمتر برای کلاس [SmartPtr](../../system/smartptr/) فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | معنای مقایسه‌ای کمتر برای کلاس [SmartPtr](../../system/smartptr/) فراهم می‌کند. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | به [SmartPtr](../../system/smartptr/) شیء انتساب-حرکتی می‌دهد. x غیرقابل استفاده می‌شود. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | به [SmartPtr](../../system/smartptr/) شیء انتساب-کپی می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | به [SmartPtr](../../system/smartptr/) شیء انتساب-کپی می‌دهد. تبدیل‌های نوع لازم را انجام می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | اشاره‌گر خام را به شیء [SmartPtr](../../system/smartptr/) اختصاص می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | مقدار اشاره‌گر را برابر nullptr قرار می‌دهد. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | بررسی می‌کند که آیا اشاره‌گر به nullptr اشاره دارد. |
| [SharedPtr](../../system/sharedptr/)\<[X509Certificate2](../x509certificate2/)\>\& [operator[]](./operator[]/)(size_t) const | دسترس‌دهنده. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | استفاده از aliasing (ایجاد شده توسط سازنده aliasing) را از اشاره‌گر حذف می‌کند و اطمینان می‌دهد که در حالت اشتراک‌گذاری مدیریت می‌کند یا در حالت ضعیف ردیابی می‌کند همان شیء که به آن اشاره دارد. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | شیء اشاره‌شده را تنظیم می‌کند. |
| void [reset](../../system/smartptr/reset/)() | اشاره‌گر را به nullptr تنظیم می‌کند. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | حالت اشاره‌گر را تنظیم می‌کند. ممکن است شمارش ارجاع‌های شیء مرجع را تغییر دهد. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | متد SetTemplateWeakPtr() را بر روی شیء اشاره‌شده (اگر موجود باشد) فراخوانی می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) با حالت مورد نیاز ایجاد می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) null-pointer با حالت مورد نیاز ایجاد می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را که به شیء مشخص اشاره دارد ایجاد می‌کند، یا اشاره‌گر خام را به [SmartPtr](../../system/smartptr/) تبدیل می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را با کپی‌سازی می‌سازد. هر دو اشاره‌گر بعد از آن به همان شیء اشاره می‌کنند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را با کپی‌سازی می‌سازد. هر دو اشاره‌گر بعد از آن به همان شیء اشاره می‌کنند. در صورت امکان تبدیل نوع را انجام می‌دهد. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را با حرکتی می‌سازد. در واقع دو اشاره‌گر را اگر هر دو در یک حالت باشند جابجا می‌کند. x ممکن است پس از فراخوانی غیرقابل استفاده باشد. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | نوع آرایه مرجع را با ایجاد آرایه‌ای جدید از نوع متفاوت تبدیل می‌کند. اگر در C# تبدیل نوع آرایه‌ای وجود داشته باشد که در C++ پشتیبانی نشود، مفید است. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | آرایه خالی را مقداردهی اولیه می‌کند. برای ترجمه برخی ساختارهای کد C# استفاده می‌شود. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | یک [SmartPtr](../../system/smartptr/) می‌سازد که اطلاعات مالکیت را با مقدار اولیه ptr به اشتراک می‌گذارد، اما اشاره‌گر p نا مرتبط و بدون مدیریت را نگه می‌دارد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | اشاره‌گر را با استفاده از static_cast بر روی شیء اشاره‌شده به نوع متفاوت تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | هر نوع اشاره‌گری را به اشاره‌گر [Object](../../system/object/) تبدیل می‌کند. نیازی به کامل بودن نوع Pointee_ ندارد. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | میان‌بر برای دریافت شیء [System::TypeInfo](../../system/typeinfo/) برای نوع Pointee_. |
|  [X509Certificate2CollectionPtr](./x509certificate2collectionptr/)() | سازنده اشاره‌گر null. |
|  [X509Certificate2CollectionPtr](./x509certificate2collectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate2Collection](../x509certificate2collection/)\>\&) | سازنده. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | شیء [SmartPtr](../../system/smartptr/) را از بین می‌برد. در صورت نیاز شمارنده ارجاع شیء اشاره‌شده را کاهش می‌دهد و شیء را حذف می‌کند. |

## مراجعه‌ها

* کلاس [SmartPtr](../../system/smartptr/)
* فضای‌نام [System::Security::Cryptography::X509Certificates](../)
* کتابخانه [Aspose.Slides](../../)