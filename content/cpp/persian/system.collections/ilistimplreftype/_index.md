---
title: IListImplRefType
second_title: "Aspose.Slides برای C++ مرجع API"
description: "قالبی که رابط System::Collections::IList را بر روی شیء System::Collections::Generic::List پیاده‌سازی می‌کند. پیاده‌سازی برای انواع مرجعی."
type: docs
weight: 131
url: /fa/system.collections/ilistimplreftype/
---
## IListImplRefType کلاس

قالبی که [System::Collections::IList](../ilist/) رابط را بر روی شیء [System::Collections::Generic::List](../../system.collections.generic/list/) پیاده‌سازی می‌کند. پیاده‌سازی برای انواع ارجاعی.

```cpp
template<typename T>class IListImplRefType : public virtual System::Collections::IList
```

## متدها

| متد | توضیح |
| --- | --- |
| int [Add](./add/)([SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | عنصری را به انتهای فهرست اضافه می‌کند. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [BoxValue](./boxvalue/)([System::SharedPtr](../../system/sharedptr/)\<T\>) | مرجع نوع را به مقدار شیء تبدیل می‌کند. |
| void [Clear](./clear/)() override | تمام عناصر را حذف می‌کند. |
| **bool** [Contains](./contains/)([SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) const override | بررسی می‌کند که آیا مورد در فهرست وجود دارد یا خیر. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند هرچند طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه نقطه شناور دوگانه به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند هرچند طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| int [get_Count](./get_count/)() const override | [ICollection.get_Count()](../icollection/get_count/) methods implementation تعداد عناصر موجود در مجموعه را دریافت می‌کند. |
| virtual **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() const | مقداری را بر می‌گرداند که نشان می‌دهد آیا فهرست اندازه ثابت دارد یا نه. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارشگر مرجع مرتبط با شیء را دریافت می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::IEnumerator](../ienumerator/)\> [GetEnumerator](./getenumerator/)() override | [IEnumerable.GetEnumerator()](../ienumerable/getenumerator/) implementation یک enumerator که از طریق مجموعه پیمایش می‌کند را بر می‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)(int, int) const override | عنصر موجود در ایندکس مشخص‌شده را دریافت می‌کند. |
|  [IListImplRefType](./ilistimplreftype/)([System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<T\>\>\>) | یک نمونه جدید از شیء ایجاد می‌کند. |
| int [IndexOf](./indexof/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) const override | اندیس اولین حضور مورد در کانتینر را دریافت می‌کند. |
| void [Insert](./insert/)(int, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | عنصر را در موقعیت مشخص وارد می‌کند و سایر عناصر را جابجا می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی (کلون) انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار اشیاء نوع مقداری را با nullptr بر اساس مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| void [Remove](./remove/)([SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | اولین نمونه از یک مورد خاص را از فهرست حذف می‌کند. |
| void [RemoveAt](./removeat/)(int) override | مورد را در موقعیت مشخص حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارش مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارش مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارش مرجع مشترک را کاهش می‌دهد و بر می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| static [System::SharedPtr](../../system/sharedptr/)\<T\> [UnboxValue](./unboxvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | تبدیل مقدار شیء به مرجع نوع خاص. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازقفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## مراجع

* کلاس [IList](../ilist/)
* فضای‌نام [System::Collections](../)
* کتابخانه [Aspose.Slides](../../)