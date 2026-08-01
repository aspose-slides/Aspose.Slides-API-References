---
title: IPdfOptions
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-formaat.
type: docs
weight: 274
url: /nl/aspose.slides.export/ipdfoptions/
---
## IPdfOptions klasse

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Pdf-formaat.

```cpp
class IPdfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommagelijken vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommagelijken vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() | Bevat een set vlaggen die aangeven welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. Zie [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() | Retourneert een array van door de gebruiker gedefinieerde namen van lettertypefamilies die [Aspose.Slides](../../aspose.slides/) als algemeen moet beschouwen. Lees [System::String](../../system/string/)[]. |
| virtual **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() | Past de gespecificeerde transparante kleur toe op een afbeelding als **true**. |
| virtual **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() | Duidt aan of de meest effectieve compressie (in plaats van de standaard) voor elke afbeelding automatisch moet worden geselecteerd. Als dit is ingesteld op **bool**.true, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere grootte van het resulterende PDF-document. |
| virtual [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() | Gewenst conformiteitsniveau voor gegenereerd PDF-document. Lees [PdfCompliance](../pdfcompliance/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Retourneert het lettertype dat wordt gebruikt als het bronlettertype niet wordt gevonden. Lees [System::String](../../system/string/). |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | Waar om een zwart kader rond elke dia te tekenen. Lees **bool**. |
| virtual **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() | Bepaalt of alle tekens van het lettertype moeten worden ingebed of alleen een gebruikte subset. Lees **bool**. |
| virtual **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() | Waar om TrueType-lettertypen in te sluiten voor ASCII-tekens 32-127. [Fonts](../../aspose.slides/fonts/) voor tekencodes groter dan 127 worden altijd ingesloten. Lees **bool**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Retourneert de visuele stijl van de gradiënt. Lees [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() | Haalt de transparante kleur van de afbeelding op. |
| virtual **bool** [get_IncludeOleData](./get_includeoledata/)() | Waar om alle OLE-gegevens uit de presentatie te converteren naar ingesloten bestanden in het resulterende PDF-document. Lees **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Biedt opties die het uiterlijk van [Ink](../../aspose.slides.ink/)-objecten in het geëxporteerde document regelen. Alleen-lezen [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | Retourneert een waarde die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. Lees **uint8_t**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | Instellen van gebruikerswachtwoord om het PDF-document te beveiligen. Lees [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Stelt een callback-object voor om voortgangsupdates op te slaan in percentage. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() | Geeft aan of tekst moet worden gerasterd als een bitmap en opgeslagen in PDF wanneer het lettertype geen vetstijlen ondersteunt. Deze aanpak kan de kwaliteit van tekst in het resulterende PDF-document verbeteren voor bepaalde lettertypen. Lees **bool**. |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | Waar om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. Lees **bool**. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is **false**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Specificeert of hyperlinks met JavaScript-oproepen moeten worden overgeslagen bij het opslaan van de presentatie. Lees **bool**. De standaardwaarde is **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Haalt de modus op waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual **float** [get_SufficientResolution](./get_sufficientresolution/)() | Retourneert een waarde die de resolutie van afbeeldingen in het PDF-document bepaalt. |
| virtual [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() | Specificeert het compressietype dat moet worden gebruikt voor alle tekstuele inhoud in het document. Lees [PdfTextCompression](../pdftextcompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Retourneert een object dat waarschuwingen ontvangt en beslist of het laadproces doorgaat of wordt afgebroken. Lees [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maak object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) | Bevat een set vlaggen die aangeven welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten. Zie [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | Stelt een array in van door de gebruiker gedefinieerde namen van lettertypefamilies die [Aspose.Slides](../../aspose.slides/) als algemeen moet beschouwen. Schrijf [System::String](../../system/string/)[]. |
| virtual void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) | Past de gespecificeerde transparante kleur toe op een afbeelding als **true**. |
| virtual void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) | Duidt aan of de meest effectieve compressie (in plaats van de standaard) voor elke afbeelding automatisch moet worden geselecteerd. Als dit is ingesteld op **bool**.true, wordt voor elke afbeelding in de presentatie het meest geschikte compressie-algoritme gekozen, wat leidt tot een kleinere grootte van het resulterende PDF-document. |
| virtual void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) | Gewenst conformiteitsniveau voor gegenereerd PDF-document. Schrijf [PdfCompliance](../pdfcompliance/). |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Stelt het lettertype in dat wordt gebruikt als het bronlettertype niet wordt gevonden. Schrijft [System::String](../../system/string/). |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | Waar om een zwart kader rond elke dia te tekenen. Schrijf **bool**. |
| virtual void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) | Bepaalt of alle tekens van het lettertype moeten worden ingebed of alleen een gebruikte subset. Schrijf **bool**. |
| virtual void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) | Waar om TrueType-lettertypen in te sluiten voor ASCII-tekens 32-127. [Fonts](../../aspose.slides/fonts/) voor tekencodes groter dan 127 worden altijd ingesloten. Schrijf **bool**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Stelt de visuele stijl van de gradiënt in. Schrijf [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) | Stelt de transparante kleur van de afbeelding in. |
| virtual void [set_IncludeOleData](./set_includeoledata/)(**bool**) | Waar om alle OLE-gegevens uit de presentatie te converteren naar ingesloten bestanden in het resulterende PDF-document. Schrijf **bool**. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | Stelt een waarde in die de kwaliteit van de JPEG-afbeeldingen in het PDF-document bepaalt. Schrijf **uint8_t**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | Instellen van gebruikerswachtwoord om het PDF-document te beveiligen. Schrijf [System::String](../../system/string/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Stelt een callback-object voor om voortgangsupdates op te slaan in percentage. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) | Geeft aan of tekst moet worden gerasterd als een bitmap en opgeslagen in PDF wanneer het lettertype geen vetstijlen ondersteunt. Deze aanpak kan de kwaliteit van tekst in het resulterende PDF-document verbeteren voor bepaalde lettertypen. Schrijf **bool**. |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | Waar om alle metafiles die in een presentatie worden gebruikt te converteren naar PNG-afbeeldingen. Schrijf **bool**. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is **false**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Specificeert of hyperlinks met JavaScript-oproepen moeten worden overgeslagen bij het opslaan van de presentatie. Schrijf **bool**. De standaardwaarde is **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_SufficientResolution](./set_sufficientresolution/)(**float**) | Stelt een waarde in die de resolutie van afbeeldingen in het PDF-document bepaalt. |
| virtual void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) | Specificeert het compressietype dat moet worden gebruikt voor alle tekstuele inhoud in het document. Schrijf [PdfTextCompression](../pdftextcompression/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces doorgaat of wordt afgebroken. Schrijf [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeelde). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [ISaveOptions](../isaveoptions/)
* Naamruimte [Aspose::Slides::Export](../)
* Bibliotheek [Aspose.Slides](../../)