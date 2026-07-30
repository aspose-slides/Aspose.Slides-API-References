---
title: AudioFrame
second_title: Aspose.Slides pro C++ referenční příručka API
description: Reprezentuje zvukový klip na snímku.
type: docs
weight: 53
url: /cs/aspose.slides/audioframe/
---
## AudioFrame třída

Represents an audio clip on a slide.

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## Metody

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Přidá nový placeholder, pokud neexistuje, a nastaví vlastnosti placeholderu na zadaný. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Vytvoří a vrátí pole prvků tvaru. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referencového typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Vrací hodnotu úprav tvaru na zadaném indexu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Vrací kolekci hodnot úprav tvaru. Pouze pro čtení [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Vrací alternativní text spojený s tvarem. Pouze pro čtení [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Vrací název alternativního textu spojeného s tvarem. Pouze pro čtení [System::String](../../system/string/). |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | Vrací index poslední stopy. Pouze pro čtení **int32_t**. |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | Vrací čas poslední stopy. Pouze pro čtení **int32_t**. |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | Vrací index počáteční stopy. Pouze pro čtení **int32_t**. |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | Vrací čas počáteční stopy. Pouze pro čtení **int32_t**. |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení.. Pouze pro čtení [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | Získá kolekci uzavřených titulků spojených s audio rámcem. Tato vlastnost je pouze pro čtení a vrací [ICaptionsCollection](../icaptionscollection/) obsahující všechny stopy titulků. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Vrací počet připojených míst na tvaru. Pouze pro čtení **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Vrací vlastní data tvaru. Pouze pro čtení [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Vrací objekt [EffectFormat](../effectformat/), který obsahuje pixelové efekty aplikované na tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají vlastnosti efektu. Pouze pro čtení [IEffectFormat](../ieffectformat/). |
| **bool** [get_Embedded](./get_embedded/)() override | Určuje, zda je zvuk vložen do prezentace. Pouze pro čtení **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | Vrací vložený audio objekt. Pouze pro čtení [IAudio](../iaudio/). |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | Určuje dobu trvání počátečního fade-in média v milisekundách. Pouze pro čtení **float**. |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | Určuje dobu trvání koncového fade-out média v milisekundách. Pouze pro čtení **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Vrací objekt [FillFormat](../fillformat/), který obsahuje vlastnosti výplně pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají výplňové vlastnosti. Pouze pro čtení [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Vrací vlastnosti rámce tvaru. Pouze pro čtení [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Získá výšku tvaru, měřenou v bodech. Pouze pro čtení **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Určuje, zda je tvar skrytý. Pouze pro čtení **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | Určuje, zda je [AudioFrame](./) skrytý. Pouze pro čtení **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Vrací hyperodkaz definovaný pro kliknutí myší. Pouze pro čtení [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Vrací správce hyperodkazů. Pouze pro čtení [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Vrací hyperodkaz definovaný pro přejetí myší. Pouze pro čtení [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | Určuje, zda je [PictureFrame](../pictureframe/) objekt Cameo nebo ne. Pouze pro čtení **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Získá možnost 'Mark as decorative'. Čtení/zápis **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Určuje, zda je tvar seskupený. Pouze pro čtení **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Určuje, zda je tvar TextHolder_PPT. Pouze pro čtení **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Vrací objekt [LineFormat](../lineformat/), který obsahuje vlastnosti formátování čáry pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají čárové vlastnosti. Pouze pro čtení [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Vrací název audio souboru, který je propojen s [AudioFrame](./). Pouze pro čtení [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Vrací název tvaru. Musí být nenulový. Použijte prázdný řetězec, pokud je potřeba. Pouze pro čtení [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Vrací unikátní identifikátor v rámci snímku, který zůstává konstantní po dobu životnosti tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení **uint32_t**. Viz také [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Vrací nadřazený objekt [GroupShape](../groupshape/), pokud je tvar seskupen. Jinak vrací null. Pouze pro čtení [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | Vrací objekt [PictureFillFormat](../picturefillformat/) pro rámec obrázku. Pouze pro čtení [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | Vrací zámky tvaru. Pouze pro čtení [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Vrací placeholder pro tvar. Vrací null, pokud tvar nemá placeholder. Pouze pro čtení [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | Určuje, zda se audio přehrává napříč snímky. Pouze pro čtení **bool**. |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | Určuje, zda je audio v cyklu. Pouze pro čtení **bool**. |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | Vrací režim přehrávání audia. Pouze pro čtení [AudioPlayModePreset](../audioplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Vrací nadřazenou prezentaci snímku. Pouze pro čtení [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Vrací surové vlastnosti rámce tvaru. Pouze pro čtení [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | Vrací měřítko výšky (relativně k původní velikosti obrázku) rámce obrázku. Hodnota 1,0 odpovídá 100 %. Pouze pro čtení **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | Vrací měřítko šířky (relativně k původní velikosti obrázku) rámce obrázku. Hodnota 1,0 odpovídá 100 %. Pouze pro čtení **float**. |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | Určuje, zda se audio automaticky posouvá na začátek po přehrání. Pouze pro čtení **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Vrací počet stupňů, o které je tvar otočen kolem osy z. Kladná hodnota znamená otočení po směru hodinových ručiček; záporná hodnota znamená opačný směr. Pouze pro čtení **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Vrací zámky tvaru. Pouze pro čtení [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Vrací objekt stylu tvaru. Pouze pro čtení [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Vrací nadřazený snímek tvaru. Pouze pro čtení [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Vrací objekt [ThreeDFormat](../threedformat/), který obsahuje 3D vlastnosti efektu pro tvar. Poznámka: může vrátit null pro určité typy tvarů, které nemají 3D vlastnosti. Pouze pro čtení [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | Určuje dobu trvání, která má být odebrána z konce média během přehrávání, v milisekundách. Pouze pro čtení **float**. |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | Určuje dobu trvání, která má být odebrána z začátku média během přehrávání, v milisekundách. Pouze pro čtení **float**. |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože tato hodnota může být uživatelem nebo programově přidělena, neměla by být považována za trvalý jedinečný klíč. Pouze pro čtení **uint32_t**. Viz také [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | Vrací hlasitost audia. Pouze pro čtení [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_VolumeValue](./get_volumevalue/)() override | Vrací hlasitost audia v procentech. Pouze pro čtení **float**. |
| **float** [get_Width](../shape/get_width/)() override | Získá šířku tvaru, měřenou v bodech. Pouze pro čtení **float**. |
| **float** [get_X](../shape/get_x/)() override | Získá x-souřadnici levého horního rohu tvaru, měřenou v bodech. Pouze pro čtení **float**. |
| **float** [get_Y](../shape/get_y/)() override | Získá y-souřadnici levého horního rohu tvaru, měřenou v bodech. Pouze pro čtení **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Vrací pozici tvaru v z-pořadí. Shapes[0] vrací tvar v zadní části z-pořadí a Shapes[Shapes.Count - 1] vrací tvar v přední části z-pořadí. Pouze pro čtení **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Vrací základní placeholder tvar (tvar z rozložení a/nebo hlavního snímku, ze kterého aktuální tvar dědí). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počitadla referencí spojenou s objektem. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Vrací kopii cesty geometrického tvaru. Souřadnice jsou relativní k levému hornímu rohu tvaru. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Vrací miniaturu tvaru. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) typ ohraničení miniatury tvaru se používá ve výchozím nastavení. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Vrací miniaturu tvaru. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie C# [System.Object.GetType()](../../system/object/gettype/) volání. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Získá vizuální ohraničení tvaru vypočítané z jeho vykresleného obsahu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie C# operátoru 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje C# lock() pro zamykání. Volat přímo nebo použít [LockContext](../../system/lockcontext/) sentinel objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Nekopíruje nic, opravdu, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Nekopíruje nic, opravdu, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává hodnotový typ objekt s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený počitadlo reference o zadanou hodnotu. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definuje, že tento tvar není placeholder. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Nastavuje alternativní text spojený s tvarem. Zápis [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Nastavuje titul alternativního textu spojený s tvarem. Zápis [System::String](../../system/string/). |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | Nastavuje index poslední stopy. Zápis **int32_t**. |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | Nastavuje čas poslední stopy. Zápis **int32_t**. |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | Nastavuje index počáteční stopy. Zápis **int32_t**. |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | Nastavuje čas počáteční stopy. Zápis **int32_t**. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení.. Zápis [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Nastavuje vložený audio objekt. Zápis [IAudio](../iaudio/). |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | Určuje dobu trvání počátečního fade-in média v milisekundách. Zápis **float**. |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | Určuje dobu trvání koncového fade-out média v milisekundách. Zápis **float**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Nastavuje vlastnosti rámce tvaru. Zápis [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Nastavuje výšku tvaru, měřenou v bodech. Zápis **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Určuje, zda je tvar skrytý. Zápis **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | Určuje, zda je [AudioFrame](./) skrytý. Zápis **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Nastavuje hyperodkaz definovaný pro kliknutí myší. Zápis [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Nastavuje hyperodkaz definovaný pro přejetí myší. Zápis [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Nastavuje možnost 'Mark as decorative'. Čtení/zápis **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Nastavuje název audio souboru, který je propojen s [AudioFrame](./). Zápis [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Nastavuje název tvaru. Musí být nenulový. Použijte prázdný řetězec, pokud je potřeba. Zápis [System::String](../../system/string/). |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | Určuje, zda je audio přehráváno napříč snímky. Zápis **bool**. |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | Určuje, zda je audio v cyklu. Zápis **bool**. |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | Nastavuje režim přehrávání audia. Zápis [AudioPlayModePreset](../audioplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Nastavuje surové vlastnosti rámce tvaru. Zápis [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | Nastavuje měřítko výšky (relativně k původní velikosti obrázku) rámce obrázku. Hodnota 1,0 odpovídá 100 %. Zápis **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | Nastavuje měřítko šířky (relativně k původní velikosti obrázku) rámce obrázku. Hodnota 1,0 odpovídá 100 %. Zápis **float**. |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | Určuje, zda se audio automaticky posouvá na začátek po přehrání. Zápis **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Nastavuje počet stupňů, o které je tvar otočen kolem osy z. Kladná hodnota znamená otočení po směru hodinových ručiček; záporná hodnota znamená opačný směr. Zápis **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | Určuje dobu trvání, která má být odebrána z konce média během přehrávání, v milisekundách. Zápis **float**. |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | Určuje dobu trvání, která má být odebrána z začátku média během přehrávání, v milisekundách. Zápis **float**. |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | Nastavuje hlasitost audia. Zápis [AudioVolumeMode](../audiovolumemode/). |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | Nastavuje hlasitost audia v procentech. Zápis **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Nastavuje šířku tvaru, měřenou v bodech. Zápis **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Nastavuje x-souřadnici levého horního rohu tvaru, měřenou v bodech. Zápis **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Nastavuje y-souřadnici levého horního rohu tvaru, měřenou v bodech. Zápis **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Aktualizuje geometrii tvaru z objektu [IGeometryPath](../igeometrypath/). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru ([ShapeType](../shapetype/)) na [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Aktualizuje geometrii tvaru z pole [IGeometryPath](../igeometrypath/). Souřadnice musí být relativní k levému hornímu rohu tvaru. Změní typ tvaru ([ShapeType](../shapetype/)) na [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (místo sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počitadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený počitadlo referencí. Neměl by být volán přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený počitadlo referencí. Neměl by být volán přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje C# typeof([System.Object](../../system/object/)) konstrukci. |
| void [Unlock](../../system/object/unlock/)() | Implementuje C# lock() pro odemčení. Volat přímo nebo použít [LockContext](../../system/lockcontext/) sentinel objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabé počitadlo referencí. Neměl by být volán přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabé počitadlo referencí. Neměl by být volán přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Ukládá obsah [Shape](../shape/) jako SVG soubor. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Ukládá obsah [Shape](../shape/) jako SVG soubor. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny interní datové struktury. |

## Poznámky

The following examples shows how to change [Audio](../audio/) Play Options.
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

## Viz také

* Třída [PictureFrame](../pictureframe/)
* Třída [IAudioFrame](../iaudioframe/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)