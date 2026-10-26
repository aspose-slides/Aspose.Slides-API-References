---
title: DynamicWeakPtr
second_title: مرجع API Aspose.Slides برای C++
description: کلاس اشاره‌گر هوشمند که حالت‌های اشاره‌گر آرگومان‌های قالب شیء ذخیره‌شده را دنبال می‌کند و پس از هر تخصیص آنها را به‌روزرسانی می‌نماید. این نوع یک اشاره‌گر برای مدیریت حذف شیء دیگر است. باید بر روی پشته تخصیص یابد و به توابع یا به صورت مقدار یا به صورت ارجاع ثابت پاس داده شود.
type: docs
weight: 781
url: /fa/system/dynamicweakptr/
---
## کلاس DynamicWeakPtr

کلاس هوشمند اشاره‌گر که حالت‌های اشاره‌گر آرگومان‌های قالب شیء ذخیره‌شده را دنبال می‌کند و پس از هر تخصیص آنها را به‌روز می‌سازد. این نوع یک اشاره‌گر برای مدیریت حذف شیء دیگر است. باید بر روی پشته تخصیص یابد و به توابع یا به صورت مقدار یا به صورت ارجاع ثابت پاس داده شود.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| Pointee | نوع. |
| trunkMode | حالت خود اشاره‌گر هوشمند، مشترک یا ضعیف. |
| weakLeafs | شاخص‌های آرگومان‌های قالب نوع ذخیره‌شده که باید به حالت اشاره‌گر ضعیف تنظیم شوند. |

## متدها

