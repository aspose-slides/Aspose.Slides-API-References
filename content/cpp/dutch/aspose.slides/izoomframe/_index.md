---
title: IZoomFrame
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een Slide Zoom-object in een dia voor.
type: docs
weight: 4252
url: /nl/aspose.slides/izoomframe/
---
## IZoomFrame klasse

Stelt een [Slide](../slide/) Zoom-object in een dia voor.

```cpp
class IZoomFrame : public virtual Aspose::Slides::IZoomObject
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Voegt een nieuwe tijdelijke aanduiding toe als er geen is en stelt de eigenschappen van de tijdelijke aanduiding in op een opgegeven. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-achtige zwevende-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-achtige zwevende-kommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Retourneert de alternatieve tekst die aan een vorm is gekoppeld. Lees [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Retourneert de titel van de alternatieve tekst die aan een vorm is gekoppeld. Lees [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lees [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Retourneert het aantal verbindingspunten op de vorm. Alleen-lezen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Retourneert het [EffectFormat](../effectformat/)-object dat pixel-effecten bevat die op een vorm zijn toegepast. Alleen-lezen [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Retourneert het [FillFormat](../fillformat/)-object dat opvulopmaakteigenschappen voor een vorm bevat. Alleen-lezen [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Retourneert de eigenschappen van het vormframe. Lees [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Retourneert de vergrendelingen van de vorm. Alleen-lezen [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Haalt de hoogte van de vorm op, gemeten in punten. Lees **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Bepaalt of de vorm verborgen is. Lees **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Retourneert de hyperlink die is gedefinieerd voor muisklik. Lees [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlinkbeheerder Alleen-lezen [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Retourneert de hyperlink die is gedefinieerd voor muis-overslaan. Lees [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | Haalt het afbeeldingstype van een zoom-object op. Lees [ZoomImageType](../zoomimagetype/). Standaardwaarde: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Haalt de optie 'Mark as decorative' op. Lezen/Schrijven **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Bepaalt of de vorm gegroepeerd is. Alleen-lezen **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Bepaalt of de vorm een TextHolder is. Alleen-lezen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Retourneert het [LineFormat](../lineformat/)-object dat lijstopmaak-eigenschappen voor een vorm bevat. Alleen-lezen [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Retourneert de naam van een vorm. Lees [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Retourneert een dia-gebonden unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanaf elke plaats in het document. Alleen-lezen **uint32_t**. Zie ook [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Retourneert het bovenliggende [GroupShape](../groupshape/)-object als de vorm gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Retourneert de tijdelijke aanduiding voor een vorm. Alleen-lezen [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Retourneert de presentatie. Alleen-lezen [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Retourneert de ruwe eigenschappen van het vormframe. Lees [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | Haalt het navigatiegedrag op in de diavoorstelling. Lees **bool**. Standaardwaarde: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Retourneert het aantal graden waarmee de opgegeven vorm rond de z-as is gedraaid. Een positieve waarde duidt een klokwijzerrotatie aan; een negatieve waarde duidt een tegenklokwijzerrotatie aan. Lees **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Retourneert de vergrendelingen van de vorm. Alleen-lezen [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | Haalt de waarde op die aangeeft of de Zoom de achtergrond van de bestemmingsdia zal gebruiken. Lees **bool**. Standaardwaarde: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Retourneert de basisdia. Alleen-lezen [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() | Haalt het dia-object op waarnaar het [Slide](../slide/) Zoom-object linkt. Lees [ISlide](../islide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Retourneert het [ThreeDFormat](../threedformat/)-object dat lijstopmaak-eigenschappen voor een vorm bevat. Alleen-lezen [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | Haalt de duur van de overgang tussen Zoom en dia op. Lees **float**. Standaardwaarde: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Retourneert een interne, presentatie-gebonden identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden hergebruikt, mag deze niet worden behandeld als een permanente unieke sleutel. Alleen-lezen **uint32_t**. Zie ook [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Haalt de breedte van de vorm op, gemeten in punten. Lees **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Haalt de x-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. Lees **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Haalt de y-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. Lees **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | Haalt afbeelding op voor zoom-object. Lees [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Retourneert de positie van een vorm in de z-volgorde. Shapes[0] retourneert de vorm achterin de z-volgorde, en Shapes[Shapes.Count - 1] retourneert de vorm voorin de z-volgorde. Alleen-lezen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Retourneert een basistijdelijke aanduidingvorm (vorm van de lay-out en/of masterslide waarvan de huidige vorm is geërfd). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Retourneert miniatuur van vorm. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) vorm miniatuurgrenzen-type wordt standaard gebruikt. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Retourneert miniatuur van vorm. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakerobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentie van waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Definieert dat deze vorm geen tijdelijke aanduiding is. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Stelt de alternatieve tekst in die aan een vorm is gekoppeld. Schrijf [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Schrijf [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Schrijf [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Stelt de eigenschappen van het vormframe in. Schrijf [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Stelt de hoogte van de vorm in, gemeten in punten. Schrijf **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Bepaalt of de vorm verborgen is. Schrijf **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Stelt de hyperlink in die is gedefinieerd voor muisklik. Schrijf [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Stelt de hyperlink in die is gedefinieerd voor muis-overslaan. Schrijf [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | Stelt het afbeeldingstype van een zoom-object in. Schrijf [ZoomImageType](../zoomimagetype/). Standaardwaarde: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Stelt de optie 'Mark as decorative' in. Lezen/Schrijven **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Stelt de naam van een vorm in. Schrijf [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Stelt de ruwe eigenschappen van het vormframe in. Schrijf [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | Stelt het navigatiegedrag in de diavoorstelling in. Schrijf **bool**. Standaardwaarde: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid. Een positieve waarde duidt klokwijzerrotatie aan; een negatieve waarde duidt tegenklokwijzerrotatie aan. Schrijf **float**. |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | Stelt de waarde in die aangeeft of de Zoom de achtergrond van de bestemmingsdia zal gebruiken. Schrijf **bool**. Standaardwaarde: true |
| virtual void [set_TargetSlide](./set_targetslide/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | Stelt het dia-object in waarnaar het [Slide](../slide/) Zoom-object linkt. Schrijf [ISlide](../islide/). |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | Stelt de duur van de overgang tussen Zoom en dia in. Schrijf **float**. Standaardwaarde: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Stelt de breedte van de vorm in, gemeten in punten. Schrijf **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Schrijf **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Schrijf **float**. |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Stelt afbeelding in voor zoom-object. Schrijf [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Hiermee kan men pointers in containers naar zwakke modus omzetten. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakerobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [IZoomObject](../izoomobject/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)