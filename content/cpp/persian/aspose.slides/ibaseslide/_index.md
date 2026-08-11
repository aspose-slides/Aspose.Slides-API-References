---
title: IBaseSlide
second_title: مرجع API Aspose.Slides برای C++
description: داده‌های مشترک برای تمام انواع اسلایدها را نماینده می‌کند.
type: docs
weight: 1496
url: /fa/aspose.slides/ibaseslide/
---
## IBaseSlide کلاس

Represents common data for all slide types.

```cpp
class IBaseSlide : public virtual Aspose::Slides::Theme::IThemeable
```

## متدها

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | یک تم مؤثر برای این شیء قابل‌تم را برمی‌گرداند. |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](./)\>) | تعیین می‌کند که آیا دو نمونه [IBaseSlide](./) برابر هستند یا نه. مقدار بازگشتی بر اساس ساختار اسلاید و محتوای ثابت محاسبه می‌شود. دو اسلاید برابر هستند اگر تمام اشکال، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسایی منحصر به فرد مانند SlideId و محتوای پویا مانند مقدار تاریخ فعلی در Date [Placeholder](../placeholder/) را در نظر نمی‌گیرد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از سمانتیک [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر وفق استاندارد IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر وفق استاندارد IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](./findshapebyalttext/)([System::String](../../system/string/)) | اولین ظاهر یک شکل با متن جایگزین مشخص‌شده را پیدا می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](./get_background/)() | پس‌زمینه اسلاید را برمی‌گرداند. فقط-خواندنی [IBackground](../ibackground/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](./get_control/)(**int32_t**) | کنترل ActiveX در ایندکس مشخص‌شده را برمی‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](./get_controls/)() | مجموعه کنترل‌های ActiveX روی یک اسلاید را برمی‌گرداند. فقط-خواندنی [IControlCollection](../icontrolcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() | داده‌های سفارشی اسلاید را برمی‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط-خواندنی [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::String](../../system/string/) [get_Name](./get_name/)() | نام یک اسلاید را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ارائه (presentation) را برمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)(**int32_t**) | شکل در ایندکس مشخص‌شده را برمی‌گرداند. فقط-خواندنی [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](./get_shapes/)() | اشکال یک اسلاید را برمی‌گرداند. فقط-خواندنی [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](./get_showmastershapes/)() | مشخص می‌کند آیا اشکال در اسلاید اصلی باید در اسلایدها نشان داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه **false** برمی‌گرداند. فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](./)\> [get_Slide](../islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط-خواندنی [IBaseSlide](./). |
| virtual **uint32_t** [get_SlideId](./get_slideid/)() | شناسه یک اسلاید را برمی‌گرداند. فقط-خواندنی **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](./get_slideshowtransition/)() | شیء TransitionEx را که شامل اطلاعات دربارهٔ پیشرفت اسلاید مشخص‌شده در طول نمایش اسلاید است، برمی‌گرداند. فقط-خواندنی [ISlideShowTransition](../islideshowtransition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](./get_timeline/)() | شیء زمان‌بند انیمیشن را برمی‌گرداند. فقط-خواندنی [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را به دست می‌آورد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| virtual void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() | بخش‌های متنی با قالب‌بندی یکسان را در تمام پاراگراف‌های همهٔ اشکال قابل‌قبول ترکیب می‌کند. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیانیه lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع برای شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_Name](./set_name/)([System::String](../../system/string/)) | نام یک اسلاید را تنظیم می‌کند. قابل‌نوشتن [System::String](../../system/string/). |
| virtual void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) | مشخص می‌کند آیا اشکال در اسلاید اصلی باید در اسلایدها نشان داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه **false** برمی‌گرداند. قابل‌نوشتن **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک پوینتر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر پوینترها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساز و کار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیانیه lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیلاً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [IThemeable](../../aspose.slides.theme/ithemeable/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)