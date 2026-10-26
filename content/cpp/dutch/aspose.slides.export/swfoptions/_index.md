---
title: SwfOptions
second_title: Aspose.Slides voor C++ API Referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Swf-indeling.
type: docs
weight: 742
url: /nl/aspose.slides.export/swfoptions/
---
## SwfOptions klasse

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in Swf-indeling.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-type-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-achtige zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-achtige zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **bool** [get_Compressed](./get_compressed/)() override | Specificeert of het gegenereerde SWF-document al dan niet moet worden gecomprimeerd. Standaard is **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Retourneert het lettertype dat wordt gebruikt als het bronlettertype niet wordt gevonden. Leest [System::String](../../system/string/). |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | Schakel contextmenu in/uit. Standaard is true. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Retourneert de visuele stijl van de kleurverloop. Lees [GradientStyle](../../aspose.slides/gradientstyle/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Specificeert de kwaliteit van JPEG-afbeeldingen. Standaard is 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | Afbeelding die als logo wordt weergegeven in de rechterbovenhoek van de viewer. De afbeelding moet een PNG van 32x64 pixels zijn, anders kan het logo onjuist worden weergegeven. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | Haalt het volledige hyperlink-adres voor een logo op. Heeft alleen effect als een [set_LogoImageBytes()](./set_logoimagebytes/) is opgegeven. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Stelt een callback-object voor om voortgangsupdates op te slaan in procenten. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | Toon/verberg onderste paneel. Kan worden overschreven in flashvars. Standaard is true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | Toon/verberg volledigschermknop. Kan worden overschreven in flashvars. Standaard is true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | Toon/verberg linkerpaneel. Kan worden overschreven in flashvars. Standaard is true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | Specificeert of er een rand rond pagina's moet worden getoond. Standaard is true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | Toon/verberg paginastepper. Kan worden overschreven in flashvars. Standaard is true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | Toon/verberg zoeksectie. Kan worden overschreven in flashvars. Standaard is true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | Toon/verberg het volledige bovenpaneel. Kan worden overschreven in flashvars. Standaard is true. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Specificeert of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. Lees **bool**. De standaardwaarde is **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Haalt de modus op waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../islideslayoutoptions/). Deze eigenschap ondersteunt het toewijzen van objecten van type [HandoutLayoutingOptions](../handoutlayoutingoptions/) niet. |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | Start met geopend linkerpaneel. Kan worden overschreven in flashvars. Standaard is false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | Specificeert of het gegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet. Standaard is **true**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lees [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashberekening van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analoge van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | Specificeert of het gegenereerde SWF-document al dan niet moet worden gecomprimeerd. Standaard is **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Stelt het te gebruiken lettertype in als het bronlettertype niet wordt gevonden. Schrijft [System::String](../../system/string/). |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | Schakel contextmenu in/uit. Standaard is true. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Stelt de visuele stijl van het kleurverloop in. Schrijf [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Specificeert de kwaliteit van JPEG-afbeeldingen. Standaard is 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Afbeelding die als logo wordt weergegeven in de rechterbovenhoek van de viewer. De afbeelding moet een PNG van 32x64 pixels zijn, anders kan het logo onjuist worden weergegeven. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | Stelt het volledige hyperlink-adres voor een logo in. Heeft alleen effect als een [set_LogoImageBytes()](./set_logoimagebytes/) is opgegeven. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Stelt een callback-object voor om voortgangsupdates op te slaan in procenten. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | Toon/verberg onderste paneel. Kan worden overschreven in flashvars. Standaard is true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | Toon/verberg volledigschermknop. Kan worden overschreven in flashvars. Standaard is true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | Toon/verberg linkerpaneel. Kan worden overschreven in flashvars. Standaard is true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | Specificeert of er een rand rond pagina's moet worden getoond. Standaard is true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | Toon/verberg paginastepper. Kan worden overschreven in flashvars. Standaard is true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | Toon/verberg zoeksectie. Kan worden overschreven in flashvars. Standaard is true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | Toon/verberg het volledige bovenpaneel. Kan worden overschreven in flashvars. Standaard is true. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Specificeert of hyperlinks met JavaScript-aanroepen moeten worden overgeslagen bij het opslaan van de presentatie. Schrijf **bool**. De standaardwaarde is **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../islideslayoutoptions/). Deze eigenschap ondersteunt het toewijzen van objecten van type [HandoutLayoutingOptions](../handoutlayoutingoptions/) niet. |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | Start met geopend linkerpaneel. Kan worden overschreven in flashvars. Standaard is false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | Specificeert of het gegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet. Standaard is **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Retourneert of stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Schrijf [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Zou niet direct moeten worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Zou niet direct moeten worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [SwfOptions](./swfoptions/)() | Standaardconstructor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het lock()-statement van C# voor ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Zou niet direct moeten worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Zou niet direct moeten worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijmaakt alle interne gegevensstructuren. |

## Opmerkingen

Het volgende voorbeeld toont hoe u PowerPoint naar SWF Flash kunt converteren. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## Zie ook

* Klasse [SaveOptions](../saveoptions/)
* Klasse [ISwfOptions](../iswfoptions/)
* Naamruimte [Aspose::Slides::Export](../)
* Bibliotheek [Aspose.Slides](../../)