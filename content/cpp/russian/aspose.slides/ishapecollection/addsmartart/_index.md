---
title: AddSmartArt()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт диаграмму SmartArt и добавляет её в конец коллекции фигур.
type: docs
weight: 40
url: /ru/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) method


Создаёт [SmartArt](../../../aspose.slides.smartart/) диаграмму и добавляет её в конец коллекции фигур.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | X-координата кадра диаграммы, в пунктах. |
| y | **float** | Y-координата кадра диаграммы, в пунктах. |
| width | **float** | Ширина кадра диаграммы, в пунктах. |
| height | **float** | Высота кадра диаграммы, в пунктах. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Тип компоновки [SmartArt](../../../aspose.slides.smartart/). |

### Возвращаемое значение

Новосозданный [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/).

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
* Класс [IShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)