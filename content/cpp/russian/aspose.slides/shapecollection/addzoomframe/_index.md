---
title: AddZoomFrame()
second_title: Aspose.Slides для C++ справочника API
description: Создаёт новый Zoom-кадр и добавляет его в конец коллекции фигур.
type: docs
weight: 105
url: /ru/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) метод


Создаёт новый Zoom-кадр и добавляет его в конец коллекции фигур.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового Zoom-кадра в пунктах. |
| y | **float** | Координата y нового Zoom-кадра в пунктах. |
| width | **float** | Ширина нового Zoom-кадра в пунктах. |
| height | **float** | Высота нового Zoom-кадра в пунктах. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Объект [ISlide](../../islide/), на который ссылается Zoom-кадр; должен принадлежать этой презентации. |

### Возвращаемое значение

Новый созданный [IZoomFrame](../../izoomframe/).

## Примечания


Этот пример демонстрирует добавление объекта Zoom в конец коллекции (предположим, что в презентации "Presentation.pptx" как минимум два слайда): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) метод


Создаёт новый Zoom-кадр и добавляет его в конец коллекции фигур.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового Zoom-кадра в пунктах. |
| y | **float** | Координата y нового Zoom-кадра в пунктах. |
| width | **float** | Ширина нового Zoom-кадра в пунктах. |
| height | **float** | Высота нового Zoom-кадра в пунктах. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Объект [ISlide](../../islide/), на который ссылается Zoom-кадр; должен принадлежать этой презентации. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Изображение для ссылаемого слайда [IPPImage](../../ippimage/). |

### Возвращаемое значение

Новый созданный [IZoomFrame](../../izoomframe/).

## Примечания


Этот пример демонстрирует добавление объекта Zoom в конец коллекции (предположим, что в презентации "Presentation.pptx" как минимум два слайда): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IZoomFrame](../../izoomframe/)
* Класс [ISlide](../../islide/)
* Класс [ShapeCollection](../)
* Класс [IPPImage](../../ippimage/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)