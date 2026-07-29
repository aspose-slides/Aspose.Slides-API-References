---
title: AudioFrame
second_title: Aspose.Slides för C++ API-referens
description: Representerar ett ljudklipp på en bild.
type: docs
weight: 53
url: /sv/aspose.slides/audioframe/
---
## AudioFrame klass


Representerar ett ljudklipp på en bild.

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Lägger till en ny platshållare om det inte finns någon och sätter platshållarens egenskaper till en specificerad. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Skapar och returnerar en array med figurens element. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil för dubbelprecision där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Returnerar figurens justeringsvärde på det angivna indexet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Returnerar en samling av figurens justeringsvärden. Skrivskyddad [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Returnerar den alternativa texten som är associerad med en figur. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Returnerar titeln på den alternativa texten som är associerad med en figur. Läs [System::String](../../system/string/). |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | Returnerar det sista spårets index. Läs **int32_t**. |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | Returnerar den sista spårets tid. Läs **int32_t**. |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | Returnerar ett startspårs index. Läs **int32_t**. |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | Returnerar startspårets tid. Läs **int32_t**. |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Egenskapen specificerar hur en figur kommer att renderas i svart-vit visningsläge. Läs [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | Hämtar samlingen av undertexter som är associerade med ljudramen. Denna egenskap är skrivskyddad och returnerar ett [ICaptionsCollection](../icaptionscollection/) som innehåller alla undertextspår. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Returnerar antalet anslutningspunkter på figuren. Skrivskyddad **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Returnerar figurens anpassade data. Skrivskyddad [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Returnerar [EffectFormat](../effectformat/)-objektet som innehåller pixeleffekter som tillämpas på en figur. Obs: kan returnera null för vissa typer av figurer som inte har effekt-egenskaper. Skrivskyddad [IEffectFormat](../ieffectformat/). |
| **bool** [get_Embedded](./get_embedded/)() override | Avgör om ett ljud är inbäddat i en presentation. Skrivskyddad **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | Returnerar inbäddat ljudobjekt. Läs [IAudio](../iaudio/). |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | Specificerar tidslängden för den initiala insluckningen av media i millisekunder. Läs **float**. |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | Specificerar tidslängden för den avslutande utsluckningen av media i millisekunder. Läs **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Returnerar [FillFormat](../fillformat/)-objektet som innehåller fyllningsformaterings-egenskaper för en figur. Obs: kan returnera null för vissa typer av figurer som inte har fyllningsegenskaper. Skrivskyddad [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Returnerar figurens ram-egenskaper. Läs [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Hämtar figurens höjd, mätt i punkter. Läs **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Avgör om figuren är dold. Läs **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | Avgör om ett [AudioFrame](./) är dolt. Läs **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Returnerar hyperlänken som definierats för musklick. Läs [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Returnerar hyperlänkshanteraren. Skrivskyddad [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Returnerar hyperlänken som definierats för muspekare. Läs [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | Avgör om [PictureFrame](../pictureframe/) är ett Cameo-objekt eller inte. Endast läs **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Hämtar 'Mark as decorative'-alternativet Läs/skriv **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Avgör om figuren är grupperad. Skrivskyddad **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Avgör om figuren är TextHolder_PPT. Skrivskyddad **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Returnerar [LineFormat](../lineformat/)-objektet som innehåller linjeformaterings-egenskaper för en figur. Obs: kan returnera null för vissa typer av figurer som inte har linjeegenskaper. Skrivskyddad [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Returnerar namnet på en ljudfil som är länkad till ett [AudioFrame](./). Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Returnerar namnet på en figur. Måste vara icke-null. Använd tom sträng om behövs. Läs [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Returnerar en bild-specifik unik identifierare som förblir konstant under figurens livstid och låter PowerPoint eller interop-kod på ett tillförlitligt sätt referera till figuren från var som helst i dokumentet. Skrivskyddad **uint32_t**. Se även [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Returnerar föräldra-[GroupShape](../groupshape/)-objektet om figuren är grupperad. Annars returneras null. Skrivskyddad [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | Returnerar [PictureFillFormat](../picturefillformat/)-objektet för en bildram. Skrivskyddad [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | Returnerar figurens lås. Skrivskyddad [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Returnerar platshållaren för en figur. Returnerar null om figuren inte har någon platshållare. Skrivskyddad [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | Avgör om ljud spelas över bilderna. Läs **bool**. |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | Avgör om ett ljud är i loop. Läs **bool**. |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | Returnerar ljuduppspelningsläget. Läs [AudioPlayModePreset](../audioplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Returnerar föräldrapresentationen för en bild. Skrivskyddad [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Returnerar de råa ram-egenskaperna för en figur. Läs [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | Returnerar skalan för höjden (i förhållande till originalbildens storlek) för bildramen. Värdet 1,0 motsvarar 100 %. Läs **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | Returnerar skalan för bredden (i förhållande till originalbildens storlek) för bildramen. Värdet 1,0 motsvarar 100 %. Läs **float**. |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | Avgör om ljud automatiskt spolas tillbaka till start efter uppspelning. Läs **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Returnerar antalet grader som den angivna figuren är roterad kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Läs **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Returnerar figurens lås. Skrivskyddad [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Returnerar figurens stilobjekt. Skrivskyddad [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Returnerar föräldrabilden för en figur. Skrivskyddad [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Returnerar [ThreeDFormat](../threedformat/)-objektet som innehåller 3D-effekt-egenskaper för en figur. Obs: kan returnera null för vissa typer av figurer som inte har 3D-egenskaper. Skrivskyddad [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | Specificerar tidslängden som ska tas bort från slutet av media under uppspelning, i millisekunder. Läs **float**. |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | Specificerar tidslängden som ska tas bort från början av media under uppspelning, i millisekunder. Läs **float**. |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Returnerar en intern, presentation-specifik identifierare avsedd för användning av tillägg eller annan kod. Eftersom detta värde kan omallokeras av användaren eller programmässigt får det inte behandlas som en beständig unik nyckel. Skrivskyddad **uint32_t**. Se även [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | Returnerar ljudvolymen. Läs [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_VolumeValue](./get_volumevalue/)() override | Returnerar ljudvolymen i procent. Läs **float**. |
| **float** [get_Width](../shape/get_width/)() override | Hämtar figurens bredd, mätt i punkter. Läs **float**. |
| **float** [get_X](../shape/get_x/)() override | Hämtar x-koordinaten för figurens övre vänstra hörn, mätt i punkter. Läs **float**. |
| **float** [get_Y](../shape/get_y/)() override | Hämtar y-koordinaten för figurens övre vänstra hörn, mätt i punkter. Läs **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Returnerar positionen för en figur i z-ordningen. Shapes[0] returnerar figuren längst bak i z-ordningen, och Shapes[Shapes.Count - 1] returnerar figuren längst fram i z-ordningen. Skrivskyddad **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Returnerar en grundläggande platshållarfigur (figur från layouten och/eller huvudbilden som den aktuella figuren ärvs från). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenstillräknar-datastrukturen som är associerad med objektet. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Returnerar en kopia av banan för geometrifiguren. Koordinaterna är relativt till figurens övre vänstra hörn. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Returnerar figurens miniatyrbild. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) miniatyrbildsgränstyp används som standard. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Returnerar figurens miniatyrbild. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar det faktiska typnamnet för objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Hämtar figurens visuella gränser beräknade från dess renderade innehåll. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning för C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referenstillräknare med angivet värde. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definierar att denna figur inte är en platshållare. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Sätter den alternativa texten som är associerad med en figur. Skriv [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Sätter titeln på den alternativa texten som är associerad med en figur. Skriv [System::String](../../system/string/). |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | Sätter ett sista spårets index. Skriv **int32_t**. |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | Sätter ett sista spårets tid. Skriv **int32_t**. |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | Sätter ett startspårs index. Skriv **int32_t**. |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | Sätter ett startspårs tid. Skriv **int32_t**. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Egenskapen specificerar hur en figur ska renderas i svart-vit visningsläge. Skriv [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Sätter inbäddat ljudobjekt. Skriv [IAudio](../iaudio/). |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | Specificerar tidslängden för den initiala insluckningen av media i millisekunder. Skriv **float**. |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | Specificerar tidslängden för den avslutande utsluckningen av media i millisekunder. Skriv **float**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Sätter figurens ram-egenskaper. Skriv [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Sätter figurens höjd, mätt i punkter. Skriv **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Avgör om figuren är dold. Skriv **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | Avgör om ett [AudioFrame](./) är dolt. Skriv **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Sätter hyperlänken som definierats för musklick. Skriv [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Sätter hyperlänken som definierats för muspekare. Skriv [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Sätter 'Mark as decorative'-alternativet Läs/skriv **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Sätter namnet på en ljudfil som länkas till ett [AudioFrame](./). Skriv [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Sätter namnet på en figur. Måste vara icke-null. Använd tom sträng om behövs. Skriv [System::String](../../system/string/). |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | Avgör om ljud spelas över bilderna. Skriv **bool**. |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | Avgör om ett ljud är i loop. Skriv **bool**. |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | Sätter ljuduppspelningsläget. Skriv [AudioPlayModePreset](../audioplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Sätter de råa ram-egenskaperna för en figur. Skriv [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | Sätter skalan för höjden (i förhållande till originalbildens storlek) för bildramen. Värdet 1,0 motsvarar 100 %. Skriv **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | Sätter skalan för bredden (i förhållande till originalbildens storlek) för bildramen. Värdet 1,0 motsvarar 100 %. Skriv **float**. |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | Avgör om ljud automatiskt spolas tillbaka till start efter uppspelning. Skriv **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Sätter antalet grader som den angivna figuren roteras kring z-axeln. Ett positivt värde indikerar medurs rotation; ett negativt värde indikerar moturs rotation. Skriv **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | Specificerar tidslängden som ska tas bort från slutet av media under uppspelning, i millisekunder. Skriv **float**. |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | Specificerar tidslängden som ska tas bort från början av media under uppspelning, i millisekunder. Skriv **float**. |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | Sätter ljudvolymen. Skriv [AudioVolumeMode](../audiovolumemode/). |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | Sätter ljudvolymen i procent. Skriv **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Sätter figurens bredd, mätt i punkter. Skriv **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Sätter x-koordinaten för figurens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Sätter y-koordinaten för figurens övre vänstra hörn, mätt i punkter. Skriv **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Uppdaterar figurens geometri från [IGeometryPath](../igeometrypath/)-objektet. Koordinaterna måste vara relativa till figurens övre vänstra hörn. Ändrar figurens typ ([ShapeType](../shapetype/)) till [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Uppdaterar figurens geometri från en array av [IGeometryPath](../igeometrypath/). Koordinaterna måste vara relativa till figurens övre vänstra hörn. Ändrar figurens typ ([ShapeType](../shapetype/)) till [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (i stället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referenstillräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referenstillräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referenstillräknare. bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referenstillräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referenstillräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Sparar innehållet av [Shape](../shape/) som SVG-fil. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Sparar innehållet av [Shape](../shape/) som SVG-fil. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Anmärkningar


Följande exempel visar hur man ändrar [Audio](../audio/) Play-alternativ. 
```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Hämtar AudioFrame-figuren
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Ställer in uppspelningsläget till att spela vid klick
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Ställer in volymen till Låg
audioFrame->set_Volume(AudioVolumeMode::Low);
// Ställer in ljudet att spelas över bilderna
audioFrame->set_PlayAcrossSlides(true);
// Inaktiverar loop för ljudet
audioFrame->set_PlayLoopMode(false);
// Döljer AudioFrame under bildspelet
audioFrame->set_HideAtShowing(true);
// Spolar tillbaka ljudet till början efter uppspelning
audioFrame->set_RewindAudio(true);
// Sparar PowerPoint-filen till disk
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## Se också

* Klass [PictureFrame](../pictureframe/)
* Klass [IAudioFrame](../iaudioframe/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)