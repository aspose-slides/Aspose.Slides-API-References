---
title: MasterSlide
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een master slide in een presentatie voor.
type: docs
weight: 4473
url: /nl/aspose.slides/masterslide/
---
## MasterSlide klasse

Stelt een master-slide in een presentatie voor.

```cpp
class MasterSlide : public Aspose::Slides::BaseSlide,
                    public Aspose::Slides::IMasterSlide
```

## Methoden

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [ApplyExternalThemeToDependingSlides](./applyexternalthemetodependingslides/)([System::String](../../system/string/)) override | Maakt een nieuwe master-slide op basis van de huidige, past een extern thema toe en past de gemaakte master-slide toe op alle afhankelijke slides. |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | Geeft een effectief thema voor deze slide terug. |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | Bepaalt of de twee [IBaseSlide](../ibaseslide/)-instanties gelijk zijn. De teruggegeven waarde wordt berekend op basis van de structuur van de slide en statische inhoud. Twee slides zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identifier-waarden, bijv. SlideId en dynamische inhoud, bijv. de huidige datumwaarde in Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met gebruik van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevende-kommagetallenvergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevende-kommagetallenvergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | Zoekt de eerste voorkomen van een vorm met de opgegeven alternatieve tekst. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | Geeft de achtergrond van de slide terug. Alleen-lezen [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_BodyStyle](./get_bodystyle/)() override | Geeft de stijl van een hoofdtekst terug. Alleen-lezen [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | Geeft de ActiveX-besturingselement op de opgegeven index terug. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | Geeft de verzameling ActiveX-besturingselementen op een slide terug. Alleen-lezen [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | Geeft de aangepaste gegevens van de slide terug. Alleen-lezen [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() override | Geeft een verzameling tekengidsen voor de master-slide terug. Alleen-lezen [IDrawingGuidesCollection](../idrawingguidescollection/) |
| **bool** [get_HasDependingSlides](./get_hasdependingslides/)() override | Geeft true terug als er minstens één slide bestaat die afhankelijk is van deze master-slide. Alleen-lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | Geeft de HeaderFooter-manager van de master-slide terug. Alleen-lezen [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | Biedt gemakkelijke toegang tot de contained hyperlinks. Alleen-lezen [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) override | Geeft de onderliggende layout-slide voor deze master-slide op de opgegeven index terug. Alleen-lezen [Aspose::Slides::ILayoutSlide](../ilayoutslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() override | Geeft de verzameling onderliggende layout-slides voor deze master-slide terug. Alleen-lezen [IMasterLayoutSlideCollection](../imasterlayoutslidecollection/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | Geeft de naam van een master-slide terug. Lees [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_OtherStyle](./get_otherstyle/)() override | Geeft de stijl van een andere tekst terug. Alleen-lezen [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | Geeft de [IPresentation](../ipresentation/)-interface terug. Alleen-lezen [IPresentation](../ipresentation/). |
| **bool** [get_Preserve](./get_preserve/)() override | Bepaalt of de bijbehorende master wordt verwijderd wanneer alle slides die die master volgen worden verwijderd. Opmerking: [Aspose.Slides](../) zal nooit een ongebruikte master zelf verwijderen; om ongebruikte masters daadwerkelijk te verwijderen, roep [MasterSlideCollection::RemoveUnused](../masterslidecollection/removeunused/) aan. Lees **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | Geeft de vorm op de opgegeven index terug. Alleen-lezen [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | Geeft de vormen van een slide terug. Alleen-lezen [IShapeCollection](../ishapecollection/). |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | Specificeert of vormen op de master-slide getoond moeten worden op slides of niet. Voor de master-slide zelf keert deze eigenschap altijd **false** terug. Lees **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Geeft de basis-slide terug. Alleen-lezen [IBaseSlide](../ibaseslide/). |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | Geeft de ID van een slide terug. Alleen-lezen **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | Geeft het Transition-object terug dat informatie bevat over hoe de opgegeven slide vordert tijdens een diavoorstelling. Alleen-lezen [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](./get_thememanager/)() override | Geeft de themabeheerder terug. Alleen-lezen [Theme::IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | Geeft het animatietijdlijnobject terug. Alleen-lezen [IAnimationTimeLine](../ianimationtimeline/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TitleStyle](./get_titlestyle/)() override | Geeft de stijl van een titeltekst terug. Alleen-lezen [ITextStyle](../itextstyle/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() override | Geeft een array met alle slides die afhankelijk zijn van deze master-slide. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is' operator. |
| void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)() override | Voegt runs met dezelfde opmaak samen in alle alinea's van alle toegestane vormen. |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | Voegt runs met dezelfde opmaak samen in alle alinea's van alle toegestane vormen. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object met nullptr per referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | Stelt de naam van een master-slide in. Schrijf [System::String](../../system/string/). |
| void [set_Preserve](./set_preserve/)(**bool**) override | Bepaalt of de bijbehorende master wordt verwijderd wanneer alle slides die die master volgen worden verwijderd. Opmerking: [Aspose.Slides](../) zal nooit een ongebruikte master zelf verwijderen; om ongebruikte masters daadwerkelijk te verwijderen, roep [MasterSlideCollection::RemoveUnused](../masterslidecollection/removeunused/) aan. Schrijf **bool**. |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | Specificeert of vormen op de master-slide getoond moeten worden op slides of niet. Voor de master-slide zelf keert deze eigenschap altijd **false** terug. Schrijf **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloon-argument in als een zwakke pointer (in plaats van gedeelde). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en geeft de gedeelde referentieteller terug. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [BaseSlide](../baseslide/)
* Klasse [IMasterSlide](../imasterslide/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)