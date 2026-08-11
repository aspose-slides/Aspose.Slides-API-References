---
title: DataSourceTypeForErrorBarsCustomValues
second_title: مرجع API Aspose.Slides برای C++
description: "انواع مقادیر را در لیست ویژگی‌های ChartDataPoint::get_ErrorBarsCustomValues مشخص می‌کند"
type: docs
weight: 404
url: /fa/aspose.slides.charts/datasourcetypeforerrorbarscustomvalues/
---
## DataSourceTypeForErrorBarsCustomValues کلاس

Specifies types of values in [ChartDataPoint::get_ErrorBarsCustomValues](../chartdatapoint/get_errorbarscustomvalues/) properties list

```cpp
class DataSourceTypeForErrorBarsCustomValues : public Aspose::Slides::Charts::IDataSourceTypeForErrorBarsCustomValues
```

## متدها

| متد | توضیح |
| --- | --- |
|  [DataSourceTypeForErrorBarsCustomValues](./datasourcetypeforerrorbarscustomvalues/)() |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از semantics C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقاط شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقاط شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXMinusValues](./get_datasourcetypeforxminusvalues/)() override | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XMinus داده‌های نقطه‌های خطا مقادیر سفارشی واقعاً موجود است. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.ErrorBarsCustomValues.XMinus.Data را مشخص می‌کند. خواندن [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXPlusValues](./get_datasourcetypeforxplusvalues/)() override | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XPlus داده‌های نقطه‌های خطا مقادیر سفارشی واقعاً موجود است. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.ErrorBarsCustomValues.XPlus.Data را مشخص می‌کند. خواندن [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYMinusValues](./get_datasourcetypeforyminusvalues/)() override | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YMinus داده‌های نقطه‌های خطا مقادیر سفارشی واقعاً موجود است. به عبارت دیگر نوع مقدار ویژگی ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data را مشخص می‌کند. خواندن [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYPlusValues](./get_datasourcetypeforyplusvalues/)() override | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YPlus داده‌های نقطه‌های خطا مقادیر سفارشی واقعاً موجود است. به عبارت دیگر نوع مقدار ویژگی ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data را مشخص می‌کند. خواندن [DataSourceType](../datasourcetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | داده ساختار شمارنده مرجع را که با شیء مرتبط است دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نقش مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. نقش مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. نقش مشابه عملگر 'is' C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری statement lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نقش مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی کپی نمی‌شود، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها را از طریق کپی فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی کپی نمی‌شود، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها را از طریق کپی فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌دار شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_DataSourceTypeForXMinusValues](./set_datasourcetypeforxminusvalues/)([DataSourceType](../datasourcetype/)) override | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XMinus داده‌های نقطه‌های خطا مقادیر سفارشی واقعاً موجود است. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.ErrorBarsCustomValues.XMinus.Data را مشخص می‌کند. نوشتن [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForXPlusValues](./set_datasourcetypeforxplusvalues/)([DataSourceType](../datasourcetype/)) override | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XPlus داده‌های نقطه‌های خطا مقادیر سفارشی واقعاً موجود است. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.ErrorBarsCustomValues.XPlus.Data را مشخص می‌کند. نوشتن [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForYMinusValues](./set_datasourcetypeforyminusvalues/)([DataSourceType](../datasourcetype/)) override | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YMinus داده‌های نقطه‌های خطا مقادیر سفارشی واقعاً موجود است. به عبارت دیگر نوع مقدار ویژگی ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data را مشخص می‌کند. نوشتن [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForYPlusValues](./set_datasourcetypeforyplusvalues/)([DataSourceType](../datasourcetype/)) override | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YPlus داده‌های نقطه‌های خطا مقادیر سفارشی واقعاً موجود است. به عبارت دیگر نوع مقدار ویژگی ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data را مشخص می‌کند. نوشتن [DataSourceType](../datasourcetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | قالب آرگومان nام را به عنوان یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و بر می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نقش مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ایجاد سازهٔ typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای مرحلهٔ باز کردن قفل statement lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## ارجاع‌ها

* کلاس [IDataSourceTypeForErrorBarsCustomValues](../idatasourcetypeforerrorbarscustomvalues/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)