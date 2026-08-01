---
title: Presentation
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt een Microsoft PowerPoint-presentatie.
type: docs
weight: 4837
url: /nl/aspose.slides/presentation/
---
## Presentation-klasse

Stelt een Microsoft PowerPoint-presentatie voor.

```cpp
class Presentation : public Aspose::Slides::IPresentation,
                     public Aspose::Slides::IDOMObject
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Dispose](./dispose/)() override | Geeft alle bronnen vrij die door dit [Presentation](./)-object worden gebruikt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt value-type-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICustomXmlPart](../icustomxmlpart/)\>\> [get_AllCustomXmlParts](./get_allcustomxmlparts/)() override | Retourneert alle aangepaste gegevensonderdelen in de presentatie. Alleen-lezen [ICustomXmlPart](../icustomxmlpart/)[]. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Audio](./get_audio/)(**int32_t**) override | Retourneert een ingebed audiobestand in de presentatie op de opgegeven index. Alleen-lezen [Aspose::Slides::IAudio](../iaudio/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioCollection](../iaudiocollection/)\> [get_Audios](./get_audios/)() override | Retourneert de collectie van alle ingebedde audiobestanden in de presentatie. Alleen-lezen [IAudioCollection](../iaudiocollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_CommentAuthor](./get_commentauthor/)(**int32_t**) override | Retourneert de commentaar-auteur op de opgegeven index. Alleen-lezen [Aspose::Slides::ICommentAuthor](../icommentauthor/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthorCollection](../icommentauthorcollection/)\> [get_CommentAuthors](./get_commentauthors/)() override | Retourneert de collectie van commentaar-auteurs. Alleen-lezen [ICommentAuthorCollection](../icommentauthorcollection/). |
| [System::DateTime](../../system/datetime/) [get_CurrentDateTime](./get_currentdatetime/)() override | Retourneert datum en tijd die de inhoud van datetime-velden zullen vervangen. Tijd van de creatie van dit [Presentation](./)-object standaard. Alleen-lezen [System::DateTime](../../system/datetime/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | Retourneert de aangepaste gegevens van de presentatie. Alleen-lezen [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_DefaultTextStyle](./get_defaulttextstyle/)() override | Retourneert de standaard tekstopmaak voor vormen. Alleen-lezen [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignature](../idigitalsignature/)\> [get_DigitalSignature](./get_digitalsignature/)(**int32_t**) override | Retourneert de digitale handtekening die wordt gebruikt om de presentatie te ondertekenen op de opgegeven index. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignatureCollection](../idigitalsignaturecollection/)\> [get_DigitalSignatures](./get_digitalsignatures/)() override | Retourneert de collectie van handtekeningen die worden gebruikt om de presentatie te ondertekenen. Alleen-lezen [IDigitalSignatureCollection](../idigitalsignaturecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [get_DocumentProperties](./get_documentproperties/)() override | Retourneert [DocumentProperties](../documentproperties/)-object dat standaard- en aangepaste documenteigenschappen bevat. Alleen-lezen [IDocumentProperties](../idocumentproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_DocumentProperty](./get_documentproperty/)([System::String](../../system/string/)) override | Retourneert aangepaste eigenschap gedefinieerd door naam. |
| **int32_t** [get_FirstSlideNumber](./get_firstslidenumber/)() override | Stelt het eerste dia-nummer van de presentatie voor |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontsManager](../ifontsmanager/)\> [get_FontsManager](./get_fontsmanager/)() override | Retourneert de lettertypebeheerder. Alleen-lezen [IFontsManager](../ifontsmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | Retourneert de werkelijke HeaderFooter-beheerder. Alleen-lezen [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | Biedt gemakkelijke toegang tot alle hyperlinks in alle presentatiedia's (niet in master-, lay-out- of notitiesdia's). Alleen-lezen [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_Image](./get_image/)(**int32_t**) override | Retourneert afbeelding in de presentatie op de opgegeven index. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImageCollection](../iimagecollection/)\> [get_Images](./get_images/)() override | Retourneert de collectie van alle afbeeldingen in de presentatie. Alleen-lezen [IImageCollection](../iimagecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) override | Retourneert de lay-outdia op index. Alleen-lezen [Aspose::Slides::ILayoutSlide](../ilayoutslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() override | Retourneert een lijst van alle lay-outdia's die in de presentatie zijn gedefinieerd. Alleen-lezen [IGlobalLayoutSlideCollection](../igloballayoutslidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [get_Master](./get_master/)(**int32_t**) override | Retourneert een masterdia gedefinieerd in de presentatie op de opgegeven index. Alleen-lezen [Aspose::Slides::IMasterSlide](../imasterslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterHandoutSlideManager](../imasterhandoutslidemanager/)\> [get_MasterHandoutSlideManager](./get_masterhandoutslidemanager/)() override | Retourneert de hand-out master-beheerder. Alleen-lezen [IMasterHandoutSlideManager](../imasterhandoutslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterNotesSlideManager](../imasternotesslidemanager/)\> [get_MasterNotesSlideManager](./get_masternotesslidemanager/)() override | Retourneert de notitie master-beheerder. Alleen-lezen [IMasterNotesSlideManager](../imasternotesslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideCollection](../imasterslidecollection/)\> [get_Masters](./get_masters/)() override | Retourneert een lijst van alle masterdia's die in de presentatie zijn gedefinieerd. Alleen-lezen [IMasterSlideCollection](../imasterslidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/)\> [get_MasterTheme](./get_mastertheme/)() override | Retourneert masterthema. Alleen-lezen [Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSize](../inotessize/)\> [get_NotesSize](./get_notessize/)() override | Retourneert notitie-dia-grootteobject. Alleen-lezen [INotesSize](../inotessize/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProtectionManager](../iprotectionmanager/)\> [get_ProtectionManager](./get_protectionmanager/)() override | Verkrijgt beheerder van de permissies voor deze presentatie. Alleen-lezen [IProtectionManager](../iprotectionmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_Section](./get_section/)(**int32_t**) override | Retourneert een dia-sectie gedefinieerd in de presentatie op de opgegeven index. Alleen-lezen [Aspose::Slides::ISection](../isection/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionCollection](../isectioncollection/)\> [get_Sections](./get_sections/)() override | Retourneert een lijst van alle dia-secties die in de presentatie zijn gedefinieerd. Alleen-lezen [ISectionCollection](../isectioncollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabelCollection](../isensitivitylabelcollection/)\> [get_SensitivityLabels](./get_sensitivitylabels/)() override | Retourneert de collectie van sensitiviteitslabels toegepast op het presentatiedocument. Alleen-lezen [ISensitivityLabelCollection](../isensitivitylabelcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)(**int32_t**) override | Retourneert een dia gedefinieerd in de presentatie op de opgegeven index. Alleen-lezen [Aspose::Slides::ISlide](../islide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideCollection](../islidecollection/)\> [get_Slides](./get_slides/)() override | Retourneert een lijst van alle dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [ISlideCollection](../islidecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowSettings](../slideshowsettings/)\> [get_SlideShowSettings](./get_slideshowsettings/)() const | Retourneert de diavoorstellinginstellingen voor de presentatie. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideSize](../islidesize/)\> [get_SlideSize](./get_slidesize/)() override | Retourneert dia-grootteobject. Alleen-lezen [ISlideSize](../islidesize/). |
| [Aspose::Slides::SourceFormat](../sourceformat/) [get_SourceFormat](./get_sourceformat/)() override | Retourneert informatie over uit welk formaat de presentatie is geladen. Alleen-lezen [SourceFormat](../sourceformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\> [get_VbaProject](./get_vbaproject/)() override | Verkrijgt VBA-project met presentatiemacro's. Alleen-lezen [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_Video](./get_video/)(**int32_t**) override | Retourneert een ingebed videobestand in de presentatie op de opgegeven index. Alleen-lezen [Aspose::Slides::IVideo](../ivideo/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoCollection](../ivideocollection/)\> [get_Videos](./get_videos/)() override | Retourneert de collectie van alle ingebedde videobestanden in de presentatie. Alleen-lezen [IVideoCollection](../ivideocollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IViewProperties](../iviewproperties/)\> [get_ViewProperties](./get_viewproperties/)() override | Verkrijgt weergave-eigenschappen van de presentatie. Alleen-lezen [IViewProperties](../iviewproperties/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Verkrijgt referentieteller-datastructuur geassocieerd met het object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) override | Retourneert Image-objecten voor alle dia's van een presentatie. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) override | Retourneert Thumbnail-Image-objecten voor gespecificeerde dia's van een presentatie. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) override | Retourneert Thumbnail-Image-objecten voor alle dia's van een presentatie met aangepaste schaal. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, **float**, **float**) override | Retourneert Thumbnail-Image-objecten voor gespecificeerde dia's van een presentatie met aangepaste schaal. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) override | Retourneert Thumbnail-Image-objecten voor alle dia's van een presentatie met opgegeven grootte. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [System::Drawing::Size](../../system.drawing/size/)) override | Retourneert Thumbnail-Image-objecten voor gespecificeerde dia's van een presentatie met opgegeven grootte. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [GetSlideById](./getslidebyid/)(**uint32_t**) override | Retourneert een [Slide](../slide/), [MasterSlide](../masterslide/) of [LayoutSlide](../layoutslide/) op basis van Id. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Verkrijgt het actuele type van object. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| void [HighlightRegex](./highlightregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/)) override | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | Voegt runs met dezelfde opmaak samen in alle alinea's in alle toegestane vormen in alle dia's. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert eigenlijk niets, initialiseert gewoon een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert gewoon een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
|  [Presentation](./presentation/)() | Deze constructor maakt een nieuwe presentatie vanaf nul. De gecreëerde presentatie heeft één lege dia. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | Deze constructor maakt een nieuwe presentatie vanaf nul. De gecreëerde presentatie heeft één lege dia. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Deze constructor is de primaire methode om een bestaande [Presentation](./) te lezen. |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | Deze constructor is de primaire methode om een bestaande [Presentation](./) te lezen. |
|  [Presentation](./presentation/)([System::String](../../system/string/)) | Deze constructor krijgt een bronbestandspad waarvan de inhoud van de [Presentation](./) wordt gelezen. |
|  [Presentation](./presentation/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | Deze constructor krijgt een bronbestandspad waarvan de inhoud van de [Presentation](./) wordt gelezen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | Vergelijkt een value-type-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [ReplaceRegex](./replaceregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekenreeks. |
| void [ReplaceText](./replacetext/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat. |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat en met extra opties. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | Slaat alle dia's van een presentatie op in een stream met het opgegeven formaat en extra opties. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../aspose.slides.export.xaml/ixamloptions/)\>) override | Slaat alle dia's van een presentatie op in een reeks bestanden die XAML-markup vertegenwoordigen. |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat met behoud van paginanummer. |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat met behoud van paginanummer. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | Slaat opgegeven dia's van een presentatie op in een stream met het opgegeven formaat met behoud van paginanummer. |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | Slaat opgegeven dia's van een presentatie op in een stream met het opgegeven formaat met behoud van paginanummer. |
| void [set_CurrentDateTime](./set_currentdatetime/)([System::DateTime](../../system/datetime/)) override | Stelt datum en tijd in die de inhoud van datetime-velden zal vervangen. Tijd van de creatie van dit [Presentation](./)-object standaard. Schrijf [System::DateTime](../../system/datetime/). |
| void [set_DocumentProperty](./set_documentproperty/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Stel aangepaste eigenschap in gedefinieerd door naam. |
| void [set_FirstSlideNumber](./set_firstslidenumber/)(**int32_t**) override | Stelt het eerste dia-nummer van de presentatie voor |
| void [set_VbaProject](./set_vbaproject/)([System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\>) override | Stelt VBA-project in met presentatiemacro's. Schrijf [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Verkrijgt de huidige waarde van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het mogelijk om aangepaste objecten naar string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de Zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Opmerkingen

Het volgende voorbeeld toont hoe een PowerPoint [Presentation](./) te maken.

```cpp
// Maak een Presentation-object aan dat een presentatiebestand voorstelt
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

// Verkrijg de eerste dia
auto slide = presentation->get_Slides()->idx_get(0);
// Voeg een autovorm van type lijn toe
slide->get_Shapes()->AddAutoShape(ShapeType::Line, 50.0f, 150.0f, 300.0f, 0.0f);
// Sla het presentatiebestand op.
presentation->Save(u"NewPresentation_out.pptx", SaveFormat::Pptx);
```
Het volgende voorbeeld toont hoe [Presentation](./) te openen en op te slaan.

```cpp
// Laad elk ondersteund bestand in Presentation, bv. ppt, pptx, odp etc.
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"Sample.odp");

// Sla het presentatiebestand op.
presentation->Save(u"OutputPresenation.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [IPresentation](../ipresentation/)
* Klasse [IDOMObject](../idomobject/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)