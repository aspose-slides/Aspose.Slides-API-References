---
title: LayoutSlide
second_title: مرجع API Aspose.Slides برای C++
description: یک اسلاید طرح‌بندی را نشان می‌دهد.
type: docs
weight: 4291
url: /fa/aspose.slides/layoutslide/
---
## LayoutSlide کلاس

یک اسلاید طرح‌بندی را نشان می‌دهد.

```cpp
class LayoutSlide : public Aspose::Slides::BaseSlide,
                    public Aspose::Slides::ILayoutSlide
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | یک تم مؤثر برای این اسلاید برمی‌گرداند. |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | تعیین می‌کند که آیا دو نمونه [IBaseSlide](../ibaseslide/) برابر هستند یا نه. مقدار بازگشتی بر اساس ساختار اسلاید و محتویات ثابت محاسبه می‌شود. دو اسلاید برابرند اگر تمامی اشکال، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات، و غیره برابر باشند. مقایسه مقدارهای شناسهٔ یکتا مانند SlideId و محتویات پویا مانند مقدار تاریخ فعلی در Date [Placeholder](../placeholder/) را در نظر نمی‌گیرد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه‌ای با سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه‌ای با سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | اولین رخداد شکلی با متن جایگزین مشخص‌شده را پیدا می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | پس‌زمینهٔ اسلاید را برمی‌گرداند. فقط-خواندنی [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | کنترل ActiveX در اندیس مشخص‌شده را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | مجموعهٔ کنترل‌های ActiveX روی یک اسلاید را برمی‌گرداند. فقط-خواندنی [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | دادهٔ سفارشی اسلاید را برمی‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() override | مجموعه‌ای از راهنمایی‌های رسم برای اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../idrawingguidescollection/) |
| **bool** [get_HasDependingSlides](./get_hasdependingslides/)() override | در صورتی که حداقل یک اسلاید وجود داشته باشد که به این اسلاید طرح‌بندی وابسته باشد، true برمی‌گرداند. فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | مدیر HeaderFooter اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط-خواندنی [IHyperlinkQueries](../ihyperlinkqueries/). |
| [SlideLayoutType](../slidelayouttype/) [get_LayoutType](./get_layouttype/)() override | نوع طرح‌بندی این اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [SlideLayoutType](../slidelayouttype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [get_MasterSlide](./get_masterslide/)() override | اسلاید اصلی برای یک طرح‌بندی را برمی‌گرداند. فقط [IMasterSlide](../imasterslide/). |
| [System::String](../../system/string/) [get_Name](../baseslide/get_name/)() override | نام اسلاید را برمی‌گرداند. فقط [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutPlaceholderManager](../ilayoutplaceholdermanager/)\> [get_PlaceholderManager](./get_placeholdermanager/)() override | مدیر جای‌نگهدارهای اسلاید طرح‌بندی را برمی‌گرداند. فقط-خواندنی [ILayoutPlaceholderManager](../ilayoutplaceholdermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | رابط [IPresentation](../ipresentation/) را برمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | شکل در اندیس مشخص‌شده را برمی‌گرداند. فقط-خواندنی [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | اشکال یک اسلاید را برمی‌گرداند. فقط-خواندنی [IShapeCollection](../ishapecollection/). |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | مشخص می‌کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نشان داده شوند یا نه. فقط **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | شناسهٔ یک اسلاید را برمی‌گرداند. فقط-خواندنی **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | شیء Transition را برمی‌گرداند که حاوی اطلاعاتی دربارهٔ نحوهٔ پیشروی اسلاید مشخص‌شده هنگام نمایش اسلایدها است. فقط-خواندنی [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | مدیر تم حاکم بر جایگزینی را برمی‌گرداند. فقط-خواندنی [Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | شیء خط زمان انیمیشن را برمی‌گرداند. فقط-خواندنی [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() override | یک آرایه شامل تمام اسلایدهایی که به این اسلاید طرح‌بندی وابسته هستند را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌سازی اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر C# 'is'. |
| void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)() override | دنباله‌های متن با قالب‌بندی یکسان را در تمام پاراگراف‌ها و تمام اشکال قابل قبول ادغام می‌کند. |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | دنباله‌های متن با قالب‌بندی یکسان را در تمام پاراگراف‌ها و تمام اشکال قابل قبول ادغام می‌کند. |
| void [Lock](../../system/object/lock/)() | اجرای قفل (lock) در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌آورد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌آورد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مرجع‌مقایسه شیء نوع مقداری با nullptr انجام می‌دهد. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| void [Remove](./remove/)() override | طرح‌بندی را از ارائه حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع اشتراکی را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_MasterSlide](./set_masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\>) override | اسلاید اصلی برای یک طرح‌بندی تنظیم می‌کند. قابل نوشتن [IMasterSlide](../imasterslide/). |
| void [set_Name](../baseslide/set_name/)([System::String](../../system/string/)) override | نام اسلاید را تنظیم می‌کند. قابل نوشتن [System::String](../../system/string/). |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | مشخص می‌کند آیا اشکال روی اسلاید اصلی باید در اسلایدها نشان داده شوند یا نه. قابل نوشتن **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. اجازه می‌دهد اشاره‌گرها در مخازن به حالت ضعیف تغییر کنند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع اشتراکی را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع اشتراکی را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل (lock) در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [BaseSlide](../baseslide/)
* کلاس [ILayoutSlide](../ilayoutslide/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)