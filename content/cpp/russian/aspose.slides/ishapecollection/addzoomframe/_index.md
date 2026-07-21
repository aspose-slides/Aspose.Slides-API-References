---
title: AddZoomFrame()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый кадр Zoom и добавляет его в конец коллекции фигур.
type: docs
weight: 92
url: /ru/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) method

Создает новый кадр Zoom и добавляет его в конец коллекции фигур.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового кадра Zoom в точках. |
| y | **float** | Координата y нового кадра Zoom в точках. |
| width | **float** | Ширина нового кадра Zoom в точках. |
| height | **float** | Высота нового кадра Zoom в точках. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) , на который ссылается кадр Zoom; должен принадлежать этой презентации. |

### Возвращаемое значение

Только что созданный [IZoomFrame](../../izoomframe/).

## Примечание

В этом примере демонстрируется добавление объекта Zoom в конец коллекции (предположим, что в презентации \"Presentation.pptx\" присутствует как минимум два слайда): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

Создает новый кадр Zoom и добавляет его в конец коллекции фигур.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового кадра Zoom в точках. |
| y | **float** | Координата y нового кадра Zoom в точках. |
| width | **float** | Ширина нового кадра Zoom в точках. |
| height | **float** | Высота нового кадра Zoom в точках. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) , на который ссылается кадр Zoom; должен принадлежать этой презентации. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Изображение для слайда, на который ссылается кадр Zoom [IPPImage](../../ippimage/). |

### Возвращаемое значение

Только что созданный [IZoomFrame](../../izoomframe/).

## Примечание

В этом примере демонстрируется добавление объекта Zoom в конец коллекции (предположим, что в презентации \"Presentation.pptx\" присутствует как минимум два слайда): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)