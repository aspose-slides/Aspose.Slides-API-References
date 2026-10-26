---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет новую форму-заполнитель на слайд макета для размещения диаграммы SmartArt.
type: docs
weight: 92
url: /ru/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---
## ILayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) method

Добавляет новую форму-заполнитель на слайд макета для размещения диаграммы [SmartArt](../../../aspose.slides.smartart/).

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата X новой формы-заполнителя. |
| y | **float** | Координата Y новой формы-заполнителя. |
| width | **float** | Ширина новой формы-заполнителя. |
| height | **float** | Высота новой формы-заполнителя. |

### Возвращаемое значение

Создан [IAutoShape](../../iautoshape/) с заполнителем [SmartArt](../../../aspose.slides.smartart/).

## Примечания

Следующий пример показывает, как добавить форму-заполнитель [SmartArt](../../../aspose.slides.smartart/) на слайд макета. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAutoShape](../../iautoshape/)
* Класс [ILayoutPlaceholderManager](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)