---
title: IPictureFrame
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een frame voor met een afbeelding erin.
type: docs
weight: 3251
url: /nl/aspose.slides/ipictureframe/
---
## IPictureFrame klasse

Stelt een frame voor met een afbeelding erin.

```cpp
class IPictureFrame : public virtual Aspose::Slides::IGeometryShape
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Voegt een nieuwe placeholder toe als er geen aanwezig is en stelt de placeholder-eigenschappen in op een opgegeven placeholder. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Maakt een array van shape-elementen aan en geeft deze terug. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Geeft de aanpassingswaarde van een shape op de opgegeven index terug. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Geeft een verzameling aanpassingswaarden van een shape terug. Alleen-lezen [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Geeft de alternatieve tekst die aan een shape is gekoppeld terug. Lezen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Geeft de titel van de alternatieve tekst die aan een shape is gekoppeld terug. Lezen [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Eigenschap bepaalt hoe een shape wordt weergegeven in zwart-wit weergavemodus. Lezen [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Geeft het aantal verbindingstoepassingen op de shape terug. Alleen-lezen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Geeft de aangepaste gegevens van de shape terug. Alleen-lezen [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Geeft het [EffectFormat](../effectformat/)-object terug dat pixel-effecten bevat die op een shape zijn toegepast. Alleen-lezen [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Geeft het [FillFormat](../fillformat/)-object terug dat opvulopmaak-eigenschappen voor een shape bevat. Alleen-lezen [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Geeft de eigenschappen van het shape-frame terug. Lezen [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Haalt de hoogte van de shape op, gemeten in points. Lezen **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Bepaalt of de shape verborgen is. Lezen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Geeft de hyperlink terug die voor muisklik is gedefinieerd. Lezen [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlinks-beheerder Alleen-lezen [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Geeft de hyperlink terug die voor muis-over is gedefinieerd. Lezen [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Haalt 'Mark as decorative' optie op Lezen/Schrijven **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Bepaalt of de shape gegroepeerd is. Alleen-lezen **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Bepaalt of de shape een TextHolder is. Alleen-lezen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Geeft het [LineFormat](../lineformat/)-object terug dat lijnopmaak-eigenschappen voor een shape bevat. Alleen-lezen [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Geeft de naam van een shape terug. Lezen [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Geeft een uniek identifier binnen de dia terug die gedurende de levensduur van de shape constant blijft en PowerPoint of interop-code in staat stelt de shape betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen **uint32_t**. Zie ook [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Geeft het bovenliggende [GroupShape](../groupshape/)-object terug als de shape gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](./get_pictureformat/)() | Geeft het [PictureFillFormat](../picturefillformat/)-object voor een picture-frame terug. Alleen-lezen [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](./get_pictureframelock/)() | Geeft de vergrendelingen van [PictureFrame](../pictureframe/) terug. Alleen-lezen [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Geeft de placeholder voor een shape terug. Alleen-lezen [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Geeft de presentatie terug. Alleen-lezen [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Geeft de ruwe eigenschappen van het shape-frame terug. Lezen [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](./get_relativescaleheight/)() | Geeft de schaal van de hoogte (ten opzichte van de oorspronkelijke afbeeldingsgrootte) van het picture-frame terug. Waarde 1,0 komt overeen met 100 %. Lezen **float**. |
| virtual **float** [get_RelativeScaleWidth](./get_relativescalewidth/)() | Geeft de schaal van de breedte (ten opzichte van de oorspronkelijke afbeeldingsgrootte) van het picture-frame terug. Waarde 1,0 komt overeen met 100 %. Lezen **float**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Geeft het aantal graden terug waarmee de opgegeven shape rond de z-as wordt geroteerd. Een positieve waarde duidt op rotatie met de klok mee; een negatieve waarde duidt op rotatie tegen de klok in. Lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Geeft de vergrendelingen van de shape terug. Alleen-lezen [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Geeft het stijlobject van de shape terug. Alleen-lezen [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Geeft het type van de geometrie-preset terug. Opmerking: bij wijziging van de waarde worden alle aanpassingswaarden teruggezet naar hun standaardwaarden. Lezen [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Geeft de basisdia terug. Alleen-lezen [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Geeft het [ThreeDFormat](../threedformat/)-object terug dat lijnopmaak-eigenschappen voor een shape bevat. Alleen-lezen [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Geeft een interne, presentatie-gebonden identifier terug bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden herwezen, mag deze niet worden beschouwd als een blijvende unieke sleutel. Alleen-lezen **uint32_t**. Zie ook [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Haalt de breedte van de shape op, gemeten in points. Lezen **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Haalt de x-coördinaat van de linkerbovenhoek van de shape op, gemeten in points. Lezen **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Haalt de y-coördinaat van de linkerbovenhoek van de shape op, gemeten in points. Lezen **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Geeft de positie van een shape in de z-volgorde terug. Shapes[0] geeft de shape achterin de z-volgorde en Shapes[Shapes.Count - 1] geeft de shape voorin de z-volgorde terug. Alleen-lezen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Geeft een basale placeholder-shape terug (shape van de lay-out en/of master-dia waar de huidige shape van erft). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Geeft een kopie van het pad van de geometrie-shape terug. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de shape. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Geeft de miniatuur van de shape terug. Standaard wordt [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) miniatuurlimiettype gebruikt. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Geeft de miniatuur van de shape terug. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert de lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maak object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, initialiseert enkel een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, Initialiseert enkel een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Definieert dat deze shape geen placeholder is. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Stelt de alternatieve tekst in die aan een shape is gekoppeld. Schrijven [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Stelt de titel van de alternatieve tekst in die aan een shape is gekoppeld. Schrijven [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Eigenschap bepaalt hoe een shape wordt weergegeven in zwart-wit weergavemodus. Schrijven [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Stelt de eigenschappen van het shape-frame in. Schrijven [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Stelt de hoogte van de shape in, gemeten in points. Schrijven **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Bepaalt of de shape verborgen is. Schrijven **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Stelt de hyperlink in die voor muisklik is gedefinieerd. Schrijven [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Stelt de hyperlink in die voor muis-over is gedefinieerd. Schrijven [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Stelt de 'Mark as decorative' optie in. Lezen/Schrijven **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Stelt de naam van een shape in. Schrijven [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Stelt de ruwe eigenschappen van het shape-frame in. Schrijven [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](./set_relativescaleheight/)(**float**) | Stelt de schaal van de hoogte (ten opzichte van de oorspronkelijke afbeeldingsgrootte) van het picture-frame in. Waarde 1,0 komt overeen met 100 %. Schrijven **float**. |
| virtual void [set_RelativeScaleWidth](./set_relativescalewidth/)(**float**) | Stelt de schaal van de breedte (ten opzichte van de oorspronkelijke afbeeldingsgrootte) van het picture-frame in. Waarde 1,0 komt overeen met 100 %. Schrijven **float**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Stelt het aantal graden in waarmee de opgegeven shape rond de z-as wordt geroteerd. Een positieve waarde duidt op rotatie met de klok mee; een negatieve waarde duidt op rotatie tegen de klok in. Schrijven **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Stelt het type van de geometrie-preset in. Opmerking: bij wijziging van de waarde worden alle aanpassingswaarden teruggezet naar hun standaardwaarden. Schrijven [Slides::ShapeType](../shapetype/). |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Stelt de breedte van de shape in, gemeten in points. Schrijven **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Stelt de x-coördinaat van de linkerbovenhoek van de shape in, gemeten in points. Schrijven **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Stelt de y-coördinaat van de linkerbovenhoek van de shape in, gemeten in points. Schrijven **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Werk de geometry van de shape bij vanuit [IGeometryPath](../igeometrypath/)-object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de shape. Verandert het type van de shape ([ShapeType](../shapetype/)) naar [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Werk de geometry van de shape bij vanuit een array van [IGeometryPath](../igeometrypath/). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de shape. Verandert het type van de shape ([ShapeType](../shapetype/)) naar [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Stelt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [IGeometryShape](../igeometryshape/)
* Namespace [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)