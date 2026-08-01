---
title: PictureFrame
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een frame met een afbeelding voor.
type: docs
weight: 4733
url: /nl/aspose.slides/pictureframe/
---
## PictureFrame klasse

Stelt een frame met een afbeelding voor.

```cpp
class PictureFrame : public Aspose::Slides::GeometryShape,
                     public virtual Aspose::Slides::IPictureFrame
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Voegt een nieuwe placeholder toe als er geen is en stelt de placeholder-eigenschappen in op een opgegeven placeholder. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Maakt een array van vorm-elementen en retourneert deze. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-type objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert IEEE-flottant-vergelijking in C#-stijl waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert IEEE-flottant-vergelijking in C#-stijl waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Retourneert de aanpassingswaarde van een vorm op de opgegeven index. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Retourneert een collectie van aanpassingswaarden van een vorm. Alleen-lezen [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Retourneert de alternatieve tekst die aan een vorm is gekoppeld. Lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Retourneert de titel van de alternatieve tekst die aan een vorm is gekoppeld. Lezen [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit weergavemodus. Lezen [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Retourneert het aantal verbindingspunten op de vorm. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Retourneert de aangepaste gegevens van de vorm. Alleen-lezen [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Retourneert het [EffectFormat](../effectformat/)-object dat pixel-effecten op een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen effect-eigenschappen hebben. Alleen-lezen [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Retourneert het [FillFormat](../fillformat/)-object dat vulopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen vul-eigenschappen hebben. Alleen-lezen [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Retourneert de eigenschappen van het vorm-frame. Lezen [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Krijgt de hoogte van de vorm, gemeten in punten. Lezen **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Bepaalt of de vorm verborgen is. Lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Retourneert de hyperlink gedefinieerd voor muisklik. Lezen [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Retourneert de hyperlink-manager. Alleen-lezen [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Retourneert de hyperlink gedefinieerd voor muis-over. Lezen [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](./get_iscameo/)() | Bepaalt of de [PictureFrame](./) een Cameo-object is of niet. Alleen-lezen **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Krijgt de optie 'Mark as decorative'. Lezen/schrijven **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Bepaalt of de vorm gegroepeerd is. Alleen-lezen **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Bepaalt of de vorm TextHolder_PPT is. Alleen-lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Retourneert het [LineFormat](../lineformat/)-object dat lijstopmaak-eigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen lijn-eigenschappen hebben. Alleen-lezen [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Retourneert de naam van een vorm. Mag niet null zijn. Gebruik een lege-string indien nodig. Lezen [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Retourneert een dia-specifieke unieke identifier die constant blijft gedurende de levensduur van de vorm en PowerPoint of interop-code in staat stelt de vorm betrouwbaar te refereren vanaf elke plek in het document. Alleen-lezen **uint32_t**. Zie ook [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Retourneert het bovenliggende [GroupShape](../groupshape/)-object als de vorm gegroepeerd is. Anders retourneert het null. Alleen-lezen [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](./get_pictureformat/)() override | Retourneert het [PictureFillFormat](../picturefillformat/)-object voor een foto-frame. Alleen-lezen [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](./get_pictureframelock/)() override | Retourneert de vergrendelingen van de vorm. Alleen-lezen [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Retourneert de placeholder voor een vorm. Retourneert null als de vorm geen placeholder heeft. Alleen-lezen [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Retourneert de bovenliggende presentatie van een dia. Alleen-lezen [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Retourneert de ruwe eigenschappen van het vorm-frame. Lezen [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](./get_relativescaleheight/)() override | Retourneert de schaal van de hoogte (relatief ten opzichte van de oorspronkelijke afbeeldingsgrootte) van het foto-frame. Waarde 1,0 correspondeert met 100 %. Lezen **float**. |
| **float** [get_RelativeScaleWidth](./get_relativescalewidth/)() override | Retourneert de schaal van de breedte (relatief ten opzichte van de oorspronkelijke afbeeldingsgrootte) van het foto-frame. Waarde 1,0 correspondeert met 100 %. Lezen **float**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Retourneert het aantal graden waarmee de opgegeven vorm rond de z-as wordt gedraaid. Een positieve waarde duidt op een klokwijzer-rotatie; een negatieve waarde op een tegen-klokwijzer-rotatie. Lezen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Retourneert de vergrendelingen van de vorm. Alleen-lezen [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Retourneert het stijl-object van de vorm. Alleen-lezen [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Retourneert de bovenliggende dia van een vorm. Alleen-lezen [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Retourneert het [ThreeDFormat](../threedformat/)-object dat 3D-effecteigenschappen voor een vorm bevat. Opmerking: kan null retourneren voor bepaalde vormen die geen 3D-eigenschappen hebben. Alleen-lezen [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Retourneert een interne, presentatie-specifieke identifier die bedoeld is voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden heringesteld, mag deze niet worden behandeld als een permanente unieke sleutel. Alleen-lezen **uint32_t**. Zie ook [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Krijgt de breedte van de vorm, gemeten in punten. Lezen **float**. |
| **float** [get_X](../shape/get_x/)() override | Krijgt de x-coördinaat van de linkerbovenhoek van de vorm, gemeten in punten. Lezen **float**. |
| **float** [get_Y](../shape/get_y/)() override | Krijgt de y-coördinaat van de linkerbovenhoek van de vorm, gemeten in punten. Lezen **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Retourneert de positie van een vorm in de z-volgorde. Shapes[0] retourneert de vorm achteraan, en Shapes[Shapes.Count - 1] retourneert de vorm vooraan. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Retourneert een basale placeholder-vorm (vorm van de lay-out en/of master-dia waarvan de huidige vorm is geërfd). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Krijgt de referentieteller-datastructuur die bij het object hoort. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Retourneert een kopie van het pad van de geometrische vorm. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de vorm. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Retourneert een miniatuur van de vorm. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) miniatuur-grens-type wordt standaard gebruikt. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Retourneert een miniatuur van de vorm. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Krijgt het daadwerkelijke type van het object. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Krijgt de visuele grenzen van de vorm, berekend uit de gerenderde inhoud. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
| [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de deeltellingsreferentieteller met de opgegeven waarde. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definieert dat deze vorm geen placeholder is. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Stelt de alternatieve tekst in die aan een vorm is gekoppeld. Schrijf [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Stelt de titel van de alternatieve tekst in die aan een vorm is gekoppeld. Schrijf [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Eigenschap specificeert hoe een vorm wordt weergegeven in zwart-wit modus. Schrijf [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Stelt de eigenschappen van het vorm-frame in. Schrijf [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Stelt de hoogte van de vorm in, gemeten in punten. Schrijf **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Bepaalt of de vorm verborgen is. Schrijf **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Stelt de hyperlink in die voor muisklik is gedefinieerd. Schrijf [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Stelt de hyperlink in die voor muis-over is gedefinieerd. Schrijf [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Stelt de optie 'Mark as decorative' in. Schrijf **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Stelt de naam van een vorm in. Mag niet null zijn. Gebruik een lege string indien nodig. Schrijf [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Stelt de ruwe eigenschappen van het vorm-frame in. Schrijf [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](./set_relativescaleheight/)(**float**) override | Stelt de schaal van de hoogte (relatief tot originele afbeeldingsgrootte) in. Waarde 1,0 correspondeert met 100 %. Schrijf **float**. |
| void [set_RelativeScaleWidth](./set_relativescalewidth/)(**float**) override | Stelt de schaal van de breedte (relatief tot originele afbeeldingsgrootte) in. Waarde 1,0 correspondeert met 100 %. Schrijf **float**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Stelt het aantal graden in waarmee de opgegeven vorm rond de z-as wordt gedraaid. Een positieve waarde duidt op klokwijzer-rotatie; een negatieve waarde op tegen-klokwijzer-rotatie. Schrijf **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_Width](../shape/set_width/)(**float**) override | Stelt de breedte van de vorm in, gemeten in punten. Schrijf **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Stelt de x-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Schrijf **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Stelt de y-coördinaat van de linkerbovenhoek van de vorm in, gemeten in punten. Schrijf **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Werk de vormgeometrie bij vanaf [IGeometryPath](../igeometrypath/)-object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm. Verandert het type van de vorm ([ShapeType](../shapetype/)) naar [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Werk de vormgeometrie bij vanaf een array van [IGeometryPath](../igeometrypath/). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm. Verandert het type van de vorm ([ShapeType](../shapetype/)) naar [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloon-argument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Krijgt de huidige waarde van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Opmerkingen

De volgende voorbeelden tonen hoe [Audio](../audio/) Frame Thumbnail te wijzigen.

```cpp
auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Voegt een audioframe toe aan de dia met een opgegeven positie en grootte.
auto audioStream = System::MakeObject<System::IO::FileStream>(u"sample2.mp3", System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(150.0f, 100.0f, 50.0f, 50.0f, audioStream);
audioStream->Dispose();

// Voegt een afbeelding toe aan de presentatieresources.
auto imageStream = System::IO::File::OpenRead(u"eagle.jpeg");
auto audioImage = presentation->get_Images()->AddImage(imageStream);
imageStream->Dispose();

// Stelt de afbeelding in voor het audioframe.
audioFrame->get_PictureFormat()->get_Picture()->set_Image(audioImage);

//Slaat de gewijzigde presentatie op naar schijf
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [GeometryShape](../geometryshape/)
* Klasse [IPictureFrame](../ipictureframe/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)