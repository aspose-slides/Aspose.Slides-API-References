---
title: AudioFrame
second_title: مرجع API Aspose.Slides برای C++
description: یک کلیپ صوتی را بر روی اسلاید نشان می‌دهد.
type: docs
weight: 53
url: /fa/aspose.slides/audioframe/
---
## AudioFrame کلاس

یک کلیپ صوتی را بر روی یک اسلاید نشان می‌دهد.

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | در صورت عدم وجود، یک جای‌دار جدید اضافه می‌کند و ویژگی‌های جای‌دار را به مقدار مشخص شده تنظیم می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیءها را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | مقدار تنظیمات یک شکل را در اندیس مشخص شده برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | مجموعه‌ای از مقادیر تنظیمات شکل را برمی‌گرداند. فقط-خواندنی [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | آخرین شاخص ترک را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | زمان آخرین ترک را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | شاخص ترک آغاز را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | زمان ترک آغاز را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | خاصیت تعیین می‌کند که یک شکل در حالت نمایش سیاه-سفید چگونه رندر شود. فقط-خواندنی [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | مجموعه زیرنویس‌های بسته مرتبط با فریم صوتی را دریافت می‌کند. این خاصیت فقط-خواندنی است و یک [ICaptionsCollection](../icaptionscollection/) حاوی تمام مسیرهای زیرنویس را برمی‌گرداند. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | شیء [EffectFormat](../effectformat/) را برمی‌گرداند که شامل افکت‌های پیکسل اعمال‌شده بر یک شکل است. نکته: برای برخی انواع شکل‌ها که ویژگی اثر ندارند ممکن است مقدار null برگرداند. فقط-خواندنی [IEffectFormat](../ieffectformat/). |
| **bool** [get_Embedded](./get_embedded/)() override | مشخص می‌کند آیا صدایی در ارائه تعبیه شده است یا خیر. فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | شیء صوتی تعبیه‌شده را برمی‌گرداند. فقط-خواندنی [IAudio](../iaudio/). |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | مدت زمان محو اولیه رسانه بر حسب میلی‌ثانیه را مشخص می‌کند. فقط-خواندنی **float**. |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | مدت زمان محو انتهایی رسانه بر حسب میلی‌ثانیه را مشخص می‌کند. فقط-خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | شیء [FillFormat](../fillformat/) را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی پر برای یک شکل است. نکته: برای برخی انواع شکل‌ها که ویژگی پر ندارند ممکن است مقدار null برگرداند. فقط-خواندنی [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | ویژگی‌های قاب شکل را برمی‌گرداند. فقط-خواندنی [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود دریافت می‌کند. فقط-خواندنی **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | تعیین می‌کند آیا شکل مخفی است یا خیر. فقط-خواندنی **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | مشخص می‌کند آیا یک [AudioFrame](./) مخفی است یا خیر. فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | پیوندی که برای کلیک موش تعریف شده است را برمی‌گرداند. فقط-خواندنی [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | مدیر پیوندها را برمی‌گرداند. فقط-خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | پیوندی که برای شناور موش تعریف شده است را برمی‌گرداند. فقط-خواندنی [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | مشخص می‌کند آیا [PictureFrame](../pictureframe/) یک شیء Cameo است یا خیر. فقط-خواندنی **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | گزینه 'علامت به‌عنوان تزئینی' را دریافت می‌کند. خواندن/نوشتن **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | مشخص می‌کند آیا شکل گروه‌بندی شده است یا خیر. فقط-خواندنی **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | مشخص می‌کند آیا شکل TextHolder_PPT است یا خیر. فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | شیء [LineFormat](../lineformat/) را باز می‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. نکته: برای برخی انواع شکل‌ها که ویژگی خط ندارند ممکن است مقدار null برگرداند. فقط-خواندنی [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | نام فایل صوتی که به یک [AudioFrame](./) لینک شده است را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | نام یک شکل را برمی‌گرداند. نباید null باشد. در صورت نیاز از رشته خالی استفاده کنید. فقط-خواندنی [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | شناسه یکتا scoped به اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop امکان ارجاع قابل اطمینان به شکل را از هرجای سند می‌دهد. فقط-خواندنی **uint32_t**. همچنین ببینید [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | شیء والد [GroupShape](../groupshape/) را در صورت گروه‌بندی شکل برمی‌گرداند. در غیر این صورت مقدار null برمی‌گرداند. فقط-خواندنی [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | شیء [PictureFillFormat](../picturefillformat/) برای یک قاب تصویر را برمی‌گرداند. فقط-خواندنی [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | جا‌دار یک شکل را برمی‌گرداند. اگر شکل جا‌داری نداشته باشد مقدار null برمی‌گرداند. فقط-خواندنی [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | مشخص می‌کند آیا صدا در تمام اسلایدها در حال پخش است یا خیر. فقط-خواندنی **bool**. |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | مشخص می‌کند آیا صدا به‌صورت حلقه‌ای است یا خیر. فقط-خواندنی **bool**. |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | حالت پخش صدا را برمی‌گرداند. فقط-خواندنی [AudioPlayModePreset](../audioplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | ارائه والد یک اسلاید را برمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | ویژگی‌های خام قاب شکل را برمی‌گرداند. فقط-خواندنی [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) قاب تصویر را برمی‌گرداند. مقدار 1.0 معادل 100٪ است. فقط-خواندنی **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | مقیاس عرض (نسبت به اندازه اصلی تصویر) قاب تصویر را برمی‌گرداند. مقدار 1.0 معادل 100٪ است. فقط-خواندنی **float**. |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | مشخص می‌کند آیا پس از پخش صدا به‌صورت خودکار به شروع باز می‌گردد یا خیر. فقط-خواندنی **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند. مقدار مثبت نشان‌دهندۀ چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهندۀ چرخش پادساعت‌گرد است. فقط-خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | شیء سبک شکل را برمی‌گرداند. فقط-خواندنی [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | شیء [ThreeDFormat](../threedformat/) را برمی‌گرداند که شامل ویژگی‌های افکت ۳بعدی برای یک شکل است. نکته: برای برخی انواع شکل‌ها که ویژگی ۳بعدی ندارند ممکن است مقدار null برگرداند. فقط-خواندنی [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | مدت زمان حذف شده از انتهای رسانه در حین پخش، بر حسب میلی‌ثانیه را مشخص می‌کند. فقط-خواندنی **float**. |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | مدت زمان حذف شده از ابتدای رسانه در حین پخش، بر حسب میلی‌ثانیه را مشخص می‌کند. فقط-خواندنی **float**. |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | شناسه داخلی scoped به ارائه که برای استفاده افزونه‌ها یا کدهای دیگر منظور شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به عنوان کلید یکتا پایدار در نظر گرفته شود. فقط-خواندنی **uint32_t**. همچنین ببینید [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | حجم صدا را برمی‌گرداند. فقط-خواندنی [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_VolumeValue](./get_volumevalue/)() override | حجم صدا را به درصد برمی‌گرداند. فقط-خواندنی **float**. |
| **float** [get_Width](../shape/get_width/)() override | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود دریافت می‌کند. فقط-خواندنی **float**. |
| **float** [get_X](../shape/get_x/)() override | مختصات x گوشهٔ بالایی-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود دریافت می‌کند. فقط-خواندنی **float**. |
| **float** [get_Y](../shape/get_y/)() override | مختصات y گوشهٔ بالایی-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود دریافت می‌کند. فقط-خواندنی **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در انتهای ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در ابتدای ترتیب z را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | یک شکل جا‌دار پایه را برمی‌گرداند (شکلی از چیدمان و/یا اسلاید اصلی که شکل کنونی از آن ارث‌بری شده است). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | یک کپی از مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالایی-چپ شکل است. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | تصویر بندانگشتی شکل را برمی‌گرداند. نوع محدودهٔ تصویر بندانگشتی [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به‌صورت پیش‌فرض استفاده می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | تصویر بندانگشتی شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | مرزهای بصری شکل را که از محتوای رندرش محاسبه شده است، دریافت می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کپی‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیربرده‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیربرده‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌وار شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | مشخص می‌کند که این شکل یک جای‌دار نیست. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | شاخص آخرین ترک را تنظیم می‌کند. نوشتن **int32_t**. |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | زمان آخرین ترک را تنظیم می‌کند. نوشتن **int32_t**. |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | شاخص ترک شروع را تنظیم می‌کند. نوشتن **int32_t**. |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | زمان ترک شروع را تنظیم می‌کند. نوشتن **int32_t**. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | خاصیت تعیین می‌کند که یک شکل در حالت نمایش سیاه-سفید چگونه رندر شود. نوشتن [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | شیء صوتی تعبیه‌شده را تنظیم می‌کند. نوشتن [IAudio](../iaudio/). |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | مدت زمان محو اولیه رسانه بر حسب میلی‌ثانیه را مشخص می‌کند. نوشتن **float**. |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | مدت زمان محو انتهایی رسانه بر حسب میلی‌ثانیه را مشخص می‌کند. نوشتن **float**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ویژگی‌های قاب شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | مشخص می‌کند آیا شکل مخفی است. نوشتن **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | مشخص می‌کند آیا یک [AudioFrame](./) مخفی است. نوشتن **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | پیوندی که برای کلیک موش تعریف شده است را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | پیوندی که برای شناور موش تعریف شده است را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | گزینه 'علامت به‌عنوان تزئینی' را تنظیم می‌کند. خواندن/نوشتن **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | نام فایل صوتی که به یک [AudioFrame](./) لینک شده است را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | نام یک شکل را تنظیم می‌کند. نباید null باشد. در صورت نیاز از رشته خالی استفاده کنید. نوشتن [System::String](../../system/string/). |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | مشخص می‌کند آیا صدا در تمام اسلایدها در حال پخش است. نوشتن **bool**. |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | مشخص می‌کند آیا صدا به‌صورت حلقه‌ای است. نوشتن **bool**. |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | حالت پخش صدا را تنظیم می‌کند. نوشتن [AudioPlayModePreset](../audioplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ویژگی‌های خام قاب شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) قاب تصویر را تنظیم می‌کند. مقدار 1.0 برابر با 100٪ است. نوشتن **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | مقیاس عرض (نسبت به اندازه اصلی تصویر) قاب تصویر را تنظیم می‌کند. مقدار 1.0 برابر با 100٪ است. نوشتن **float**. |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | مشخص می‌کند آیا پس از پخش صدا به‌صورت خودکار به شروع باز می‌گردد. نوشتن **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را تنظیم می‌کند. مقدار مثبت نشان‌دهندۀ چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهندۀ چرخش پادساعت‌گرد است. نوشتن **float**. |
| [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | مدت زمان حذف شده از انتهای رسانه در حین پخش، بر حسب میلی‌ثانیه را مشخص می‌کند. نوشتن **float**. |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | مدت زمان حذف شده از ابتدای رسانه در حین پخش، بر حسب میلی‌ثانیه را مشخص می‌کند. نوشتن **float**. |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | حجم صدا را تنظیم می‌کند. نوشتن [AudioVolumeMode](../audiovolumemode/). |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | حجم صدا را به درصد تنظیم می‌کند. نوشتن **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| void [set_X](../shape/set_x/)(**float**) override | مختصات x گوشهٔ بالایی-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | مختصات y گوشهٔ بالایی-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | هندسه شکل را از شیء [IGeometryPath](../igeometrypath/) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالایی-چپ شکل باشد. نوع شکل ([ShapeType](../shapetype/)) را به [ShapeType::Custom](../shapetype/) تغییر می‌دهد. |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | هندسه شکل را از آرایهٔ [IGeometryPath](../igeometrypath/) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالایی-چپ شکل باشد. نوع شکل ([ShapeType](../shapetype/)) را به [ShapeType::Custom](../shapetype/) تغییر می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (نه اشتراک‌گذاری) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارش ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارش ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری با دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارش ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارش ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | محتویات [Shape](../shape/) را به‌عنوان فایل SVG ذخیره می‌کند. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | محتویات [Shape](../shape/) را به‌عنوان فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برید. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## توضیحات

مثال‌های زیر نشان می‌دهند چگونه گزینه‌های پخش [Audio](../audio/) را تغییر دهید. 
```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Gets the AudioFrame shape
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Sets the Play mode to play on click
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Sets the volume to Low
audioFrame->set_Volume(AudioVolumeMode::Low);
// Sets the audio to play across slides
audioFrame->set_PlayAcrossSlides(true);
// Disables loop for the audio
audioFrame->set_PlayLoopMode(false);
// Hides the AudioFrame during the slide show
audioFrame->set_HideAtShowing(true);
// Rewinds the audio to start after playing
audioFrame->set_RewindAudio(true);
// Saves the PowerPoint file to disk
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [PictureFrame](../pictureframe/)
* کلاس [IAudioFrame](../iaudioframe/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)