---
title: AddOleObjectFrame()
second_title: Aspose.Slides for C++ – Dokumentacja API
description: Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 66
url: /pl/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method

Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
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

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) method

Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x nowej ramki OLE, w punktach. |
| y | **float** | Współrzędna y nowej ramki OLE, w punktach. |
| width | **float** | Szerokość nowej ramki OLE, w punktach. |
| height | **float** | Wysokość nowej ramki OLE, w punktach. |
| className | [System::String](../../../system/string/) | Nazwa klasy obiektu OLE. |
| path | [System::String](../../../system/string/) | Ścieżka do połączonego pliku. |

### Wartość zwracana

Nowo utworzony [IOleObjectFrame](../../ioleobjectframe/).

## Uwagi

Ta ścieżka jest przechowywana dosłownie w prezentacji. Jeśli podano względną ścieżkę, plik będzie niedostępny przy otwieraniu prezentacji z innego katalogu.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOleObjectFrame](../../ioleobjectframe/)
* Class [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Class [IShapeCollection](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)