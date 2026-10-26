---
title: InsertZoomFrame()
second_title: Aspose.Slides для C++ справочник API
description: Создает новый Zoom-кадр и вставляет его в коллекцию фигур в указанном индексе.
type: docs
weight: 118
url: /ru/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) метод

Создаёт новый Zoom-кадр и вставляет его в коллекцию фигур в указанном индексе.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, в который будет вставлен Zoom-кадр. |
| x | **float** | Координата x нового Zoom-кадра в пунктах. |
| y | **float** | Координата y нового Zoom-кадра в пунктах. |
| width | **float** | Ширина нового Zoom-кадра в пунктах. |
| height | **float** | Высота нового Zoom-кадра в пунктах. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) referenced by the Zoom frame. |

### Возвращаемое значение

Недавно созданный [IZoomFrame](../../izoomframe/).

## Замечания

Этот пример демонстрирует создание и вставку объекта Zoom в указанный индекс коллекции (предположим, что в презентации "Presentation.pptx" имеется как минимум два слайда):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) метод

Создаёт новый Zoom-кадр с предопределённым изображением и вставляет его в коллекцию фигур в указанном индексе.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, в который будет вставлен Zoom-кадр. |
| x | **float** | Координата x нового Zoom-кадра в пунктах. |
| y | **float** | Координата y нового Zoom-кадра в пунктах. |
| width | **float** | Ширина нового Zoom-кадра в пунктах. |
| height | **float** | Высота нового Zoom-кадра в пунктах. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [ISlide](../../islide/) referenced by the Zoom frame. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Изображение для слайда, на который ссылается Zoom-кадр [IPPImage](../../ippimage/). |

### Возвращаемое значение

Недавно созданный [IZoomFrame](../../izoomframe/).

## Замечания

Этот пример демонстрирует создание и вставку объекта Zoom в указанный индекс коллекции (предположим, что в презентации "Presentation.pptx" имеется как минимум два слайда):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IZoomFrame](../../izoomframe/)
* Класс [ISlide](../../islide/)
* Класс [ShapeCollection](../)
* Класс [IPPImage](../../ippimage/)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)