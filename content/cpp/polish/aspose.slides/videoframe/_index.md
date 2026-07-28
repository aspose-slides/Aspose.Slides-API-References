---
title: VideoFrame
second_title: Aspose.Slides - referencja API dla C++
description: Reprezentuje klip wideo na slajdzie.
type: docs
weight: 5552
url: /pl/aspose.slides/videoframe/
---
## Klasa VideoFrame

Reprezentuje klip wideo na slajdzie.

```cpp
class VideoFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IVideoFrame
```

## Metody

| Metoda | Opis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Dodaje nowy placeholder, jeśli nie istnieje, i ustawia właściwości placeholder na określony. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Tworzy i zwraca tablicę elementów kształtu. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Zwraca wartość dopasowania kształtu pod wskazanym indeksem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Zwraca kolekcję wartości dopasowań kształtu. Tylko do odczytu [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Zwraca tekst alternatywny powiązany z kształtem. Odczyt [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Zwraca tytuł tekstu alternatywnego powiązanego z kształtem. Odczyt [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. Odczyt [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | Pobiera kolekcję zamkniętych napisów powiązanych z ramką wideo. Ta własność jest tylko do odczytu i zwraca [ICaptionsCollection](../icaptionscollection/) zawierający wszystkie ścieżki napisów. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Zwraca liczbę punktów połączeń na kształcie. Tylko do odczytu **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Zwraca własne dane kształtu. Tylko do odczytu [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Zwraca obiekt [EffectFormat](../effectformat/), który zawiera efekty pikseli zastosowane do kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości efektów. Tylko do odczytu [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_EmbeddedVideo](./get_embeddedvideo/)() override | Zwraca osadzony obiekt wideo. Odczyt [IVideo](../ivideo/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Zwraca obiekt [FillFormat](../fillformat/), który zawiera właściwości formatowania wypełnienia dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie posiadają właściwości wypełnienia. Tylko do odczytu [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Zwraca właściwości ramki kształtu. Odczyt [IShapeFrame](../ishapeframe/). |
| **bool** [get_FullScreenMode](./get_fullscreenmode/)() override | Określa, czy wideo jest wyświetlane w trybie pełnoekranowym. Odczyt **bool**. |
| **float** [get_Height](../shape/get_height/)() override | Pobiera wysokość kształtu, mierzona w punktach. Odczyt **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Określa, czy kształt jest ukryty. Odczyt **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | Określa, czy [VideoFrame](./) jest ukryty. Odczyt **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Zwraca hiperlink zdefiniowany dla kliknięcia myszą. Odczyt [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Zwraca menedżera hiperlinków. Tylko do odczytu [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Zwraca hiperlink zdefiniowany dla najechania myszą. Odczyt [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | Określa, czy [PictureFrame](../pictureframe/) jest obiektem Cameo. Tylko do odczytu **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Pobiera opcję 'Mark as decorative'. Odczyt/zapis **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Określa, czy kształt jest grupowany. Tylko do odczytu **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Określa, czy kształt jest TextHolder_PPT. Tylko do odczytu **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Zwraca obiekt [LineFormat](../lineformat/), który zawiera właściwości formatowania linii dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości linii. Tylko do odczytu [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Zwraca nazwę pliku wideo powiązanego z [VideoFrame](./). Odczyt [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Zwraca nazwę kształtu. Nie może być null. W razie potrzeby użyj pustego ciągu. Odczyt [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Zwraca unikalny identyfikator w zakresie slajdu, który pozostaje stały przez cały czas życia kształtu i umożliwia PowerPointowi lub kodowi interop niezawodne odwoływanie się do kształtu z dowolnego miejsca dokumentu. Tylko do odczytu **uint32_t**. Zobacz także [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Zwraca obiekt rodzica [GroupShape](../groupshape/), jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | Zwraca obiekt [PictureFillFormat](../picturefillformat/) dla ramki obrazu. Tylko do odczytu [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | Zwraca blokady kształtu. Tylko do odczytu [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Zwraca placeholder dla kształtu. Zwraca null, jeśli kształt nie ma placeholdera. Tylko do odczytu [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | Określa, czy wideo jest w pętli. Odczyt **bool**. |
| [VideoPlayModePreset](../videoplaymodepreset/) [get_PlayMode](./get_playmode/)() override | Zwraca tryb odtwarzania wideo. Odczyt [VideoPlayModePreset](../videoplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Zwraca prezentację nadrzędną slajdu. Tylko do odczytu [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Zwraca surowe właściwości ramki kształtu. Odczyt [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | Zwraca skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100%. Odczyt **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | Zwraca skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100%. Odczyt **float**. |
| **bool** [get_RewindVideo](./get_rewindvideo/)() override | Określa, czy wideo jest automatycznie przewijane do początku po zakończeniu odtwarzania. Odczyt **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Zwraca liczbę stopni, o które określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodnie z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwny do ruchu wskazówek zegara. Odczyt **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Zwraca blokady kształtu. Tylko do odczytu [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Zwraca obiekt stylu kształtu. Tylko do odczytu [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Zwraca slajd nadrzędny kształtu. Tylko do odczytu [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Zwraca obiekt [ThreeDFormat](../threedformat/), który zawiera właściwości efektów 3D dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości 3D. Tylko do odczytu [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | Obetnij koniec [ms] |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | Obetnij początek [ms] |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Zwraca wewnętrzny identyfikator w zakresie prezentacji przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie powinna być traktowana jako trwały unikalny klucz. Tylko do odczytu **uint32_t**. Zobacz także [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | Zwraca poziom głośności audio. Odczyt [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_Width](../shape/get_width/)() override | Pobiera szerokość kształtu, mierzona w punktach. Odczyt **float**. |
| **float** [get_X](../shape/get_x/)() override | Pobiera współrzędną x lewego górnego rogu kształtu, mierzona w punktach. Odczyt **float**. |
| **float** [get_Y](../shape/get_y/)() override | Pobiera współrzędną y lewego górnego rogu kształtu, mierzona w punktach. Odczyt **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Zwraca pozycję kształtu w kolejności z. Shapes[0] zwraca kształt na końcu kolejności z, a Shapes[Shapes.Count - 1] zwraca kształt na początku kolejności z. Tylko do odczytu **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Zwraca podstawowy kształt placeholder (kształt z układu i/lub slajdu głównego, z którego dziedziczy bieżący kształt). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Zwraca kopię ścieżki geometrycznego kształtu. Współrzędne są względem lewego górnego rogu kształtu. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Zwraca miniaturkę kształtu. Typ granic miniaturki [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) jest używany domyślnie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Zwraca miniaturkę kształtu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współny licznik referencji o podaną wartość. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Określa, że ten kształt nie jest placeholderem. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Ustawia tekst alternatywny powiązany z kształtem. Zapis [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Ustawia tytuł tekstu alternatywnego powiązanego z kształtem. Zapis [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. Zapis [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedVideo](./set_embeddedvideo/)([System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) override | Ustawia osadzony obiekt wideo. Zapis [IVideo](../ivideo/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ustawia właściwości ramki kształtu. Zapis [IShapeFrame](../ishapeframe/). |
| void [set_FullScreenMode](./set_fullscreenmode/)(**bool**) override | Określa, czy wideo jest wyświetlane w trybie pełnoekranowym. Zapis **bool**. |
| void [set_Height](../shape/set_height/)(**float**) override | Ustawia wysokość kształtu, mierzoną w punktach. Zapis **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Określa, czy kształt jest ukryty. Zapis **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | Określa, czy [VideoFrame](./) jest ukryty. Zapis **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ustawia hiperlink zdefiniowany dla kliknięcia myszą. Zapis [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ustawia hiperlink zdefiniowany dla najechania myszą. Zapis [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Ustawia opcję 'Mark as decorative'. Odczyt/zapis **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Ustawia nazwę pliku wideo powiązanego z [VideoFrame](./). Zapis [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Ustawia nazwę kształtu. Nie może być null. W razie potrzeby użyj pustego ciągu. Zapis [System::String](../../system/string/). |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | Określa, czy wideo jest w pętli. Zapis **bool**. |
| void [set_PlayMode](./set_playmode/)([VideoPlayModePreset](../videoplaymodepreset/)) override | Ustawia tryb odtwarzania wideo. Zapis [VideoPlayModePreset](../videoplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ustawia surowe właściwości ramki kształtu. Zapis [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | Ustawia skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100%. Zapis **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | Ustawia skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1.0 odpowiada 100%. Zapis **float**. |
| void [set_RewindVideo](./set_rewindvideo/)(**bool**) override | Określa, czy wideo jest automatycznie przewijane do początku po zakończeniu odtwarzania. Zapis **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodnie z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwny. Zapis **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | Obetnij koniec [ms] |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | Obetnij początek [ms] |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | Ustawia poziom głośności audio. Zapis [AudioVolumeMode](../audiovolumemode/). |
| void [set_Width](../shape/set_width/)(**float**) override | Ustawia szerokość kształtu, mierzoną w punktach. Zapis **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. Zapis **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. Zapis **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Aktualizuje geometrię kształtu z obiektu [IGeometryPath](../igeometrypath/). Współrzędne muszą być względem lewego górnego rogu kształtu. Zmienia typ kształtu ([ShapeType](../shapetype/)) na [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Aktualizuje geometrię kształtu z tablicy [IGeometryPath](../igeometrypath/). Współrzędne muszą być względem lewego górnego rogu kształtu. Zmienia typ kształtu ([ShapeType](../shapetype/)) na [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; użyj inteligentnych wskaźników lub ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Zapisuje zawartość [Shape](../shape/) jako plik SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Zapisuje zawartość [Shape](../shape/) jako plik SVG. |
| virtual  [~Object](../../system/object/~object/)() | Zniszcza obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [PictureFrame](../pictureframe/)
* Klasa [IVideoFrame](../ivideoframe/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)