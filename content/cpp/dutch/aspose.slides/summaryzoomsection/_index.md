---
title: SummaryZoomSection
second_title: Aspose.Slides voor C++ API-referentie
description: Representeert een Summary Zoom Section-object in een Summary Zoom-frame.
type: docs
weight: 5331
url: /nl/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection klasse

Stelt een Summary Zoom [Section](../section/) object voor in een Summary Zoom-frame.

```cpp
class SummaryZoomSection : public Aspose::Slides::SectionZoomFrame,
                           public Aspose::Slides::ISummaryZoomSection
```

## Methoden

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Voegt een nieuwe placeholder toe als er geen bestaat en stelt de placeholder-eigenschappen in op een opgegeven placeholder. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-kommagetal vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-kommagetal vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Retourneert de alternatieve tekst die aan een vorm is gekoppeld. Lees [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Retourneert de titel van de alternatieve tekst die aan een vorm is gekoppeld. Lees [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Eigenschap geeft aan hoe een vorm wordt gerenderd in zwart-wit weergavemodus. Lees [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Retourneert het aantal verbindingspunten op de vorm. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [ICustomData](../icustomdata/). |
| [System::String](../../system/string/) [get_Description](./get_description/)() override | Retourneert de tekstbeschrijving van het Summary Zoom [Section](../section/) object. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Retourneert het [EffectFormat](../effectformat/) object dat pixel-effecten bevat die op een vorm zijn toegepast. Opmerking: kan null retourneren voor bepaalde vormen die geen effect-eigenschappen hebben. Alleen-lezen [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Retourneert het [FillFormat](../fillformat/) object dat vulopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen vul-eigenschappen hebben. Alleen-lezen [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Retourneert de eigenschappen van het vormframe. Lees [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Retourneert de vergrendelingen van de vorm. Alleen-lezen [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Haalt de hoogte van de vorm op, gemeten in punten. Lees **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Bepaalt of de vorm verborgen is. Lees **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Retourneert de hyperlink die is gedefinieerd voor muisklik. Lees [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Retourneert de hyperlink-beheerder. Alleen-lezen [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Retourneert de hyperlink die is gedefinieerd voor muis-over. Lees [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | Haalt het afbeeldings-type van een zoom-object op. Lees [ZoomImageType](../zoomimagetype/). Standaardwaarde: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Haalt de optie 'Mark as decorative' op. Lezen/Schrijven **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Bepaalt of de vorm gegroepeerd is. Alleen-lezen **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Retourneert het [LineFormat](../lineformat/) object dat lijn-opmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen lijn-eigenschappen hebben. Alleen-lezen [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Retourneert de naam van een vorm. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lees [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Retourneert een uniek id dat beperkt is tot de dia en gedurende de levensduur van de vorm constant blijft, zodat PowerPoint of interop-code de vorm betrouwbaar kan refereren vanuit elk deel van het document. Alleen-lezen **uint32_t**. Zie ook [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Retourneert het bovenliggende [GroupShape](../groupshape/) object als de vorm gegroepeerd is. Anders retourneert het null. Alleen-lezen [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Retourneert de placeholder voor een vorm. Retourneert null als de vorm geen placeholder heeft. Alleen-lezen [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Retourneert de bovenliggende presentatie van een dia. Alleen-lezen [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Retourneert de ruwe eigenschappen van het vormframe. Lees [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | Haalt het navigatiegedrag in diavoorstelling op. Lees **bool**. Standaardwaarde: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | Retourneert het aantal graden dat de opgegeven vorm rond de z-as is geroteerd. Een positieve waarde geeft rotatie met de klok mee aan; een negatieve waarde geeft tegen de klok in rotatie aan. Lees **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Retourneert de vergrendelingen van de vorm. Alleen-lezen [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | Haalt de waarde op die aangeeft of de Zoom de achtergrond van de doel-dia zal gebruiken. Lees **bool**. Standaardwaarde: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Retourneert de bovenliggende dia van een vorm. Alleen-lezen [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](../sectionzoomframe/get_targetsection/)() override | Haalt het sectie-object op waarop het [Section](../section/) Zoom-object linkt. Lees [ISection](../isection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Retourneert het [ThreeDFormat](../threedformat/) object dat 3D-effecteigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen 3D-eigenschappen hebben. Alleen-lezen [IThreeDFormat](../ithreedformat/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Retourneert de teksttitel van het Summary Zoom [Section](../section/) object. |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | Haalt de duur van de overgang tussen Zoom en dia op. Lees **float**. Standaardwaarde: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Retourneert een interne, presentatie-gebonden identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden herverdeeld, mag deze niet worden behandeld als een permanente unieke sleutel. Alleen-lezen **uint32_t**. Zie ook [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Haalt de breedte van de vorm op, gemeten in punten. Lees **float**. |
| **float** [get_X](../shape/get_x/)() override | Haalt de x-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. Lees **float**. |
| **float** [get_Y](../shape/get_y/)() override | Haalt de y-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. Lees **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | Haalt de afbeelding voor een zoom-object op. Lees [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Retourneert de positie van een vorm in de Z-volgorde. Shapes[0] retourneert de vorm achterin de Z-volgorde, en Shapes[Shapes.Count - 1] retourneert de vorm voorin de Z-volgorde. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Retourneert een basale placeholder-vorm (vorm van de lay-out en/of master-dia waarvan de huidige vorm is geërfd). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const Analogie van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hash-berekening van aangepaste objecten mogelijk. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override Retourneert miniatuur van vorm. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) miniatuurbereik-type wordt standaard gebruikt. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override Retourneert miniatuur van vorm. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const Haalt het daadwerkelijke type van het object op. Analogie van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() Haalt de visuele grenzen van de vorm op, berekend vanuit de gerenderde inhoud. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const Controleert of het object een instantie is van het type beschreven door targetType. Analogie van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const Analogie van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste typen mogelijk. |
| [Object](../../system/object/object/)() Maakt object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) Kopie-constructor. Kopieert eigenlijk niets, initialiseert enkel een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert enkel een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override Definieert dat deze vorm geen placeholder is. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override Stelt de alternatieve tekst in die aan een vorm is gekoppeld. Schrijf [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override Stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Schrijf [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override Eigenschap geeft aan hoe een vorm wordt gerenderd in zwart-wit weergavemodus. Schrijf [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Description](./set_description/)([System::String](../../system/string/)) override Retourneert de tekstbeschrijving van het Summary Zoom [Section](../section/) object. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override Stelt de eigenschappen van het vormframe in. Schrijf [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override Stelt de hoogte van de vorm in, gemeten in punten. Schrijf **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override Bepaalt of de vorm verborgen is. Schrijf **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override Stelt de hyperlink in die is gedefinieerd voor muisklik. Schrijf [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override Stelt de hyperlink in die is gedefinieerd voor muis-over. Schrijf [IHyperlink](../ihyperlink/). |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override Stelt het afbeeldings-type van een zoom-object in. Schrijf [ZoomImageType](../zoomimagetype/). Standaardwaarde: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override Stelt 'Mark as decorative' optie in. Lezen/Schrijven **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override Stelt de naam van een vorm in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Schrijf [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override Stelt de ruwe eigenschappen van het vormframe in. Schrijf [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override Stelt het navigatiegedrag in diavoorstelling in. Schrijf **bool**. Standaardwaarde: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override Stelt het aantal graden in dat de opgegeven vorm rond de z-as is geroteerd. Een positieve waarde geeft rotatie met de klok mee aan; een negatieve waarde geeft rotatie tegen de klok in aan. Schrijf **float**. |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override Stelt de waarde in die aangeeft of de Zoom de achtergrond van de doel-dia zal gebruiken. Schrijf **bool**. Standaardwaarde: true |
| void [set_TargetSection](../sectionzoomframe/set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override Stelt het sectie-object in waarop het [Section](../section/) Zoom-object linkt. Schrijf [ISection](../isection/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override Retourneert de teksttitel van het Summary Zoom [Section](../section/) object. |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override Stelt de duur van de overgang tussen Zoom en dia in. Schrijf **float**. Standaardwaarde: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override Stelt de breedte van de vorm in, gemeten in punten. Schrijf **float**. |
| void [set_X](../shape/set_x/)(**float**) override Stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Schrijf **float**. |
| void [set_Y](../shape/set_y/)(**float**) override Stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Schrijf **float**. |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override Stelt de afbeelding in voor een zoom-object. Schrijf [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) Stelt het n'th sjabloon-argument in op een zwakke pointer (in plaats van gedeelde). Stelt het mogelijk om pointers in containers naar zwakke modus te wijzigen. |
| int [SharedCount](../../system/object/sharedcount/)() const Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const Analogie van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| virtual  [~Object](../../system/object/~object/)() Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [SectionZoomFrame](../sectionzoomframe/)
* Klasse [ISummaryZoomSection](../isummaryzoomsection/)
* Namespace [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)