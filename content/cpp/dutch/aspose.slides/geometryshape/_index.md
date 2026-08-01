---
title: GeometryShape
second_title: Aspose.Slides voor C++ API Referentie
description: Vertegenwoordigt de bovenliggende klasse voor alle geometrische vormen.
type: docs
weight: 1080
url: /nl/aspose.slides/geometryshape/
---
## GeometryShape klasse

Vertegenwoordigt de bovenliggende klasse voor alle geometrische vormen.

```cpp
class GeometryShape : public Aspose::Slides::Shape,
                      public virtual Aspose::Slides::IGeometryShape
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Voegt een nieuwe placeholder toe als er geen bestaat en stelt placeholder-eigenschappen in op een opgegeven. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](./createshapeelements/)() override | Maakt en retourneert een array van shape-elementen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert een C#-achtige floating-point-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert een C#-achtige floating-point-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](./get_adjustment/)(**int32_t**) override | Retourneert de aanpassingswaarde van een shape op de opgegeven index. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](./get_adjustments/)() override | Retourneert een collectie van aanpassingswaarden van een shape. Alleen-lezen [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Retourneert de alternatieve tekst die aan een shape is gekoppeld. Alleen-lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Retourneert de titel van de alternatieve tekst die aan een shape is gekoppeld. Alleen-lezen [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Eigenschap geeft aan hoe een shape wordt weergegeven in zwart-wit weergavemodus. Alleen-lezen [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Retourneert het aantal verbindingspunten op de shape. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Retourneert de aangepaste gegevens van de shape. Alleen-lezen [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Retourneert het [EffectFormat](../effectformat/)-object dat pixel-effecten bevat die op een shape zijn toegepast. Opmerking: kan null retourneren voor bepaalde vormen die geen effecteigenschappen hebben. Alleen-lezen [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Retourneert het [FillFormat](../fillformat/)-object dat vul-opmaak eigenschappen voor een shape bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen vul-eigenschappen hebben. Alleen-lezen [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Retourneert de eigenschappen van het shape-frame. Alleen-lezen [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Haalt de hoogte van de shape op, gemeten in points. Alleen-lezen **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Bepaalt of de shape verborgen is. Alleen-lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Retourneert de hyperlink die is gedefinieerd voor muisklik. Alleen-lezen [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Retourneert de hyperlink-manager. Alleen-lezen [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Retourneert de hyperlink die is gedefinieerd voor muis-over. Alleen-lezen [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Haalt de optie 'Mark as decorative' op. Lees/schrijf **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Bepaalt of de shape gegroepeerd is. Alleen-lezen **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Bepaalt of de shape TextHolder_PPT is. Alleen-lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Retourneert het [LineFormat](../lineformat/)-object dat lijn-opmaak eigenschappen voor een shape bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen lijn-eigenschappen hebben. Alleen-lezen [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Retourneert de naam van een shape. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Alleen-lezen [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Retourneert een unieke identifier met slide-bereik die constant blijft gedurende de levensduur van de shape en PowerPoint of interop-code in staat stelt de shape betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen **uint32_t**. Zie ook [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Retourneert het bovenliggende [GroupShape](../groupshape/)-object als de shape gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Retourneert de placeholder voor een shape. Retourneert null als de shape geen placeholder heeft. Alleen-lezen [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Retourneert de bovenliggende presentatie van een slide. Alleen-lezen [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Retourneert de ruwe shape-frame-eigenschappen. Alleen-lezen [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Retourneert het aantal graden waarmee de opgegeven shape rond de z-as is geroteerd. Een positieve waarde duidt op een klokwijzerrotatie; een negatieve waarde duidt op een tegen-klokwijzerrotatie. Alleen-lezen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Retourneert de vergrendelingen van de shape. Alleen-lezen [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](./get_shapestyle/)() override | Retourneert het stijl-object van de shape. Alleen-lezen [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override | Retourneert het type van de geometrie-preset. Opmerking: bij wijziging van de waarde worden alle aanpassingswaarden gereset naar hun standaardwaarden. Alleen-lezen [Slides::ShapeType](../shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Retourneert de bovenliggende slide van een shape. Alleen-lezen [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Retourneert het [ThreeDFormat](../threedformat/)-object dat 3D-effecteigenschappen voor een shape bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen 3D-eigenschappen hebben. Alleen-lezen [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Retourneert een interne, presentatie-gebonden identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden heringesteld, mag deze niet worden beschouwd als een blijvende unieke sleutel. Alleen-lezen **uint32_t**. Zie ook [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Haalt de breedte van de shape op, gemeten in points. Alleen-lezen **float**. |
| **float** [get_X](../shape/get_x/)() override | Haalt de x-coördinaat van de linkerbovenhoek van de shape op, gemeten in points. Alleen-lezen **float**. |
| **float** [get_Y](../shape/get_y/)() override | Haalt de y-coördinaat van de linkerbovenhoek van de shape op, gemeten in points. Alleen-lezen **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Retourneert de positie van een shape in de z-volgorde. Shapes[0] retourneert de shape achterin de z-volgorde, en Shapes[Shapes.Count - 1] retourneert de shape voorin de z-volgorde. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Retourneert een basis-placeholder-shape (shape van de lay-out en/of master-slide waarvan de huidige shape is geërfd). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentie-teller datastructuur op die met het object is geassocieerd. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](./getgeometrypaths/)() override | Retourneert een kopie van het pad van de geometrie-shape. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de shape. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Retourneert een miniatuur van de shape. Standaard wordt [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) shape thumbnail bounds-type gebruikt. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Retourneert een miniatuur van de shape. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Haalt de visuele grenzen van de shape op, berekend op basis van de gerenderde inhoud. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analoge van de C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert de C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieer-constructor. Kopieert in feite niets, initialiseert enkel een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert in feite niets, initialiseert enkel een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definieert dat deze shape geen placeholder is. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Stelt de alternatieve tekst in die aan een shape is gekoppeld. Schrijf [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Stelt de titel van de alternatieve tekst in die aan een shape is gekoppeld. Schrijf [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Eigenschap geeft aan hoe een shape wordt weergegeven in zwart-wit weergavemodus. Schrijf [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Stelt de eigenschappen van het shape-frame in. Schrijf [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Stelt de hoogte van de shape in, gemeten in points. Schrijf **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Bepaalt of de shape verborgen is. Schrijf **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Stelt de hyperlink in die is gedefinieerd voor muisklik. Schrijf [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Stelt de hyperlink in die is gedefinieerd voor muis-over. Schrijf [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Stelt de optie 'Mark as decorative' in. Lees/schrijf **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Stelt de naam van een shape in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Schrijf [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Stelt de ruwe shape-frame-eigenschappen in. Schrijf [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Stelt het aantal graden in waarmee de opgegeven shape rond de z-as is geroteerd. Een positieve waarde duidt op een klokwijzerrotatie; een negatieve waarde duidt op een tegen-klokwijzerrotatie. Schrijf **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | Stelt het type van de geometrie-preset in. Opmerking: bij wijziging van de waarde worden alle aanpassingswaarden gereset naar hun standaardwaarden. Schrijf [Slides::ShapeType](../shapetype/). |
| void [set_Width](../shape/set_width/)(**float**) override | Stelt de breedte van de shape in, gemeten in points. Schrijf **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Stelt de x-coördinaat van de linkerbovenhoek van de shape in, gemeten in points. Schrijf **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Stelt de y-coördinaat van de linkerbovenhoek van de shape in, gemeten in points. Schrijf **float**. |
| void [SetGeometryPath](./setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Werkt de shape-geometrie bij vanuit [IGeometryPath](../igeometrypath/) object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de shape. Wijzigt het type van de shape ([ShapeType](../shapetype/)) naar [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](./setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Werkt de shape-geometrie bij vanuit een array van [IGeometryPath](../igeometrypath/). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de shape. Wijzigt het type van de shape ([ShapeType](../shapetype/)) naar [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloon-argument in als een zwakke pointer (in plaats van een gedeelde). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Shape](../shape/)
* Klasse [IGeometryShape](../igeometryshape/)
* Namespace [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)