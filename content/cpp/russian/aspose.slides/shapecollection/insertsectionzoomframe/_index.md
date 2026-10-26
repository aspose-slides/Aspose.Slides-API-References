---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides для C++ справочник API
description: Создает новый Section Zoom-кадр и вставляет его в коллекцию фигур в указанный индекс.
type: docs
weight: 144
url: /ru/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) method

Создает новый [Section](../../section/) Zoom-кадр и вставляет его в коллекцию фигур в указанном индексе.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, в котором вставить [Section](../../section/) Zoom-кадр. |
| x | **float** | Координата x нового [Section](../../section/) Zoom-кадра в пунктах. |
| y | **float** | Координата y нового [Section](../../section/) Zoom-кадра в пунктах. |
| width | **float** | Ширина нового [Section](../../section/) Zoom-кадра в пунктах. |
| height | **float** | Высота нового [Section](../../section/) Zoom-кадра в пунктах. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/), на который ссылается [Section](../../section/) Zoom-кадр; должен принадлежать этой презентации и содержать минимум один слайд. |

### Return Value

Новосозданный [ISectionZoomFrame](../../isectionzoomframe/).

## Remarks

В этом примере демонстрируется создание и вставка объекта [Section](../../section/) Zoom в указанный индекс коллекции (предполагается, что в презентации "Presentation.pptx" имеется минимум две секции): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method

Создает новый [Section](../../section/) Zoom-кадр с предустановленным изображением и вставляет его в коллекцию фигур в указанном индексе.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, в котором вставить [Section](../../section/) Zoom-кадр. |
| x | **float** | Координата x нового [Section](../../section/) Zoom-кадра в пунктах. |
| y | **float** | Координата y нового [Section](../../section/) Zoom-кадра в пунктах. |
| width | **float** | Ширина нового [Section](../../section/) Zoom-кадра в пунктах. |
| height | **float** | Высота нового [Section](../../section/) Zoom-кадра в пунктах. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/), на который ссылается [Section](../../section/) Zoom-кадр; должен принадлежать этой презентации и содержать минимум один слайд. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Изображение, отображаемое внутри [Section](../../section/) Zoom-кадра. |

### Return Value

Новосозданный [ISectionZoomFrame](../../isectionzoomframe/).

## Remarks

В этом примере демонстрируется создание и вставка объекта [Section](../../section/) Zoom в указанный индекс коллекции (предполагается, что в презентации "Presentation.pptx" имеется минимум две секции): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## See Also

* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISectionZoomFrame](../../isectionzoomframe/)
* Класс [ISection](../../isection/)
* Класс [ShapeCollection](../)
* Класс [IPPImage](../../ippimage/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)