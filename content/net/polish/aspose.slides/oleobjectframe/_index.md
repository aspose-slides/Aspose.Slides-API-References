---
title: OleObjectFrame
second_title: Odwołanie do API Aspose.Sildes dla .NET
description: Reprezentuje obiekt OLE na slajdzie.
type: docs
weight: 9210
url: /pl/aspose.slides/oleobjectframe/
---
## OleObjectFrame klasa

Reprezentuje obiekt OLE na slajdzie.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Zwraca lub ustawia alternatywny tekst powiązany z kształtem. Odczyt/zapis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Zwraca lub ustawia tytuł alternatywnego tekstu powiązanego z kształtem. Odczyt/zapis String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Umożliwia pobranie podstawowego interfejsu IGraphicalObject. Tylko odczyt [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Właściwość określa, jak kształt będzie renderowany w trybie czarno-biały. Odczyt/zapis [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Zwraca liczbę miejsc połączeń w kształcie. Tylko odczyt Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Zwraca własne dane kształtu. Tylko odczyt [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Zwraca obiekt EffectFormat, który zawiera efekty pikselowe zastosowane do kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości efektu. Tylko odczyt [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Pobiera lub ustawia informacje o osadzonych danych OLE. Odczyt/zapis [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Zwraca nazwę pliku osadzonego obiektu OLE. |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Zwraca ścieżkę osadzonego obiektu OLE. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości wypełnienia. Tylko odczyt [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Zwraca lub ustawia właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Zwraca blokady kształtu. Tylko odczyt [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Pobiera lub ustawia wysokość kształtu, mierzoną w punktach. Odczyt/zapis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Określa, czy kształt jest ukryty. Odczyt/zapis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla kliknięcia myszą. Odczyt/zapis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Zwraca menedżer hiperłączy. Tylko odczyt [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Zwraca lub ustawia hiperłącze zdefiniowane dla najechania myszą. Odczyt/zapis [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Pobiera lub ustawia opcję 'Mark as decorative'. Odczyt/zapis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Określa, czy kształt jest grupowany. Tylko odczyt Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Określa, czy obiekt jest widoczny jako ikona. Odczyt/zapis Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Określa, czy obiekt jest powiązany z zewnętrznym plikiem. Tylko odczyt Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Określa, czy kształt jest TextHolder_PPT. Tylko odczyt Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Zwraca obiekt LineFormat, który zawiera właściwości formatowania linii dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości linii. Tylko odczyt [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Zwraca pełną ścieżkę do pliku powiązanego. Używana będzie krótka nazwa pliku. Tylko odczyt String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Zwraca pełną ścieżkę do pliku powiązanego. Używana będzie długa nazwa pliku. Odczyt/zapis String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Zwraca względną ścieżkę do pliku powiązanego, jeśli istnieje, w przeciwnym razie zwraca pusty ciąg. Tylko odczyt String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Zwraca lub ustawia nazwę kształtu. Nie może być null. W razie potrzeby użyj pustego ciągu. Odczyt/zapis String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Zwraca lub ustawia nazwę obiektu. Odczyt/zapis String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Zwraca ProgID obiektu. Tylko odczyt String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Zwraca unikalny identyfikator zakresu slajdu, który pozostaje stały przez całą żywotność kształtu i umożliwia PowerPointowi lub kodowi interop wiarygodne odwołanie się do kształtu z dowolnego miejsca w dokumencie. Tylko odczyt UInt32. Zobacz także [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Zwraca obiekt nadrzędny GroupShape, jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko odczyt [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Zwraca placeholder dla kształtu. Zwraca null, jeśli kształt nie ma placeholdera. Tylko odczyt [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Zwraca prezentację nadrzędną slajdu. Tylko odczyt [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Zwraca lub ustawia surowe właściwości ramki kształtu. Odczyt/zapis [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Zwraca lub ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwny. Odczyt/zapis Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Zwraca blokady kształtu. Tylko odczyt [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 właściwości) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Zwraca slajd nadrzędny kształtu. Tylko odczyt [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Zwraca obiekt właściwości wypełnienia obrazu OleObject. Tylko odczyt [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Zwraca lub ustawia tytuł ikony OleObject. Odczyt/zapis String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Zwraca obiekt ThreeDFormat, który zawiera właściwości efektów 3D dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają właściwości 3D. Tylko odczyt [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Zwraca wewnętrzny identyfikator zakresu prezentacji przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować jako trwały unikalny klucz. Tylko odczyt UInt32. Zobacz także [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Określa, czy powiązany osadzony obiekt jest automatycznie aktualizowany przy otwieraniu lub drukowaniu prezentacji. Odczyt/zapis Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Pobiera lub ustawia szerokość kształtu, mierzoną w punktach. Odczyt/zapis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Pobiera lub ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. Odczyt/zapis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Pobiera lub ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. Odczyt/zapis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Zwraca pozycję kształtu w kolejności z. Shapes[0] zwraca kształt znajdujący się z tyłu kolejności z, a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności z. Tylko odczyt Int32. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Dodaje nowy placeholder, jeśli go brak, i ustawia jego właściwości na podane. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Zwraca podstawowy kształt placeholder (kształt z układu i/lub slajdu master, z którego dziedziczy bieżący kształt). Zwraca null, jeśli bieżący kształt nie jest dziedziczony. |
| [GetImage](../../aspose.slides/shape/getimage)() | Zwraca miniaturę kształtu. Domyślnie używany jest typ granic miniatury ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Zwraca miniaturę kształtu. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Określa, że ten kształt nie jest placeholderem. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Ustawia informacje o osadzonych danych OLE. Ta metoda zmienia właściwości obiektu, aby odzwierciedlić nowe dane i ustawia flagę IsObjectLink na false, co wskazuje, że obiekt OLE jest osadzony. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Zapisuje zawartość kształtu jako plik SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Zapisuje zawartość kształtu jako plik SVG. |

### Przykłady

Poniższy przykład pokazuje, jak uzyskać dostęp do ramek obiektów OLE.

```csharp
[C#]
// Ładuje plik PPTX do obiektu prezentacji
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Uzyskuje dostęp do pierwszego slajdu
    ISlide sld = pres.Slides[0];
    // Rzutuje kształt na OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Odczytuje obiekt OLE i zapisuje go na dysku
    if (oleObjectFrame != null)
    {
        // Pobiera wbudowane dane pliku
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Pobiera rozszerzenie wbudowanego pliku
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Tworzy ścieżkę do zapisania wyodrębnionego pliku
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Zapisuje wyodrębnione dane
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### Zobacz także

* klasa [GraphicalObject](../graphicalobject)
* interfejs [IOleObjectFrame](../ioleobjectframe)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->