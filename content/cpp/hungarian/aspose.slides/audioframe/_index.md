---
title: AudioFrame
second_title: Aspose.Slides C++ API Referenciája
description: Egy dián található audio klipeket ábrázol.
type: docs
weight: 53
url: /hu/aspose.slides/audioframe/
---
## AudioFrame osztály


Represents an audio clip on a slide.

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## Módszerek

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Új helykitöltőt ad hozzá, ha nincs, és a helykitöltő tulajdonságait egy megadott helykitöltőre állítja. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Létrehozza és visszaadja a forma elemeinek tömbjét. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN-t egyenlőnek tekint, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN-t egyenlőnek tekint, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Visszaadja a forma beállítási értékét a megadott indexen. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Visszaad egy gyűjteményt a forma beállítási értékeiről. Csak olvasható [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Visszaadja a forma alternatív szövegét. Olvasható [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Visszaadja a forma alternatív szövegének címét. Olvasható [System::String](../../system/string/). |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | Visszaadja az utolsó sáv indexét. Olvasható **int32_t**. |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | Visszaadja az utolsó sáv időpontját. Olvasható **int32_t**. |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | Visszaadja a kezdő sáv indexét. Olvasható **int32_t**. |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | Visszaadja a kezdő sáv időpontját. Olvasható **int32_t**. |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban. Olvasható [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | Lekéri a zárt feliratok gyűjteményét, amely az audiokerethez tartozik. Ez a tulajdonság csak olvasható, és egy [ICaptionsCollection](../icaptionscollection/)-t ad vissza, amely tartalmazza az összes feliratsávot. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Visszaadja a forma csatlakozási pontjainak számát. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Visszaadja a forma egyéni adatait. Csak olvasható [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Visszaadja a [EffectFormat](../effectformat/) objektumot, amely a forma alkalmazott pixel-effektusait tartalmazza. Megjegyzés: bizonyos alakzattípusoknál, amelyeknek nincs effektustulajdonságuk, null értéket adhat vissza. Csak olvasható [IEffectFormat](../ieffectformat/). |
| **bool** [get_Embedded](./get_embedded/)() override | Megállapítja, hogy hang be van-e ágyazva a bemutatóba. Csak olvasható **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | Visszaadja a beágyazott audio objektumot. Olvasható [IAudio](../iaudio/). |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | A média kezdeti beolvasztásának időtartamát adja meg ezredmásodpercben. Olvasható **float**. |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | A média befejező kivezetésének időtartamát adja meg ezredmásodpercben. Olvasható **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Visszaadja a [FillFormat](../fillformat/) objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusoknál, amelyeknek nincs kitöltési tulajdonságuk, null értéket adhat vissza. Csak olvasható [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Visszaadja a forma keret tulajdonságait. Olvasható [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Lekéri a forma magasságát pontban mérve. Olvasható **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Megállapítja, hogy a forma rejtett-e. Olvasható **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | Megállapítja, hogy egy [AudioFrame](./) rejtett-e. Olvasható **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Visszaadja az egérkattintáshoz definiált hiperhivatkozást. Olvasható [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasható [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Visszaadja az egér fölé mozgatásához definiált hiperhivatkozást. Olvasható [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | Megállapítja, hogy a [PictureFrame](../pictureframe/) Cameo objektum-e vagy sem. Csak olvasható **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Lekéri a 'Mark as decorative' beállítást. Olvasás/írás **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Megállapítja, hogy a forma csoportosított-e. Csak olvasható **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Megállapítja, hogy a forma TextHolder_PPT-e. Csak olvasható **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Visszaadja a [LineFormat](../lineformat/) objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusoknál, amelyeknek nincs vonaltulajdonságuk, null értéket adhat vissza. Csak olvasható [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Visszaadja egy audiofájl nevét, amely egy [AudioFrame](./)-hez kapcsolódik. Olvasható [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Visszaadja egy forma nevét. Nem lehet null. Szükség esetén használjon üres karakterláncot. Olvasható [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Visszaad egy diára korlátozott egyedi azonosítót, amely a forma élettartama alatt állandó marad, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon a formára a dokumentum bármely részéből. Csak olvasható **uint32_t**. Lásd még [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Visszaadja a szülő [GroupShape](../groupshape/) objektumot, ha a forma csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | Visszaadja a [PictureFillFormat](../picturefillformat/) objektumot egy képkerethez. Csak olvasható [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | Visszaadja a forma zárolásait. Csak olvasható [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Visszaadja a forma helykitöltőjét. Null értéket ad vissza, ha a formának nincs helykitöltője. Csak olvasható [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | Megállapítja, hogy az audio a diákon át játszódik-e. Olvasható **bool**. |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | Megállapítja, hogy az audio ismétlődik-e. Olvasható **bool**. |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | Visszaadja az audio lejátszási módot. Olvasható [AudioPlayModePreset](../audioplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Visszaadja a dia szülő bemutatóját. Csak olvasható [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Visszaadja a nyers forma keret tulajdonságait. Olvasható [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | Visszaadja a képkeret magasságának (az eredeti képmérettel arányosan) méretezését. Az 1.0 érték 100%-nak felel meg. Olvasható **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | Visszaadja a képkeret szélességének (az eredeti képmérettel arányosan) méretezését. Az 1.0 érték 100%-nak felel meg. Olvasható **float**. |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | Megállapítja, hogy az audio automatikusan visszatekerődik-e a lejátszás után. Olvasható **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Visszaadja, hogy hány fokkal van elforgatva a megadott forma a z-tengely körül. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellenkező irányt. Olvasható **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Visszaadja a forma zárolásait. Csak olvasható [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Visszaadja a forma stílusobjektumát. Csak olvasható [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Visszaadja a forma szülő diáját. Csak olvasható [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Visszaadja a [ThreeDFormat](../threedformat/) objektumot, amely a forma 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusoknál, amelyeknek nincs 3D tulajdonságuk, null értéket adhat vissza. Csak olvasható [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | Megadja, hogy mennyi időt kell eltávolítani a média végéről lejátszás közben, ezredmásodpercben. Olvasható **float**. |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | Megadja, hogy mennyi időt kell eltávolítani a média elejéről lejátszás közben, ezredmásodpercben. Olvasható **float**. |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Visszaad egy belső, a bemutatóra korlátozott azonosítót, amelyet kiegészítők vagy más kódok használhatnak. Mivel ezt az értéket a felhasználó vagy programozás útján újra lehet rendelni, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható **uint32_t**. Lásd még [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | Visszaadja az audio hangerőt. Olvasható [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_VolumeValue](./get_volumevalue/)() override | Visszaadja az audio hangerőt százalékban. Olvasható **float**. |
| **float** [get_Width](../shape/get_width/)() override | Lekéri a forma szélességét pontban mérve. Olvasható **float**. |
| **float** [get_X](../shape/get_x/)() override | Lekéri a forma bal-felső sarkának x-koordinátáját pontban mérve. Olvasható **float**. |
| **float** [get_Y](../shape/get_y/)() override | Lekéri a forma bal-felső sarkának y-koordinátáját pontban mérve. Olvasható **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Visszaadja egy forma pozícióját a z-sorrendben. A Shapes[0] a háttérben lévő formát adja vissza, a Shapes[Shapes.Count - 1] pedig az előre helyezkedő formát. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Visszaad egy alap helykitöltő formát (a elrendezésből és/vagy a mester diából származó formát, amelyből a jelenlegi forma örököl). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Visszaadja a geometriai forma útvonalának másolatát. A koordináták a forma bal felső sarkához képest relatívak. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Visszaadja a forma bélyegképét. Alapértelmezés szerint a [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) forma bélyegkép határoló típust használ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Visszaadja a forma bélyegképét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Lekéri a forma vizuális határait, a megjelenített tartalom alapján számítva. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializálja az új objektumot, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak inicializálja az új objektumot, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Meghatározza, hogy ez a forma nem helykitöltő. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Beállítja a forma alternatív szövegét. Írás [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Beállítja a forma alternatív szövegének címét. Írás [System::String](../../system/string/). |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | Beállítja az utolsó sáv indexét. Írás **int32_t**. |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | Beállítja az utolsó sáv időpontját. Írás **int32_t**. |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | Beállítja a kezdő sáv indexét. Írás **int32_t**. |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | Beállítja a kezdő sáv időpontját. Írás **int32_t**. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Az tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér módon. Írás [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Beállítja a beágyazott audio objektumot. Írás [IAudio](../iaudio/). |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | Megadja a média kezdeti beolvasztásának időtartamát ezredmásodpercben. Írás **float**. |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | Megadja a média végső kivezetésének időtartamát ezredmásodpercben. Írás **float**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Beállítja a forma keret tulajdonságait. Írás [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Beállítja a forma magasságát pontban mérve. Írás **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Beállítja, hogy a forma rejtett-e. Írás **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | Beállítja, hogy egy [AudioFrame](./) rejtett-e. Írás **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Beállítja az egérkattintáshoz definiált hiperhivatkozást. Írás [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Beállítja az egér fölé mozgatásához definiált hiperhivatkozást. Írás [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Beállítja a 'Mark as decorative' opciót. Olvasás/írás **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Beállítja egy audiofájl nevét, amely egy [AudioFrame](./)-hez kapcsolódik. Írás [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Beállítja egy forma nevét. Nem lehet null. Szükség esetén használjon üres karakterláncot. Írás [System::String](../../system/string/). |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | Beállítja, hogy az audio a diákon át játszódik-e. Írás **bool**. |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | Beállítja, hogy az audio ismétlődik-e. Írás **bool**. |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | Beállítja az audio lejátszási módot. Írás [AudioPlayModePreset](../audioplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Beállítja a nyers forma keret tulajdonságait. Írás [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | Beállítja a képkeret magasságának (az eredeti képmérettel arányosan) méretezését. Az 1.0 érték 100%-nak felel meg. Írás **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | Beállítja a képkeret szélességének (az eredeti képmérettel arányosan) méretezését. Az 1.0 érték 100%-nak felel meg. Írás **float**. |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | Beállítja, hogy az audio automatikusan visszatekerődik-e a lejátszás után. Írás **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Beállítja, hogy hány fokkal legyen elforgatva a megadott forma a z-tengely körül. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellenkező irányt. Írás **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | Megadja, hogy mennyi időt kell eltávolítani a média végéről lejátszás közben, ezredmásodpercben. Írás **float**. |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | Megadja, hogy mennyi időt kell eltávolítani a média elejéről lejátszás közben, ezredmásodpercben. Írás **float**. |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | Beállítja az audio hangerőt. Írás [AudioVolumeMode](../audiovolumemode/). |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | Beállítja az audio hangerőt százalékban. Írás **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Beállítja a forma szélességét pontban mérve. Írás **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Beállítja a forma bal-felső sarkának x-koordinátáját pontban mérve. Írás **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Beállítja a forma bal-felső sarkának y-koordinátáját pontban mérve. Írás **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Frissíti a forma geometriáját a [IGeometryPath](../igeometrypath/) objektum alapján. A koordinátáknak a forma bal felső sarkához képest relatívaknak kell lenniük. A forma típusát ([ShapeType](../shapetype/)) [ShapeType::Custom](../shapetype/)-ra változtatja. |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Frissíti a forma geometriáját a [IGeometryPath](../igeometrypath/) tömb alapján. A koordinátáknak a forma bal felső sarkához képest relatívaknak kell lenniük. A forma típusát ([ShapeType](../shapetype/)) [ShapeType::Custom](../shapetype/)-ra változtatja. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóvá (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok sztringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Elmenti a [Shape](../shape/) tartalmát SVG fájlként. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések

A következő példák bemutatják, hogyan változtatható meg a [Audio](../audio/) lejátszási beállítás.
```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Gets the AudioFrame shape
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Sets the Play mode to play on click
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Sets the volume to Low
audioFrame->set_Volume(AudioVolumeMode::Low);
// Sets the audio to play across slides
audioFrame->set_PlayAcrossSlides(true);
// Disables loop for the audio
audioFrame->set_PlayLoopMode(false);
// Hides the AudioFrame during the slide show
audioFrame->set_HideAtShowing(true);
// Rewinds the audio to start after playing
audioFrame->set_RewindAudio(true);
// Saves the PowerPoint file to disk
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [PictureFrame](../pictureframe/)
* Osztály [IAudioFrame](../iaudioframe/)
* Névterület [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)