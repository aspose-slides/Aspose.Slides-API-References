---
title: IAudioFrame
second_title: Aspose.Slides för C++ API-referens
description: Representerar ett ljudklipp på en bild.
type: docs
weight: 1353
url: /sv/aspose.slides/iaudioframe/
---
## IAudioFrame klass

Representerar ett ljudklipp på en bild.

```cpp
class IAudioFrame : public virtual Aspose::Slides::IPictureFrame
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Lägger till en ny platshållare om det inte finns någon och sätter platshållarens egenskaper till en specificerad. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Skapar och returnerar en array av formens element. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Returnerar ett justeringsvärde för formen på det angivna indexet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Returnerar en samling av formens justeringsvärden. Skrivskyddad [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Returnerar alternativtexten som är associerad med en form. Läs [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Returnerar titeln på alternativtexten som är associerad med en form. Läs [System::String](../../system/string/). |
| virtual **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() | Returnerar sista spårindexet. Läs **int32_t**. |
| virtual **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() | Returnerar sista spårtid. Läs **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() | Returnerar startspårindex. Läs **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() | Returnerar startspårtid. Läs **int32_t**. |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Egenskap specificerar hur en form renderas i svart-vit visningsläge. Läs [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | Hämtar samlingen av undertexter som är associerade med ljudramen. Denna egenskap är skrivskyddad och returnerar ett [ICaptionsCollection](../icaptionscollection/) som innehåller alla undertextspår. |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Returnerar antalet anslutningspunkter på formen. Skrivskyddad **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Returnerar formens anpassade data. Skrivskyddad [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Returnerar [EffectFormat](../effectformat/)-objektet som innehåller pixeleffekter som tillämpas på en form. Skrivskyddad [IEffectFormat](../ieffectformat/). |
| virtual **bool** [get_Embedded](./get_embedded/)() | Avgör om ett ljud är inbäddat i en presentation. Skrivskyddad **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() | Returnerar inbäddat ljudobjekt. Läs [IAudio](../iaudio/). |
| virtual **float** [get_FadeInDuration](./get_fadeinduration/)() | Anger tidslängden för den initiala fade-in för mediet i millisekunder. Läs **float**. |
| virtual **float** [get_FadeOutDuration](./get_fadeoutduration/)() | Anger tidslängden för den avslutande fade-out för mediet i millisekunder. Läs **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Returnerar [FillFormat](../fillformat/)-objektet som innehåller fyllningsformateringsegenskaper för en form. Skrivskyddad [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Returnerar formramens egenskaper. Läs [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Hämtar formens höjd, mätt i punkter. Läs **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Avgör om formen är dold. Läs **bool**. |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | Avgör om en [AudioFrame](../audioframe/) är dold. Läs **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Returnerar hyperlänken som definierats för musklick. Läs [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlänks-hanterare Skrivskyddad [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Returnerar hyperlänken som definierats för musöver. Läs [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Hämtar alternativet 'Mark as decorative'. Läs/skriv **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Avgör om formen är grupperad. Skrivskyddad **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Avgör om formen är TextHolder. Skrivskyddad **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Returnerar [LineFormat](../lineformat/)-objektet som innehåller linjeformateringsegenskaper för en form. Skrivskyddad [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | Returnerar namnet på en ljudfil som är länkad till en [AudioFrame](../audioframe/). Läs [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Returnerar namnet på en form. Läs [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Returnerar en bild-specifik unik identifierare som förblir konstant under formens livstid och låter PowerPoint eller interop-kod pålitligt referera till formen från var som helst i dokumentet. Skrivskyddad **uint32_t**. Se även [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Returnerar föräldra-[GroupShape](../groupshape/)-objektet om formen är grupperad. Annars returneras null. Skrivskyddad [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | Returnerar [PictureFillFormat](../picturefillformat/)-objektet för en bildram. Skrivskyddad [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | Returnerar [PictureFrame](../pictureframe/)-låsen. Skrivskyddad [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Returnerar platshållaren för en form. Skrivskyddad [IPlaceholder](../iplaceholder/). |
| virtual **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() | Avgör om ett ljud spelas över bildspelen. Läs **bool**. |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | Avgör om ett ljud är loopat. Läs **bool**. |
| virtual [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() | Returnerar ljuduppspelningsläget. Läs [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Skrivskyddad [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Returnerar den råa formramens egenskaper. Läs [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | Returnerar skalning av höjden (relativt originalbildens storlek) för bildramen. Värdet 1,0 motsvarar 100 %. Läs **float**. |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | Returnerar skalning av bredden (relativt originalbildens storlek) för bildramen. Värdet 1,0 motsvarar 100 %. Läs **float**. |
| virtual **bool** [get_RewindAudio](./get_rewindaudio/)() | Avgör om ett ljud automatiskt spolas tillbaka till början efter uppspelning. Läs **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Returnerar antalet grader som den angivna formen roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Returnerar formens lås. Skrivskyddad [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Returnerar formens stilobjekt. Skrivskyddad [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Returnerar geometrins förinställda typ. Observera: vid värdeförändring återställs alla justeringsvärden till sina standardvärden. Läs [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Returnerar grundbilden. Skrivskyddad [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Returnerar [ThreeDFormat](../threedformat/)-objektet som innehåller linjeformateringsegenskaper för en form. Skrivskyddad [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder. Läs **float**. |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | Anger tidslängden som ska tas bort från början av mediet under uppspelning, i millisekunder. Läs **float**. |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Returnerar en intern, presentation-specifik identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omfördelas av användaren eller programmässigt, får det inte behandlas som en bestående unik nyckel. Skrivskyddad **uint32_t**. Se även [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | Returnerar ljudvolymen. Läs [AudioVolumeMode](../audiovolumemode/). |
| virtual **float** [get_VolumeValue](./get_volumevalue/)() | Returnerar ljudvolymen i procent. Läs **float**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Hämtar formens bredd, mätt i punkter. Läs **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Hämtar x-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Hämtar y-koordinaten för formens övre vänstra hörn, mätt i punkter. Läs **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Returnerar positionen för en form i z-ordningen. Shapes[0] returnerar formen längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar formen längst fram i z-ordningen. Skrivskyddad **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Returnerar en grundläggande platshållarform (form från layouten och/eller mastern som den aktuella formen ärvs från). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenstabellens datastruktur som är associerad med objektet. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Returnerar en kopia av geometriformens bana. Koordinaterna är relativa till formens övre vänstra hörn. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Returnerar formens miniatyr. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) miniatyrgränstypt används som standard. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Returnerar formens miniatyr. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska typen för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr per referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referenstallning med angivet värde. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Definierar att denna form inte är en platshållare. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Sätter alternativtexten som är associerad med en form. Skriv [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Sätter titeln på alternativtexten som är associerad med en form. Skriv [System::String](../../system/string/). |
| virtual void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) | Sätter sista spårindex. Skriv **int32_t**. |
| virtual void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) | Sätter sista spårtid. Skriv **int32_t**. |
| virtual void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) | Sätter startspårindex. Skriv **int32_t**. |
| virtual void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) | Sätter startspårtid. Skriv **int32_t**. |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Egenskap specificerar hur en form renderas i svart-vit visningsläge. Skriv [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Sätter inbäddat ljudobjekt. Skriv [IAudio](../iaudio/). |
| virtual void [set_FadeInDuration](./set_fadeinduration/)(**float**) | Anger tidslängden för den initiala fade-in för mediet i millisekunder. Skriv **float**. |
| virtual void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) | Anger tidslängden för den avslutande fade-out för mediet i millisekunder. Skriv **float**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Sätter formramens egenskaper. Skriv [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Sätter formens höjd, mätt i punkter. Skriv **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Avgör om formen är dold. Skriv **bool**. |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | Avgör om en [AudioFrame](../audioframe/) är dold. Skriv **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Sätter hyperlänken som definierats för musklick. Skriv [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Sätter hyperlänken som definierats för musöver. Skriv [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Sätter alternativet 'Mark as decorative'. Läs/skriv **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | Sätter namnet på en ljudfil som är länkad till en [AudioFrame](../audioframe/). Skriv [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Sätter namnet på en form. Skriv [System::String](../../system/string/). |
| virtual void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) | Avgör om ett ljud spelas över bildspelen. Skriv **bool**. |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | Avgör om ett ljud är loopat. Skriv **bool**. |
| virtual void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) | Sätter ljuduppspelningsläget. Skriv [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Sätter den råa formramens egenskaper. Skriv [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | Sätter skalning av höjden (relativt originalbildens storlek) för bildramen. Värdet 1,0 motsvarar 100 %. Skriv **float**. |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | Sätter skalning av bredden (relativt originalbildens storlek) för bildramen. Värdet 1,0 motsvarar 100 %. Skriv **float**. |
| virtual void [set_RewindAudio](./set_rewindaudio/)(**bool**) | Avgör om ett ljud automatiskt spolas tillbaka till början efter uppspelning. Skriv **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Sätter antalet grader som den angivna formen roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Skriv **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Sätter geometrins förinställda typ. Observera: vid värdeförändring återställs alla justeringsvärden till sina standardvärden. Skriv [Slides::ShapeType](../shapetype/). |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | Anger tidslängden som ska tas bort från slutet av mediet under uppspelning, i millisekunder. Skriv **float**. |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | Anger tidslängden som ska tas bort från början av mediet under uppspelning, i millisekunder. Skriv **float**. |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | Sätter ljudvolymen. Skriv [AudioVolumeMode](../audiovolumemode/). |
| virtual void [set_VolumeValue](./set_volumevalue/)(**float**) | Sätter ljudvolymen i procent. Skriv **float**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Sätter formens bredd, mätt i punkter. Skriv **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Sätter x-koordinaten för formens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Sätter y-koordinaten för formens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Uppdaterar formens geometri från [IGeometryPath](../igeometrypath/)-objektet. Koordinaterna måste vara relativa till formens övre vänstra hörn. Ändrar formens typ ([ShapeType](../shapetype/)) till [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Uppdaterar formens geometri från en array av [IGeometryPath](../igeometrypath/). Koordinaterna måste vara relativa till formens övre vänstra hörn. Ändrar formens typ ([ShapeType](../shapetype/)) till [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in det n'te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referenstalning. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referenstallning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referenstallning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjektet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referenstallning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referenstallning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Sparar innehållet av [Shape](../shape/) som SVG-fil. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Sparar innehållet av [Shape](../shape/) som SVG-fil. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [IPictureFrame](../ipictureframe/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)