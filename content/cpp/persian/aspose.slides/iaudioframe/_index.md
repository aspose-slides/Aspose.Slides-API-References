---
title: IAudioFrame
second_title: مرجع API Aspose.Slides برای C++
description: یک کلیپ صوتی را بر روی اسلاید نشان می‌دهد.
type: docs
weight: 1353
url: /fa/aspose.slides/iaudioframe/
---
## IAudioFrame کلاس

یک کلیپ صوتی را بر روی اسلاید نشان می‌دهد.

```cpp
class IAudioFrame : public virtual Aspose::Slides::IPictureFrame
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | در صورت عدم وجود، یک جای‌نگهدار جدید اضافه می‌کند و ویژگی‌های جای‌نگهدار را به مورد مشخص‌شده تنظیم می‌کند. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | آرایه‌ای از عناصر شکل را ایجاد و بازمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌ای به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌ای به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | تنها برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | مقدار تنظیمات یک شکل را در ایندکس مشخص‌شده بازمی‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | مجموعه‌ای از مقادیر تنظیمات شکل را بازمی‌گرداند. فقط-خواندنی [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | متن جایگزین مرتبط با یک شکل را بازمی‌گرداند. خواندنی [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | عنوان متن جایگزین مرتبط با یک شکل را بازمی‌گرداند. خواندنی [System::String](../../system/string/). |
| virtual **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() | ایندکس آخرین مسیر را بازمی‌گرداند. خواندنی **int32_t**. |
| virtual **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() | زمان آخرین مسیر را بازمی‌گرداند. خواندنی **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() | ایندکس مسیر شروع را بازمی‌گرداند. خواندنی **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() | زمان مسیر شروع را بازمی‌گرداند. خواندنی **int32_t**. |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. خواندنی [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | مجموعه زیرنویس‌های بسته مرتبط با قاب صوتی را دریافت می‌کند. این ویژگی فقط-خواندنی است و یک [ICaptionsCollection](../icaptionscollection/) حاوی تمام مسیرهای زیرنویس را بازمی‌گرداند. |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | تعداد نقاط اتصال روی شکل را بازمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | داده‌های سفارشی شکل را بازمی‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | شیء [EffectFormat](../effectformat/) را که شامل اثرات پیکسل اعمال‌شده به یک شکل است، بازمی‌گرداند. فقط-خواندنی [IEffectFormat](../ieffectformat/). |
| virtual **bool** [get_Embedded](./get_embedded/)() | تعیین می‌کند آیا صدایی در ارائه تعبیه شده است یا نه. فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() | شیء صوتی تعبیه‌شده را بازمی‌گرداند. خواندنی [IAudio](../iaudio/). |
| virtual **float** [get_FadeInDuration](./get_fadeinduration/)() | مدت زمان محو اولیه رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی **float**. |
| virtual **float** [get_FadeOutDuration](./get_fadeoutduration/)() | مدت زمان محو انتهایی رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | شیء [FillFormat](../fillformat/) را که شامل ویژگی‌های قالب‌بندی پر برای یک شکل است، بازمی‌گرداند. فقط-خواندنی [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | ویژگی‌های قاب شکل را بازمی‌گرداند. خواندنی [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود دریافت می‌کند. خواندنی **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | تعیین می‌کند آیا شکل مخفی است یا نه. خواندنی **bool**. |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | تعیین می‌کند آیا یک [AudioFrame](../audioframe/) مخفی است یا نه. خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | پیوندی که برای کلیک ماوس تعریف شده است را بازمی‌گرداند. خواندنی [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدیر پیوندها فقط-خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | پیوندی که برای عبور ماوس تعریف شده است را بازمی‌گرداند. خواندنی [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | گزینه «Mark as decorative» را دریافت می‌کند. خواند/نوشت **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | تعیین می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | تعیین می‌کند آیا شکل TextHolder است یا نه. فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | شیء [LineFormat](../lineformat/) را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است بازمی‌گرداند. فقط-خواندنی [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | نام یک فایل صوتی که به یک [AudioFrame](../audioframe/) لینک شده است را بازمی‌گرداند. خواندنی [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | نام یک شکل را بازمی‌گرداند. خواندنی [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | یک شناسه یکتا در سطح اسلاید که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای بینابری اجازه می‌دهد شکل را به‌صورت قابل اطمینان از هر نقطه‌ای در سند ارجاع دهند. فقط-خواندنی **uint32_t**. همچنین ببینید [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | شیء والد [GroupShape](../groupshape/) را در صورت گروه‌بندی شکل بازمی‌گرداند. در غیر این صورت مقدار null را برمی‌گرداند. فقط-خواندنی [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | شیء [PictureFillFormat](../picturefillformat/) را برای قاب تصویر بازمی‌گرداند. فقط-خواندنی [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | قفل‌های [PictureFrame](../pictureframe/) را بازمی‌گرداند. فقط-خواندنی [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | جای‌نگهدار یک شکل را بازمی‌گرداند. فقط-خواندنی [IPlaceholder](../iplaceholder/). |
| virtual **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() | تعیین می‌کند آیا یک صدا در تمام اسلایدها پخش می‌شود یا نه. خواندنی **bool**. |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | تعیین می‌کند آیا یک صدا به‌صورت حلقه‌ای است یا نه. خواندنی **bool**. |
| virtual [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() | حالت پخش صدا را بازمی‌گرداند. خواندنی [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ارائه را بازمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | ویژگی‌های خام قاب شکل را بازمی‌گرداند. خواندنی [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) قاب تصویر را بازمی‌گرداند. مقدار 1.0 معادل 100٪ است. خواندنی **float**. |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | مقیاس عرض (نسبت به اندازه اصلی تصویر) قاب تصویر را بازمی‌گرداند. مقدار 1.0 معادل 100٪ است. خواندنی **float**. |
| virtual **bool** [get_RewindAudio](./get_rewindaudio/)() | تعیین می‌کند آیا یک صدا پس از پخش به‌صورت خودکار به شروع بازگردانده می‌شود یا نه. خواندنی **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را بازمی‌گرداند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش ضدساعتی است. خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | قفل‌های شکل را بازمی‌گرداند. فقط-خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | شیء سبک شکل را بازمی‌گرداند. فقط-خواندنی [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | نوع پیش‌تنظیم ژئومتری را بازمی‌گرداند. نکته: با تغییر مقدار، تمام مقادیر تنظیم مجدداً به مقدار پیش‌فرض خود بازمی‌گردند. خواندنی [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | اسلاید پایه را بازمی‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | شیء [ThreeDFormat](../threedformat/) را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است بازمی‌گرداند. فقط-خواندنی [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | مدت زمان حذف‌شده از انتهای رسانه در حین پخش را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی **float**. |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | مدت زمان حذف‌شده از ابتدای رسانه در حین پخش را بر حسب میلی‌ثانیه مشخص می‌کند. خواندنی **float**. |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | شناسه داخلی scoped به ارائه که برای افزونه‌ها یا کدهای دیگر منظور شده است. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس مجدداً تخصیص یابد، نباید به‌عنوان کلید یکتا دائمی در نظر گرفته شود. فقط-خواندنی **uint32_t**. همچنین ببینید [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | حجم صدا را بازمی‌گرداند. خواندنی [AudioVolumeMode](../audiovolumemode/). |
| virtual **float** [get_VolumeValue](./get_volumevalue/)() | حجم صدا را به درصد بازمی‌گرداند. خواندنی **float**. |
| virtual **float** [get_Width](../ishape/get_width/)() | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود دریافت می‌کند. خواندنی **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | مختصات x گوشه بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود دریافت می‌کند. خواندنی **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | مختصات y گوشه بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود دریافت می‌کند. خواندنی **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | موقعیت یک شکل در z-order را بازمی‌گرداند. Shapes[0] شکل را در پشت‌ترین موقعیت z-order برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلوی‌ترین موقعیت برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | یک شکل جای‌نگهدار پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن ارث‌بری می‌کند) را بازمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | کپی مسیر شکل ژئومتری را بازمی‌گرداند. مختصات‌ها نسبت به گوشه بالا-چپ شکل نسبی هستند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | تصویر کوچک شکل را بازمی‌گرداند. نوع محدوده تصویر کوچک [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به‌صورت پیش‌فرض استفاده می‌شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | تصویر کوچک شکل را بازمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# «is». |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی می‌کند و امکان ساخت کپی برای کلاس‌های مشتق‌شده را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی می‌کند و امکان ساخت کپی برای کلاس‌های مشتق‌شده را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | ویژه‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | ویژه‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | تعریف می‌کند که این شکل یک جای‌نگهدار نیست. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشت [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشت [System::String](../../system/string/). |
| virtual void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) | ایندکس آخرین مسیر را تنظیم می‌کند. نوشت **int32_t**. |
| virtual void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) | زمان آخرین مسیر را تنظیم می‌کند. نوشت **int32_t**. |
| virtual void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) | ایندکس مسیر شروع را تنظیم می‌کند. نوشت **int32_t**. |
| virtual void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) | زمان مسیر شروع را تنظیم می‌کند. نوشت **int32_t**. |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. نوشت [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | شیء صوتی تعبیه‌شده را تنظیم می‌کند. نوشت [IAudio](../iaudio/). |
| virtual void [set_FadeInDuration](./set_fadeinduration/)(**float**) | مدت زمان محو اولیه رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. نوشت **float**. |
| virtual void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) | مدت زمان محو انتهایی رسانه را بر حسب میلی‌ثانیه مشخص می‌کند. نوشت **float**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ویژگی‌های قاب شکل را تنظیم می‌کند. نوشت [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشت **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | تعیین می‌کند آیا شکل مخفی است یا نه. نوشت **bool**. |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | تعیین می‌کند آیا یک [AudioFrame](../audioframe/) مخفی است یا نه. نوشت **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | پیوندی که برای کلیک ماوس تعریف شده است را تنظیم می‌کند. نوشت [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | پیوندی که برای عبور ماوس تعریف شده است را تنظیم می‌کند. نوشت [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | گزینه «Mark as decorative» را تنظیم می‌کند. خواندن/نوشتن **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | نام یک فایل صوتی که به یک [AudioFrame](../audioframe/) لینک شده است را تنظیم می‌کند. نوشت [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | نام یک شکل را تنظیم می‌کند. نوشت [System::String](../../system/string/). |
| virtual void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) | تعیین می‌کند آیا یک صدا در تمام اسلایدها پخش می‌شود یا نه. نوشت **bool**. |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | تعیین می‌کند آیا یک صدا به‌صورت حلقه‌ای است یا نه. نوشت **bool**. |
| virtual void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) | حالت پخش صدا را تنظیم می‌کند. نوشت [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ویژگی‌های خام قاب شکل را تنظیم می‌کند. نوشت [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) قاب تصویر را تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. نوشت **float**. |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | مقیاس عرض (نسبت به اندازه اصلی تصویر) قاب تصویر را تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. نوشت **float**. |
| virtual void [set_RewindAudio](./set_rewindaudio/)(**bool**) | تعیین می‌کند آیا یک صدا پس از پخش به‌صورت خودکار به شروع بازگردانده می‌شود یا نه. نوشت **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش ضدساعتی است. نوشت **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | نوع پیش‌تنظیم ژئومتری را تنظیم می‌کند. نکته: با تغییر مقدار، تمام مقادیر تنظیم مجدداً به مقدار پیش‌فرض خود بازمی‌گردند. نوشت [Slides::ShapeType](../shapetype/). |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | مدت زمان حذف‌شده از انتهای رسانه در حین پخش را بر حسب میلی‌ثانیه مشخص می‌کند. نوشت **float**. |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | مدت زمان حذف‌شده از ابتدای رسانه در حین پخش را بر حسب میلی‌ثانیه مشخص می‌کند. نوشت **float**. |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | حجم صدا را تنظیم می‌کند. نوشت [AudioVolumeMode](../audiovolumemode/). |
| virtual void [set_VolumeValue](./set_volumevalue/)(**float**) | حجم صدا را به درصد تنظیم می‌کند. نوشت **float**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشت **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | مختصات x گوشه بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشت **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | مختصات y گوشه بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشت **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | شکل را از شیء [IGeometryPath](../igeometrypath/) به‌روز می‌کند. مختصات‌ها باید نسبت به گوشه بالا-چپ شکل باشند. نوع شکل ([ShapeType](../shapetype/)) را به [ShapeType::Custom](../shapetype/) تغییر می‌دهد. |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | شکل را از آرایهٔ [IGeometryPath](../igeometrypath/) به‌روز می‌کند. مختصات‌ها باید نسبت به گوشه بالا-چپ شکل باشند. نوع شکل ([ShapeType](../shapetype/)) را به [ShapeType::Custom](../shapetype/) تغییر می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگو nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی آزادسازی قفل عبارت C# lock() . به‌صورت مستقیم صدا بزنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | محتوای [Shape](../shape/) را به عنوان فایل SVG ذخیره می‌کند. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | محتوای [Shape](../shape/) را به عنوان فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## مراجع

* کلاس [IPictureFrame](../ipictureframe/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)