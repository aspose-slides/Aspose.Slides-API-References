---
title: X509ExtensionCollectionPtr
second_title: مرجع API Aspose.Slides برای C++
description: اشاره‌گری به مجموعه‌ای از افزونه‌های X509. این نوع یک اشاره‌گر برای مدیریت حذف شیء دیگر است. باید در پشته اختصاص داده شود و به توابع به صورت مقدار یا ارجاع ثابت پاس داده شود.
type: docs
weight: 170
url: /fa/system.security.cryptography.x509certificates/x509extensioncollectionptr/
---
## X509ExtensionCollectionPtr کلاس

Pointer to collection of X509 extensions. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
class X509ExtensionCollectionPtr : public System::SmartPtr<X509ExtensionCollection>
```

## روش‌ها

| متد | توضیح |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | دسترس‌ساز متد [begin()](../../system/smartptr/begin/) از مجموعه زیرین. فقط وقتی SmartPtr_ نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد، کامپایل می‌شود. |
| auto [begin](../../system/smartptr/begin/)() const | دسترس‌ساز متد [begin()](../../system/smartptr/begin/) از مجموعه زیرین. فقط وقتی SmartPtr_ نوع تخصصی با متد [begin()](../../system/smartptr/begin/) باشد، کامپایل می‌شود. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | اشاره‌گر را به همان نوع خود تبدیل می‌کند. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | با استفاده از static_cast اشاره‌گر را به نوع پایه تبدیل می‌کند. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | با استفاده از dynamic_cast اشاره‌گر را به نوع مشتق تبدیل می‌کند. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | با استفاده از dynamic_cast اشاره‌گر را به نوع مشتق تبدیل می‌کند. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | دسترس‌ساز متد [cbegin()](../../system/smartptr/cbegin/) از مجموعه زیرین. فقط وقتی SmartPtr_ نوع تخصصی با متد [cbegin()](../../system/smartptr/cbegin/) باشد، کامپایل می‌شود. |
| auto [cend](../../system/smartptr/cend/)() const | دسترس‌ساز متد [cend()](../../system/smartptr/cend/) از مجموعه زیرین. فقط وقتی SmartPtr_ نوع تخصصی با متد [cend()](../../system/smartptr/cend/) باشد، کامپایل می‌شود. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | با استفاده از const_cast بر روی شیء اشاره‌شده، اشاره‌گر را به نوع متفاوتی تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | با استفاده از dynamic_cast بر روی شیء اشاره‌شده، اشاره‌گر را به نوع متفاوتی تبدیل می‌کند. |
| auto [end](../../system/smartptr/end/)() | دسترس‌ساز متد [end()](../../system/smartptr/end/) از مجموعه زیرین. فقط وقتی SmartPtr_ نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد، کامپایل می‌شود. |
| auto [end](../../system/smartptr/end/)() const | دسترس‌ساز متد [end()](../../system/smartptr/end/) از مجموعه زیرین. فقط وقتی SmartPtr_ نوع تخصصی با متد [end()](../../system/smartptr/end/) باشد، کامپایل می‌شود. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | شیء اشاره‌شده را به‌دست می‌آورد. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | حالت اشاره‌گر را به‌دست می‌آورد. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | شیء اشاره‌شده را به‌دست می‌آورد، اما تضمین می‌کند که اشاره‌گر در حالت اشتراکی است. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | تعداد اشاره‌گرهای اشتراکی موجود به شیء مرجع را دریافت می‌کند، شامل اشاره‌گر فعلی هم می‌شود. تضمین می‌کند که اشاره‌گر فعلی در حالت اشتراکی است. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | متد [GetHashCode()](../../system/smartptr/gethashcode/) را بر روی شیء اشاره‌شده فراخوانی می‌کند. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | شیء مرجع فعلی (در صورت وجود) را به‌دست می‌آورد یا استثنا می‌اندازد. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | شیء اشاره‌شده (در صورت وجود) را به‌دست می‌آورد یا nullptr برمی‌گرداند. مشابه [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | شیء مرجع را به‌دست می‌آورد. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | شیء اشاره‌شده (در صورت وجود) را به‌دست می‌آورد یا nullptr برمی‌گرداند. مشابه [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء اشاره‌شده از نوع خاص یا نوع فرزند آن است. پیروی از معنای 'is' در C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | بررسی می‌کند آیا اشاره‌گر به شیء دیگری غیر از شیء مالک (ایجاد شده توسط سازنده‌ی aliasing) اشاره دارد. |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | بررسی می‌کند آیا اشاره‌گر در حالت اشتراکی است. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | بررسی می‌کند آیا اشاره‌گر در حالت ضعیف (weak) است. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | بررسی می‌کند آیا اشاره‌گر خالی (null) نیست. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | بررسی می‌کند آیا اشاره‌گر خالی (null) است. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | مرجع به شیء اشاره‌شده را به‌دست می‌آورد. تضمین می‌کند که اشاره‌گر خالی نیست. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | امکان دسترسی به اعضای شیء مرجع را فراهم می‌کند. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | رفتار مقایسه کمتر برای کلاس [SmartPtr](../../system/smartptr/) را ارائه می‌دهد. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | رفتار مقایسه کمتر برای کلاس [SmartPtr](../../system/smartptr/) را ارائه می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | با Move-assign به شیء [SmartPtr](../../system/smartptr/) اختصاص می‌دهد. x دیگر قابل استفاده نیست. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | با Copy-assign به شیء [SmartPtr](../../system/smartptr/) اختصاص می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | با Copy-assign به شیء [SmartPtr](../../system/smartptr/) اختصاص می‌دهد. تبدیل‌های نوع لازم را انجام می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | اشاره‌گر خام را به شیء [SmartPtr](../../system/smartptr/) اختصاص می‌دهد. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | مقدار اشاره‌گر را به nullptr تنظیم می‌کند. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | بررسی می‌کند آیا اشاره‌گر به nullptr اشاره دارد. |
| [SharedPtr](../../system/sharedptr/)\<[X509Extension](../x509extension/)\>\& [operator[]](./operator[]/)(**int32_t**) const | دسترس‌ساز. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | حذف aliasing (ایجاد شده توسط سازنده‌ی aliasing) از اشاره‌گر، اطمینان می‌دهد که اگر اشتراکی باشد مدیریت می‌کند یا اگر ضعیف باشد پیگیری می‌کند همان شیء‌ای که به آن اشاره دارد. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | شیء اشاره‌شده را تنظیم می‌کند. |
| void [reset](../../system/smartptr/reset/)() | اشاره‌گر را به nullptr تنظیم می‌کند. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | حالت اشاره‌گر را تنظیم می‌کند. ممکن است شمارش‌های مرجع شیء مرجع را تغییر دهد. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | متد SetTemplateWeakPtr() را بر روی شیء اشاره‌شده (در صورت وجود) فراخوانی می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) با حالت مورد نیاز را ایجاد می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) با مقدار null-pointer و حالت مورد نیاز را ایجاد می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) که به شیء مشخص اشاره دارد را ایجاد می‌کند یا اشاره‌گر خام را به [SmartPtr](../../system/smartptr/) تبدیل می‌کند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت کپی می‌سازد. هر دو اشاره‌گر پس از آن به یک شیء اشاره می‌کنند. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت کپی می‌سازد. هر دو اشاره‌گر پس از آن به یک شیء اشاره می‌کنند. در صورت امکان تبدیل نوع را انجام می‌دهد. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | شیء [SmartPtr](../../system/smartptr/) را به‌صورت Move می‌سازد. عملاً دو اشاره‌گر را اگر هر دو در همان حالت باشند، جابجا می‌کند. x ممکن است پس از فراخوانی غیرقابل استفاده باشد. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | نوع آرایه مرجع را با ایجاد آرایه‌ای جدید از نوع متفاوت تبدیل می‌کند. مفید وقتی در C# تبدیل نوع آرایه‌ای وجود دارد که در C++ پشتیبانی نمی‌شود. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | آرایه خالی را مقداردهی اولیه می‌کند. برای ترجمه برخی ساختارهای کد C# استفاده می‌شود. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) را می‌سازد که اطلاعات مالکیت را با مقدار اولیه ptr به اشتراک می‌گذارد، اما یک اشاره‌گر نامرتبط و غیرمدیریت‌شده p را نگه می‌دارد. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با static_cast بر روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | هر نوع اشاره‌گری را به اشاره‌گر به [Object](../../system/object/) تبدیل می‌کند. نیازی به تکمیل نوع Pointee_ نیست. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | میان‌بر برای دریافت شیء [System::TypeInfo](../../system/typeinfo/) برای نوع Pointee_. |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)() | سازنده‌ی اشاره‌گر null. |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509ExtensionCollection](../x509extensioncollection/)\>\&) | سازنده. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | شیء [SmartPtr](../../system/smartptr/) را از بین می‌برد. در صورت نیاز، شمارنده مرجع شیء اشاره‌شده را کاهش داده و شیء را حذف می‌کند. |

## موارد مرتبط

* کلاس [SmartPtr](../../system/smartptr/)
* فضای نام [System::Security::Cryptography::X509Certificates](../)
* کتابخانه [Aspose.Slides](../../)