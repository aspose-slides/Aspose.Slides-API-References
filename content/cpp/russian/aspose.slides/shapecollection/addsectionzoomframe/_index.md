---
title: AddSectionZoomFrame()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый кадр Section Zoom и добавляет его в конец коллекции фигур.
type: docs
weight: 131
url: /ru/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) метод

Создает новый [Section](../../section/) Zoom кадр и добавляет его в конец коллекции фигур.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | X-координата нового [Section](../../section/) Zoom кадра, в пунктах. |
| y | **float** | Y-координата нового [Section](../../section/) Zoom кадра, в пунктах. |
| width | **float** | Ширина нового [Section](../../section/) Zoom кадра, в пунктах. |
| height | **float** | Высота нового [Section](../../section/) Zoom кадра, в пунктах. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/), на который ссылается [Section](../../section/) Zoom кадр; должен принадлежать этой презентации и содержать как минимум один слайд. |

### Возвращаемое значение

Созданный [ISectionZoomFrame](../../isectionzoomframe/).

## Примечания

Этот пример демонстрирует добавление [Section](../../section/) Zoom объекта в конец коллекции (предположим, что в презентации "Presentation.pptx" присутствует как минимум два раздела):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) метод

Создает новый [Section](../../section/) Zoom кадр с предопределенным изображением и добавляет его в конец коллекции фигур.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | X-координата нового [Section](../../section/) Zoom кадра, в пунктах. |
| y | **float** | Y-координата нового [Section](../../section/) Zoom кадра, в пунктах. |
| width | **float** | Ширина нового [Section](../../section/) Zoom кадра, в пунктах. |
| height | **float** | Высота нового [Section](../../section/) Zoom кадра, в пунктах. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/), на который ссылается [Section](../../section/) Zoom кадр; должен принадлежать этой презентации и содержать как минимум один слайд. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) для отображения внутри [Section](../../section/) Zoom кадра. |

### Возвращаемое значение

Созданный [ISectionZoomFrame](../../isectionzoomframe/).

## Примечания

Этот пример демонстрирует добавление [Section](../../section/) Zoom объекта в конец коллекции (предположим, что в презентации "Presentation.pptx" присутствует как минимум два раздела):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ISectionZoomFrame](../../isectionzoomframe/)
* Класс [ISection](../../isection/)
* Класс [ShapeCollection](../)
* Класс [IPPImage](../../ippimage/)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)