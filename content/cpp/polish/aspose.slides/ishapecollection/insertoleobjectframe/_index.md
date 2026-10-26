---
title: InsertOleObjectFrame()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów w określonym indeksie.
type: docs
weight: 79
url: /pl/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metoda

Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym należy wstawić ramkę obiektu OLE. |
| x | **float** | Współrzędna x nowej ramki OLE, w punktach. |
| y | **float** | Współrzędna y nowej ramki OLE, w punktach. |
| width | **float** | Szerokość nowej ramki OLE, w punktach. |
| height | **float** | Wysokość nowej ramki OLE, w punktach. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Informacje o osadzonych danych OLE ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Wartość zwracana

Nowo utworzony [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) metoda

Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym należy wstawić ramkę obiektu OLE. |
| x | **float** | Współrzędna x nowej ramki OLE, w punktach. |
| y | **float** | Współrzędna y nowej ramki OLE, w punktach. |
| width | **float** | Szerokość nowej ramki OLE, w punktach. |
| height | **float** | Wysokość nowej ramki OLE, w punktach. |
| className | [System::String](../../../system/string/) | Nazwa klasy obiektu OLE. |
| path | [System::String](../../../system/string/) | Ścieżka do powiązanego pliku. |

### Wartość zwracana

Nowo utworzony [IOleObjectFrame](../../ioleobjectframe/).

## Uwagi

Ta ścieżka jest przechowywana dosłownie w prezentacji. Jeśli podano ścieżkę względną, plik będzie niedostępny podczas otwierania prezentacji z innego katalogu.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)