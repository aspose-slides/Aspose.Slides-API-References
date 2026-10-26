---
title: InsertSectionZoomFrame()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый кадр Section Zoom и вставляет его в коллекцию фигур по указанному индексу.
type: docs
weight: 131
url: /ru/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) метод

Создает новый [Section](../../section/) Zoom-кадр и вставляет его в коллекцию фигур по указанному индексу.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс, начинающийся с нуля, по которому вставляется [Section](../../section/) Zoom-кадр. |
| x | **float** | Координата x нового [Section](../../section/) Zoom-кадра, в пунктах. |
| y | **float** | Координата y нового [Section](../../section/) Zoom-кадра, в пунктах. |
| width | **float** | Ширина нового [Section](../../section/) Zoom-кадра, в пунктах. |
| height | **float** | Высота нового [Section](../../section/) Zoom-кадра, в пунктах. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/), на которую ссылается [Section](../../section/) Zoom-кадр; должна принадлежать этой презентации и содержать хотя бы один слайд. |

### Возвращаемое значение

Новый созданный [ISectionZoomFrame](../../isectionzoomframe/).

## Примечания

Этот пример демонстрирует создание и вставку объекта [Section](../../section/) Zoom в указанный индекс коллекции (предполагается, что в презентации "Presentation.pptx" присутствует как минимум две секции): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) метод


Создает новый [Section](../../section/) Zoom-кадр с предустановленным изображением и вставляет его в коллекцию фигур по указанному индексу.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс, начинающийся с нуля, по которому вставляется [Section](../../section/) Zoom-кадр. |
| x | **float** | Координата x нового [Section](../../section/) Zoom-кадра, в пунктах. |
| y | **float** | Координата y нового [Section](../../section/) Zoom-кадра, в пунктах. |
| width | **float** | Ширина нового [Section](../../section/) Zoom-кадра, в пунктах. |
| height | **float** | Высота нового [Section](../../section/) Zoom-кадра, в пунктах. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/), на которую ссылается [Section](../../section/) Zoom-кадр; должна принадлежать этой презентации и содержать хотя бы один слайд. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Изображение, отображаемое внутри [Section](../../section/) Zoom-кадра. |

### Возвращаемое значение

Новый созданный [ISectionZoomFrame](../../isectionzoomframe/).

## Примечания

Этот пример демонстрирует создание и вставку объекта [Section](../../section/) Zoom в указанный индекс коллекции (предполагается, что в презентации "Presentation.pptx" присутствует как минимум две секции): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ISectionZoomFrame](../../isectionzoomframe/)
* Класс [ISection](../../isection/)
* Класс [IShapeCollection](../)
* Класс [IPPImage](../../ippimage/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)