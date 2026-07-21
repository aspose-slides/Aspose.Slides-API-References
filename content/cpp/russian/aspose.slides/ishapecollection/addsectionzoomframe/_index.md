---
title: AddSectionZoomFrame()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новую Section Zoom-рамку и добавляет её в конец коллекции фигур.
type: docs
weight: 118
url: /ru/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) метод

Создает новый [Section](../../section/) Zoom-рамку и добавляет её в конец коллекции фигур.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Координата x новой [Section](../../section/) Zoom-рамки, в пунктах. |
| y | **float** | Координата y новой [Section](../../section/) Zoom-рамки, в пунктах. |
| width | **float** | Ширина новой [Section](../../section/) Zoom-рамки, в пунктах. |
| height | **float** | Высота новой [Section](../../section/) Zoom-рамки, в пунктах. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/), на который ссылается [Section](../../section/) Zoom-рамка; должен принадлежать этой презентации и содержать как минимум один слайд. |

### Return Value

Новосозданный [ISectionZoomFrame](../../isectionzoomframe/).

## Remarks

В этом примере демонстрируется добавление объекта [Section](../../section/) Zoom в конец коллекции (предполагается, что в презентации "Presentation.pptx" присутствует как минимум две секции):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) метод

Создает новый [Section](../../section/) Zoom-кадр с предопределенным изображением и добавляет его в конец коллекции фигур.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Координата x новой [Section](../../section/) Zoom-рамки, в пунктах. |
| y | **float** | Координата y новой [Section](../../section/) Zoom-рамки, в пунктах. |
| width | **float** | Ширина новой [Section](../../section/) Zoom-рамки, в пунктах. |
| height | **float** | Высота новой [Section](../../section/) Zoom-рамки, в пунктах. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/), на который ссылается [Section](../../section/) Zoom-рамка; должен принадлежать этой презентации и содержать как минимум один слайд. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) для отображения внутри [Section](../../section/) Zoom-рамки. |

### Return Value

Новосозданный [ISectionZoomFrame](../../isectionzoomframe/).

## Remarks

В этом примере демонстрируется добавление объекта [Section](../../section/) Zoom в конец коллекции (предполагается, что в презентации "Presentation.pptx" присутствует как минимум две секции):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISectionZoomFrame](../../isectionzoomframe/)
* Класс [ISection](../../isection/)
* Класс [IShapeCollection](../)
* Класс [IPPImage](../../ippimage/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)