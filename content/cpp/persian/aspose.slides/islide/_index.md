---
title: ISlide
second_title: Aspose.Slides برای C++ مرجع API
description: نمایانگر یک اسلاید در یک ارائه.
type: docs
weight: 3758
url: /fa/aspose.slides/islide/
---
## ISlide کلاس

Represents a slide in a presentation.

```cpp
class ISlide : public virtual Aspose::Slides::IBaseSlide,
               public Aspose::Slides::Theme::IOverrideThemeable
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | یک تم مؤثر برای این شی قابل تم را برمی‌گرداند. |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | تعیین می‌کند آیا دو نمونه [IBaseSlide](../ibaseslide/) برابر هستند یا خیر. مقدار بازگشتی بر اساس ساختار اسلاید و محتوای ثابت محاسبه می‌شود. دو اسلاید برابر هستند اگر تمام اشکال، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. این مقایسه مقادیر شناسه‌های یکتا مانند SlideId و محتوای پویا مانند مقدار تاریخ فعلی در Date [Placeholder](../placeholder/) را در نظر نمی‌گیرد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | اولین رخداد یک شکل با متن جایگزین مشخص شده را پیدا می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | پس‌زمینه اسلاید را برمی‌گرداند. فقط-خواندنی [IBackground](../ibackground/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | کنترل ActiveX در اندیس مشخص شده را برمی‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | مجموعه کنترل‌های ActiveX موجود در یک اسلاید را برمی‌گرداند. فقط-خواندنی [IControlCollection](../icontrolcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | داده‌های سفارشی اسلاید را برمی‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideHeaderFooterManager](../islideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | مدیریت HeaderFooter اسلاید را برمی‌گرداند. فقط-خواندنی [ISlideHeaderFooterManager](../islideheaderfootermanager/). |
| virtual **bool** [get_Hidden](./get_hidden/)() | تعیین می‌کند آیا اسلاید مشخص شده در نمایش اسلاید مخفی است یا خیر. خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | دسترسی راحت به هایپرلینک‌های موجود را فراهم می‌کند. فقط-خواندنی [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)() | اسلاید چیدمان برای اسلاید فعلی را برمی‌گرداند. خواندنی [ILayoutSlide](../ilayoutslide/). |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | نام یک اسلاید را برمی‌گرداند. خواندنی [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INotesSlideManager](../inotesslidemanager/)\> [get_NotesSlideManager](./get_notesslidemanager/)() | دسترسی به اسلاید یادداشت‌ها، افزودن و حذف آن را امکان‌پذیر می‌کند. فقط-خواندنی [INotesSlideManager](../inotesslidemanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ارائه را برمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | شکل در اندیس مشخص شده را برمی‌گرداند. فقط-خواندنی [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | شکل‌های یک اسلاید را برمی‌گرداند. فقط-خواندنی [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | مشخص می‌کند آیا اشکال در اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه **false** برمی‌گرداند. خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | شناسه یک اسلاید را برمی‌گرداند. فقط-خواندنی **uint32_t**. |
| virtual **int32_t** [get_SlideNumber](./get_slidenumber/)() | شماره یک اسلاید را برمی‌گرداند. ایندکس اسلاید در [IPresentation::get_Slides()](../ipresentation/get_slides/) مجموعه همیشه برابر با SlideNumber - 1 است. خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | شیء TransitionEx را که شامل اطلاعاتی درباره پیشروی اسلاید مشخص شده در نمایش اسلاید است، برمی‌گرداند. فقط-خواندنی [ISlideShowTransition](../islideshowtransition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | مدیر تم جایگزین را برمی‌گرداند. فقط-خواندنی [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | شیء خط زمان انیمیشن را برمی‌گرداند. فقط-خواندنی [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)(**float**, **float**) | شیء تصویر با مقیاس‌گذاری سفارشی را برمی‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() | شیء تصویر بندانگشتی (۲۰٪ از اندازه واقعی) را برمی‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::Drawing::Size](../../system.drawing/size/)) | شیء تصویر با اندازه مشخص را برمی‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>) | شیء تفسیر تِیف بک‌مپ بندانگشتی با پارامترهای مشخص را برمی‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | شیء بیت‌مپ بندانگشتی را برمی‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) | شیء بیت‌مپ بندانگشتی با مقیاس‌گذاری سفارشی را برمی‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) | شیء بیت‌مپ بندانگشتی با اندازه مشخص را برمی‌گرداند. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>\> [GetSlideComments](./getslidecomments/)([System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\>) | تمام نظرات اسلاید اضافه شده توسط نویسنده خاص را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء یک نمونه از نوع توصیف شده توسط targetType است. معادل عملگر C# 'is'. |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | دست‌های متنی با قالب‌بندی یکسان را در تمامی پاراگراف‌ها در تمام شکل‌های قابل قبول ترکیب می‌کند. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری عبارت C# lock() را پیاده‌سازی می‌کند. مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع برای شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| virtual void [Remove](./remove/)() | اسلاید را از ارائه حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [Reset](./reset/)() | موقعیت، اندازه و قالب‌بندی هر شکلی که یک نمونهٔ اولیه در [LayoutSlide](../layoutslide/) دارد را بازنشانی می‌کند. |
| virtual void [set_Hidden](./set_hidden/)(**bool**) | تعیین می‌کند آیا اسلاید مشخص شده در نمایش اسلاید مخفی است یا خیر. نوشتن **bool**. |
| virtual void [set_LayoutSlide](./set_layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) | اسلاید چیدمان برای اسلاید جاری را تنظیم می‌کند. نوشتن [ILayoutSlide](../ilayoutslide/). |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | نام یک اسلاید را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | مشخص می‌کند آیا اشکال روی اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه **false** برمی‌گرداند. نوشتن **bool**. |
| virtual void [set_SlideNumber](./set_slidenumber/)(**int32_t**) | شماره یک اسلاید را برمی‌گرداند. ایندکس اسلاید در [IPresentation::get_Slides()](../ipresentation/get_slides/) مجموعه همیشه برابر با SlideNumber - 1 است. نوشتن **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک Weak Pointer (به جای Shared) تنظیم می‌کند. امکان تبدیل اشاره‌گرها در کانتینرها به حالت Weak را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری عبارت C# lock() را رفع می‌کند. مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [WriteAsEmf](./writeasemf/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | محتویات اسلاید را به‌صورت فایل EMF ذخیره می‌کند. |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | محتویات اسلاید را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | محتویات اسلاید را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [IBaseSlide](../ibaseslide/)
* کلاس [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)