---
title: ISVGOptions
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt een SVG-optie.
type: docs
weight: 404
url: /nl/aspose.slides.export/isvgoptions/
---
## ISVGOptions klasse

Vertegenwoordigt een SVG-optie.

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met de C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Retourneert het lettertype dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Leest [System::String](../../system/string/). |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | Een booleaanse vlag geeft aan of de bijgesneden delen deel blijven uitmaken van het document. Indien true worden de bijgesneden delen verwijderd, indien false worden ze geserialiseerd in het document (wat mogelijk tot een groter bestand kan leiden). Lees **bool**. |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | Bepaalt of 3D-tekst is uitgeschakeld in SVG. Lees **bool**. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | Haalt een waarde op die aangeeft of tekst wordt gerenderd zonder ligaturen. Wanneer ingesteld op **true**, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap **false**. |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | Schakelt het splitsen van FromCornerX- en FromCenter-gradienten uit. Lees **bool**. |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | SVG 1.1 mist de mogelijkheid om insluitsels voor markers te definiëren. [Aspose.Slides](../../aspose.slides/) SVG-schrijfmotor heeft een oplossing voor dat probleem: het cropt het uiteinde van de lijn met een pijl, zodat de lijn niet overlapt met markers. Deze optie schakelt dergelijk gedrag uit. Lees **bool**. |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | Bepaalt een manier waarop extern geladen lettertypen worden behandeld. Lees [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Retourneert de visuele stijl van de gradient. Lees [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Biedt opties die het uiterlijk van [Ink](../../aspose.slides.ink/)-objecten in het geëxporteerde document beheersen. Alleen-lezen [IInkOptions](../iinkoptions/) |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Bepaalt de JPEG-coderingskwaliteit. Lees **int32_t**. |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | Retourneert de ondergrens voor resolutie bij metafile rasterisatie. Lees **int32_t**. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | Vertegenwoordigt het compressieniveau van de afbeeldingen. Lees [PicturesCompression](../picturescompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Vertegenwoordigt een callback-object voor het opslaan van voortgangsupdates in procenten. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | Retourneert en stelt een callback-interface in die de gebruiker in staat stelt de vormconversie te controleren. Lees [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Specificeert of hyperlinks met JavaScript-aanroepen overgeslagen moeten worden bij het opslaan van de presentatie. Lees **bool**. De standaardwaarde is **false**. |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | Bepaalt of de opgegeven rotatie van de vorm moet worden uitgevoerd bij het renderen of niet. Lees **bool**. Standaardwaarde is true. |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | Bepaalt of het tekstframe al dan niet wordt opgenomen in een rendergebied. Lees **bool**. Standaardwaarde is false. |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | Bepaalt of de tekst op een dia wordt opgeslagen als grafisch element. Lees **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Retourneert een object dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lees [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Schakelt hashing van aangepaste objecten in. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-sentinelobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Schakelt het klonen van aangepaste types in. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, alleen een nieuw object initialiseren en copy-construeren van subklassen mogelijk maken. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, alleen een nieuw object initialiseren en copy-construeren van subklassen mogelijk maken. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if\<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>\::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>\::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object referentieel met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Stelt het lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Schrijft [System::String](../../system/string/). |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | Een booleaanse vlag geeft aan of de bijgesneden delen deel blijven uitmaken van het document. Indien true worden de bijgesneden delen verwijderd, indien false worden ze geserialiseerd in het document (wat mogelijk tot een groter bestand kan leiden). Schrijf **bool**. |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | Bepaalt of 3D-tekst is uitgeschakeld in SVG. Schrijf **bool**. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | Stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. Wanneer ingesteld op **true**, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap **false**. |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | Schakelt het splitsen van FromCornerX- en FromCenter-gradienten uit. Schrijf **bool**. |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | SVG 1.1 mist de mogelijkheid om insluitsels voor markers te definiëren. [Aspose.Slides](../../aspose.slides/) SVG-schrijfmotor heeft een oplossing voor dat probleem: het cropt het uiteinde van de lijn met een pijl, zodat de lijn niet overlapt met markers. Deze optie schakelt dergelijk gedrag uit. Schrijf **bool**. |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | Bepaalt een manier waarop extern geladen lettertypen worden behandeld. Schrijf [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Stelt de visuele stijl van de gradient in. Schrijf [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Bepaalt de JPEG-coderingskwaliteit. Schrijf **int32_t**. |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | Stelt de ondergrens voor resolutie bij metafile rasterisatie in. Schrijf **int32_t**. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | Vertegenwoordigt het compressieniveau van de afbeeldingen. Schrijf [PicturesCompression](../picturescompression/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Vertegenwoordigt een callback-object voor het opslaan van voortgangsupdates in procenten. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | Retourneert en stelt een callback-interface in die de gebruiker in staat stelt de vormconversie te controleren. Schrijf [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Specificeert of hyperlinks met JavaScript-aanroepen overgeslagen moeten worden bij het opslaan van de presentatie. Schrijf **bool**. De standaardwaarde is **false**. |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | Bepaalt of de opgegeven rotatie van de vorm moet worden uitgevoerd bij het renderen of niet. Schrijf **bool**. Standaardwaarde is true. |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | Bepaalt of het tekstframe al dan niet wordt opgenomen in een rendergebied. Schrijf **bool**. Standaardwaarde is false. |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | Bepaalt of de tekst op een dia wordt opgeslagen als grafisch element. Schrijf **bool**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Schrijf [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n-de sjabloonargument in als een weak-pointer (in plaats van shared). Maakt het mogelijk om pointers in containers te schakelen naar weak-modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Schakelt het converteren van aangepaste objecten naar string in. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-sentinelobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de weak-referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de weak-referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [ISaveOptions](../isaveoptions/)
* Naamruimte [Aspose::Slides::Export](../)
* Bibliotheek [Aspose.Slides](../../)