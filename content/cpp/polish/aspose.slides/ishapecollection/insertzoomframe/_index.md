---
title: InsertZoomFrame()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów pod wskazanym indeksem.
type: docs
weight: 105
url: /pl/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) method

Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów pod wskazanym indeksem.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, pod którym ma zostać wstawiona ramka Zoom. |
| x | **float** | Współrzędna x nowej ramki Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Zoom, w punktach. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Obiekt [ISlide](../../islide/) odwoływany przez ramkę Zoom. |

### Wartość zwracana

Nowo utworzony [IZoomFrame](../../izoomframe/).

## Uwagi

Ten przykład demonstruje tworzenie i wstawianie obiektu Zoom pod wskazanym indeksem kolekcji (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwie slajdy): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

Tworzy nową ramkę Zoom z predefiniowanym obrazem i wstawia ją do kolekcji kształtów pod wskazanym indeksem.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, pod którym ma zostać wstawiona ramka Zoom. |
| x | **float** | Współrzędna x nowej ramki Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Zoom, w punktach. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Obiekt [ISlide](../../islide/) odwoływany przez ramkę Zoom. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Obraz dla odwoływanego slajdu [IPPImage](../../ippimage/). |

### Wartość zwracana

Nowo utworzony [IZoomFrame](../../izoomframe/).

## Uwagi

Ten przykład demonstruje tworzenie i wstawianie obiektu Zoom pod wskazanym indeksem kolekcji (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwie slajdy): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IZoomFrame](../../izoomframe/)
* Klasa [ISlide](../../islide/)
* Klasa [IShapeCollection](../)
* Klasa [IPPImage](../../ippimage/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)