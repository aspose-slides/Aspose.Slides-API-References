---
title: OleObjectFrame
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt een OLE-object op een dia.
type: docs
weight: 4603
url: /nl/aspose.slides/oleobjectframe/
---
## OleObjectFrame klasse

Stelt een OLE-object op een dia voor.

```cpp
class OleObjectFrame : public Aspose::Slides::GraphicalObject,
                       public Aspose::Slides::IOleObjectFrame
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Voegt een nieuwe placeholder toe als er geen is en stelt de placeholder-eigenschappen in op een opgegeven. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met de C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl drijvende-komma vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl drijvende-komma vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Retourneert de alternatieve tekst die aan een vorm is gekoppeld. Lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Retourneert de titel van de alternatieve tekst die aan een vorm is gekoppeld. Lezen [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Eigenschap geeft aan hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Retourneert het aantal verbindingspunten op de vorm. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Retourneert het [EffectFormat](../effectformat/)-object dat pixel-effecten op een vorm bevat. Let op: kan null retourneren voor bepaalde vormen die geen effect-eigenschappen hebben. Alleen-lezen [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() override | Haalt informatie op over OLE-ingesloten gegevens. Lezen [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/). |
| [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() override | Retourneert de bestandsnaam van het ingesloten OLE-object. |
| [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() override | Retourneert het pad van het ingesloten OLE-object. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Retourneert het [FillFormat](../fillformat/)-object dat opvul-formaterings-eigenschappen voor een vorm bevat. Let op: kan null retourneren voor bepaalde vormen die geen opvul-eigenschappen hebben. Alleen-lezen [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Retourneert de eigenschappen van het vorm-frame. Lezen [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Retourneert de vergrendelingen van de vorm. Alleen-lezen [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Haalt de hoogte van de vorm op, gemeten in punten. Lezen **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Bepaalt of de vorm verborgen is. Lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Retourneert de hyperlink die is gedefinieerd voor muisklik. Lezen [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Retourneert de hyperlink-beheerder. Alleen-lezen [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Retourneert de hyperlink die is gedefinieerd voor muisover. Lezen [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Haalt de optie 'Mark as decorative' op. Lezen/schrijven **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Bepaalt of de vorm gegroepeerd is. Alleen-lezen **bool**. |
| **bool** [get_IsObjectIcon](./get_isobjecticon/)() override | Bepaalt of een object zichtbaar is als pictogram. Lezen **bool**. |
| **bool** [get_IsObjectLink](./get_isobjectlink/)() override | Bepaalt of een object gekoppeld is aan een extern bestand. Alleen-lezen **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Retourneert het [LineFormat](../lineformat/)-object dat lijn-opmaak-eigenschappen voor een vorm bevat. Let op: kan null retourneren voor bepaalde vormen die geen lijn-eigenschappen hebben. Alleen-lezen [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() override | Retourneert het volledige pad naar een gekoppeld bestand. Korte bestandsnaam wordt gebruikt. Alleen-lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Retourneert het volledige pad naar een gekoppeld bestand. Lange bestandsnaam wordt gebruikt. Lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() override | Retourneert het relatieve pad naar een gekoppeld bestand indien aanwezig, anders een lege tekenreeks. Alleen-lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Retourneert de naam van een vorm. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() override | Retourneert de naam van een object. Lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() override | Retourneert de ProgID van een object. Alleen-lezen [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Retourneert een dia-specifieke unieke identifier die gedurende de levensduur van de vorm constant blijft en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen **uint32_t**. Zie ook [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Retourneert het bovenliggende [GroupShape](../groupshape/)-object als de vorm gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Retourneert de placeholder voor een vorm. Retourneert null als de vorm geen placeholder heeft. Alleen-lezen [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Retourneert de bovenliggende presentatie van een dia. Alleen-lezen [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Retourneert de ruwe vorm-frame-eigenschappen. Lezen [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Retourneert het aantal graden waarin de opgegeven vorm rond de z-as is geroteerd. Een positieve waarde geeft een draai met de klok mee aan; een negatieve waarde een draai tegen de klok in. Lezen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Retourneert de vergrendelingen van de vorm. Alleen-lezen [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Retourneert de bovenliggende dia van een vorm. Alleen-lezen [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() override | Retourneert het OleObject-beeldvulling-eigenschappen-object. Alleen-lezen [IPictureFillFormat](../ipicturefillformat/). |
| [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() override | Retourneert de titel voor het OleObject-pictogram. Lezen [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Retourneert het [ThreeDFormat](../threedformat/)-object dat 3D-effect-eigenschappen voor een vorm bevat. Let op: kan null retourneren voor bepaalde vormen die geen 3D-eigenschappen hebben. Alleen-lezen [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Retourneert een interne, presentatie-specifieke identifier die bedoeld is voor gebruik door invoegtoepassingen of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden herkend, mag deze niet worden beschouwd als een permanente unieke sleutel. Alleen-lezen **uint32_t**. Zie ook [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_UpdateAutomatic](./get_updateautomatic/)() override | Bepaalt of het gekoppelde ingesloten object automatisch wordt bijgewerkt wanneer de presentatie wordt geopend of afgedrukt. Lezen **bool**. |
| **float** [get_Width](../shape/get_width/)() override | Haalt de breedte van de vorm op, gemeten in punten. Lezen **float**. |
| **float** [get_X](../shape/get_x/)() override | Haalt de x-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. Lezen **float**. |
| **float** [get_Y](../shape/get_y/)() override | Haalt de y-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. Lezen **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Retourneert de positie van een vorm in de z-volgorde. Shapes[0] geeft de vorm aan de achterkant van de z-volgorde, en Shapes[Shapes.Count - 1] geeft de vorm aan de voorkant van de z-volgorde. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Retourneert een basis-placeholder-vorm (vorm van de lay-out en/of masterslide waarvan de huidige vorm is geërfd). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashwaarden voor aangepaste objecten mogelijk. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Retourneert de miniatuur van de vorm. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) vorm-miniatuur-grenzen-type wordt standaard gebruikt. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Retourneert de miniatuur van de vorm. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Haalt de visuele grenzen van de vorm op, berekend vanuit de gerenderde inhoud. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert de C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definieert dat deze vorm geen placeholder is. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Stelt de alternatieve tekst in die aan een vorm is gekoppeld. Schrijven [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Schrijven [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Eigenschap bepaalt hoe een vorm wordt weergegeven in zwart-wit modus. Schrijven [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Stelt de eigenschappen van het vorm-frame in. Schrijven [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Stelt de hoogte van de vorm in, gemeten in punten. Schrijven **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Bepaalt of de vorm verborgen is. Schrijven **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Stelt de hyperlink in die is gedefinieerd voor muisklik. Schrijven [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Stelt de hyperlink in die is gedefinieerd voor muisover. Schrijven [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Stelt de optie 'Mark as decorative' in. Schrijven/Lezen **bool**. |
| void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) override | Bepaalt of een object zichtbaar is als pictogram. Schrijven **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Retourneert het volledige pad naar een gekoppeld bestand. Lange bestandsnaam wordt gebruikt. Schrijven [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Stelt de naam van een vorm in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Schrijven [System::String](../../system/string/). |
| void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) override | Stelt de naam van een object in. Schrijven [System::String](../../system/string/). |
| void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) override | Retourneert de ProgID van een object. Alleen-lezen [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Stelt de ruwe vorm-frame-eigenschappen in. Schrijven [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt geroteerd. Een positieve waarde geeft een draai met de klok mee aan; een negatieve waarde een draai tegen de klok in. Schrijven **float**. |
| void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) override | Stelt de titel in voor het OleObject-pictogram. Schrijven [System::String](../../system/string/). |
| void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) override | Bepaalt of het gekoppelde ingesloten object automatisch wordt bijgewerkt wanneer de presentatie wordt geopend of afgedrukt. Schrijven **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | Stelt de breedte van de vorm in, gemeten in punten. Schrijven **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Schrijven **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Schrijven **float**. |
| void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | Stelt informatie in over OLE-ingesloten gegevens. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloon-argument in op een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar tekenreeks mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Maakt alle interne gegevensstructuren vrij. |

## Opmerkingen

Het volgende voorbeeld laat zien hoe OLE-object-frames benaderd worden. ```cpp
// Laadt de PPTX in een presentatie-object
auto pres = System::MakeObject<Presentation>(u"AccessingOLEObjectFrame.pptx");

// Benadert de eerste dia
auto slide = pres->get_Slides()->idx_get(0);
// Cast de vorm naar OleObjectFrame
System::SharedPtr<OleObjectFrame> oleObjectFrame = System::AsCast<OleObjectFrame>(slide->get_Shapes()->idx_get(0));
// Leest het OLE-object en schrijft het naar schijf
if (oleObjectFrame != nullptr)
{
    // Haalt ingesloten bestandsgegevens op
    System::ArrayPtr<uint8_t> data = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileData();
    // Haalt ingesloten bestands-extensie op
    System::String fileExtention = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileExtension();
    // Maakt een pad aan om het geëxtraheerde bestand op te slaan
    System::String extractedPath = System::String(u"excelFromOLE_out") + fileExtention;
    // Slaat de geëxtraheerde gegevens op
    auto stream = System::MakeObject<System::IO::FileStream>(extractedPath,
                                                             System::IO::FileMode::Create,
                                                             System::IO::FileAccess::Write);
    stream->Write(data, 0, data->get_Length());
}
```

## Zie ook

* Klasse [GraphicalObject](../graphicalobject/)
* Klasse [IOleObjectFrame](../ioleobjectframe/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)