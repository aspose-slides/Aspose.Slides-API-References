---
title: IAudioFrame
second_title: Aspose.Slides voor C++ API-referentie
description: Representeert een audiofragment op een dia.
type: docs
weight: 1353
url: /nl/aspose.slides/iaudioframe/
---
## IAudioFrame klasse

Stelt een audiofragment op een dia voor.

```cpp
class IAudioFrame : public virtual Aspose::Slides::IPictureFrame
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Voegt een nieuwe placeholder toe als er geen is en stelt de placeholder-eigenschappen in op een opgegeven placeholder. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Maakt een array van shape-elementen aan en retourneert deze. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl drijvende-kommagetalvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl drijvende-kommagetalvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Retourneert de aanpassingswaarde van een shape op de opgegeven index. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Retourneert een verzameling aanpassingswaarden van een shape. Alleen-lezen [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Retourneert de alternatieve tekst die aan een shape is gekoppeld. Lezen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Retourneert de titel van de alternatieve tekst die aan een shape is gekoppeld. Lezen [System::String](../../system/string/). |
| virtual **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() | Retourneert een laatste track-index. Lezen **int32_t**. |
| virtual **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() | Retourneert een laatste track-tijd. Lezen **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() | Retourneert een start-track-index. Lezen **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() | Retourneert een start-track-tijd. Lezen **int32_t**. |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Eigenschap specificeert hoe een shape wordt weergegeven in zwart-wit weergavemodus. Lezen [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | Haalt de verzameling gesloten ondertitels op die bij het audio-frame horen. Deze eigenschap is alleen-lezen en retourneert een [ICaptionsCollection](../icaptionscollection/) met alle ondertitel-tracks. |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Retourneert het aantal verbindingspunten op de shape. Alleen-lezen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Retourneert de aangepaste gegevens van de shape. Alleen-lezen [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Retourneert het [EffectFormat](../effectformat/)-object dat pixel-effecten bevat die op een shape zijn toegepast. Alleen-lezen [IEffectFormat](../ieffectformat/). |
| virtual **bool** [get_Embedded](./get_embedded/)() | Bepaalt of een geluid is ingebed in een presentatie. Alleen-lezen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() | Retourneert het ingebedde audio-object. Lezen [IAudio](../iaudio/). |
| virtual **float** [get_FadeInDuration](./get_fadeinduration/)() | Specificeert de tijdsduur van de initiële fade-in van de media in milliseconden. Lezen **float**. |
| virtual **float** [get_FadeOutDuration](./get_fadeoutduration/)() | Specificeert de tijdsduur van de eindfade-out van de media in milliseconden. Lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Retourneert het [FillFormat](../fillformat/)-object dat opvulopmaak-eigenschappen voor een shape bevat. Alleen-lezen [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Retourneert de eigenschappen van het shape-frame. Lezen [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Haalt de hoogte van de shape op, gemeten in points. Lezen **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Bepaalt of de shape verborgen is. Lezen **bool**. |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | Bepaalt of een [AudioFrame](../audioframe/) verborgen is. Lezen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Retourneert de hyperlink die is gedefinieerd voor muisklik. Lezen [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlinks-manager Alleen-lezen [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Retourneert de hyperlink die is gedefinieerd voor muis-over. Lezen [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Haalt de 'Mark as decorative'-optie op. Lezen/Schrijven **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Bepaalt of de shape gegroepeerd is. Alleen-lezen **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Bepaalt of de shape een TextHolder is. Alleen-lezen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Retourneert het [LineFormat](../lineformat/)-object dat lijnopmaak-eigenschappen voor een shape bevat. Alleen-lezen [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | Retourneert de naam van een audiobestand dat gekoppeld is aan een [AudioFrame](../audioframe/). Lezen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Retourneert de naam van een shape. Lezen [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Retourneert een uniek identificatienummer binnen de dia dat constant blijft gedurende de levensduur van de shape en PowerPoint of interop-code in staat stelt de shape betrouwbaar te refereren vanuit elk deel van het document. Alleen-lezen **uint32_t**. Zie ook [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Retourneert het bovenliggende [GroupShape](../groupshape/)-object als de shape gegroepeerd is. Anders wordt null geretourneerd. Alleen-lezen [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | Retourneert het [PictureFillFormat](../picturefillformat/)-object voor een picture-frame. Alleen-lezen [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | Retourneert de vergrendelingen van [PictureFrame](../pictureframe/). Alleen-lezen [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Retourneert de placeholder voor een shape. Alleen-lezen [IPlaceholder](../iplaceholder/). |
| virtual **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() | Bepaalt of een audio wordt afgespeeld over de dia's. Lezen **bool**. |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | Bepaalt of een audio in een lus wordt afgespeeld. Lezen **bool**. |
| virtual [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() | Retourneert de afspeelmodus voor audio. Lezen [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Retourneert de presentatie. Alleen-lezen [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Retourneert de ruwe shape-frame-eigenschappen. Lezen [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | Retourneert de schaal van de hoogte (relatief ten opzichte van de originele afbeeldingsgrootte) van het picture-frame. Waarde 1.0 komt overeen met 100 %. Lezen **float**. |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | Retourneert de schaal van de breedte (relatief ten opzichte van de originele afbeeldingsgrootte) van het picture-frame. Waarde 1.0 komt overeen met 100 %. Lezen **float**. |
| virtual **bool** [get_RewindAudio](./get_rewindaudio/)() | Bepaalt of een audio automatisch wordt teruggespoeld naar het begin na het afspelen. Lezen **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Retourneert het aantal graden waarmee de opgegeven shape rond de z-as is gedraaid. Een positieve waarde duidt op een klokwijzerrotatie; een negatieve waarde duidt op een tegenwijzerrotatie. Lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Retourneert de vergrendelingen van de shape. Alleen-lezen [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Retourneert het stijlobject van de shape. Alleen-lezen [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Retourneert het vooraf gedefinieerde geometrie-type. Opmerking: bij wijziging van de waarde worden alle aanpassingswaarden teruggezet naar hun standaardwaarden. Lezen [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Retourneert de basisslide. Alleen-lezen [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Retourneert het [ThreeDFormat](../threedformat/)-object dat lijnopmaak-eigenschappen voor een shape bevat. Alleen-lezen [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | Specificeert de tijdsduur die aan het einde van de media wordt weggelaten tijdens het afspelen, in milliseconden. Lezen **float**. |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | Specificeert de tijdsduur die aan het begin van de media wordt weggelaten tijdens het afspelen, in milliseconden. Lezen **float**. |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Retourneert een interne, presentatie-specifieke identifier bedoeld voor gebruik door add-ins of andere code. Omdat deze waarde door de gebruiker of programmatisch kan worden hertoegewezen, mag deze niet worden behandeld als een blijvende unieke sleutel. Alleen-lezen **uint32_t**. Zie ook [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | Retourneert het audiovolume. Lezen [AudioVolumeMode](../audiovolumemode/). |
| virtual **float** [get_VolumeValue](./get_volumevalue/)() | Retourneert het audiovolume in percentages. Lezen **float**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Haalt de breedte van de shape op, gemeten in points. Lezen **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Haalt de x-coördinaat van de linkerbovenhoek van de shape op, gemeten in points. Lezen **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Haalt de y-coördinaat van de linkerbovenhoek van de shape op, gemeten in points. Lezen **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Retourneert de positie van een shape in de z-volgorde. Shapes[0] retourneert de shape achteraan in de z-volgorde, en Shapes[Shapes.Count - 1] retourneert de shape vooraan in de z-volgorde. Alleen-lezen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Retourneert een basis-placeholder-shape (shape van de lay-out en/of master-slide waarvan de huidige shape is geërfd). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Retourneert een kopie van het pad van de geometrie-shape. Coördinaten zijn relatief ten opzichte van de linkerbovenhoek van de shape. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Retourneert een miniatuur van de shape. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) shape thumbnail bounds type wordt standaard gebruikt. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Retourneert een miniatuur van de shape. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analog van de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert in feite niets, initialiseert slechts een nieuw object en maakt kopiëren van afgeleide klassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert in feite niets, initialiseert slechts een nieuw object en maakt kopiëren van afgeleide klassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr per referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Definieert dat deze shape geen placeholder is. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Stelt de alternatieve tekst in die aan een shape is gekoppeld. Schrijven [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Stelt de titel van de alternatieve tekst in die aan een shape is gekoppeld. Schrijven [System::String](../../system/string/). |
| virtual void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) | Stelt een laatste track-index in. Schrijven **int32_t**. |
| virtual void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) | Stelt een laatste track-tijd in. Schrijven **int32_t**. |
| virtual void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) | Stelt een start-track-index in. Schrijven **int32_t**. |
| virtual void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) | Stelt een start-track-tijd in. Schrijven **int32_t**. |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Eigenschap specificeert hoe een shape wordt weergegeven in zwart-wit weergavemodus. Schrijven [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Stelt het ingebedde audio-object in. Schrijven [IAudio](../iaudio/). |
| virtual void [set_FadeInDuration](./set_fadeinduration/)(**float**) | Specificeert de tijdsduur van de initiële fade-in van de media in milliseconden. Schrijven **float**. |
| virtual void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) | Specificeert de tijdsduur van de eind-fade-out van de media in milliseconden. Schrijven **float**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Stelt de eigenschappen van het shape-frame in. Schrijven [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Stelt de hoogte van de shape in, gemeten in points. Schrijven **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Bepaalt of de shape verborgen is. Schrijven **bool**. |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | Bepaalt of een [AudioFrame](../audioframe/) verborgen is. Schrijven **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Stelt de hyperlink in die is gedefinieerd voor muisklik. Schrijven [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Stelt de hyperlink in die is gedefinieerd voor muis-over. Schrijven [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Stelt de 'Mark as decorative'-optie in. Lezen/Schrijven **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | Stelt de naam van een audiobestand in dat is gekoppeld aan een [AudioFrame](../audioframe/). Schrijven [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Stelt de naam van een shape in. Schrijven [System::String](../../system/string/). |
| virtual void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) | Bepaalt of een audio over de dia's wordt afgespeeld. Schrijven **bool**. |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | Bepaalt of een audio in een lus wordt afgespeeld. Schrijven **bool**. |
| virtual void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) | Stelt de afspeelmodus voor audio in. Schrijven [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Stelt de ruwe shape-frame-eigenschappen in. Schrijven [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | Stelt de schaal van de hoogte (relatief ten opzichte van de originele afbeeldingsgrootte) van het picture-frame in. Waarde 1.0 komt overeen met 100 %. Schrijven **float**. |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | Stelt de schaal van de breedte (relatief ten opzichte van de originele afbeeldingsgrootte) van het picture-frame in. Waarde 1.0 komt overeen met 100 %. Schrijven **float**. |
| virtual void [set_RewindAudio](./set_rewindaudio/)(**bool**) | Bepaalt of een audio automatisch wordt teruggespoeld naar het begin na afspelen. Schrijven **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Stelt het aantal graden in waarmee de opgegeven shape rond de z-as wordt gedraaid. Een positieve waarde duidt op een klokwijzerrotatie; een negatieve waarde duidt op een tegenwijzerrotatie. Schrijven **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Stelt het vooraf gedefinieerde geometrie-type in. Opmerking: bij wijziging van de waarde worden alle aanpassingswaarden teruggezet naar hun standaardwaarden. Schrijven [Slides::ShapeType](../shapetype/). |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | Specificeert de tijdsduur die aan het einde van de media wordt weggelaten tijdens het afspelen, in milliseconden. Schrijven **float**. |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | Specificeert de tijdsduur die aan het begin van de media wordt weggelaten tijdens het afspelen, in milliseconden. Schrijven **float**. |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | Stelt het audiovolume in. Schrijven [AudioVolumeMode](../audiovolumemode/). |
| virtual void [set_VolumeValue](./set_volumevalue/)(**float**) | Stelt het audiovolume in percentages. Schrijven **float**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Stelt de breedte van de shape in, gemeten in points. Schrijven **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Stelt de x-coördinaat van de linkerbovenhoek van de shape in, gemeten in points. Schrijven **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Stelt de y-coördinaat van de linkerbovenhoek van de shape in, gemeten in points. Schrijven **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Werk de geometrie van de shape bij vanuit het [IGeometryPath](../igeometrypath/)-object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de shape. Wijzigt het type van de shape ([ShapeType](../shapetype/)) naar [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Werk de geometrie van de shape bij vanuit een array van [IGeometryPath](../igeometrypath/). Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de shape. Wijzigt het type van de shape ([ShapeType](../shapetype/)) naar [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in als een zwakke pointer (in plaats van gedeelde). Stelt het mogelijk om pointers in containers te wisselen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Vergroot de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Vermindert en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het unlocken van het C# lock()-statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Vergroot de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Vermindert de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Slaat de inhoud van [Shape](../shape/) op als SVG-bestand. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijmaakt alle interne datastructuren. |

## Zie ook

* Klasse [IPictureFrame](../ipictureframe/)
* Namespace [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)