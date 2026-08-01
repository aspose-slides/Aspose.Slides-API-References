---
title: ISmartArt
second_title: Aspose.Slides voor C++ API Referentie
description: Stelt een SmartArt-diagram voor.
type: docs
weight: 1
url: /nl/aspose.slides.smartart/ismartart/
---
## ISmartArt klasse

Stelt een [SmartArt](../smartart/) diagram voor.

```cpp
class ISmartArt : public virtual Aspose::Slides::IGraphicalObject
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | Voegt een nieuwe placeholder toe als er geen is en stelt de placeholder-eigenschappen in op een opgegeven. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-komma vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-komma vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() | Retourneert collecties van alle knooppunten in [SmartArt](../smartart/) object. Alleen-lezen [ISmartArtNodeCollection](../ismartartnodecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | Retourneert de alternatieve tekst gekoppeld aan een vorm. Lezen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | Retourneert de titel van de alternatieve tekst gekoppeld aan een vorm. Lezen [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | Eigenschap bepaalt hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() | Retourneer of stel de kleurstijl in van het [SmartArt](../smartart/) object. Lezen [SmartArtColorType](../smartartcolortype/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | Retourneert het aantal verbindingspunten op de vorm. Alleen-lezen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | Retourneert het [EffectFormat](../../aspose.slides/effectformat/) object dat pixel-effecten bevat die op een vorm zijn toegepast. Alleen-lezen [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | Retourneert het [FillFormat](../../aspose.slides/fillformat/) object dat vulopmaak-eigenschappen voor een vorm bevat. Alleen-lezen [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | Retourneert de eigenschappen van het vorm-frame. Lezen [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | Retourneert de vergrendelingen van de vorm. Alleen-lezen [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | Haalt de hoogte van de vorm op, gemeten in punten. Lezen **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | Bepaalt of de vorm verborgen is. Lezen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | Retourneert de hyperlink gedefinieerd voor muisklik. Lezen [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlinks-beheer Alleen-lezen [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | Retourneert de hyperlink gedefinieerd voor muis-over. Lezen [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | Haalt de 'Mark as decorative'-optie op. Lezen/schrijven **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | Bepaalt of de vorm gegroepeerd is. Alleen-lezen **bool**. |
| virtual **bool** [get_IsReversed](./get_isreversed/)() | Retourneer of stel de status van het [SmartArt](../smartart/) diagram in ten aanzien van (links-naar-rechts) LTR of (rechts-naar-links) RTL, indien het diagram omkeren ondersteunt. Lezen **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | Bepaalt of de vorm een TextHolder is. Alleen-lezen **bool**. |
| virtual [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() | Retourneer of stel de lay-out in van het [SmartArt](../smartart/) object. Lezen [SmartArtLayoutType](../smartartlayouttype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | Retourneert het [LineFormat](../../aspose.slides/lineformat/) object dat lijn-opmaak-eigenschappen voor een vorm bevat. Alleen-lezen [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | Retourneert de naam van een vorm. Lezen [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) | Retourneert een knooppunt uit de collectie van wortelknooppunten in [SmartArt](../smartart/) object op de opgegeven index. Alleen-lezen [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) | Retourneert een knooppunt uit de collectie met alle knooppunten in [SmartArt](../smartart/) object op de opgegeven index. Alleen-lezen [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() | Retourneert collecties van wortelknooppunten in [SmartArt](../smartart/) object. Alleen-lezen [ISmartArtNodeCollection](../ismartartnodecollection/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | Retourneert een uniek identifier binnen de dia die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen **uint32_t**. Zie ook [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | Retourneert het bovenliggende [GroupShape](../../aspose.slides/groupshape/) object als de vorm gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | Retourneert de placeholder voor een vorm. Alleen-lezen [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retourneert de presentatie. Alleen-lezen [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() | Retourneer of stel de snelle stijl in van het [SmartArt](../smartart/) object. Lezen [SmartArtQuickStyleType](../smartartquickstyletype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | Retourneert de ruwe vorm-frame-eigenschappen. Lezen [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | Retourneert het aantal graden waarmee de opgegeven vorm om de z-as is geroteerd. Een positieve waarde duidt een klokrichting rotatie aan; een negatieve waarde duidt een tegen-klokrichting rotatie aan. Lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | Retourneert de vergrendelingen van de vorm. Alleen-lezen [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retourneert de basisdia. Alleen-lezen [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | Retourneert het [ThreeDFormat](../../aspose.slides/threedformat/) object dat lijn-opmaak-eigenschappen voor een vorm bevat. Alleen-lezen [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | Retourneert een interne, presentatie-gescopeerde identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden hertoegewezen, mag deze niet worden beschouwd als een permanente unieke sleutel. Alleen-lezen **uint32_t**. Zie ook [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | Haalt de breedte van de vorm op, gemeten in punten. Lezen **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | Haalt de x-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. Lezen **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | Haalt de y-coördinaat van de linkerbovenhoek van de vorm op, gemeten in punten. Lezen **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | Retourneert de positie van een vorm in de z-volgorde. Shapes[0] retourneert de vorm achterin de z-volgorde, en Shapes[Shapes.Count - 1] retourneert de vorm voorin de z-volgorde. Alleen-lezen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | Retourneert een basis-placeholder-vorm (vorm van de lay-out en/of masterslide waarvan de huidige vorm is geërfd). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Stelt hashing van aangepaste objecten mogelijk. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | Retourneert miniatuur van de vorm. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) vorm-miniatuurboundstype wordt standaard gebruikt. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | Retourneert miniatuur van de vorm. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Stelt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en stelt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en stelt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert het gedeelde referentieteller met de opgegeven waarde. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | Definieert dat deze vorm geen placeholder is. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | Stelt de alternatieve tekst in die aan een vorm gekoppeld is. Schrijven [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Stelt de titel van de alternatieve tekst in die aan een vorm gekoppeld is. Schrijven [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | Eigenschap bepaalt hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Schrijven [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) | Retourneer of stel de kleurstijl in van het [SmartArt](../smartart/) object. Schrijven [SmartArtColorType](../smartartcolortype/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Stelt de eigenschappen van het vorm-frame in. Schrijven [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | Stelt de hoogte van de vorm in, gemeten in punten. Schrijven **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | Bepaalt of de vorm verborgen is. Schrijven **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Stelt de hyperlink in die gedefinieerd is voor muisklik. Schrijven [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Stelt de hyperlink in die gedefinieerd is voor muis-over. Schrijven [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | Stelt de optie 'Mark as decorative' in. Lezen/schrijven **bool**. |
| virtual void [set_IsReversed](./set_isreversed/)(**bool**) | Retourneer of stel de status van het [SmartArt](../smartart/) diagram in ten aanzien van (links-naar-rechts) LTR of (rechts-naar-links) RTL, indien het diagram omkeren ondersteunt. Schrijven **bool**. |
| virtual void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) | Retourneer of stel de lay-out in van het [SmartArt](../smartart/) object. Schrijven [SmartArtLayoutType](../smartartlayouttype/). |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | Stelt de naam van een vorm in. Schrijven [System::String](../../system/string/). |
| virtual void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) | Retourneer of stel de snelle stijl in van het [SmartArt](../smartart/) object. Schrijven [SmartArtQuickStyleType](../smartartquickstyletype/). |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Stelt de ruwe vorm-frame-eigenschappen in. Schrijven [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | Stelt het aantal graden in waarmee de opgegeven vorm om de z-as is geroteerd. Een positieve waarde duidt een klokrichting rotatie aan; een negatieve waarde duidt een tegen-klokrichting rotatie aan. Schrijven **float**. |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | Stelt de breedte van de vorm in, gemeten in punten. Schrijven **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | Stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Schrijven **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | Stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Schrijven **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th template-argument in als een zwakke pointer (in plaats van gedeeld). Stelt om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Stelt omzetten van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Slaat de inhoud van [Shape](../../aspose.slides/shape/) op als SVG-bestand. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Slaat de inhoud van [Shape](../../aspose.slides/shape/) op als SVG-bestand. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* Namespace [Aspose::Slides::SmartArt](../)
* Bibliotheek [Aspose.Slides](../../)