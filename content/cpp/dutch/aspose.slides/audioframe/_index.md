---
title: AudioFrame
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een audiofragment op een dia voor.
type: docs
weight: 53
url: /nl/aspose.slides/audioframe/
---
## AudioFrame klasse


Represents an audio clip on a slide.

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Voegt een nieuwe placeholder toe als er geen is en stelt placeholder-eigenschappen in op een opgegeven. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Creëert en retourneert een array van shape-elementen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommavergelijking waarbij twee NaN’s als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommavergelijking waarbij twee NaN’s als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Retourneert de aanpassingswaarde van een shape op de opgegeven index. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Retourneert een collectie van aanpassingswaarden van een shape. Alleen-lezen [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Retourneert de alternatieve tekst die aan een shape is gekoppeld. Lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Retourneert de titel van de alternatieve tekst die aan een shape is gekoppeld. Lezen [System::String](../../system/string/). |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | Retourneert een laatste track-index. Lezen **int32_t**. |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | Retourneert een laatste track-tijd. Lezen **int32_t**. |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | Retourneert een start track-index. Lezen **int32_t**. |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | Retourneert een start track-tijd. Lezen **int32_t**. |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Eigenschap geeft aan hoe een shape wordt weergegeven in zwart-wit weergavemodus. Lezen [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | Haalt de collectie gesloten ondertitels op die bij het audioframe horen. Deze eigenschap is alleen-lezen en retourneert een [ICaptionsCollection](../icaptionscollection/) met alle ondertitelingstracks. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Retourneert het aantal verbindingspunten op de shape. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Retourneert de aangepaste gegevens van de shape. Alleen-lezen [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Retourneert het [EffectFormat](../effectformat/)-object dat pixel-effecten bevat die op een shape zijn toegepast. Opmerking: kan null retourneren voor bepaalde shape-types die geen effecteigenschappen hebben. Alleen-lezen [IEffectFormat](../ieffectformat/). |
| **bool** [get_Embedded](./get_embedded/)() override | Bepaalt of een geluid is ingebed in een presentatie. Alleen-lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | Retourneert ingebed audio-object. Lezen [IAudio](../iaudio/). |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. Lezen **float**. |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | Specificeert de tijdsduur voor de einde fade-out van de media in milliseconden. Lezen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Retourneert het [FillFormat](../fillformat/)-object dat opvulopmaak-eigenschappen voor een shape bevat. Opmerking: kan null retourneren voor bepaalde shape-types die geen opvul-eigenschappen hebben. Alleen-lezen [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Retourneert de eigenschappen van het shape-frame. Lezen [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Haalt de hoogte van de shape op, gemeten in punten. Lezen **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Bepaalt of de shape verborgen is. Lezen **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | Bepaalt of een [AudioFrame](./) verborgen is. Lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Retourneert de hyperlink die is gedefinieerd voor muisklik. Lezen [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Retourneert de hyperlink-beheerder. Alleen-lezen [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Retourneert de hyperlink die is gedefinieerd voor muis-over. Lezen [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | Bepaalt of de [PictureFrame](../pictureframe/) een Cameo-object is of niet. Alleen-lezen **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Haalt de optie ‘Mark as decorative’ op. Lezen/schrijven **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Bepaalt of de shape gegroepeerd is. Alleen-lezen **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Bepaalt of de shape TextHolder_PPT is. Alleen-lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Retourneert het [LineFormat](../lineformat/)-object dat lijnopmaak-eigenschappen voor een shape bevat. Opmerking: kan null retourneren voor bepaalde shape-types die geen lijn-eigenschappen hebben. Alleen-lezen [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Retourneert de naam van een audiobestand dat is gekoppeld aan een [AudioFrame](./). Lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Retourneert de naam van een shape. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Lezen [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Retourneert een uniëk identifier binnen de dia, dat constant blijft gedurende de levensduur van de shape en PowerPoint of interop-code in staat stelt de shape betrouwbaar te refereren vanuit elke plaats in het document. Alleen-lezen **uint32_t**. Zie ook [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Retourneert het bovenliggende [GroupShape](../groupshape/)-object als de shape gegroepeerd is. Anders null. Alleen-lezen [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | Retourneert het [PictureFillFormat](../picturefillformat/)-object voor een afbeeldingsframe. Alleen-lezen [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | Retourneert de vergrendelingen van de shape. Alleen-lezen [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Retourneert de placeholder voor een shape. Retourneert null als de shape geen placeholder heeft. Alleen-lezen [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | Bepaalt of audio over de dia’s heen wordt afgespeeld. Lezen **bool**. |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | Bepaalt of een audio wordt herhaald. Lezen **bool**. |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | Retourneert de audio-afspeelmodus. Lezen [AudioPlayModePreset](../audioplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Retourneert de bovenliggende presentatie van een dia. Alleen-lezen [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Retourneert de ruwe eigenschappen van het shape-frame. Lezen [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | Retourneert de schaal van de hoogte (relatief aan de originele afbeeldingsgrootte) van het afbeeldingsframe. Waarde 1.0 komt overeen met 100%. Lezen **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | Retourneert de schaal van de breedte (relatief aan de originele afbeeldingsgrootte) van het afbeeldingsframe. Waarde 1.0 komt overeen met 100%. Lezen **float**. |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | Bepaalt of audio automatisch naar het begin wordt teruggespoeld na het afspelen. Lezen **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Retourneert het aantal graden waarmee de opgegeven shape om de z-as is geroteerd. Een positieve waarde duidt op rotatie met de klok mee; een negatieve waarde duidt op rotatie tegen de klok in. Lezen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Retourneert de vergrendelingen van de shape. Alleen-lezen [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Retourneert het stijlobject van de shape. Alleen-lezen [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Retourneert de bovenliggende dia van een shape. Alleen-lezen [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Retourneert het [ThreeDFormat](../threedformat/)-object dat 3D-effecteigenschappen voor een shape bevat. Opmerking: kan null retourneren voor bepaalde shape-types die geen 3D-eigenschappen hebben. Alleen-lezen [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | Specificeert de tijdsduur die van het einde van de media wordt verwijderd tijdens afspelen, in milliseconden. Lezen **float**. |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | Specificeert de tijdsduur die van het begin van de media wordt verwijderd tijdens afspelen, in milliseconden. Lezen **float**. |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Retourneert een interne, presentatie-bepaalde identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde kan worden her-toegewezen door de gebruiker of programmatisch, mag deze niet worden behandeld als een permanente unieke sleutel. Alleen-lezen **uint32_t**. Zie ook [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | Retourneert het audiovolume. Lezen [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_VolumeValue](./get_volumevalue/)() override | Retourneert het audiovolume in procenten. Lezen **float**. |
| **float** [get_Width](../shape/get_width/)() override | Haalt de breedte van de shape op, gemeten in punten. Lezen **float**. |
| **float** [get_X](../shape/get_x/)() override | Haalt de x-coördinaat van de linkerbovenhoek van de shape op, gemeten in punten. Lezen **float**. |
| **float** [get_Y](../shape/get_y/)() override | Haalt de y-coördinaat van de linkerbovenhoek van de shape op, gemeten in punten. Lezen **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Retourneert de positie van een shape in de z-volgorde. Shapes[0] retourneert de shape aan de achterkant van de z-volgorde, en Shapes[Shapes.Count - 1] retourneert de shape aan de voorkant van de z-volgorde. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Retourneert een basis placeholder-shape (shape van de lay-out en/of masterdia waarvan de huidige shape is geërfd). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Retourneert een kopie van het pad van de geometrische shape. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de shape. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Retourneert miniatuur van shape. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) shape thumbnail bounds type wordt standaard gebruikt. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Retourneert miniatuur van shape. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Haalt de visuele grenzen van de shape op, berekend uit de gerenderde inhoud. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analoge van C# ‘is’-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentinel-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object via referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definieert dat deze shape geen placeholder is. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Stelt de alternatieve tekst in die aan een shape is gekoppeld. Schrijf [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Stelt de titel van de alternatieve tekst in die aan een shape is gekoppeld. Schrijf [System::String](../../system/string/). |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | Stelt een laatste track-index in. Schrijf **int32_t**. |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | Stelt een laatste track-tijd in. Schrijf **int32_t**. |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | Stelt een start track-index in. Schrijf **int32_t**. |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | Stelt een start track-tijd in. Schrijf **int32_t**. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Eigenschap geeft aan hoe een shape wordt weergegeven in zwart-wit weergavemodus. Schrijf [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Stelt een ingebed audio-object in. Schrijf [IAudio](../iaudio/). |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | Specificeert de tijdsduur voor de initiële fade-in van de media in milliseconden. Schrijf **float**. |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | Specificeert de tijdsduur voor de eind-fade-out van de media in milliseconden. Schrijf **float**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Stelt de eigenschappen van het shape-frame in. Schrijf [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Stelt de hoogte van de shape in, gemeten in punten. Schrijf **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Bepaalt of de shape verborgen is. Schrijf **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | Bepaalt of een [AudioFrame](./) verborgen is. Schrijf **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Stelt de hyperlink in die is gedefinieerd voor muisklik. Schrijf [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Stelt de hyperlink in die is gedefinieerd voor muis-over. Schrijf [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Stelt de optie ‘Mark as decorative’ in. Lezen/schrijven **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Stelt de naam van een audiobestand in dat is gekoppeld aan een [AudioFrame](./). Schrijf [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Stelt de naam van een shape in. Mag niet null zijn. Gebruik een lege tekenreeks indien nodig. Schrijf [System::String](../../system/string/). |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | Bepaalt of audio over de dia’s heen wordt afgespeeld. Schrijf **bool**. |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | Bepaalt of een audio wordt herhaald. Schrijf **bool**. |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | Stelt de audio-afspeelmodus in. Schrijf [AudioPlayModePreset](../audioplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Stelt de ruwe eigenschappen van het shape-frame in. Schrijf [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | Stelt de schaal van de hoogte (relatief aan de originele afbeelding) van het frame in. Waarde 1.0 komt overeen met 100%. Schrijf **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | Stelt de schaal van de breedte (relatief aan de originele afbeelding) van het frame in. Waarde 1.0 komt overeen met 100%. Schrijf **float**. |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | Bepaalt of audio automatisch naar het begin wordt teruggespoeld na het afspelen. Schrijf **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Stelt het aantal graden in waarmee de opgegeven shape rond de z-as wordt geroteerd. Een positieve waarde duidt op rotatie met de klok mee; een negatieve waarde duidt op rotatie tegen de klok in. Schrijf **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | Specificeert de tijdsduur die van het einde van de media wordt verwijderd tijdens afspelen, in milliseconden. Schrijf **float**. |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | Specificeert de tijdsduur die van het begin van de media wordt verwijderd tijdens afspelen, in milliseconden. Schrijf **float**. |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | Stelt het audiovolume in. Schrijf [AudioVolumeMode](../audiovolumemode/). |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | Stelt het audiovolume in procenten in. Schrijf **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Stelt de breedte van de shape in, gemeten in punten. Schrijf **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Stelt de x-coördinaat van de linkerbovenhoek van de shape in, gemeten in punten. Schrijf **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Stelt de y-coördinaat van de linkerbovenhoek van de shape in, gemeten in punten. Schrijf **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Werkt de geometrie van de shape bij vanuit [IGeometryPath](../igeometrypath/)-object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de shape. Wijzigt het type van de shape ([ShapeType](../shapetype/)) naar [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Werkt de geometrie van de shape bij vanuit een array van [IGeometryPath](../igeometrypath/). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de shape. Wijzigt het type van de shape ([ShapeType](../shapetype/)) naar [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th template-argument in als een zwakke pointer (in plaats van gedeelde). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentinel-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Opmerkingen

De volgende voorbeelden laten zien hoe [Audio](../audio/) afspeelopties te wijzigen.
```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Haalt de AudioFrame-shape op
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Stelt de afspeelmodus in op afspelen bij klikken
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Stelt het volume in op Laag
audioFrame->set_Volume(AudioVolumeMode::Low);
// Stelt de audio in om over dia's heen te spelen
audioFrame->set_PlayAcrossSlides(true);
// Schakelt lus voor de audio uit
audioFrame->set_PlayLoopMode(false);
// Verbergt de AudioFrame tijdens de diavoorstelling
audioFrame->set_HideAtShowing(true);
// Spoelt de audio terug naar het begin na afspelen
audioFrame->set_RewindAudio(true);
// Slaat het PowerPoint-bestand op schijf
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [PictureFrame](../pictureframe/)
* Klasse [IAudioFrame](../iaudioframe/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)