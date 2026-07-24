---
title: Presentation
second_title: Aspose.Slides için C++ API Referansı
description: Microsoft PowerPoint sunumunu temsil eder.
type: docs
weight: 4837
url: /tr/aspose.slides/presentation/
---
## Presentation sınıfı

Microsoft PowerPoint sunumunu temsil eder.

```cpp
class Presentation : public Aspose::Slides::IPresentation,
                     public Aspose::Slides::IDOMObject
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [Dispose](./dispose/)() override | Bu [Presentation](./) nesnesi tarafından kullanılan tüm kaynakları serbest bırakır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) anlamı ile karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesnelerini karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesnelerini karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICustomXmlPart](../icustomxmlpart/)\>\> [get_AllCustomXmlParts](./get_allcustomxmlparts/)() override | Sunumdaki tüm özel veri bölümlerini döndürür. Yalnızca okuma [ICustomXmlPart](../icustomxmlpart/)[]. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Audio](./get_audio/)(**int32_t**) override | Belirtilen indeksteki gömülü ses dosyasını döndürür. Yalnızca okuma [Aspose::Slides::IAudio](../iaudio/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioCollection](../iaudiocollection/)\> [get_Audios](./get_audios/)() override | Sunumdaki tüm gömülü ses dosyalarının koleksiyonunu döndürür. Yalnızca okuma [IAudioCollection](../iaudiocollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_CommentAuthor](./get_commentauthor/)(**int32_t**) override | Belirtilen indeksteki yorum yazarını döndürür. Yalnızca okuma [Aspose::Slides::ICommentAuthor](../icommentauthor/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthorCollection](../icommentauthorcollection/)\> [get_CommentAuthors](./get_commentauthors/)() override | Yorum yazarlarının koleksiyonunu döndürür. Yalnızca okuma [ICommentAuthorCollection](../icommentauthorcollection/). |
| [System::DateTime](../../system/datetime/) [get_CurrentDateTime](./get_currentdatetime/)() override | Tarih ve saat alanlarını değiştirecek tarih ve zamanı döndürür. Varsayılan olarak bu [Presentation](./) nesnesinin oluşturulma zamanı. Okuma [System::DateTime](../../system/datetime/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | Sunumun özel verilerini döndürür. Yalnızca okuma [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_DefaultTextStyle](./get_defaulttextstyle/)() override | Şekiller için varsayılan metin stilini döndürür. Yalnızca okuma [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignature](../idigitalsignature/)\> [get_DigitalSignature](./get_digitalsignature/)(**int32_t**) override | Belirtilen indeksteki sunumu imzalayan dijital imzayı döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignatureCollection](../idigitalsignaturecollection/)\> [get_DigitalSignatures](./get_digitalsignatures/)() override | Sunumu imzalayan imzaların koleksiyonunu döndürür. Yalnızca okuma [IDigitalSignatureCollection](../idigitalsignaturecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [get_DocumentProperties](./get_documentproperties/)() override | [DocumentProperties](../documentproperties/) nesnesini döndürür; bu nesne standart ve özel belge özelliklerini içerir. Yalnızca okuma [IDocumentProperties](../idocumentproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_DocumentProperty](./get_documentproperty/)([System::String](../../system/string/)) override | İsimle tanımlanan özel özelliği döndürür. |
| **int32_t** [get_FirstSlideNumber](./get_firstslidenumber/)() override | Sunumdaki ilk slayt numarasını temsil eder. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontsManager](../ifontsmanager/)\> [get_FontsManager](./get_fontsmanager/)() override | Yazı tipi yöneticisini döndürür. Yalnızca okuma [IFontsManager](../ifontsmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | Gerçek HeaderFooter yöneticisini döndürür. Yalnızca okuma [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | Tüm sunum slaytlarındaki (master, layout, not slaytları hariç) tüm köprülerin kolay erişimini sağlar. Yalnızca okuma [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_Image](./get_image/)(**int32_t**) override | Belirtilen indeksteki sunumdaki resmi döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImageCollection](../iimagecollection/)\> [get_Images](./get_images/)() override | Sunumdaki tüm resimlerin koleksiyonunu döndürür. Yalnızca okuma [IImageCollection](../iimagecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) override | İndekse göre yerleşim slaytını döndürür. Yalnızca okuma [Aspose::Slides::ILayoutSlide](../ilayoutslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() override | Sunumda tanımlı tüm yerleşim slaytlarının listesini döndürür. Yalnızca okuma [IGlobalLayoutSlideCollection](../igloballayoutslidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [get_Master](./get_master/)(**int32_t**) override | Belirtilen indeksteki sunumda tanımlı bir master slaytı döndürür. Yalnızca okuma [Aspose::Slides::IMasterSlide](../imasterslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterHandoutSlideManager](../imasterhandoutslidemanager/)\> [get_MasterHandoutSlideManager](./get_masterhandoutslidemanager/)() override | El ilanı master yöneticisini döndürür. Yalnızca okuma [IMasterHandoutSlideManager](../imasterhandoutslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterNotesSlideManager](../imasternotesslidemanager/)\> [get_MasterNotesSlideManager](./get_masternotesslidemanager/)() override | Notlar master yöneticisini döndürür. Yalnızca okuma [IMasterNotesSlideManager](../imasternotesslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideCollection](../imasterslidecollection/)\> [get_Masters](./get_masters/)() override | Sunumda tanımlı tüm master slaytların listesini döndürür. Yalnızca okuma [IMasterSlideCollection](../imasterslidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/)\> [get_MasterTheme](./get_mastertheme/)() override | Master temayı döndürür. Yalnızca okuma [Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSize](../inotessize/)\> [get_NotesSize](./get_notessize/)() override | Not slaytı boyut nesnesini döndürür. Yalnızca okuma [INotesSize](../inotessize/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProtectionManager](../iprotectionmanager/)\> [get_ProtectionManager](./get_protectionmanager/)() override | Bu sunumun izin yöneticisini alır. Yalnızca okuma [IProtectionManager](../iprotectionmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_Section](./get_section/)(**int32_t**) override | Belirtilen indeksteki sunumda tanımlı bir slayt bölümünü döndürür. Yalnızca okuma [Aspose::Slides::ISection](../isection/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionCollection](../isectioncollection/)\> [get_Sections](./get_sections/)() override | Sunumda tanımlı tüm slayt bölümlerinin listesini döndürür. Yalnızca okuma [ISectionCollection](../isectioncollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabelCollection](../isensitivitylabelcollection/)\> [get_SensitivityLabels](./get_sensitivitylabels/)() override | Sunum belgesine uygulanan hassasiyet etiketlerinin koleksiyonunu döndürür. Yalnızca okuma [ISensitivityLabelCollection](../isensitivitylabelcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)(**int32_t**) override | Belirtilen indeksteki sunumda tanımlı bir slaytı döndürür. Yalnızca okuma [Aspose::Slides::ISlide](../islide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideCollection](../islidecollection/)\> [get_Slides](./get_slides/)() override | Sunumda tanımlı tüm slaytların listesini döndürür. Yalnızca okuma [ISlideCollection](../islidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowSettings](../slideshowsettings/)\> [get_SlideShowSettings](./get_slideshowsettings/)() const | Sunumun slayt gösterisi ayarlarını döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideSize](../islidesize/)\> [get_SlideSize](./get_slidesize/)() override | Slayt boyut nesnesini döndürür. Yalnızca okuma [ISlideSize](../islidesize/). |
| [Aspose::Slides::SourceFormat](../sourceformat/) [get_SourceFormat](./get_sourceformat/)() override | Sunumun yüklendiği format hakkında bilgiyi döndürür. Yalnızca okuma [SourceFormat](../sourceformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\> [get_VbaProject](./get_vbaproject/)() override | Sunum makroları içeren VBA projesini alır. Okuma [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_Video](./get_video/)(**int32_t**) override | Belirtilen indeksteki sunumdaki gömülü video dosyasını döndürür. Yalnızca okuma [Aspose::Slides::IVideo](../ivideo/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoCollection](../ivideocollection/)\> [get_Videos](./get_videos/)() override | Sunumdaki tüm gömülü video dosyalarının koleksiyonunu döndürür. Yalnızca okuma [IVideoCollection](../ivideocollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IViewProperties](../iviewproperties/)\> [get_ViewProperties](./get_viewproperties/)() override | Sunum genelindeki görünüm özelliklerini alır. Yalnızca okuma [IViewProperties](../iviewproperties/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin hashlenmesini sağlar. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) override | Sunumun tüm slaytları için Image nesnelerini döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) override | Sunumun belirli slaytları için Thumbnail Image nesnelerini döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) override | Özel ölçeklendirme ile sunumun tüm slaytları için Thumbnail Image nesnelerini döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, **float**, **float**) override | Özel ölçeklendirme ile sunumun belirli slaytları için Thumbnail Image nesnelerini döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) override | Belirtilen boyutla sunumun tüm slaytları için Thumbnail Image nesnelerini döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [System::Drawing::Size](../../system.drawing/size/)) override | Belirtilen boyutla sunumun belirli slaytları için Thumbnail Image nesnelerini döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [GetSlideById](./getslidebyid/)(**uint32_t**) override | Id ile bir [Slide](../slide/), [MasterSlide](../masterslide/) veya [LayoutSlide](../layoutslide/) döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| void [HighlightRegex](./highlightregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | Belirtilen renk ile düzenli ifadenin tüm eşleşmelerini vurgular. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/)) override | Belirtilen renk ile örnek metnin tüm eşleşmelerini vurgular. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | Belirtilen renk ile örnek metnin tüm eşleşmelerini vurgular. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogu. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | Tüm slaytlardaki tüm uygun şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip runları birleştirir. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
|  [Presentation](./presentation/)() | Bu kurucu, yeni bir sunumu sıfırdan oluşturur. Oluşturulan sunum bir boş slayta sahiptir. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | Bu kurucu, yeni bir sunumu sıfırdan oluşturur. Oluşturulan sunum bir boş slayta sahiptir. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Bu kurucu, mevcut bir [Presentation](./) okumanın temel mekanizmasıdır. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | Bu kurucu, mevcut bir [Presentation](./) okumanın temel mekanizmasıdır. |
|  [Presentation](./presentation/)([System::String](../../system/string/)) | Bu kurucu, [Presentation](./) içeriğinin okunduğu kaynak dosya yolunu alır. |
|  [Presentation](./presentation/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | Bu kurucu, [Presentation](./) içeriğinin okunduğu kaynak dosya yolunu alır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirilmiş şekli. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirilmiş şekli. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [ReplaceRegex](./replaceregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | Düzenli ifadenin tüm eşleşmelerini belirtilen dizeyle değiştirir. |
| void [ReplaceText](./replacetext/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | Belirtilen metnin tüm oluşumlarını başka bir belirtilen metinle değiştirir. |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | Tüm slaytları belirtilen formatta bir dosyaya kaydeder. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | Tüm slaytları belirtilen formatta bir akışa kaydeder. |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | Tüm slaytları belirtilen formatta ve ek seçeneklerle bir dosyaya kaydeder. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | Tüm slaytları belirtilen formatta ve ek seçeneklerle bir akışa kaydeder. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../aspose.slides.export.xaml/ixamloptions/)\>) override | Tüm slaytları XAML işaretlemesini temsil eden bir dosya kümesine kaydeder. |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | Belirtilen slaytları sayfa numarası koruyarak belirtilen formatta bir dosyaya kaydeder. |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | Belirtilen slaytları sayfa numarası koruyarak belirtilen formatta bir dosyaya kaydeder. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | Belirtilen slaytları sayfa numarası koruyarak belirtilen formatta bir akışa kaydeder. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | Belirtilen slaytları sayfa numarası koruyarak belirtilen formatta bir akışa kaydeder. |
| void [set_CurrentDateTime](./set_currentdatetime/)([System::DateTime](../../system/datetime/)) override | Tarih ve saat alanlarının içeriğini değiştirecek tarih ve saati ayarlar. Varsayılan olarak bu [Presentation](./) nesnesinin oluşturulma zamanı. Yaz [System::DateTime](../../system/datetime/). |
| void [set_DocumentProperty](./set_documentproperty/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | İsimle tanımlanan özel özelliği ayarlar. |
| void [set_FirstSlideNumber](./set_firstslidenumber/)(**int32_t**) override | Sunumdaki ilk slayt numarasını temsil eder. |
| void [set_VbaProject](./set_vbaproject/)([System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\>) override | Sunum makrolarıyla VBA projesini ayarlar. Yaz [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını bir zayıf gösterici olarak ayarlar (paylaşılan yerine). Kapsayıcılardaki göstergeleri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler ya da ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler ya da ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler ya da ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler ya da ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Açıklamalar

Aşağıdaki örnek PowerPoint [Presentation](./) oluşturmayı gösterir. 
```cpp
// Sunum dosyasını temsil eden bir Presentation nesnesi oluşturun
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

// İlk slaytı al
auto slide = presentation->get_Slides()->idx_get(0);
// Tipi çizgi olan bir otomatik şekil ekle
slide->get_Shapes()->AddAutoShape(ShapeType::Line, 50.0f, 150.0f, 300.0f, 0.0f);
// Sunum dosyasını kaydet.
presentation->Save(u"NewPresentation_out.pptx", SaveFormat::Pptx);
```
Aşağıdaki örnek [Presentation](./) açıp kaydetmeyi gösterir. 
```cpp
// Presentation içinde desteklenen herhangi bir dosyayı yükleyin, ör. ppt, pptx, odp vb.
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"Sample.odp");

// Sunum dosyasını kaydet.
presentation->Save(u"OutputPresenation.pptx", SaveFormat::Pptx);
```

## İlgili

* Sınıf [IPresentation](../ipresentation/)
* Sınıf [IDOMObject](../idomobject/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)