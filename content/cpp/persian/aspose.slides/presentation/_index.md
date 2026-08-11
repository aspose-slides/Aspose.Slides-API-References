---
title: Presentation
second_title: مرجع API Aspose.Slides برای C++
description: یک ارائه Microsoft PowerPoint را نشان می‌دهد.
type: docs
weight: 4837
url: /fa/aspose.slides/presentation/
---
## Presentation کلاس

Represents a Microsoft PowerPoint presentation.

```cpp
class Presentation : public Aspose::Slides::IPresentation,
                     public Aspose::Slides::IDOMObject
```

## متدها

| Method | Description |
| --- | --- |
| void [Dispose](./dispose/)() override | تمام منابع استفاده شده توسط این [Presentation](./) شی را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICustomXmlPart](../icustomxmlpart/)\>\> [get_AllCustomXmlParts](./get_allcustomxmlparts/)() override | تمام بخش‌های داده سفارشی را در ارائه باز می‌گرداند. فقط-خواندنی [ICustomXmlPart](../icustomxmlpart/)[]. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Audio](./get_audio/)(**int32_t**) override | فایل صوتی درون‌ساخته در ارائه را در ایندکس مشخص شده باز می‌گرداند. فقط-خواندنی [Aspose::Slides::IAudio](../iaudio/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioCollection](../iaudiocollection/)\> [get_Audios](./get_audios/)() override | مجموعه تمام فایل‌های صوتی درون‌ساخته در ارائه را باز می‌گرداند. فقط-خواندنی [IAudioCollection](../iaudiocollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_CommentAuthor](./get_commentauthor/)(**int32_t**) override | نویسندهٔ نظر را در ایندکس مشخص شده باز می‌گرداند. فقط-خواندنی [Aspose::Slides::ICommentAuthor](../icommentauthor/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthorCollection](../icommentauthorcollection/)\> [get_CommentAuthors](./get_commentauthors/)() override | مجموعهٔ نویسندگان نظرات را باز می‌گرداند. فقط-خواندنی [ICommentAuthorCollection](../icommentauthorcollection/). |
| [System::DateTime](../../system/datetime/) [get_CurrentDateTime](./get_currentdatetime/)() override | تاریخ و زمان را باز می‌گرداند که محتوای فیلدهای datetime را جایگزین می‌کند. به طور پیش‌فرض زمان ایجاد این [Presentation](./). فقط-خواندنی [System::DateTime](../../system/datetime/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | داده‌های سفارشی ارائه را باز می‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_DefaultTextStyle](./get_defaulttextstyle/)() override | سبک متن پیش‌فرض برای اشکال را باز می‌گرداند. فقط-خواندنی [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignature](../idigitalsignature/)\> [get_DigitalSignature](./get_digitalsignature/)(**int32_t**) override | امضای دیجیتال استفاده شده برای امضای ارائه در ایندکس مشخص شده را باز می‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignatureCollection](../idigitalsignaturecollection/)\> [get_DigitalSignatures](./get_digitalsignatures/)() override | مجموعهٔ امضاهای استفاده شده برای امضای ارائه را باز می‌گرداند. فقط-خواندنی [IDigitalSignatureCollection](../idigitalsignaturecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [get_DocumentProperties](./get_documentproperties/)() override | [DocumentProperties](../documentproperties/) شیی را باز می‌گرداند که شامل خصوصیات سند استاندارد و سفارشی است. فقط-خواندنی [IDocumentProperties](../idocumentproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_DocumentProperty](./get_documentproperty/)([System::String](../../system/string/)) override | ویژگی سفارشی تعریف‌شده توسط نام را باز می‌گرداند. |
| **int32_t** [get_FirstSlideNumber](./get_firstslidenumber/)() override | شمارهٔ اولین اسلاید در ارائه را نمایندگی می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontsManager](../ifontsmanager/)\> [get_FontsManager](./get_fontsmanager/)() override | مدیر قلم‌ها را باز می‌گرداند. فقط-خواندنی [IFontsManager](../ifontsmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | مدیر HeaderFooter فعلی را باز می‌گرداند. فقط-خواندنی [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | دسترسی آسان به تمام پیوندهای موجود در تمام اسلایدهای ارائه (نه در مستر، طرح‌بندی، اسلایدهای یادداشت) را فراهم می‌کند. فقط-خواندنی [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_Image](./get_image/)(**int32_t**) override | تصویر در ارائه را در ایندکس مشخص شده باز می‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImageCollection](../iimagecollection/)\> [get_Images](./get_images/)() override | مجموعه تمام تصاویر در ارائه را باز می‌گرداند. فقط-خواندنی [IImageCollection](../iimagecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) override | اسلاید طرح‌بندی را بر اساس ایندکس باز می‌گرداند. فقط-خواندنی [Aspose::Slides::ILayoutSlide](../ilayoutslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() override | فهرست تمام اسلایدهای طرح‌بندی تعریف‌شده در ارائه را باز می‌گرداند. فقط-خواندنی [IGlobalLayoutSlideCollection](../igloballayoutslidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [get_Master](./get_master/)(**int32_t**) override | اسلاید مستر تعریف‌شده در ارائه را در ایندکس مشخص شده باز می‌گرداند. فقط-خواندنی [Aspose::Slides::IMasterSlide](../imasterslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterHandoutSlideManager](../imasterhandoutslidemanager/)\> [get_MasterHandoutSlideManager](./get_masterhandoutslidemanager/)() override | مدیر مستر برگه‌برداری را باز می‌گرداند. فقط-خواندنی [IMasterHandoutSlideManager](../imasterhandoutslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterNotesSlideManager](../imasternotesslidemanager/)\> [get_MasterNotesSlideManager](./get_masternotesslidemanager/)() override | مدیر مستر یادداشت‌ها را باز می‌گرداند. فقط-خواندنی [IMasterNotesSlideManager](../imasternotesslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideCollection](../imasterslidecollection/)\> [get_Masters](./get_masters/)() override | فهرست تمام اسلایدهای مستر تعریف‌شده در ارائه را باز می‌گرداند. فقط-خواندنی [IMasterSlideCollection](../imasterslidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/)\> [get_MasterTheme](./get_mastertheme/)() override | تم مستر را باز می‌گرداند. فقط-خواندنی [Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSize](../inotessize/)\> [get_NotesSize](./get_notessize/)() override | شی اندازه اسلاید یادداشت‌ها را باز می‌گرداند. فقط-خواندنی [INotesSize](../inotessize/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProtectionManager](../iprotectionmanager/)\> [get_ProtectionManager](./get_protectionmanager/)() override | مدیر مجوزهای این ارائه را دریافت می‌کند. فقط-خواندنی [IProtectionManager](../iprotectionmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_Section](./get_section/)(**int32_t**) override | بخش اسلاید تعریف‌شده در ارائه را در ایندکس مشخص شده باز می‌گرداند. فقط-خواندنی [Aspose::Slides::ISection](../isection/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionCollection](../isectioncollection/)\> [get_Sections](./get_sections/)() override | فهرست تمام بخش‌های اسلاید تعریف‌شده در ارائه را باز می‌گرداند. فقط-خواندنی [ISectionCollection](../isectioncollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabelCollection](../isensitivitylabelcollection/)\> [get_SensitivityLabels](./get_sensitivitylabels/)() override | مجموعهٔ برچسب‌های حساسیتی اعمال‌شده به سند ارائه را باز می‌گرداند. فقط-خواندنی [ISensitivityLabelCollection](../isensitivitylabelcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)(**int32_t**) override | اسلاید تعریف‌شده در ارائه را در ایندکس مشخص شده باز می‌گرداند. فقط-خواندنی [Aspose::Slides::ISlide](../islide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideCollection](../islidecollection/)\> [get_Slides](./get_slides/)() override | فهرست تمام اسلایدهای تعریف‌شده در ارائه را باز می‌گرداند. فقط-خواندنی [ISlideCollection](../islidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowSettings](../slideshowsettings/)\> [get_SlideShowSettings](./get_slideshowsettings/)() const | تنظیمات نمایش اسلایدها برای ارائه را باز می‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideSize](../islidesize/)\> [get_SlideSize](./get_slidesize/)() override | شی اندازه اسلاید را باز می‌گرداند. فقط-خواندنی [ISlideSize](../islidesize/). |
| [Aspose::Slides::SourceFormat](../sourceformat/) [get_SourceFormat](./get_sourceformat/)() override | اطلاعات دربارهٔ فرمت بارگذاری ارائه را باز می‌گرداند. فقط-خواندنی [SourceFormat](../sourceformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\> [get_VbaProject](./get_vbaproject/)() override | پروژه VBA با ماکروهای ارائه را دریافت می‌کند. فقط-خواندنی [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_Video](./get_video/)(**int32_t**) override | فایل ویدئوی درون‌ساخته در ارائه را در ایندکس مشخص شده باز می‌گرداند. فقط-خواندنی [Aspose::Slides::IVideo](../ivideo/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoCollection](../ivideocollection/)\> [get_Videos](./get_videos/)() override | مجموعه تمام فایل‌های ویدئوی درون‌ساخته در ارائه را باز می‌گرداند. فقط-خواندنی [IVideoCollection](../ivideocollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IViewProperties](../iviewproperties/)\> [get_ViewProperties](./get_viewproperties/)() override | ویژگی‌های نمای کلی ارائه را دریافت می‌کند. فقط-خواندنی [IViewProperties](../iviewproperties/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شی را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) override | شی‌های Image را برای تمام اسلایدهای ارائه باز می‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) override | شی‌های Thumbnail Image را برای اسلایدهای مشخص شده از یک ارائه باز می‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) override | شی‌های Thumbnail Image را برای تمام اسلایدهای ارائه با مقیاس سفارشی باز می‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, **float**, **float**) override | شی‌های Thumbnail Image را برای اسلایدهای مشخص شده از یک ارائه با مقیاس سفارشی باز می‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) override | شی‌های Thumbnail Image را برای تمام اسلایدهای ارائه با اندازهٔ مشخص باز می‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [System::Drawing::Size](../../system.drawing/size/)) override | شی‌های Thumbnail Image را برای اسلایدهای مشخص شده از یک ارائه با اندازهٔ مشخص باز می‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [GetSlideById](./getslidebyid/)(**uint32_t**) override | یک [Slide](../slide/)، [MasterSlide](../masterslide/) یا [LayoutSlide](../layoutslide/) را بر اساس Id باز می‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| void [HighlightRegex](./highlightregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | تمام تطابق‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/)) override | تمام تطابق‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | تمام تطابق‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شی نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | قطعات متن با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام اشکال قابل‌پذیر در تمام اسلایدها ترکیب می‌کند. |
| void [Lock](../../system/object/lock/)() | اجرا کننده قفل‌گذاری عبارت lock() در C#. به‌صورت مستقیم صدا بزنید یا از شی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شی را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌نماید. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
|  [Presentation](./presentation/)() | این سازنده یک ارائه جدید از صفر می‌سازد. ارائهٔ ایجادشده دارای یک اسلاید خالی است. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | این سازنده یک ارائه جدید از صفر می‌سازد. ارائهٔ ایجادشده دارای یک اسلاید خالی است. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | این سازنده مکانیزم اصلی برای خواندن یک [Presentation](./) موجود است. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | این سازنده مکانیزم اصلی برای خواندن یک [Presentation](./) موجود است. |
|  [Presentation](./presentation/)([System::String](../../system/string/)) | این سازنده مسیر فایل منبعی را می‌گیرد که محتویات [Presentation](./) از آن خوانده می‌شود. |
|  [Presentation](./presentation/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | این سازنده مسیر فایل منبعی را می‌گیرد که محتویات [Presentation](./) از آن خوانده می‌شود. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شی نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | ویژه‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | ویژه‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| void [ReplaceRegex](./replaceregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | تمام تطابق‌های عبارت منظم را با رشتهٔ مشخص شده جایگزین می‌کند. |
| void [ReplaceText](./replacetext/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | تمام رخدادهای متن مشخص شده را با متن دیگری که مشخص شده است جایگزین می‌کند. |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | تمام اسلایدهای یک ارائه را به فایلی با قالب مشخص ذخیره می‌کند. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | تمام اسلایدهای یک ارائه را به یک جریان با قالب مشخص ذخیره می‌کند. |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | تمام اسلایدهای یک ارائه را به فایلی با قالب مشخص و گزینه‌های اضافه ذخیره می‌کند. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | تمام اسلایدهای یک ارائه را به یک جریان با قالب مشخص و گزینه‌های اضافه ذخیره می‌کند. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../aspose.slides.export.xaml/ixamloptions/)\>) override | تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌ها که نشانگر XAML هستند ذخیره می‌کند. |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | اسلایدهای مشخص شده از یک ارائه را به فایلی با قالب مشخص و حفظ شماره صفحه ذخیره می‌کند. |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | اسلایدهای مشخص شده از یک ارائه را به فایلی با قالب مشخص و حفظ شماره صفحه ذخیره می‌کند. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | اسلایدهای مشخص شده از یک ارائه را به یک جریان با قالب مشخص و حفظ شماره صفحه ذخیره می‌کند. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | اسلایدهای مشخص شده از یک ارائه را به یک جریان با قالب مشخص و حفظ شماره صفحه ذخیره می‌کند. |
| void [set_CurrentDateTime](./set_currentdatetime/)([System::DateTime](../../system/datetime/)) override | تاریخ و زمان را تنظیم می‌کند که محتوای فیلدهای datetime را جایگزین می‌کند. به طور پیش‌فرض زمان ایجاد این [Presentation](./). قابل نوشتن [System::DateTime](../../system/datetime/). |
| void [set_DocumentProperty](./set_documentproperty/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | ویژگی سفارشی تعریف‌شده توسط نام را تنظیم می‌کند. |
| void [set_FirstSlideNumber](./set_firstslidenumber/)(**int32_t**) override | شمارهٔ اولین اسلاید در ارائه را نمایندگی می‌کند. |
| void [set_VbaProject](./set_vbaproject/)([System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\>) override | پروژه VBA با ماکروهای ارائه را تنظیم می‌کند. قابل نوشتن [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شی را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## توضیحات

مثال زیر نشان می‌دهد چگونه یک PowerPoint [Presentation](./) ایجاد شود.
```cpp
// یک شی Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

// اولین اسلاید را دریافت می‌کند
auto slide = presentation->get_Slides()->idx_get(0);
// یک شکل خودکار از نوع خط اضافه می‌کند
slide->get_Shapes()->AddAutoShape(ShapeType::Line, 50.0f, 150.0f, 300.0f, 0.0f);
// فایل ارائه را ذخیره می‌کند.
presentation->Save(u"NewPresentation_out.pptx", SaveFormat::Pptx);
```
مثال زیر نشان می‌دهد چگونه [Presentation](./) را باز و ذخیره کنید.
```cpp
// هر فایل پشتیبانی‌شده‌ای را در Presentation بارگذاری کنید، مثلاً ppt، pptx، odp و غیره.
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"Sample.odp");

// فایل ارائه را ذخیره کنید.
presentation->Save(u"OutputPresenation.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [IPresentation](../ipresentation/)
* کلاس [IDOMObject](../idomobject/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)