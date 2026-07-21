---
title: InsertZoomFrame()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый Zoom frame и вставляет его в коллекцию фигур по указанному индексу.
type: docs
weight: 105
url: /ru/aspose.slides/ishapecollection/insertzoomframe/
---
## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) метод


Создает новый Zoom frame и вставляет его в коллекцию фигур по указанному индексу.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, по которому будет вставлен Zoom frame. |
| x | **float** | Координата x нового Zoom frame в пунктах. |
| y | **float** | Координата y нового Zoom frame в пунктах. |
| width | **float** | Ширина нового Zoom frame в пунктах. |
| height | **float** | Высота нового Zoom frame в пунктах. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Объект [ISlide](../../islide/), на который ссылается Zoom frame. |

### Возвращаемое значение

Созданный [IZoomFrame](../../izoomframe/).

## Примечания


В этом примере демонстрируется создание и вставка объекта Zoom в указанный индекс коллекции (предположим, что в презентации "Presentation.pptx" содержится как минимум два слайда): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## IShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) метод


Создает новый Zoom frame с предопределенным изображением и вставляет его в коллекцию фигур по указанному индексу.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, по которому будет вставлен Zoom frame. |
| x | **float** | Координата x нового Zoom frame в пунктах. |
| y | **float** | Координата y нового Zoom frame в пунктах. |
| width | **float** | Ширина нового Zoom frame в пунктах. |
| height | **float** | Высота нового Zoom frame в пунктах. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Объект [ISlide](../../islide/), на который ссылается Zoom frame. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Изображение для слайда, на который ссылается Zoom frame [IPPImage](../../ippimage/). |

### Возвращаемое значение

Созданный [IZoomFrame](../../izoomframe/).

## Примечания


В этом примере демонстрируется создание и вставка объекта Zoom в указанный индекс коллекции (предположим, что в презентации "Presentation.pptx" содержится как минимум два слайда): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```


## Смотрите также

* Типedef [SharedPtr](../../../system/sharedptr/)
* Класс [IZoomFrame](../../izoomframe/)
* Класс [ISlide](../../islide/)
* Класс [IShapeCollection](../)
* Класс [IPPImage](../../ippimage/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)