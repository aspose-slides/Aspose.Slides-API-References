---
title: VideoFrame
second_title: Aspose.Sildes dla .NET: odniesienie API
description: Reprezentuje klip wideo na slajdzie.
type: docs
weight: 11700
url: /pl/aspose.slides/videoframe/
---
## Klasa VideoFrame

Reprezentuje klip wideo na slajdzie.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Zwraca kolekcję wartości regulacji kształtu. Tylko do odczytu [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Zwraca lub ustawia alternatywny tekst powiązany z kształtem. Odczyt/zapis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Zwraca lub ustawia tytuł alternatywnego tekstu powiązanego z kształtem. Odczyt/zapis String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białego. Odczyt/zapis [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Zwraca kolekcję zamkniętych napisów powiązanych z klatką wideo. Ta właściwość jest tylko do odczytu i zwraca [`ICaptionsCollection`](../icaptionscollection) zawierający wszystkie ścieżki napisów. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Zwraca liczbę punktów połączeń na kształcie. Tylko do odczytu Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Zwraca niestandardowe dane kształtu. Tylko do odczytu [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Zwraca obiekt EffectFormat zawierający efekty pikselowe zastosowane do kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości efektów. Tylko do odczytu [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Zwraca lub ustawia osadzony obiekt wideo. Odczyt/zapis [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości wypełnienia. Tylko do odczytu [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Zwraca lub ustawia właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Określa, czy wideo jest wyświetlane w trybie pełnoekranowym. Odczyt/zapis Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Zwraca lub ustawia wysokość kształtu, mierzona w punktach. Odczyt/zapis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Określa, czy kształt jest ukryty. Odczyt/zapis Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Określa, czy VideoFrame jest ukryty. Odczyt/zapis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszą. Odczyt/zapis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Zwraca menedżer hiperłączy. Tylko do odczytu [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą. Odczyt/zapis [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Określa, czy PictureFrame jest obiektem Cameo. Tylko do odczytu Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Zwraca lub ustawia opcję 'Mark as decorative'. Odczyt/zapis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Określa, czy kształt jest pogrupowany. Tylko do odczytu Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Określa, czy kształt jest TextHolder_PPT. Tylko do odczytu Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości linii. Tylko do odczytu [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Zwraca lub ustawia nazwę pliku wideo powiązanego z VideoFrame. Odczyt/zapis String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Zwraca lub ustawia nazwę kształtu. Nie może być null. W razie potrzeby użyj pustego ciągu. Odczyt/zapis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Zwraca unikalny identyfikator zakresu slajdu, który pozostaje stały przez cały okres życia kształtu i pozwala PowerPointowi lub kodowi interop niezawodnie odwoływać się do kształtu z dowolnego miejsca w dokumencie. Tylko do odczytu UInt32. Zobacz także [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Zwraca obiekt GroupShape nadrzędny, jeśli kształt jest pogrupowany. W przeciwnym razie zwraca null. Tylko do odczytu [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Zwraca obiekt PictureFillFormat dla ramki obrazu. Tylko do odczytu [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Zwraca blokady kształtu. Tylko do odczytu [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Zwraca placeholder dla kształtu. Zwraca null, jeśli kształt nie ma placeholdera. Tylko do odczytu [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Określa, czy wideo jest zapętlone. Odczyt/zapis Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Zwraca lub ustawia tryb odtwarzania wideo. Odczyt/zapis [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Zwraca prezentację nadrzędną slajdu. Tylko do odczytu [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Zwraca lub ustawia surowe właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Zwraca lub ustawia skalę wysokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1,0 odpowiada 100 %. Odczyt/zapis Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Zwraca lub ustawia skalę szerokości (względem oryginalnego rozmiaru obrazu) ramki obrazu. Wartość 1,0 odpowiada 100 %. Odczyt/zapis Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Określa, czy wideo jest automatycznie przewijane do początku po zakończeniu odtwarzania. Odczyt/zapis Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z. Dodatnia wartość oznacza obrót zgodny z ruchem wskazówek zegara; ujemna – przeciwny. Odczyt/zapis Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Zwraca blokady kształtu. Tylko do odczytu [`IPictureFrameLock`](../ipictureframelock). (2 właściwości) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Zwraca obiekt stylu kształtu. Tylko do odczytu [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Zwraca lub ustawia typ AutoShape dla PictureFrame. Dozwolone są wszystkie elementy zestawu [`ShapeType`](../shapetype), z wyjątkiem wszelkich linii: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Zwraca slajd nadrzędny kształtu. Tylko do odczytu [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Zwraca obiekt ThreeDFormat zawierający właściwości efektu 3D dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości 3D. Tylko do odczytu [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Przycięcie końca [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Przycięcie początku [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Zwraca wewnętrzny identyfikator zakresu prezentacji przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować jako trwały unikalny klucz. Tylko do odczytu UInt32. Zobacz także [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Zwraca lub ustawia głośność dźwięku. Odczyt/zapis [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Zwraca lub ustawia szerokość kształtu, mierzona w punktach. Odczyt/zapis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Zwraca lub ustawia współrzędną x lewego górnego rogu kształtu, mierzona w punktach. Odczyt/zapis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Zwraca lub ustawia współrzędną y lewego górnego rogu kształtu, mierzona w punktach. Odczyt/zapis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Zwraca pozycję kształtu w kolejności z. Shapes[0] zwraca kształt na końcu kolejności z, a Shapes[Shapes.Count - 1] zwraca kształt na początku kolejności z. Tylko do odczytu Int32. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Tworzy i zwraca tablicę elementów kształtu. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu nadrzędnego, z którego dziedziczy bieżący kształt). Zwraca null, jeśli bieżący kształt nie jest dziedziczony. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Zwraca kopię ścieżki geometrycznego kształtu. Współrzędne są względem lewego górnego rogu kształtu. |
| [GetImage](../../aspose.slides/shape/getimage)() | Zwraca miniaturkę kształtu. Domyślnie używany jest typ ShapeThumbnailBounds.Shape dla granic miniaturki. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Zwraca miniaturkę kształtu. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Określa, że ten kształt nie jest placeholderem. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualizuje geometrię kształtu z obiektu [`IGeometryPath`](../igeometrypath). Współrzędne muszą być względem lewego górnego rogu kształtu. Zmienia typ kształtu ([`ShapeType`](../geometryshape/shapetype)) na Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualizuje geometrię kształtu z tablicy [`IGeometryPath`](../igeometrypath). Współrzędne muszą być względem lewego górnego rogu kształtu. Zmienia typ kształtu ([`ShapeType`](../geometryshape/shapetype)) na Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Zapisuje zawartość Shape jako plik SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Zapisuje zawartość Shape jako plik SVG. |

### Zobacz także

* klasa [PictureFrame](../pictureframe)
* interfejs [IVideoFrame](../ivideoframe)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->