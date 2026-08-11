---
title: IStringOrDoubleChartValue
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر مقدار رشته‌ای یا double است که می‌تواند در سند ارائهٔ pptx به دو روش ذخیره شود: 1) در سلول/سلول‌های کتاب‌کار مرتبط با نمودار؛ 2) به عنوان مقدار صریح."
type: docs
weight: 1210
url: /fa/aspose.slides.charts/istringordoublechartvalue/
---
## IStringOrDoubleChartValue کلاس

نمایانگر مقدار رشته‌ای یا double است که می‌تواند در سند ارائهٔ pptx به دو روش ذخیره شود: ۱) در سلول/سلول‌های کتاب‌کار مربوط به نمودار؛ ۲) به‌عنوان مقدار صریح.

```cpp
class IStringOrDoubleChartValue : public Aspose::Slides::Charts::ISingleCellChartValue
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_AsCell](../isinglecellchartvalue/get_ascell/)() | سلول دادهٔ نمودار را برمی‌گرداند. [IChartDataCell](../ichartdatacell/) را بخوانید. |
| virtual **double** [get_AsLiteralDouble](./get_asliteraldouble/)() | عدد double صریح را برمی‌گرداند اگر ویژگی DataSourceType برابر [DataSourceType::DoubleLiterals](../datasourcetype/) باشد. **double** را بخوانید. |
| virtual [System::String](../../system/string/) [get_AsLiteralString](./get_asliteralstring/)() | رشتهٔ صریح را برمی‌گرداند اگر ویژگی DataSourceType برابر [DataSourceType::StringLiterals](../datasourcetype/) باشد. [System::String](../../system/string/) را بخوانید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Data](../ibasechartvalue/get_data/)() |  |
| virtual [Aspose::Slides::Charts::DataSourceType](../datasourcetype/) [get_DataSourceType](../ibasechartvalue/get_datasourcetype/)() | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble فعال است. به عبارت دیگر نوع مقدار ویژگی Data را مشخص می‌کند. این ویژگی فقط-خواندنی است. برای تغییر مقدار این ویژگی می‌توانید از یکی از ویژگی‌های ChartDataPointCollection.DataSourceTypeFor<...> استفاده کنید. [DataSourceType](../datasourcetype/) را بخوانید. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نمونه‌ای از متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. نمونه‌ای از فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. نمونه‌ای از عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌کردن را با استفاده از عبارت C# lock() پیاده‌سازی می‌کند. به‌طور مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نمونه‌ای از متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ نسخه‌برداری. در واقع هیچ‌چیز را کپی نمی‌کند، تنها شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخه‌برداری از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیز را کپی نمی‌کند، تنها شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخه‌برداری از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌وار شیء از نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_AsCell](../isinglecellchartvalue/set_ascell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | سلول دادهٔ نمودار را تنظیم می‌کند. [IChartDataCell](../ichartdatacell/) را بنویسید. |
| virtual void [set_AsLiteralDouble](./set_asliteraldouble/)(**double**) | عدد double صریح را تنظیم می‌کند اگر ویژگی DataSourceType برابر [DataSourceType::DoubleLiterals](../datasourcetype/) باشد. **double** را بنویسید. |
| virtual void [set_AsLiteralString](./set_asliteralstring/)([System::String](../../system/string/)) | رشتهٔ صریح را تنظیم می‌کند اگر ویژگی DataSourceType برابر [DataSourceType::StringLiterals](../datasourcetype/) باشد. [System::String](../../system/string/) را بنویسید. |
| virtual void [set_Data](../ibasechartvalue/set_data/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) |  |
| virtual void [set_DataSourceType](../ibasechartvalue/set_datasourcetype/)([Aspose::Slides::Charts::DataSourceType](../datasourcetype/)) | مشخص می‌کند که آیا ویژگی AsCell یا AsLiteralString یا AsLiteralDouble فعال است. به عبارت دیگر نوع مقدار ویژگی Data را مشخص می‌کند. این ویژگی فقط-خواندنی است. برای تغییر مقدار این ویژگی می‌توانید از یکی از ویژگی‌های ChartDataPointCollection.DataSourceTypeFor<...> استفاده کنید. [DataSourceType](../datasourcetype/) را بنویسید. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در قالب‌ها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ بجای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ بجای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual **double** [ToDouble](./todouble/)() | مقدار را به double تبدیل می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نمونه‌ای از متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | باز کردن قفل را با استفاده از عبارت C# lock() پیاده‌سازی می‌کند. به‌طور مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ بجای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ بجای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [ISingleCellChartValue](../isinglecellchartvalue/)
* فضای‌نامی [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)