---
title: IDataSourceTypeForErrorBarsCustomValues
second_title: مرجع API Aspose.Slides برای C++
description: انواع مقادیر را در فهرست ویژگی‌های ChartDataPoint.ErrorBarsCustomValues مشخص می‌کند
type: docs
weight: 976
url: /fa/aspose.slides.charts/idatasourcetypeforerrorbarscustomvalues/
---
## IDataSourceTypeForErrorBarsCustomValues کلاس

نوع مقادیر در فهرست ویژگی‌های ChartDataPoint.ErrorBarsCustomValues را مشخص می‌کند

```cpp
class IDataSourceTypeForErrorBarsCustomValues : public virtual System::Object
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قواعد [Object.Equals](../../system/object/equals/) زبان C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXMinusValues](./get_datasourcetypeforxminusvalues/)() | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XMinus نقاط داده برای مقادیر سفارشی نوارهای خطا واقعی است یا نه. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.ErrorBarsCustomValues.XMinus.Data را مشخص می‌کند. بخوانید [DataSourceType](../datasourcetype/). |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXPlusValues](./get_datasourcetypeforxplusvalues/)() | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XPlus نقاط داده برای مقادیر سفارشی نوارهای خطا واقعی است یا نه. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.ErrorBarsCustomValues.XPlus.Data را مشخص می‌کند. بخوانید [DataSourceType](../datasourcetype/). |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYMinusValues](./get_datasourcetypeforyminusvalues/)() | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YMinus نقاط داده برای مقادیر سفارشی نوارهای خطا واقعی است یا نه. به عبارت دیگر نوع مقدار ویژگی ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data را مشخص می‌کند. بخوانید [DataSourceType](../datasourcetype/). |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYPlusValues](./get_datasourcetypeforyplusvalues/)() | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YPlus نقاط داده برای مقادیر سفارشی نوارهای خطا واقعی است یا نه. به عبارت دیگر نوع مقدار ویژگی ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data را مشخص می‌کند. بخوانید [DataSourceType](../datasourcetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C#. هش‌سازی اشیاء سفارشی را امکان‌پذیر می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ نسخه‌برداری. در واقع هیچ‌ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی در زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی در زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_DataSourceTypeForXMinusValues](./set_datasourcetypeforxminusvalues/)([DataSourceType](../datasourcetype/)) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XMinus نقاط داده برای مقادیر سفارشی نوارهای خطا واقعی است یا نه. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.ErrorBarsCustomValues.XMinus.Data را مشخص می‌کند. بنویسید [DataSourceType](../datasourcetype/). |
| virtual void [set_DataSourceTypeForXPlusValues](./set_datasourcetypeforxplusvalues/)([DataSourceType](../datasourcetype/)) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی XPlus نقاط داده برای مقادیر سفارشی نوارهای خطا واقعی است یا نه. به عبارت دیگر نوع مقدار ویژگی ChartDataPoint.ErrorBarsCustomValues.XPlus.Data را مشخص می‌کند. بنویسید [DataSourceType](../datasourcetype/). |
| virtual void [set_DataSourceTypeForYMinusValues](./set_datasourcetypeforyminusvalues/)([DataSourceType](../datasourcetype/)) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YMinus نقاط داده برای مقادیر سفارشی نوارهای خطا واقعی است یا نه. به عبارت دیگر نوع مقدار ویژگی ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data را مشخص می‌کند. بنویسید [DataSourceType](../datasourcetype/). |
| virtual void [set_DataSourceTypeForYPlusValues](./set_datasourcetypeforyplusvalues/)([DataSourceType](../datasourcetype/)) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble در شیء ویژگی YPlus نقاط داده برای مقادیر سفارشی نوارهای خطا واقعی است یا نه. به عبارت دیگر نوع مقدار ویژگی ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data را مشخص می‌کند. بنویسید [DataSourceType](../datasourcetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در‌ظرف‌خانه‌ها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | تعداد شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | تعداد شمارندهٔ مرجع مشترک را کاهش می‌دهد و باز می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) زبان C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | تعداد شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | تعداد شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)