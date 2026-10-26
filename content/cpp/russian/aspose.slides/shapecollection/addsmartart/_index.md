---
title: AddSmartArt()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт диаграмму SmartArt и добавляет её в конец коллекции фигур.
type: docs
weight: 79
url: /ru/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) метод

Создаёт диаграмму [SmartArt](../../../aspose.slides.smartart/) и добавляет её в конец коллекции фигур.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x рамки диаграммы, в пунктах. |
| y | **float** | Координата y рамки диаграммы, в пунктах. |
| width | **float** | Ширина рамки диаграммы, в пунктах. |
| height | **float** | Высота рамки диаграммы, в пунктах. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Тип макета [SmartArt](../../../aspose.slides.smartart/). |

### Возвращаемое значение

Новый созданный [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/).

## Примечания

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## Смотрите также

* Перечисление [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Класс [ShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)