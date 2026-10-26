---
title: SmartPtr
second_title: مرجع API Aspose.Slides برای C++
description: "کلاس اشاره‌گری برای پوشاندن انواع که در هِیپ تخصیص می‌یابند. از آن برای مدیریت حافظه کلاس‌های ارث‌برنده Object استفاده کنید. این نوع اشاره‌گر از معنای اشاره‌گرهای تهاجمی پیروی می‌کند. شمارنده مرجع یا در خود Object ذخیره می‌شود یا در ساختار شمارنده‌ای که به نمونهٔ Object به‌طور سفتی وابسته است. در هر صورت، تمام نمونه‌های SmartPtr یک گروه مالکیت تک‌تک می‌سازند بدون توجه به نحوهٔ ایجادشان، که متفاوت از رفتار کلاس std::shared_ptr است. تبدیل اشاره‌گر خام به SmartPtr ایمن است به شرطی که نمونه‌های دیگر SmartPtr داشته باشند که ارجاع‌های مشترک به همان شیء را نگه دارند. یک نمونهٔ کلاس SmartPtr می‌تواند در دو حالت باشد: اشاره‌گر مشترک و اشاره‌گر ضعیف. برای زنده نگه داشتن شیء، باید شمارش ارجاع‌های مشترک به آن مثبت باشد. هر دو اشاره‌گر ضعیف و مشترک می‌توانند برای دسترسی به شیء هدف (برای فراخوانی متدها، خواندن یا نوشتن فیلدها و غیره) استفاده شوند، اما اشاره‌گرهای ضعیف در شمارش مرجع‌های اشاره‌گر مشترک شرکت نمی‌کنند. شیء زمانی حذف می‌شود که آخرین اشاره‌گر 'shared' SmartPtr به آن نابود شود. بنابراین، اطمینان حاصل کنید که این اتفاق نیفتد وقتی دیگر اشاره‌گرهای مشترک SmartPtr به شیء وجود ندارند، مثلاً در طول ساخت یا تخریب شیء. از اشیای محافظ System::Object::ThisProtector (در کد C++) یا ویژگی‌های CppCTORSelfReference یا CppSelfReference (در کد C# ترجمه شده) برای رفع این مشکل استفاده کنید. به‌طور مشابه، برای شکستن ارجاع‌های حلقه‌ای از کلاس اشاره‌گر System::WeakPtr یا حالت اشاره‌گر System::SmartPtrMode::Weak (در کد C++) یا ویژگی CppWeakPtr (در کد C# ترجمه شده) استفاده کنید. اگر دو یا بیش‌از یک شیء با استفاده از اشاره‌گرهای 'shared' به یکدیگر ارجاع دهند، هرگز حذف نخواهند شد. اگر نوع اشاره‌گر (ضعیف یا مشترک) در زمان اجرا باید تغییر کند، از متد System::SmartPtr<T>::set_Mode() یا کلاس System::DynamicWeakPtr استفاده کنید. کلاس SmartPtr هیچ متد مجازی ندارد. تنها زمانی باید از آن ارث‌بری کنید که استراتژی مدیریت حافظهٔ خودتان را می‌سازید. این نوع، اشاره‌گری برای مدیریت حذف شیء دیگری است. باید در پشته تخصیص داده شود و به توابع یا به‌صورت مقدار یا به‌صورت مرجع ثابت پاس شود."
type: docs
weight: 1236
url: /fa/system/smartptr/
---
## کلاس SmartPtr