| Method | Description |
| --- | --- |
| auto [begin](../smartptr/begin/)() | دسترس‌پذیر برای متد [begin()](../smartptr/begin/) یک مجموعه زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [begin()](../smartptr/begin/) باشد. |
| auto [begin](../smartptr/begin/)() const | دسترس‌پذیر برای متد [begin()](../smartptr/begin/) یک مجموعه زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [begin()](../smartptr/begin/) باشد. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | اشاره‌گر را به نوع خودش تبدیل می‌کند. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | اشاره‌گر را به نوع پایه با استفاده از static_cast تبدیل می‌کند. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | اشاره‌گر را به نوع مشتق‌شده با dynamic_cast تبدیل می‌کند. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | اشاره‌گر را به نوع مشتق‌شده با dynamic_cast تبدیل می‌کند. |
| auto [cbegin](../smartptr/cbegin/)() const | دسترس‌پذیر برای متد [cbegin()](../smartptr/cbegin/) یک مجموعه زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [cbegin()](../smartptr/cbegin/) باشد. |
| auto [cend](../smartptr/cend/)() const | دسترس‌پذیر برای متد [cend()](../smartptr/cend/) یک مجموعه زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [cend()](../smartptr/cend/) باشد. |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از const_cast روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از dynamic_cast روی شیء اشاره‌شده تبدیل می‌کند. |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | یک اشاره‌گر هوشمند تهی ایجاد می‌کند. |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | یک اشاره‌گر هوشمند که به شیء داده‌شده اشاره می‌کند ایجاد می‌کند. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | یک اشاره‌گر هوشمند را با سازندهٔ copy ایجاد می‌کند. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | یک اشاره‌گر هوشمند را با سازندهٔ copy ایجاد می‌کند. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | یک اشاره‌گر هوشمند را با سازندهٔ copy ایجاد می‌کند. |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | یک اشاره‌گر هوشمند را با سازندهٔ move ایجاد می‌کند. |
| auto [end](../smartptr/end/)() | دسترس‌پذیر برای متد [end()](../smartptr/end/) یک مجموعه زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [end()](../smartptr/end/) باشد. |
| auto [end](../smartptr/end/)() const | دسترس‌پذیر برای متد [end()](../smartptr/end/) یک مجموعه زیرین. فقط در صورتی کامپایل می‌شود که SmartPtr_ نوع تخصصی با متد [end()](../smartptr/end/) باشد. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | شیء اشاره‌شده را برمی‌گرداند. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | حالت اشاره‌گر را برمی‌گرداند. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | شیء اشاره‌شده را برمی‌گرداند، ولی اطمینان می‌دهد که اشاره‌گر در حالت shared است. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | تعداد اشاره‌گرهای shared موجود به شیء مرجع را (از جمله اشاره‌گر فعلی) برمی‌گرداند. اطمینان می‌دهد که اشاره‌گر فعلی در حالت shared است. |
| int [GetHashCode](../smartptr/gethashcode/)() const | متد [GetHashCode()](../smartptr/gethashcode/) را روی شیء اشاره‌شده فراخوانی می‌کند. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | شیء مرجع فعلی را (در صورت وجود) برمی‌گرداند یا استثنا می‌اندازد. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | شیء اشاره‌شده را (در صورت وجود) یا nullptr برمی‌گرداند. مشابه [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | شیء مرجع را برمی‌گرداند. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | شیء اشاره‌شده را (در صورت وجود) یا nullptr برمی‌گرداند. مشابه [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | بررسی می‌کند که آیا شیء اشاره‌شده از نوع خاص یا نوع فرزند آن است. مطابق معناگر 'is' در C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | بررسی می‌کند که آیا اشاره‌گر به شیء دیگری غیر از شیء مالک (ایجاد شده توسط سازندهٔ aliasing) اشاره می‌کند. |
| **bool** [IsShared](../smartptr/isshared/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت shared است. |
| **bool** [IsWeak](../smartptr/isweak/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت weak است. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | بررسی می‌کند که آیا اشاره‌گر خالی نیست. |
| **bool** [operator!](../smartptr/operator_not/)() const | بررسی می‌کند که آیا اشاره‌گر خالی است. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | مرجع به شیء اشاره‌شده را برمی‌گرداند. اطمینان می‌دهد که اشاره‌گر خالی نیست. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | دسترسی به اعضای شیء مرجع را فراهم می‌کند. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | معنای مقایسه کمتر برای کلاس [SmartPtr](../smartptr/) را فراهم می‌کند. |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | معنای مقایسه کمتر برای کلاس [SmartPtr](../smartptr/) را فراهم می‌کند. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | اشاره‌گر هوشمند را با انتساب انتقالی مقداردهی می‌کند. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | اشاره‌گر هوشمند را با انتساب کپی مقداردهی می‌کند. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | اشاره‌گر هوشمند را با انتساب کپی مقداردهی می‌کند. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | اشاره‌گر هوشمند را مقداردهی می‌کند. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | اشاره‌گر هوشمند را به null تنظیم می‌کند. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | بررسی می‌کند که آیا اشاره‌گر هوشمند خالی است. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | از اشاره‌گر aliasing (ایجاد شده توسط سازندهٔ aliasing) را حذف می‌کند و اطمینان می‌دهد که (اگر shared باشد) مدیریت یا (اگر weak باشد) ردیابی همان شیئی که به آن اشاره می‌کند را انجام می‌دهد. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | شیء اشاره‌شده را تنظیم می‌کند. |
| void [reset](../smartptr/reset/)() | اشاره‌گر را به nullptr تنظیم می‌کند. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | حالت اشاره‌گر را تنظیم می‌کند. ممکن است شمارش مرجع شیء مرجع را تغییر دهد. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | متد SetTemplateWeakPtr() را روی شیء اشاره‌شده (در صورت وجود) فراخوانی می‌کند. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | شیء [SmartPtr](../smartptr/) با حالت مورد نیاز ایجاد می‌کند. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | شیء [SmartPtr](../smartptr/) با اشاره‌گر null و حالت مورد نیاز ایجاد می‌کند. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | شیء [SmartPtr](../smartptr/) را که به شیء مشخص شده اشاره می‌کند ایجاد می‌کند، یا اشاره‌گر خام را به [SmartPtr](../smartptr/) تبدیل می‌کند. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | شیء [SmartPtr](../smartptr/) را با سازندهٔ copy می‌سازد. هر دو اشاره‌گر پس از آن به یک شیء اشاره می‌کنند. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | شیء [SmartPtr](../smartptr/) را با سازندهٔ copy می‌سازد. هر دو اشاره‌گر پس از آن به یک شیء اشاره می‌کنند. اگر اجازه باشد تبدیل نوع انجام می‌شود. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | شیء [SmartPtr](../smartptr/) را با سازندهٔ move می‌سازد. در واقع دو اشاره‌گر را اگر هر دو از یک حالت باشند جابجا می‌کند. ممکن است x پس از فراخوانی قابل استفاده نباشد. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | نوع آرایه مرجع را با ایجاد آرایه‌ای از نوع متفاوت تبدیل می‌کند. مفید است اگر در C# تبدیل نوع آرایه‌ای وجود داشته باشد که در C++ پشتیبانی نمی‌شود. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | آرایه خالی را مقداردهی می‌کند. برای ترجمه برخی ساختارهای کد C# استفاده می‌شود. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | یک [SmartPtr](../smartptr/) می‌سازد که اطلاعات مالکیت را با مقدار اولیه ptr به اشتراک می‌گذارد، اما یک اشاره‌گر نامرتبط و بدون مدیریت p را نگه می‌دارد. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | اشاره‌گر را به نوع متفاوتی با استفاده از static_cast روی شیء اشاره‌شده تبدیل می‌کند. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | هر نوع اشاره‌گری را به اشاره‌گری به [Object](../object/) تبدیل می‌کند. نیازی به کامل بودن نوع Pointee_ ندارد. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | میان‌بر برای دریافت شیء [System::TypeInfo](../typeinfo/) برای نوع Pointee_. |
|  [~SmartPtr](../smartptr/~smartptr/)() | شیء [SmartPtr](../smartptr/) را نابود می‌کند. در صورت لزوم شمارنده مرجع شیء اشاره‌شده را کاهش داده و شیء را حذف می‌کند. |

## تعاریف نوع

| Typedef | Description |
| --- | --- |
| [SmartPtr_](./smartptr_/) | نام مستعار پایه کلاس [SmartPtr](../smartptr/). |
| [DynamicWeakPtr_](./dynamicweakptr_/) | نام مستعار نوع خود. |
| [Pointee_](./pointee_/) | نوع اشاره‌شده. |

## موارد مرتبط

* کلاس [SmartPtr](../smartptr/)
* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)