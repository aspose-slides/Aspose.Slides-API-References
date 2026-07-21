---
title: AddChartPlaceholder()
second_title: Aspose.Slides для C++ справка API
description: Добавляет новую форму-заполнитель на слайд макета для размещения диаграммы.
type: docs
weight: 66
url: /ru/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) метод

Добавляет новую форму-заполнитель на слайд макета для размещения диаграммы.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата X новой формы-заполнителя. |
| y | **float** | Координата Y новой формы-заполнителя. |
| width | **float** | Ширина новой формы-заполнителя. |
| height | **float** | Высота новой формы-заполнителя. |

### Возвращаемое значение

Создан [IAutoShape](../../iautoshape/) с заполнителем диаграммы.

## Примечания

Следующий пример демонстрирует, как добавить форму-заполнитель диаграммы на слайд макета. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAutoShape](../../iautoshape/)
* Класс [LayoutPlaceholderManager](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)