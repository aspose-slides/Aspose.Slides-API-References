---
title: SmartArt
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een SmartArt-diagram voor
type: docs
weight: 66
url: /nl/aspose.slides.smartart/smartart/
---
## SmartArt klasse

Stelt een [SmartArt](./) diagram voor

```cpp
class SmartArt : public Aspose::Slides::GraphicalObject,
                 public Aspose::Slides::SmartArt::ISmartArt
```

## Methoden

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | Voegt een nieuwe placeholder toe als er geen is en stelt de placeholder-eigenschappen in op een opgegeven. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Bootst C#-stijl zwevende-komma vergelijking na waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Bootst C#-stijl zwevende-komma vergelijking na waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() override | Retourneert collecties van alle knooppunten in het [SmartArt](./) object. Alleen-lezen [ISmartArtNodeCollection](../ismartartnodecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | Retourneert de alternatieve tekst geassocieerd met een vorm. Alleen-lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | Retourneert de titel van de alternatieve tekst geassocieerd met een vorm. Alleen-lezen [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemode.. Alleen-lezen [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() override | Retourneert kleurstijl van [SmartArt](./) object. Alleen-lezen [SmartArtColorType](../smartartcolortype/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | Retourneert het aantal verbindingspunten op de vorm. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [ICustomData](../../aspose.slides/icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | Retourneert het [EffectFormat](../../aspose.slides/effectformat/) object dat pixel-effecten bevat die op een vorm zijn toegepast. Opmerking: kan null retourneren voor bepaalde vormen die geen effecteigenschappen hebben. Alleen-lezen [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | Retourneert het [FillFormat](../../aspose.slides/fillformat/) object dat opvulopmaakeigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen opvuleigenschappen hebben. Alleen-lezen [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | Retourneert de eigenschappen van het vormframe. Alleen-lezen [IShapeFrame](../../aspose.slides/ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | Retourneert de vergrendelingen van de vorm. Alleen-lezen [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | Haalt de hoogte van de vorm op, gemeten in punten. Alleen-lezen **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | Bepaalt of de vorm verborgen is. Alleen-lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | Retourneert de hyperlink gedefinieerd voor muisklik. Alleen-lezen [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | Retourneert de hyperlinkmanager. Alleen-lezen [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | Retourneert de hyperlink gedefinieerd voor muisover. Alleen-lezen [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | Haalt de 'Mark as decorative' optie op. Lezen/schrijven **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | Bepaalt of de vorm gegroepeerd is. Alleen-lezen **bool**. |
| **bool** [get_IsReversed](./get_isreversed/)() override | Retourneert of stelt de toestand van het [SmartArt](./) diagram in met betrekking tot (van links naar rechts) LTR of (van rechts naar links) RTL, indien het diagram omkering ondersteunt. Alleen-lezen **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen **bool**. |
| [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() override | Retourneert de lay-out van het [SmartArt](./) object. Alleen-lezen [SmartArtLayoutType](../smartartlayouttype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | Retourneert het [LineFormat](../../aspose.slides/lineformat/) object dat lijnopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen lijn-eigenschappen hebben. Alleen-lezen [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | Retourneert de naam van een vorm. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Alleen-lezen [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) override | Retourneert een knooppunt uit de collectie van wortelknooppunten in [SmartArt](./) object op de opgegeven index. Alleen-lezen [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) override | Retourneert een knooppunt uit de collectie met alle knooppunten in [SmartArt](./) object op de opgegeven index. Alleen-lezen [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() override | Retourneert collecties van wortelknooppunten in [SmartArt](./) object. Alleen-lezen [ISmartArtNodeCollection](../ismartartnodecollection/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | Retourneert een dia-specifieke unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanaf elk punt in het document. Alleen-lezen **uint32_t**. Zie ook [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | Retourneert het bovenliggende [GroupShape](../../aspose.slides/groupshape/) object als de vorm gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | Retourneert de placeholder voor een vorm. Retourneert null als de vorm geen placeholder heeft. Alleen-lezen [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | Retourneert de bovenliggende presentatie van een dia. Alleen-lezen [IPresentation](../../aspose.slides/ipresentation/). |
| [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() override | Retourneert de snelle stijl van [SmartArt](./) object. Alleen-lezen [SmartArtQuickStyleType](../smartartquickstyletype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | Retourneert de ruwe vormframe-eigenschappen. Alleen-lezen [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | Retourneert het aantal graden waarmee de opgegeven vorm rond de z-as is geroteerd. Een positieve waarde duidt op een rotatie met de klok mee; een negatieve waarde duidt op een rotatie tegen de klok in. Alleen-lezen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | Retourneert de vergrendelingen van de vorm. Alleen-lezen [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | Retourneert de bovenliggende dia van een vorm. Alleen-lezen [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | Retourneert het [ThreeDFormat](../../aspose.slides/threedformat/) object dat 3D-effecteigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen 3D-eigenschappen hebben. Alleen-lezen [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | Retourneert een interne, presentatie-specifieke identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden herkend, mag deze niet worden behandeld als een blijvende unieke sleutel. Alleen-lezen **uint32_t**. Zie ook [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | Haalt de breedte van de vorm op, gemeten in punten. Alleen-lezen **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | Haalt de x-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. Alleen-lezen **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | Haalt de y-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. Alleen-lezen **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | Retourneert de positie van een vorm in de z-volgorde. Shapes[0] retourneert de vorm achterin de z-volgorde, en Shapes[Shapes.Count - 1] retourneert de vorm voorin de z-volgorde. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | Retourneert een basis placeholder-vorm (vorm van de lay-out en/of masterdia waarvan de huidige vorm is geërfd). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Stelt hashing van aangepaste objecten in staat. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | Retourneert miniatuur van vorm. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) vorm-miniatuurbereikstype wordt standaard gebruikt. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | Retourneert miniatuur van vorm. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | Haalt de visuele begrenzing van de vorm op, berekend vanuit de gerenderde inhoud. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type beschreven door targetType is. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentinel-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Stelt klonen van aangepaste types in staat. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, initialiseert enkel een nieuw object en stelt kopie-construeren van subklassen in staat. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert enkel een nieuw object en stelt kopie-construeren van subklassen in staat. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de gespecificeerde waarde. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | Definieert dat deze vorm geen placeholder is. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | Stelt de alternatieve tekst in die aan een vorm is gekoppeld. Schrijf [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Schrijf [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit modus.. Schrijf [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) override | Stelt de kleurstijl van [SmartArt](./) object in. Schrijf [SmartArtColorType](../smartartcolortype/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Stelt de eigenschappen van het vormframe in. Schrijf [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | Stelt de hoogte van de vorm in, gemeten in punten. Schrijf **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | Bepaalt of de vorm verborgen is. Schrijf **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Stelt de hyperlink in die gedefinieerd is voor muisklik. Schrijf [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Stelt de hyperlink in die gedefinieerd is voor muisover. Schrijf [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | Stelt 'Mark as decorative' optie in. Lezen/schrijven **bool**. |
| void [set_IsReversed](./set_isreversed/)(**bool**) override | Retourneert of stelt de status van het [SmartArt](./) diagram in met betrekking tot (van links naar rechts) LTR of (van rechts naar links) RTL, indien het diagram omkering ondersteunt. Schrijf **bool**. |
| void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) override | Stelt de lay-out van het [SmartArt](./) object in. Schrijf [SmartArtLayoutType](../smartartlayouttype/). |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | Stelt de naam van een vorm in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Schrijf [System::String](../../system/string/). |
| void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) override | Stelt de snelle stijl van [SmartArt](./) object in. Schrijf [SmartArtQuickStyleType](../smartartquickstyletype/). |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Stelt de ruwe vormframe-eigenschappen in. Schrijf [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | Stelt het aantal graden in waarmee de opgegeven vorm rond de z-as is geroteerd. Een positieve waarde duidt op rotatie met de klok mee; een negatieve waarde duidt op rotatie tegen de klok in. Schrijf **float**. |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | Stelt de breedte van de vorm in, gemeten in punten. Schrijf **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | Stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Schrijf **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | Stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Schrijf **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeelde). Staat het wisselen van pointers in containers naar zwakke modus toe. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Stelt omzetten van aangepaste objecten naar string in staat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentinel-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Slaat de inhoud van [Shape](../../aspose.slides/shape/) op als SVG-bestand. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Slaat de inhoud van [Shape](../../aspose.slides/shape/) op als SVG-bestand. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijgeeft alle interne gegevensstructuren. |

## Zie ook

* Klasse [GraphicalObject](../../aspose.slides/graphicalobject/)
* Klasse [ISmartArt](../ismartart/)
* Namespace [Aspose::Slides::SmartArt](../)
* Library [Aspose.Slides](../../)