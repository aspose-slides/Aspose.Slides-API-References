---
title: PdfOptions
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-formaat.
type: docs
weight: 573
url: /nl/aspose.slides.export/pdfoptions/
---
## PdfOptions klasse

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-formaat.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | Bevat een reeks vlaggen die aangeven welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. Zie [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | Retourneert een array met gebruikersgedefinieerde namen van lettertypefamilies die [Aspose.Slides](../../aspose.slides/) als gemeenschappelijk moet beschouwen. Lees [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | Past de opgegeven transparante kleur toe op een afbeelding als **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | Geeft aan of de meest effectieve compressie (in plaats van de standaardcompressie) voor elke afbeelding automatisch moet worden geselecteerd. Als ingesteld op **bool**.true, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere grootte van het resulterende PDF-document. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | Gewenst conformatieniveau voor het gegenereerde PDF-document. Lees [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Retourneert het lettertype dat wordt gebruikt als het bronlettertype niet wordt gevonden. Lees [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | Waar om een zwart kader rond elke dia te tekenen. Lees **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een subset. Lees **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | Bepaalt of [Aspose.Slides](../../aspose.slides/) algemene lettertypen zal insluiten voor ASCII (33..127 codebereik) tekst. [Fonts](../../aspose.slides/fonts/) voor tekencodes groter dan 127 worden altijd ingesloten. De lijst met algemene lettertypen omvat de 14 basislettertypen van PDF en extra door de gebruiker gespecificeerde lettertypen. Lees **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Retourneert de visuele stijl van de gradient. Lees [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Haalt de transparante kleur van de afbeelding op. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | Waar om alle OLE-gegevens uit de presentatie te converteren naar ingesloten bestanden in het resulterende PDF. Lees **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Biedt opties die de weergave van [Ink](../../aspose.slides.ink/) objecten in het geëxporteerde document beheren. Alleen-lezen [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Retourneert een waarde die de kwaliteit van de JPEG-afbeeldingen binnen het PDF-document bepaalt. Lees **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Instellen van gebruikerswachtwoord om het PDF-document te beveiligen. Lees [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Stelt een callback-object voor het opslaan van voortgangsupdates in procenten voor. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | Geeft aan of tekst gerasterd moet worden als een bitmap en opgeslagen in PDF wanneer het lettertype geen vette stijl ondersteunt. Deze aanpak kan de kwaliteit van tekst in het resulterende PDF voor bepaalde lettertypen verbeteren. Lees **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | Waar om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. Lees **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Geef aan of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Geef aan of hyperlinks met JavaScript-oproepen moeten worden overgeslagen bij het opslaan van de presentatie. Lees **bool**. De standaardwaarde is **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Haalt de modus op waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | Retourneert een waarde die de resolutie van afbeeldingen binnen het PDF-document bepaalt. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | Specificeert welke compressietype moet worden gebruikt voor alle tekstuele inhoud in het document. Lees [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lees [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van de C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement voor vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewaker-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, initieert gewoon een nieuw object en maakt het mogelijk kopieerconstructie van subklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initieert gewoon een nieuw object en maakt het mogelijk kopieerconstructie van subklassen. |
|  [PdfOptions](./pdfoptions/)() | Standaardconstructor. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Bevat een reeks vlaggen die aangeven welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. Zie [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Stelt een array in met gebruikersgedefinieerde namen van lettertypefamilies die [Aspose.Slides](../../aspose.slides/) als gemeenschappelijk moet beschouwen. Schrijf [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | Past de opgegeven transparante kleur toe op een afbeelding als **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Geeft aan of de meest effectieve compressie (in plaats van de standaardcompressie) voor elke afbeelding automatisch moet worden geselecteerd. Als ingesteld op **bool**.true, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere grootte van het resulterende PDF-document. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | Gewenst conformatieniveau voor het gegenereerde PDF-document. Schrijf [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Stelt het lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. Schrijft [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | Waar om een zwart kader rond elke dia te tekenen. Schrijf **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Bepaalt of alle tekens van het lettertype moeten worden ingesloten of alleen een subset. Schrijf **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | Bepaalt of [Aspose.Slides](../../aspose.slides/) algemene lettertypen zal insluiten voor ASCII (33..127 codebereik) tekst. [Fonts](../../aspose.slides/fonts/) voor tekencodes groter dan 127 worden altijd ingesloten. De lijst met algemene lettertypen omvat de 14 basislettertypen van PDF en extra door de gebruiker gespecificeerde lettertypen. Schrijf **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Stelt de visuele stijl van de gradient in. Schrijf [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Stelt de transparante kleur van de afbeelding in. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | Waar om alle OLE-gegevens uit de presentatie te converteren naar ingesloten bestanden in het resulterende PDF. Schrijf **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen binnen het PDF-document bepaalt. Schrijf **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Instellen van gebruikerswachtwoord om het PDF-document te beveiligen. Schrijf [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Stelt een callback-object voor het opslaan van voortgangsupdates in procenten voor. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | Geeft aan of tekst gerasterd moet worden als een bitmap en opgeslagen in PDF wanneer het lettertype geen vette stijl ondersteunt. Deze aanpak kan de kwaliteit van tekst in het resulterende PDF voor bepaalde lettertypen verbeteren. Schrijf **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | Waar om alle metafiles die in een presentatie worden gebruikt om te zetten naar PNG-afbeeldingen. Schrijf **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Geef aan of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Geef aan of hyperlinks met JavaScript-oproepen moeten worden overgeslagen bij het opslaan van de presentatie. Schrijf **bool**. De standaardwaarde is **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | Stelt een waarde in die de resolutie van afbeeldingen binnen het PDF-document bepaalt. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | Specificeert het compressietype dat moet worden gebruikt voor alle tekstuele inhoud in het document. Schrijf [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Schrijf [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'te sjabloonargument in als een zwakke pointer (in plaats van een gedeelde). Staat toe om pointers in containers te schakelen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het mogelijk aangepaste objecten naar string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement voor ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewaker-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Opmerkingen



Het volgende voorbeeld toont hoe PowerPoint te converteren naar PDF met aangepaste opties. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instantieert de PdfOptions-klasse
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Stelt de JPEG-kwaliteit in
pdfOptions->set_JpegQuality(90);
// Stelt het gedrag voor metafiles in
pdfOptions->set_SaveMetafilesAsPng(true);
// Stelt het tekstcompressieniveau in
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// Definieert de PDF-standaard
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// Slaat de presentatie op als PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 Het volgende voorbeeld toont hoe PowerPoint te converteren naar PDF met verborgen dia's. 
```cpp
// Instantieert een Presentation-klasse die een PowerPoint-bestand vertegenwoordigt
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instantieert de PdfOptions-klasse
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Voegt verborgen dia's toe
pdfOptions->set_ShowHiddenSlides(true);
// Slaat de presentatie op als PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 Het volgende voorbeeld toont hoe PowerPoint te converteren naar een wachtwoordbeveiligde PDF. 
```cpp
// Instantieert een Presentation-object dat een PowerPoint-bestand vertegenwoordigt
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// Stelt PDF-wachtwoord en toegangsrechten in
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// Slaat de presentatie op als PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 Het volgende voorbeeld toont hoe PowerPoint te converteren naar PDF met notities. 
```cpp
// Instantieer een Presentation-object dat een presentatiebestand vertegenwoordigt
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## Zie ook

* Klasse [SaveOptions](../saveoptions/)
* Klasse [IPdfOptions](../ipdfoptions/)
* Namespace [Aspose::Slides::Export](../)
* Bibliotheek [Aspose.Slides](../../)