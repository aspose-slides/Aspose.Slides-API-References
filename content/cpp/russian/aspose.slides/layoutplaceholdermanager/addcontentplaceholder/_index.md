---
title: AddContentPlaceholder()
second_title: Справочник по API Aspose.Slides для C++
description: Добавляет новую форму-заполнитель в макетный слайд для размещения контента, такого как изображение, таблица, медиа или текст.
type: docs
weight: 1
url: /ru/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) метод

Добавляет новую форму-заполнитель в макетный слайд для размещения контента, такого как изображение, таблица, медиа или текст.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата X новой формы-заполнителя. |
| y | **float** | Координата Y новой формы-заполнителя. |
| width | **float** | Ширина новой формы-заполнителя. |
| height | **float** | Высота новой формы-заполнителя. |

### Возвращаемое значение

Создан [IAutoShape](../../iautoshape/) с заполнителем Content.

## Примечания

Следующий пример показывает, как добавить форму-заполнитель Content в макетный слайд. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAutoShape](../../iautoshape/)
* Класс [LayoutPlaceholderManager](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)