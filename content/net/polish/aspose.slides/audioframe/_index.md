---
title: AudioFrame
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Reprezentuje klip audio na slajdzie.
type: docs
weight: 870
url: /pl/aspose.slides/audioframe/
---
## AudioFrame klasa

Reprezentuje klip dźwiękowy na slajdzie.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Zwraca kolekcję wartości regulacji kształtu. Tylko do odczytu [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Zwraca lub ustawia tekst alternatywny powiązany z kształtem. Odczyt/zapis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Zwraca lub ustawia tytuł tekstu alternatywnego powiązanego z kształtem. Odczyt/zapis String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Zwraca lub ustawia indeks ostatniej ścieżki. Odczyt/zapis Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Zwraca lub ustawia czas ostatniej ścieżki. Odczyt/zapis Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Zwraca lub ustawia indeks ścieżki początkowej. Odczyt/zapis Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Zwraca lub ustawia czas ścieżki początkowej. Odczyt/zapis Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Właściwość określa, jak kształt będzie renderowany w trybie wyświetlania czarno-białym. Odczyt/zapis [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | Pobiera kolekcję napisów zamkniętych powiązanych z ramką audio. Ta właściwość jest tylko do odczytu i zwraca [`ICaptionsCollection`](../icaptionscollection) zawierający wszystkie ścieżki napisów. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Zwraca liczbę punktów połączeń na kształcie. Tylko do odczytu Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Zwraca niestandardowe dane kształtu. Tylko do odczytu [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Zwraca obiekt EffectFormat zawierający efekty pikselowe zastosowane do kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości efektów. Tylko do odczytu [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Określa, czy dźwięk jest osadzony w prezentacji. Tylko do odczytu Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Zwraca lub ustawia osadzony obiekt audio. Odczyt/zapis [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Określa czas trwania początkowego wyciszenia mediów w milisekundach. Odczyt/zapis Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Określa czas trwania końcowego wyciszenia mediów w milisekundach. Odczyt/zapis Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Zwraca obiekt FillFormat zawierający właściwości formatowania wypełnienia dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości wypełnienia. Tylko do odczytu [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Zwraca lub ustawia właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Pobiera lub ustawia wysokość kształtu, wyrażoną w punktach. Odczyt/zapis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Określa, czy kształt jest ukryty. Odczyt/zapis Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Określa, czy AudioFrame jest ukryty. Odczyt/zapis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Zwraca lub ustawia hiperlink definiowany dla kliknięcia myszy. Odczyt/zapis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Zwraca menedżera hiperlinków. Tylko do odczytu [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Zwraca lub ustawia hiperlink definiowany dla najechania myszą. Odczyt/zapis [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Określa, czy PictureFrame jest obiektem Cameo. Tylko do odczytu Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Pobiera lub ustawia opcję „Oznacz jako dekoracyjny”. Odczyt/zapis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Określa, czy kształt jest grupowany. Tylko do odczytu Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Określa, czy kształt jest TextHolder_PPT. Tylko do odczytu Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Zwraca obiekt LineFormat zawierający właściwości formatowania linii dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości linii. Tylko do odczytu [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Zwraca lub ustawia nazwę pliku audio powiązanego z AudioFrame. Odczyt/zapis String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Zwraca lub ustawia nazwę kształtu. Nie może być null. W razie potrzeby użyj pustego ciągu. Odczyt/zapis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Zwraca unikalny identyfikator slajdu, który pozostaje stały przez cały czas życia kształtu i umożliwia niezawodne odwoływanie się do kształtu w kodzie PowerPoint lub interop. Tylko do odczytu UInt32. Zobacz także [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Zwraca obiekt nadrzędny GroupShape, jeśli kształt jest grupowany. W przeciwnym wypadku zwraca null. Tylko do odczytu [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Zwraca obiekt PictureFillFormat dla ramki obrazu. Tylko do odczytu [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Zwraca blokady kształtu. Tylko do odczytu [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Zwraca placeholder dla kształtu. Zwraca null, jeśli kształt nie ma placeholdera. Tylko do odczytu [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Określa, czy dźwięk odtwarzany jest na wszystkich slajdach. Odczyt/zapis Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Określa, czy dźwięk jest zapętlony. Odczyt/zapis Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Zwraca lub ustawia tryb odtwarzania audio. Odczyt/zapis [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Zwraca prezentację nadrzędną slajdu. Tylko do odczytu [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Zwraca lub ustawia surowe właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Zwraca lub ustawia skalę wysokości (względem pierwotnego rozmiaru obrazu) ramki obrazu. Wartość 1,0 odpowiada 100 %. Odczyt/zapis Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Zwraca lub ustawia skalę szerokości (względem pierwotnego rozmiaru obrazu) ramki obrazu. Wartość 1,0 odpowiada 100 %. Odczyt/zapis Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Określa, czy audio jest automatycznie przewijane do początku po odtworzeniu. Odczyt/zapis Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Zwraca lub ustawia liczbę stopni obrotu kształtu wokół osi Z. Pozytywna wartość oznacza obrót zgodny z ruchem wskazówek zegara; negatywna – przeciwny. Odczyt/zapis Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Zwraca blokady kształtu. Tylko do odczytu [`IPictureFrameLock`](../ipictureframelock). (2 właściwości) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Zwraca obiekt stylu kształtu. Tylko do odczytu [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Zwraca lub ustawia typ AutoShape dla PictureFrame. Dozwolone są wszystkie elementy zestawu [`ShapeType`](../shapetype), z wyjątkiem wszystkich rodzajów linii: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Zwraca nadrzędny slajd kształtu. Tylko do odczytu [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Zwraca obiekt ThreeDFormat zawierający właściwości efektów 3D dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości 3D. Tylko do odczytu [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Określa czas trwania, który ma zostać usunięty z końca mediów podczas odtwarzania, w milisekundach. Odczyt/zapis Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Określa czas trwania, który ma zostać usunięty z początku mediów podczas odtwarzania, w milisekundach. Odczyt/zapis Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Zwraca wewnętrzny, prezentacyjny identyfikator przeznaczony do użytku przez dodatki lub inny kod. Ponieważ wartość może być zmieniona przez użytkownika lub programowo, nie należy jej traktować jako trwały unikalny klucz. Tylko do odczytu UInt32. Zobacz także [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Zwraca lub ustawia głośność audio. Odczyt/zapis [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Zwraca lub ustawia głośność audio w procentach. Odczyt/zapis Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Pobiera lub ustawia szerokość kształtu, wyrażoną w punktach. Odczyt/zapis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Pobiera lub ustawia współrzędną X lewego górnego rogu kształtu, wyrażoną w punktach. Odczyt/zapis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Pobiera lub ustawia współrzędną Y lewego górnego rogu kształtu, wyrażoną w punktach. Odczyt/zapis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Zwraca pozycję kształtu w kolejności Z. Shapes[0] zwraca kształt znajdujący się z tyłu kolejności Z, a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności Z. Tylko do odczytu Int32. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Tworzy i zwraca tablicę elementów kształtu. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Zwraca podstawowy kształt placeholder (kształt z układu i/lub slajdu głównego, z którego dziedziczy bieżący kształt). Zwraca null, jeśli bieżący kształt nie jest dziedziczony. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Zwraca kopię ścieżki kształtu geometrycznego. Współrzędne są względem lewego górnego rogu kształtu. |
| [GetImage](../../aspose.slides/shape/getimage)() | Zwraca miniaturę kształtu. Domyślnie używany jest typ ShapeThumbnailBounds.Shape określający granice miniatury. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds,float,float) | Zwraca miniaturę kształtu. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definiuje, że ten kształt nie jest placeholderem. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aktualizuje geometrię kształtu z obiektu [`IGeometryPath`](../igeometrypath). Współrzędne muszą być względem lewego górnego rogu kształtu. Zmienia typ kształtu ([`ShapeType`](../geometryshape/shapetype)) na Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aktualizuje geometrię kształtu z tablicy [`IGeometryPath`](../igeometrypath). Współrzędne muszą być względem lewego górnego rogu kształtu. Zmienia typ kształtu ([`ShapeType`](../geometryshape/shapetype)) na Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Zapisuje zawartość kształtu jako plik SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream,ISVGOptions) | Zapisuje zawartość kształtu jako plik SVG. |

### Przykłady

Poniższe przykłady pokazują, jak zmienić opcje odtwarzania audio.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Pobiera kształt AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Ustawia tryb odtwarzania na odtwarzanie po kliknięciu
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Ustawia głośność na Niska
    audioFrame.Volume = AudioVolumeMode.Low;
    // Ustawia odtwarzanie audio na wszystkich slajdach
    audioFrame.PlayAcrossSlides = true;
    // Wyłącza powtarzanie dla audio
    audioFrame.PlayLoopMode = false;
    // Ukrywa AudioFrame podczas pokazu slajdów
    audioFrame.HideAtShowing = true;
    // Cofa audio do początku po odtworzeniu
    audioFrame.RewindAudio = true;
    // Zapisuje plik PowerPoint na dysku
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Zobacz także

* klasa [PictureFrame](../pictureframe)
* interfejs [IAudioFrame](../iaudioframe)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->