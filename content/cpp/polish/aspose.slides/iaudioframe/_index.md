---
title: IAudioFrame
second_title: Referencja API Aspose.Slides dla C++
description: Reprezentuje klip audio na slajdzie.
type: docs
weight: 1353
url: /pl/aspose.slides/iaudioframe/
---
## IAudioFrame klasa


Reprezentuje klip audio na slajdzie.

```cpp
class IAudioFrame : public virtual Aspose::Slides::IPictureFrame
```

## Metody

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Dodaje nowy placeholder, jeśli go nie ma i ustawia właściwości placeholdera na określony. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Tworzy i zwraca tablicę elementów kształtu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Zwraca wartość dopasowania kształtu pod określonym indeksem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Zwraca kolekcję wartości dopasowania kształtu. Tylko do odczytu [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Zwraca tekst alternatywny powiązany z kształtem. Tylko do odczytu [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Zwraca tytuł tekstu alternatywnego powiązanego z kształtem. Tylko do odczytu [System::String](../../system/string/). |
| virtual **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() | Zwraca ostatni indeks ścieżki. Tylko do odczytu **int32_t**. |
| virtual **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() | Zwraca czas ostatniej ścieżki. Tylko do odczytu **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() | Zwraca indeks początkowej ścieżki. Tylko do odczytu **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() | Zwraca czas początkowej ścieżki. Tylko do odczytu **int32_t**. |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białym. Tylko do odczytu [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | Pobiera kolekcję zamkniętych napisów powiązanych z ramką audio. Ta właściwość jest tylko do odczytu i zwraca [ICaptionsCollection](../icaptionscollection/) zawierający wszystkie ścieżki napisów. |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Zwraca liczbę miejsc połączeń na kształcie. Tylko do odczytu **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Zwraca dane niestandardowe kształtu. Tylko do odczytu [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Zwraca obiekt [EffectFormat](../effectformat/), który zawiera efekty pikseli zastosowane do kształtu. Tylko do odczytu [IEffectFormat](../ieffectformat/). |
| virtual **bool** [get_Embedded](./get_embedded/)() | Określa, czy dźwięk jest osadzony w prezentacji. Tylko do odczytu **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() | Zwraca osadzony obiekt audio. Tylko do odczytu [IAudio](../iaudio/). |
| virtual **float** [get_FadeInDuration](./get_fadeinduration/)() | Określa czas trwania początkowego zanikania (fade-in) mediów w milisekundach. Tylko do odczytu **float**. |
| virtual **float** [get_FadeOutDuration](./get_fadeoutduration/)() | Określa czas trwania końcowego zanikania (fade-out) mediów w milisekundach. Tylko do odczytu **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Zwraca obiekt [FillFormat](../fillformat/), który zawiera właściwości formatowania wypełnienia dla kształtu. Tylko do odczytu [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Zwraca właściwości ramki kształtu. Tylko do odczytu [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Pobiera wysokość kształtu, mierzona w punktach. Tylko do odczytu **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Określa, czy kształt jest ukryty. Tylko do odczytu **bool**. |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | Określa, czy [AudioFrame](../audioframe/) jest ukryty. Tylko do odczytu **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Zwraca hiperłącze zdefiniowane dla kliknięcia myszy. Tylko do odczytu [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Menedżer hiperłączy Tylko do odczytu [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Zwraca hiperłącze zdefiniowane dla najechania myszą. Tylko do odczytu [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Pobiera opcję 'Mark as decorative'. Odczyt/zapis **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Określa, czy kształt jest grupowany. Tylko do odczytu **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Określa, czy kształt jest TextHolder. Tylko do odczytu **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Zwraca obiekt [LineFormat](../lineformat/), który zawiera właściwości formatowania linii dla kształtu. Tylko do odczytu [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | Zwraca nazwę pliku audio, który jest powiązany z [AudioFrame](../audioframe/). Tylko do odczytu [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Zwraca nazwę kształtu. Tylko do odczytu [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Zwraca unikalny identyfikator scoped do slajdu, który pozostaje stały przez cały okres życia kształtu i pozwala PowerPointowi lub kodowi interop na niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie. Tylko do odczytu **uint32_t**. Zobacz także [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Zwraca rodzica [GroupShape](../groupshape/) jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | Zwraca obiekt [PictureFillFormat](../picturefillformat/) dla ramki obrazu. Tylko do odczytu [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | Zwraca blokady [PictureFrame](../pictureframe/). Tylko do odczytu [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Zwraca placeholder dla kształtu. Tylko do odczytu [IPlaceholder](../iplaceholder/). |
| virtual **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() | Określa, czy audio odtwarzane jest na wszystkich slajdach. Tylko do odczytu **bool**. |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | Określa, czy audio jest zapętlone. Tylko do odczytu **bool**. |
| virtual [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() | Zwraca tryb odtwarzania audio. Tylko do odczytu [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Zwraca prezentację. Tylko do odczytu [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Zwraca surowe właściwości ramki kształtu. Tylko do odczytu [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | Zwraca skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1,0 odpowiada 100%. Tylko do odczytu **float**. |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | Zwraca skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1,0 odpowiada 100%. Tylko do odczytu **float**. |
| virtual **bool** [get_RewindAudio](./get_rewindaudio/)() | Określa, czy audio jest automatycznie przewijane do początku po odtworzeniu. Tylko do odczytu **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Zwraca liczbę stopni, o które określony kształt jest obrócony wokół osi z. Dodatnia wartość wskazuje obrót zgodny z ruchem wskazówek zegara; ujemna wskazuje obrót przeciwny. Tylko do odczytu **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Zwraca blokady kształtu. Tylko do odczytu [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Zwraca obiekt stylu kształtu. Tylko do odczytu [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Zwraca typ presetu geometrii. Uwaga: przy zmianie wartości wszystkie wartości dopasowań zostaną zresetowane do wartości domyślnych. Tylko do odczytu [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Zwraca bazowy slajd. Tylko do odczytu [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Zwraca obiekt [ThreeDFormat](../threedformat/), który zawiera właściwości formatowania linii dla kształtu. Tylko do odczytu [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | Określa czas trwania, który ma zostać usunięty z końca mediów podczas odtwarzania, w milisekundach. Tylko do odczytu **float**. |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | Określa czas trwania, który ma zostać usunięty z początku mediów podczas odtwarzania, w milisekundach. Tylko do odczytu **float**. |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Zwraca wewnętrzny, scoped do prezentacji identyfikator przeznaczony do użytku przez dodatki lub inny kod. Ponieważ wartość tę można ponownie przypisać przez użytkownika lub programowo, nie należy traktować jej jako trwałego unikalnego klucza. Tylko do odczytu **uint32_t**. Zobacz także [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | Zwraca poziom głośności audio. Tylko do odczytu [AudioVolumeMode](../audiovolumemode/). |
| virtual **float** [get_VolumeValue](./get_volumevalue/)() | Zwraca poziom głośności audio w procentach. Tylko do odczytu **float**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Pobiera szerokość kształtu, mierzona w punktach. Tylko do odczytu **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Pobiera współrzędną x lewego górnego rogu kształtu, mierzona w punktach. Tylko do odczytu **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Pobiera współrzędną y lewego górnego rogu kształtu, mierzona w punktach. Tylko do odczytu **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Zwraca pozycję kształtu w kolejności z-order. Shapes[0] zwraca kształt z tyłu kolejności, a Shapes[Shapes.Count - 1] zwraca kształt z przodu kolejności. Tylko do odczytu **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Zwraca podstawowy placeholder kształtu (kształt z układu i/lub slajdu master, z którego dziedziczy bieżący kształt). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Zwraca kopię ścieżki geometrii kształtu. Współrzędne są względem lewego górnego rogu kształtu. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie obiektów niestandardowych. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Zwraca miniaturę kształtu. Domyślnie używany jest typ ograniczeń miniatury [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Zwraca miniaturę kształtu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogia wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogia operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje instrukcję lock() języka C#. Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje wartość typu referencyjnego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Definiuje, że ten kształt nie jest placeholderem. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Ustawia tekst alternatywny powiązany z kształtem. Zapis [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Ustawia tytuł tekstu alternatywnego powiązanego z kształtem. Zapis [System::String](../../system/string/). |
| virtual void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) | Ustawia ostatni indeks ścieżki. Zapis **int32_t**. |
| virtual void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) | Ustawia czas ostatniej ścieżki. Zapis **int32_t**. |
| virtual void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) | Ustawia indeks początkowej ścieżki. Zapis **int32_t**. |
| virtual void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) | Ustawia czas początkowej ścieżki. Zapis **int32_t**. |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białym. Zapis [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Ustawia osadzony obiekt audio. Zapis [IAudio](../iaudio/). |
| virtual void [set_FadeInDuration](./set_fadeinduration/)(**float**) | Określa czas trwania początkowego zanikania (fade-in) mediów w milisekundach. Zapis **float**. |
| virtual void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) | Określa czas trwania końcowego zanikania (fade-out) mediów w milisekundach. Zapis **float**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ustawia właściwości ramki kształtu. Zapis [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Ustawia wysokość kształtu, mierzona w punktach. Zapis **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Określa, czy kształt jest ukryty. Zapis **bool**. |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | Określa, czy [AudioFrame](../audioframe/) jest ukryty. Zapis **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Ustawia hiperłącze zdefiniowane dla kliknięcia myszy. Zapis [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Ustawia hiperłącze zdefiniowane dla najechania myszą. Zapis [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Ustawia opcję 'Mark as decorative'. Odczyt/zapis **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | Ustawia nazwę pliku audio, który jest powiązany z [AudioFrame](../audioframe/). Zapis [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Ustawia nazwę kształtu. Zapis [System::String](../../system/string/). |
| virtual void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) | Określa, czy audio odtwarzane jest na wszystkich slajdach. Zapis **bool**. |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | Określa, czy audio jest zapętlone. Zapis **bool**. |
| virtual void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) | Ustawia tryb odtwarzania audio. Zapis [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ustawia surowe właściwości ramki kształtu. Zapis [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | Ustawia skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1,0 odpowiada 100%. Zapis **float**. |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | Ustawia skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1,0 odpowiada 100%. Zapis **float**. |
| virtual void [set_RewindAudio](./set_rewindaudio/)(**bool**) | Określa, czy audio jest automatycznie przewijane do początku po odtworzeniu. Zapis **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z. Dodatnia wartość wskazuje obrót zgodny z ruchem wskazówek zegara; ujemna wskazuje obrót przeciwny. Zapis **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Ustawia typ presetu geometrii. Uwaga: przy zmianie wartości wszystkie wartości dopasowań zostaną zresetowane do wartości domyślnych. Zapis [Slides::ShapeType](../shapetype/). |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | Określa czas trwania, który ma zostać usunięty z końca mediów podczas odtwarzania, w milisekundach. Zapis **float**. |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | Określa czas trwania, który ma zostać usunięty z początku mediów podczas odtwarzania, w milisekundach. Zapis **float**. |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | Ustawia poziom głośności audio. Zapis [AudioVolumeMode](../audiovolumemode/). |
| virtual void [set_VolumeValue](./set_volumevalue/)(**float**) | Ustawia poziom głośności audio w procentach. Zapis **float**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Ustawia szerokość kształtu, mierzona w punktach. Zapis **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Ustawia współrzędną x lewego górnego rogu kształtu, mierzona w punktach. Zapis **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Ustawia współrzędną y lewego górnego rogu kształtu, mierzona w punktach. Zapis **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Aktualizuje geometrię kształtu z obiektu [IGeometryPath](../igeometrypath/). Współrzędne muszą być względem lewego górnego rogu kształtu. Zmienia typ kształtu ([ShapeType](../shapetype/)) na [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Aktualizuje geometrię kształtu z tablicy [IGeometryPath](../igeometrypath/). Współrzędne muszą być względem lewego górnego rogu kształtu. Zmienia typ kształtu ([ShapeType](../shapetype/)) na [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera aktualną wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję obiektów niestandardowych na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji lock() języka C#. Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Zapisuje zawartość [Shape](../shape/) jako plik SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Zapisuje zawartość [Shape](../shape/) jako plik SVG. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Zobacz także

* Klasa [IPictureFrame](../ipictureframe/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)