کلاس اشاره‌گری برای پوشاندن انواع که در هِیپ تخصیص می‌یابند. از آن برای مدیریت حافظه کلاس‌های ارث‌برنده [Object](../object/) استفاده کنید. این نوع اشاره‌گر از معنای اشاره‌گرهای تهاجمی پیروی می‌کند. شمارنده‌ مرجع یا در خود [Object](../object/) ذخیره می‌شود یا در ساختار شمارنده‌ای که به نمونه [Object](../object/) به‌طور سفتی وابسته است. در هر صورت، تمام نمونه‌های [SmartPtr](./) یک گروه مالکیت تک‌تک ایجاد می‌کنند بدون در نظر گرفتن نحوه ایجادشان، که متفاوت از رفتار کلاس std::shared_ptr است. تبدیل اشاره‌گر خام به [SmartPtr](./) ایمن است به شرطی که نمونه‌های دیگر [SmartPtr](./) داشته باشند که ارجاع‌های مشترک به همان شیء را نگه دارند. نمونهٔ کلاس [SmartPtr](./) می‌تواند در دو حالت باشد: اشاره‌گر مشترک و اشاره‌گر ضعیف. برای زنده نگه داشتن شیء، باید شمارش ارجاع‌های مشترک به آن مثبت باشد. هر دو اشاره‌گر ضعیف و مشترک می‌توانند برای دسترسی به شیء هدف (برای فراخوانی متدها، خواندن یا نوشتن فیلدها، و غیره) استفاده شوند، اما اشاره‌گرهای ضعیف در شمارش مرجع‌های اشاره‌گر مشترک شرکت نمی‌کنند. [Object](../object/) زمانی حذف می‌شود که آخرین اشاره‌گر 'shared' [SmartPtr](./) به آن نابود شود. بنابراین، اطمینان حاصل کنید که این اتفاق نیفتد وقتی دیگر اشاره‌گرهای مشترک [SmartPtr](./) به شیء وجود ندارند، مثلاً در طول ساخت یا تخریب شیء. برای رفع این مشکل از اشیای محافظ System::Object::ThisProtector (در کد C++) یا ویژگی‌های CppCTORSelfReference یا CppSelfReference (در کد C# ترجمه شده) استفاده کنید. به‌طور مشابه، برای شکستن ارجاع‌های حلقه‌ای از کلاس اشاره‌گر [System::WeakPtr](../weakptr/) یا حالت اشاره‌گر [System::SmartPtrMode::Weak](../smartptrmode/) (در کد C++) یا ویژگی CppWeakPtr (در کد C# ترجمه شده) استفاده کنید. اگر دو یا چند شیء با استفاده از اشاره‌گرهای 'shared' به یکدیگر ارجاع دهند، هرگز حذف نخواهند شد. اگر نوع اشاره‌گر (ضعیف یا مشترک) در زمان اجرا باید تعویض شود، از متد [System::SmartPtr<T>::set_Mode()](./set_mode/) یا کلاس [System::DynamicWeakPtr](../dynamicweakptr/) استفاده کنید. کلاس [SmartPtr](./) هیچ متد مجازی ندارد. تنها زمانی باید از آن ارث‌بری کنید که استراتژی مدیریت حافظه خودتان را می‌سازید. این نوع، اشاره‌گری برای مدیریت حذف شیء دیگری است. باید در پشته تخصیص داده شود و به توابع یا به‌صورت مقدار یا به‌صورت مرجع ثابت پاس شود.

```cpp
template<class T>class SmartPtr
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء اشاره‌شده. باید یا [System::Object](../object/) باشد یا زیرکلاس آن. |

## متدها

| متد | توضیح |
| --- | --- |
| auto [begin](./begin/)() | دسترس‌گر برای متد [begin()](./begin/) از یک مجموعهٔ زیربنایی. تنها زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [begin()](./begin/) باشد. |
| auto [begin](./begin/)() const | دسترس‌گر برای متد [begin()](./begin/) از یک مجموعهٔ زیربنایی. تنها زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [begin()](./begin/) باشد. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | تبدیل اشاره‌گر به نوع خودش. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | تبدیل اشاره‌گر به نوع پایه با استفاده از static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | تبدیل اشاره‌گر به نوع مشتق شده با dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | تبدیل اشاره‌گر به نوع مشتق شده با dynamic_cast. |
| auto [cbegin](./cbegin/)() const | دسترس‌گر برای متد [cbegin()](./cbegin/) از یک مجموعهٔ زیربنایی. تنها زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [cbegin()](./cbegin/) باشد. |
| auto [cend](./cend/)() const | دسترس‌گر برای متد [cend()](./cend/) از یک مجموعهٔ زیربنایی. تنها زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [cend()](./cend/) باشد. |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | تبدیل اشاره‌گر به نوع دیگر با استفاده از const_cast روی شیء هدف. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | تبدیل اشاره‌گر به نوع دیگر با استفاده از dynamic_cast روی شیء هدف. |
| auto [end](./end/)() | دسترس‌گر برای متد [end()](./end/) از یک مجموعهٔ زیربنایی. تنها زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [end()](./end/) باشد. |
| auto [end](./end/)() const | دسترس‌گر برای متد [end()](./end/) از یک مجموعهٔ زیربنایی. تنها زمانی کامپایل می‌شود که SmartPtr_ یک نوع تخصصی با متد [end()](./end/) باشد. |
| [Pointee_](./pointee_/) * [get](./get/)() const | دریافت شیء اشاره‌شده. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | دریافت حالت اشاره‌گر. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | دریافت شیء اشاره‌شده، اما اطمینان می‌دهد که اشاره‌گر در حالت مشترک است. |
| int [get_shared_count](./get_shared_count/)() const | دریافت تعداد اشاره‌گرهای مشترکی که به شیء مرجع وجود دارند، شامل این اشاره‌گر. اطمینان می‌دهد که اشاره‌گر فعلی در حالت مشترک است. |
| int [GetHashCode](./gethashcode/)() const | فراخوانی [GetHashCode()](./gethashcode/) روی شیء اشاره‌شده. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | دریافت شیء مرجع فعلی (در صورت وجود) یا پرتاب استثنا. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | دریافت شیء اشاره‌شده (در صورت وجود) یا nullptr. همانند [get()](./get/). |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | دریافت شیء مرجع. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | دریافت شیء اشاره‌شده (در صورت وجود) یا nullptr. همانند [get()](./get/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | بررسی اینکه آیا شیء اشاره‌شده از نوع خاص یا نوع فرزندی آن است. مطابق معنای 'is' در C#. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | بررسی اینکه آیا اشاره‌گر به شیء دیگری غیر از مالکی که ایجاد کرده است (ساخته شده توسط سازندهٔ aliasing) اشاره دارد. |
| **bool** [IsShared](./isshared/)() const | بررسی اینکه آیا اشاره‌گر در حالت مشترک است. |
| **bool** [IsWeak](./isweak/)() const | بررسی اینکه آیا اشاره‌گر در حالت ضعیف است. |
| explicit  [operator bool](./operator_bool/)() const | بررسی اینکه آیا اشاره‌گر مقدار null ندارد. |
| **bool** [operator!](./operator_not/)() const | بررسی اینکه آیا اشاره‌گر مقدار null دارد. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | دریافت مرجع به شیء اشاره‌شده. اطمینان می‌دهد که اشاره‌گر null نیست. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | امکان دسترسی به اعضای شیء مرجع. |
| **bool** [operator<](./operator_less/)(Y *) const | ارائه معنای مقایسه کمتر برای کلاس [SmartPtr](./). |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | ارائه معنای مقایسه کمتر برای کلاس [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | انتساب جابجایی شیء [SmartPtr](./). x پس از آن غیرقابل استفاده می‌شود. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | انتساب کپی شیء [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | انتساب کپی شیء [SmartPtr](./). تبدیل‌های نوع ضروری را انجام می‌دهد. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | انتساب اشاره‌گر خام به شیء [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | تنظیم مقدار اشاره‌گر به nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | بررسی اینکه آیا اشاره‌گر به nullptr اشاره دارد. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | حذف aliasing (ساخته شده توسط سازندهٔ aliasing) از اشاره‌گر، اطمینان می‌دهد که اگر مشترک باشد مدیریت می‌کند یا اگر ضعیف باشد ردیابی همان شیء را دارد. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | تنظیم شیء اشاره‌شده. |
| void [reset](./reset/)() | تنظیم اشاره‌گر به nullptr. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | تنظیم حالت اشاره‌گر. ممکن است شمارش مرجع‌های شیء مرجع را تغییر دهد. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | فراخوانی متد SetTemplateWeakPtr() روی شیء اشاره‌شده (در صورت وجود). |
| [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | ساخت شیء [SmartPtr](./) با حالت مورد نیاز. |
| [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | ساخت شیء [SmartPtr](./) با مقدار null و حالت مورد نیاز. |
| [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | ساخت [SmartPtr](./) که به شیء مشخص اشاره می‌کند، یا تبدیل اشاره‌گر خام به [SmartPtr](./). |
| [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | ساخت کپی شیء [SmartPtr](./). هر دو اشاره‌گر پس از آن به همان شیء اشاره می‌کنند. |
| [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | ساخت کپی شیء [SmartPtr](./). هر دو اشاره‌گر پس از آن به همان شیء اشاره می‌کنند. در صورت امکان تبدیل نوع انجام می‌شود. |
| [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | ساخت جابجایی شیء [SmartPtr](./). عملاً دو اشاره‌گر را اگر در همان حالت باشند، جابجا می‌کند. x ممکن است پس از فراخوانی غیرقابل استفاده باشد. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | تبدیل نوع آرایهٔ مرجع با ایجاد آرایه‌ای جدید از نوع متفاوت. مفید هنگام وجود تبدیل نوع آرایه در C# که در C++ پشتیبانی نمی‌شود. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | مقداردهی اولیه آرایهٔ خالی. برای ترجمهٔ برخی سازه‌های کد C# استفاده می‌شود. |
| [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | ساخت [SmartPtr](./) که اطلاعات مالکیت را با مقدار اولیهٔ ptr به اشتراک می‌گذارد، اما اشاره‌گر نامرتبط و غیرمدیریت‌شدهٔ p را نگه می‌دارد. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | تبدیل اشاره‌گر به نوع دیگر با static_cast روی شیء هدف. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | تبدیل هر نوع اشاره‌گری به اشاره‌گر به [Object](../object/). نیازی به کامل بودن نوع Pointee_ نیست. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | میانبر برای دریافت شیء [System::TypeInfo](../typeinfo/) برای نوع Pointee_. |
| [~SmartPtr](./~smartptr/)() | نابودسازی شیء [SmartPtr](./). در صورت نیاز، شمارنده مرجع شیء اشاره‌شده را کاهش می‌دهد و شیء را حذف می‌کند. |

## نام‌نوع‌ها

| نام‌نوع | توضیح |
| --- | --- |
| [Pointee_](./pointee_/) | نوع اشاره‌شده. |
| [SmartPtr_](./smartptr_/) | نوع اشاره‌گر هوشمند تخصصی. |
| [ArrayType](./arraytype/) | همانند Pointee_، اگر تخصصی از [System::Array](../array/) باشد، و در غیر این صورت void. |
| [ValueType](./valuetype/) | نوع ذخیره‌سازی آرایهٔ اشاره‌شده. فقط زمانی معنی دارد که T تخصصی از [System::Array](../array/) باشد. |

## موارد مرتبط

* Namespace [System](../)
* Library [Aspose.Slides](../../)