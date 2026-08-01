---
title: TiffOptions
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in TIFF-indeling.
type: docs
weight: 768
url: /nl/aspose.slides.export/tiffoptions/
---
## TiffOptions klasse

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in TIFF-indeling.

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | Specificeert het algoritme voor het converteren van een kleurafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) is ingesteld op [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) of [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/). Lezen [BlackWhiteConversionMode](../blackwhiteconversionmode/). Standaard is [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | Specificeert het compressietype. Lezen [TiffCompressionTypes](../tiffcompressiontypes/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Retourneert het lettertype dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Leest [System::String](../../system/string/). |
| **uint32_t** [get_DpiX](./get_dpix/)() override | Specificeert de horizontale resolutie in punten per inch. Lezen **uint32_t**. |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | Specificeert de verticale resolutie in punten per inch. Lezen **uint32_t**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Retourneert de visuele stijl van de gradiënt. Lezen [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | Specificeert de grootte van een gegenereerde TIFF-afbeelding. Standaardwaarde is 0x0, wat betekent dat gegenereerde afbeeldingsgroottes worden berekend op basis van de grootte van de presentatieslides. Lezen [System::Drawing::Size](../../system.drawing/size/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Biedt opties die het uiterlijk van [Ink](../../aspose.slides.ink/)-objecten in het geëxporteerde document regelen. Alleen-lezen [IInkOptions](../iinkoptions/) |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | Specificeert het pixelformaat voor de gegenereerde afbeeldingen. Lezen [ImagePixelFormat](../imagepixelformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Stelt een callback-object voor voor het opslaan van voortgangsupdates in procenten. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Specificeert of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. Lezen **bool**. De standaardwaarde is **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Haalt de modus op waarin dia's worden geplaatst op de pagina bij het exporteren van een presentatie [ISlidesLayoutOptions](../islideslayoutoptions/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Schakelt hashing van aangepaste objecten in. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analog van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement locken. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waarnemingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Schakelt klonen van aangepaste typen in. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentiewaarde-type-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | Specificeert het algoritme voor het converteren van een kleurafbeelding naar een zwart-wit afbeelding. Deze optie wordt alleen toegepast als [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) is ingesteld op [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) of [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/). Schrijven [BlackWhiteConversionMode](../blackwhiteconversionmode/). Standaard is [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | Specificeert het compressietype. Schrijven [TiffCompressionTypes](../tiffcompressiontypes/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Stelt het lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Schrijft [System::String](../../system/string/). |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | Specificeert de horizontale resolutie in punten per inch. Schrijven **uint32_t**. |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | Specificeert de verticale resolutie in punten per inch. Schrijven **uint32_t**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Stelt de visuele stijl van de gradiënt in. Schrijft [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | Specificeert de grootte van een gegenereerde TIFF-afbeelding. Standaardwaarde is 0x0, wat betekent dat gegenereerde afbeeldingsgroottes worden berekend op basis van de grootte van de presentatieslides. Schrijven [System::Drawing::Size](../../system.drawing/size/). |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | Specificeert het pixelformaat voor de gegenereerde afbeeldingen. Schrijven [ImagePixelFormat](../imagepixelformat/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Stelt een callback-object voor voor het opslaan van voortgangsupdates in procenten. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Specificeert of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. Schrijven **bool**. De standaardwaarde is **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Stelt de modus in waarin dia's worden geplaatst op de pagina bij het exporteren van een presentatie [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Schrijven [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel n'th-sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [TiffOptions](./tiffoptions/)() | Standaardconstructor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/)-methode. Schakelt het omzetten van aangepaste objecten naar string in. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendelen. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waarnemingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Bevrijdt alle interne gegevensstructuren. |

## Opmerkingen

Het volgende voorbeeld toont hoe PowerPoint te converteren naar TIFF met standaardgrootte. 
```cpp
// Instantieer een Presentation-object dat een presentatiebestand vertegenwoordigt
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// De presentatie opslaan als TIFF-document
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```
 Het volgende voorbeeld toont hoe PowerPoint te converteren naar TIFF met aangepaste grootte. 
```cpp
// Instantieer een Presentation-object dat een Presentation-bestand vertegenwoordigt
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// Instantieer de TiffOptions-klasse
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// Instellen van compressietype
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// Compressietypen
// Default - Geeft het standaardcompressieschema (LZW) aan.
// None - Geeft aan geen compressie.
// CCITT3
// CCITT4
// LZW
// RLE
// Diepte is afhankelijk van het compressietype en kan niet handmatig worden ingesteld.
// Resolutie-eenheid is altijd gelijk aan "2" (punten per inch)
// Instellen van beeld-DPI
opts->set_DpiX(200);
opts->set_DpiY(100);
// Stel afbeeldingsgrootte in
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// Sla de presentatie op als TIFF met de opgegeven afbeeldingsgrootte
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```
 Het volgende voorbeeld toont hoe PowerPoint te converteren naar TIFF met aangepast afbeelding-pixelformaat. 
```cpp
// Instantieer een Presentation-object dat een Presentation-bestand vertegenwoordigt
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// Sla de presentatie op als TIFF met de opgegeven afbeeldingsgrootte
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## Zie ook

* Klasse [SaveOptions](../saveoptions/)
* Klasse [ITiffOptions](../itiffoptions/)
* Naamruimte [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)