---
title: AddTextPlaceholder()
second_title: Aspose.Slides для C++ API справочник
description: Добавляет новую форму заполнителя на слайд шаблона для размещения текстового содержимого.
type: docs
weight: 27
url: /ru/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) метод

Добавляет новую форму заполнителя на слайд шаблона для размещения текстового содержимого.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата X новой формы заполнителя. |
| y | **float** | Координата Y новой формы заполнителя. |
| width | **float** | Ширина новой формы заполнителя. |
| height | **float** | Высота новой формы заполнителя. |

### Возвращаемое значение

Создан [IAutoShape](../../iautoshape/) с текстовым заполнителем.

## Примечания

Следующий пример показывает, как добавить форму заполнителя Text на слайд шаблона. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)