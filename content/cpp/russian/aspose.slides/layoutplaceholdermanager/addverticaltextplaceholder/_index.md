---
title: AddVerticalTextPlaceholder()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет новую форму-заполнитель на слайд макета для размещения текстового содержимого в вертикальном направлении.
type: docs
weight: 40
url: /ru/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) method

Добавляет новую форму-заполнитель на слайд макета для размещения текстового содержимого в вертикальном направлении.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата X новой формы-заполнителя. |
| y | **float** | Координата Y новой формы-заполнителя. |
| width | **float** | Ширина новой формы-заполнителя. |
| height | **float** | Высота новой формы-заполнителя. |

### Возвращаемое значение

Создан [IAutoShape](../../iautoshape/) с заполнителем Text (Vertical).

## Замечания

Следующий пример демонстрирует, как добавить форму-заполнитель Text (Vertical) на слайд макета. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)