---
title: ISwfOptions
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt opties die bepalen hoe een presentatie wordt opgeslagen in SWF-formaat.
type: docs
weight: 469
url: /nl/aspose.slides.export/iswfoptions/
---
## ISwfOptions klasse

Biedt opties die bepalen hoe een presentatie wordt opgeslagen in SWF-indeling.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagelijken vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagelijken vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **bool** [get_Compressed](./get_compressed/)() | Specificeert of het gegenereerde SWF-document gecomprimeerd moet worden of niet. Standaard is **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Retourneert het lettertype dat wordt gebruikt als het brontype niet wordt gevonden. Leest [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | Schakel contextmenu in of uit. Standaard is true. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Retourneert de visuele stijl van de verloop. Lees [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Specificeert de kwaliteit van JPEG-afbeeldingen.  

 Standaard is 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Afbeelding die als logo in de rechterbovenhoek van de viewer wordt weergegeven.  

 De afbeelding moet een PNG van 32x64 pixels zijn, anders kan het logo onjuist worden weergegeven. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Haalt het volledige hyperlinkadres voor een logo op. Heeft alleen effect als een [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) is opgegeven. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Stelt een callback-object voor het opslaan van voortgangsupdates in procenten voor. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Toon/verberg onderpaneel. Kan worden overschreven in flashvars. Standaard is true. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Toon/verberg volledige-schermknop. Kan worden overschreven in flashvars. Standaard is true. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Toon/verberg linker paneel. Kan worden overschreven in flashvars. Standaard is true. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Specificeert of een rand rond pagina's moet worden getoond. Standaard is true. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Toon/verberg paginastepper. Kan worden overschreven in flashvars. Standaard is true. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Toon/verberg zoeksectie. Kan worden overschreven in flashvars. Standaard is true. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Toon/verberg het volledige bovenpaneel. Kan worden overschreven in flashvars. Standaard is true. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Specificeert of hyperlinks met JavaScript-aanroepen overgeslagen moeten worden bij het opslaan van de presentatie. Lees **bool**. De standaardwaarde is **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Haalt de modus op waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../islideslayoutoptions/). Deze eigenschap ondersteunt het toewijzen van objecten van type **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** niet. |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Start met geopend linker paneel. Kan worden overschreven in flashvars. Standaard is false. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Specificeert of het gegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet. Standaard is **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Retourneert een object dat waarschuwingen ontvangt en beslist of het laadproces doorgaat of wordt afgebroken. Lees [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling van C# lock()-statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, initialiseert enkel een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr via referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Specificeert of het gegenereerde SWF-document gecomprimeerd moet worden of niet. Standaard is **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Stelt het lettertype in dat wordt gebruikt als het brontype niet wordt gevonden. Schrijft [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | Schakel contextmenu in of uit. Standaard is true. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Stelt de visuele stijl van de verloop in. Schrijf [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Specificeert de kwaliteit van JPEG-afbeeldingen.  

 Standaard is 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Afbeelding die als logo in de rechterbovenhoek van de viewer wordt weergegeven.  

 De afbeelding moet een PNG van 32x64 pixels zijn, anders kan het logo onjuist worden weergegeven. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Stelt het volledige hyperlinkadres voor een logo in. Heeft alleen effect als een [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) is opgegeven. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Stelt een callback-object voor het opslaan van voortgangsupdates in procenten voor. Zie [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Toon/verberg onderpaneel. Kan worden overschreven in flashvars. Standaard is true. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Toon/verberg volledige-schermknop. Kan worden overschreven in flashvars. Standaard is true. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Specificeert of het gegenereerde document verborgen dia's moet bevatten of niet. Standaard is **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Toon/verberg linker paneel. Kan worden overschreven in flashvars. Standaard is true. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Specificeert of een rand rond pagina's moet worden getoond. Standaard is true. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Toon/verberg paginastepper. Kan worden overschreven in flashvars. Standaard is true. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Toon/verberg zoeksectie. Kan worden overschreven in flashvars. Standaard is true. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Toon/verberg het volledige bovenpaneel. Kan worden overschreven in flashvars. Standaard is true. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Specificeert of hyperlinks met JavaScript-aanroepen overgeslagen moeten worden bij het opslaan van de presentatie. Schrijf **bool**. De standaardwaarde is **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Stelt de modus in waarin dia's op de pagina worden geplaatst bij het exporteren van een presentatie [ISlidesLayoutOptions](../islideslayoutoptions/). Deze eigenschap ondersteunt het toewijzen van objecten van type **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** niet. |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Start met geopend linker paneel. Kan worden overschreven in flashvars. Standaard is false. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Specificeert of het gegenereerde SWF-document de geïntegreerde documentviewer moet bevatten of niet. Standaard is **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces moet doorgaan of worden afgebroken. Schrijf [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het mogelijk om aangepaste objecten naar een string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van C# lock()-statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [ISaveOptions](../isaveoptions/)
* Naamruimte [Aspose::Slides::Export](../)
* Bibliotheek [Aspose.Slides](../../)