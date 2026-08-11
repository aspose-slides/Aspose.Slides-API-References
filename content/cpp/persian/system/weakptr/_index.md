---
title: WeakPtr
second_title: "مرجع API Aspose.Slides برای C++"
description: "کلاس فرعی System::SmartPtr که در هنگام ساخت در حالت ضعیف تنظیم می‌شود. لطفاً توجه داشته باشید که این کلاس تضمین نمی‌کند نمونهٔ آن همیشه در حالت ضعیف باقی بماند، زیرا متد set_Mode() همچنان در دسترس است. این نوع یک اشاره‌گر برای مدیریت حذف اشیای دیگر است. باید روی پشته تخصیص داده شود و به توابع یا به‌صورت مقدار یا به‌صورت ارجاع ثابت پاس داده شود."
type: docs
weight: 1496
url: /fa/system/weakptr/
---
## WeakPtr کلاس

Subclass of [System::SmartPtr](../smartptr/) which sets itself to weak mode at construction. Please note that this class doesn't guarantee that its instance will always remain in weak mode as [set_Mode()](../smartptr/set_mode/) is still accessible. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اشاره‌گر. |

## متدها

| متد | توضیح |
| --- | --- |
| auto [begin](../smartptr/begin/)() | دستگیره‌ای برای متد [begin()](../smartptr/begin/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع خاصی با متد [begin()](../smartptr/begin/) باشد. |
| auto [begin](../smartptr/begin/)() const | دستگیره‌ای برای متد [begin()](../smartptr/begin/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع خاصی با متد [begin()](../smartptr/begin/) باشد. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | اشاره‌گر را به نوع خودش تبدیل می‌کند. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | اشاره‌گر را با استفاده از static_cast به نوع پایه تبدیل می‌کند. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | اشاره‌گر را با استفاده از dynamic_cast به نوع مشتق تبدیل می‌کند. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | اشاره‌گر را با استفاده از dynamic_cast به نوع مشتق تبدیل می‌کند. |
| auto [cbegin](../smartptr/cbegin/)() const | دستگیره‌ای برای متد [cbegin()](../smartptr/cbegin/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع خاصی با متد [cbegin()](../smartptr/cbegin/) باشد. |
| auto [cend](../smartptr/cend/)() const | دستگیره‌ای برای متد [cend()](../smartptr/cend/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع خاصی با متد [cend()](../smartptr/cend/) باشد. |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | اشاره‌گر را با استفاده از const_cast روی شیء اشاره‌شده به نوع دیگری تبدیل می‌کند. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | اشاره‌گر را با استفاده از dynamic_cast روی شیء اشاره‌شده به نوع دیگری تبدیل می‌کند. |
| auto [end](../smartptr/end/)() | دستگیره‌ای برای متد [end()](../smartptr/end/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع خاصی با متد [end()](../smartptr/end/) باشد. |
| auto [end](../smartptr/end/)() const | دستگیره‌ای برای متد [end()](../smartptr/end/) از یک مجموعه زیرین. فقط زمانی کامپایل می‌شود که SmartPtr_ نوع خاصی با متد [end()](../smartptr/end/) باشد. |
| **bool** [expired](./expired/)() const | بررسی می‌کند که آیا شیء مرجع قبلاً حذف شده است یا نه. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | شیء اشاره‌شده را برمی‌گرداند. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | حالت اشاره‌گر را برمی‌گرداند. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | شیء اشاره‌شده را برمی‌گرداند، اما اطمینان می‌دهد که اشاره‌گر در حالت مشترک است. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | تعداد اشاره‌گرهای مشترک موجود به شیء مرجع، شامل این اشاره‌گر، را برمی‌گرداند. اطمینان می‌دهد که اشاره‌گر فعلی در حالت مشترک است. |
| [Object](../object/) * [get_weak](./get_weak/)() const | شیء مرجع را برمی‌گرداند. اطمینان می‌دهد که اشاره‌گر در حالت ضعیف است. |
| int [GetHashCode](../smartptr/gethashcode/)() const | متد [GetHashCode()](../smartptr/gethashcode/) را روی شیء اشاره‌شده (در صورت وجود) صدا می‌زند. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | شیء مرجع فعلی را (در صورت وجود) برمی‌گرداند یا استثنا می‌اندازد. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | شیء اشاره‌شده را (در صورت وجود) یا nullptr برمی‌گرداند. مشابه [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | شیء مرجع را برمی‌گرداند. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | شیء اشاره‌شده را (در صورت وجود) یا nullptr برمی‌گرداند. مشابه [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | بررسی می‌کند که آیا شیء اشاره‌شده از نوع خاص یا زیرنوع آن است. مطابق معنای 'is' در C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | بررسی می‌کند که آیا اشاره‌گر به شیء دیگری غیر از مالکی که ایجاد شده است (از سازنده aliasing) اشاره می‌کند. |
| **bool** [IsShared](../smartptr/isshared/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت مشترک است. |
| **bool** [IsWeak](../smartptr/isweak/)() const | بررسی می‌کند که آیا اشاره‌گر در حالت ضعیف است. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | بررسی می‌کند که آیا اشاره‌گر تهی نیست. |
| **bool** [operator!](../smartptr/operator_not/)() const | بررسی می‌کند که آیا اشاره‌گر تهی است. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | مرجع به شیء اشاره‌شده را برمی‌گرداند. اطمینان می‌دهد که اشاره‌گر تهی نیست. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | اجاز می‌دهد به اعضای شیء مرجع دسترسی داشته باشید. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | معنا‌گذاری مقایسه کمتر برای کلاس [SmartPtr](../smartptr/) فراهم می‌کند. |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | معنا‌گذاری مقایسه کمتر برای کلاس [SmartPtr](../smartptr/) فراهم می‌کند. |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | مقدار را به اشاره‌گر ضعیف اختصاص می‌دهد. به اپراتور تخصیص خاص SmartPtr_ فراخوانی می‌کند. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | به‌صورت جابجایی مقدار [SmartPtr](../smartptr/) را اختصاص می‌دهد. x پس از فراخوانی غیرقابل استفاده می‌شود. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | کپی-تخصیص شیء [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | کپی-تخصیص شیء [SmartPtr](../smartptr/). تبدیل‌های نوع مورد نیاز را انجام می‌دهد. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | اشاره‌گر خام را به شیء [SmartPtr](../smartptr/) اختصاص می‌دهد. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | مقدار اشاره‌گر را به nullptr تنظیم می‌کند. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | بررسی می‌کند که آیا اشاره‌گر ضعیف تهی است. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | دستگاه aliasing (ایجاد شده توسط سازنده aliasing) را از اشاره‌گر حذف می‌کند و اطمینان می‌دهد که آن (اگر مشترک باشد) مدیریت یا (اگر ضعیف باشد) ردیابی همان شیئ را که به آن اشاره می‌کند، انجام می‌دهد. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | شیء اشاره‌شده را تنظیم می‌کند. |
| void [reset](../smartptr/reset/)() | اشاره‌گر را به nullptr تنظیم می‌کند. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | حالت اشاره‌گر را تنظیم می‌کند. ممکن است شمارنده‌های مرجع شیء مرجع را تغییر دهد. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | متد SetTemplateWeakPtr() را روی شیء اشاره‌شده (در صورت وجود) صدا می‌زند. |
| [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | شیء [SmartPtr](../smartptr/) با حالت مورد نیاز را ایجاد می‌کند. |
| [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | شیء [SmartPtr](../smartptr/)null-pointer با حالت مورد نیاز را ایجاد می‌کند. |
| [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | شیء [SmartPtr](../smartptr/) که به شیء مشخص اشاره می‌کند ایجاد می‌کند یا اشاره‌گر خام را به [SmartPtr](../smartptr/) تبدیل می‌کند. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | شیء [SmartPtr](../smartptr/) را به صورت کپی ساختار می‌کند. هر دو اشاره‌گر پس از آن به یک شیء اشاره می‌کنند. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | شیء [SmartPtr](../smartptr/) را به صورت کپی ساختار می‌کند. هر دو اشاره‌گر پس از آن به یک شیء اشاره می‌کنند. در صورت امکان تبدیل نوع انجام می‌دهد. |
| [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | شیء [SmartPtr](../smartptr/) را به صورت جابجایی ساختار می‌کند. به‌طور مؤثر دو اشاره‌گر را در صورت هم‌حالت بودنشان جابجا می‌کند. x ممکن است پس از فراخوانی غیرقابل استفاده باشد. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | نوع آرایه مرجع را با ایجاد آرایه‌ای جدید از نوع متفاوت تبدیل می‌کند. مفید است وقتی در C# تبدیل نوع آرایه‌ای وجود دارد که در C++ پشتیبانی نمی‌شود. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | آرایه خالی را مقداردهی اولیه می‌کند. برای ترجمه برخی ساختارهای کد C# استفاده می‌شود. |
| [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | یک [SmartPtr](../smartptr/) می‌سازد که اطلاعات مالکیت را با مقدار اولیه ptr به اشتراک می‌گذارد، اما یک اشاره‌گر نامرتبط و بدون مدیریت p را نگه می‌دارد. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | اشاره‌گر را با استفاده از static_cast روی شیء اشاره‌شده به نوع دیگری تبدیل می‌کند. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | هر نوع اشاره‌گری را به اشاره‌گر به [Object](../object/) تبدیل می‌کند. نیازی به تکمیل نوع Pointee_ نیست. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | راه‌حلی برای دریافت شیء [System::TypeInfo](../typeinfo/) برای نوع Pointee_. |
| [WeakPtr](./weakptr/)(std::nullptr_t) | یک اشاره‌گر تهی ایجاد می‌کند. |
| [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | یک اشاره‌گر ضعیف به شیء داده شده ایجاد می‌کند. |
| [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | یک اشاره‌گر ضعیف ایجاد می‌کند که به همان اشاره‌گری که ptr به آن اشاره می‌کند، ارجاع می‌دهد. |
| [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | یک اشاره‌گر ضعیف ایجاد می‌کند که به همان اشاره‌گری که x به آن اشاره می‌کند، ارجاع می‌دهد. |
| [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | یک اشاره‌گر ضعیف را به‌صورت کپی می‌سازد. |
| [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | یک اشاره‌گر ضعیف را به‌صورت کپی می‌سازد. |
| [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | یک اشاره‌گر ضعیف را به‌صورت جابجایی می‌سازد. |
| [~SmartPtr](../smartptr/~smartptr/)() | شیء [SmartPtr](../smartptr/) را از بین می‌برد. در صورت لزوم، شمارنده مرجع شیء اشاره‌شده را کاهش داده و شیء را حذف می‌کند. |

## تعریف‌های نوع

| تعریف نوع | توضیح |
| --- | --- |
| [SmartPtr_](./smartptr_/) | نام مستعار برای کلاس [SmartPtr](../smartptr/) مربوطه. |
| [WeakPtr_](./weakptr_/) | نام مستعار برای نوع خودش. |
| [Pointee_](./pointee_/) | نوع اشاره‌شده. |

## مراجع

* کلاس [SmartPtr](../smartptr/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)