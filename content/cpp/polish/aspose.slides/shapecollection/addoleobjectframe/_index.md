---
title: AddOleObjectFrame()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 183
url: /pl/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metoda


Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki OLE, w punktach. |
| y | **float** | Współrzędna y nowej ramki OLE, w punktach. |
| width | **float** | Szerokość nowej ramki OLE, w punktach. |
| height | **float** | Wysokość nowej ramki OLE, w punktach. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Informacje o osadzonych danych OLE ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Wartość zwracana

Nowo utworzony [IOleObjectFrame](../../ioleobjectframe/).

## Uwagi



Poniższy przykład pokazuje, jak dodawać ramki obiektów OLE do [Slides](../../) programu PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

// Uzyskuje dostęp do pierwszego slajdu
auto slide = pres->get_Slides()->idx_get(0);
// Ładuje plik Excel do strumienia
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// Tworzy obiekt danych do osadzenia
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Dodaje kształt ramki obiektu OLE
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
// Zapisuje plik PPTX na dysk
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) metoda


Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki OLE, w punktach. |
| y | **float** | Współrzędna y nowej ramki OLE, w punktach. |
| width | **float** | Szerokość nowej ramki OLE, w punktach. |
| height | **float** | Wysokość nowej ramki OLE, w punktach. |
| className | [System::String](../../../system/string/) | Nazwa klasy obiektu OLE. |
| path | [System::String](../../../system/string/) | Ścieżka do pliku powiązanego. |

### Wartość zwracana

Nowo utworzony [IOleObjectFrame](../../ioleobjectframe/).

## Uwagi



Ta ścieżka jest przechowywana dosłownie w prezentacji. Jeśli podano ścieżkę względną, plik będzie niedostępny przy otwieraniu prezentacji z innego katalogu.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IOleObjectFrame](../../ioleobjectframe/)
* Klasa [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Klasa [ShapeCollection](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)