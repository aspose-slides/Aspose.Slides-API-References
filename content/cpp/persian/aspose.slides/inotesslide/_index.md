---
title: INotesSlide
second_title: Aspose.Slides برای C++ API ارجاعی
description: یک اسلاید یادداشت در یک ارائه را نمایندگی می‌کند.
type: docs
weight: 3017
url: /fa/aspose.slides/inotesslide/
---
## INotesSlide کلاس

یک اسلاید یادداشت در یک ارائه را نمایندگی می‌کند.

```cpp
class INotesSlide : public virtual Aspose::Slides::IBaseSlide,
                    public Aspose::Slides::Theme::IOverrideThemeable
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | یک تم مؤثر برای این شیء قابل تم‌گذاری را باز می‌گرداند. |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | تعیین می‌کند که دو نمونه [IBaseSlide](../ibaseslide/) برابر هستند یا نه. مقدار بازگشتی بر پایه ساختار اسلاید و محتوای ثابت محاسبه می‌شود. دو اسلاید برابرند اگر همهٔ اشکال، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسهٔ یکتا مثل SlideId و محتوای پویا مثل مقدار تاریخ فعلی در Date [Placeholder](../placeholder/) را در نظر نمی‌گیرد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با معنای [Object.Equals](../../system/object/equals/) زبان C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به-سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به-سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | اولین رخداد شکلی با متن جایگزین مشخص‌شده را پیدا می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | پس‌زمینه اسلاید را باز می‌گرداند. فقط-خواندنی [IBackground](../ibackground/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | کنترل ActiveX در اندیس مشخص‌شده را باز می‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | مجموعهٔ کنترل‌های ActiveX روی یک اسلاید را باز می‌گرداند. فقط-خواندنی [IControlCollection](../icontrolcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | دادهٔ سفارشی اسلاید را باز می‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INotesSlideHeaderFooterManager](../inotesslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | مدیریت HeaderFooter اسلاید یادداشت را باز می‌گرداند. فقط-خواندنی [INotesSlideHeaderFooterManager](../inotesslideheaderfootermanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط-خواندنی [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | نام یک اسلاید را باز می‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_NotesTextFrame](./get_notestextframe/)() | اگر متنی برای یادداشت‌ها وجود داشته باشد یک [TextFrame](../textframe/) با متن یادداشت‌ها را باز می‌گرداند. فقط-خواندنی [ITextFrame](../itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_ParentSlide](./get_parentslide/)() | یک ParentSlide را باز می‌گرداند. فقط-خواندنی [ISlide](../islide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ارائه را باز می‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | شکلی در اندیس مشخص‌شده را باز می‌گرداند. فقط-خواندنی [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | اشکال یک اسلاید را باز می‌گرداند. فقط-خواندنی [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | مشخص می‌کند آیا اشکال روی اسلاید مستر باید روی اسلایدها نشان داده شوند یا نه. برای خود اسلاید مستر این ویژگی همیشه **false** بر می‌گرداند. فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | اسلاید پایه را باز می‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | شناسهٔ یک اسلاید را باز می‌گرداند. فقط-خواندنی **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | شیء TransitionEx را باز می‌گرداند که اطلاعاتی در مورد نحوه پیشرفت اسلاید مشخص‌شده در نمایش اسلایدها دارد. فقط-خواندنی [ISlideShowTransition](../islideshowtransition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | مدیر تم جایگزین را باز می‌گرداند. فقط-خواندنی [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | شیء خط زمان انیمیشن را باز می‌گرداند. فقط-خواندنی [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. مشابه اپراتور C# `is`. |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | اجرای‌های با قالب‌بندی مشابه را در تمام پاراگراف‌ها در تمام اشکال قابل قبول ترکیب می‌کند. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی بیانیهٔ C# `lock()` برای قفل‌گذاری. به‌صورت مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ نسخه‌برداری. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی اولیه می‌کند و امکان ساخت نسخه‌برداری از زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی اولیه می‌کند و امکان ساخت نسخه‌برداری از زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء از نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع اشتراکی را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | نام یک اسلاید را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | مشخص می‌کند آیا اشکال روی اسلاید مستر باید روی اسلایدها نشان داده شوند یا نه. برای خود اسلاید مستر این ویژگی همیشه **false** بر می‌گرداند. نوشتن **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگوی یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در سازنده‌ها به حالت ضعیف فراهم می‌شود. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع اشتراکی را کاهش می‌دهد و مقدار آن را باز می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ C# `typeof([System.Object](../../system/object/))`. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بیانیهٔ C# `lock()` برای بازقفل‌گذاری. به‌صورت مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* Class [IBaseSlide](../ibaseslide/)
* Class [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)