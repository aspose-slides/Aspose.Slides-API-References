---
title: InsertOleObjectFrame()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów w określonym indeksie.
type: docs
weight: 196
url: /pl/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metoda

Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym ma zostać wstawiona ramka obiektu OLE. |
| x | **float** | Współrzędna x nowej ramki OLE, w punktach. |
| y | **float** | Współrzędna y nowej ramki OLE, w punktach. |
| width | **float** | Szerokość nowej ramki OLE, w punktach. |
| height | **float** | Wysokość nowej ramki OLE, w punktach. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Informacje o osadzonych danych OLE ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Wartość zwracana

Nowo utworzony [IOleObjectFrame](../../ioleobjectframe/).

## Uwagi

Ten przykład pokazuje wstawianie obiektu OLE pod drugim indeksem: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) metoda

Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym ma zostać wstawiona ramka obiektu OLE. |
| x | **float** | Współrzędna x nowej ramki OLE, w punktach. |
| y | **float** | Współrzędna y nowej ramki OLE, w punktach. |
| width | **float** | Szerokość nowej ramki OLE, w punktach. |
| height | **float** | Wysokość nowej ramki OLE, w punktach. |
| className | [System::String](../../../system/string/) | Nazwa klasy obiektu OLE. |
| path | [System::String](../../../system/string/) | Ścieżka do powiązanego pliku. |

### Wartość zwracana

Nowo utworzona ramka obiektu OLE.

## Uwagi

Ta ścieżka jest przechowywana dosłownie w prezentacji. Jeśli zostanie podana ścieżka względna, plik będzie niedostępny przy otwieraniu prezentacji z innego katalogu.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IOleObjectFrame](../../ioleobjectframe/)
* Klasa [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Klasa [ShapeCollection](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)