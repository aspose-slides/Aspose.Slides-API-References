---
title: AddContentPlaceholder()
second_title: Справочник по API Aspose.Slides для C++
description: Добавляет новую форму-заполнитель на слайд-макет для размещения содержимого, такого как изображение, таблица, медиафайл или текст.
type: docs
weight: 1
url: /ru/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) метод

Добавляет новую фигуру-заполнитель на слайд-макет для размещения содержимого, например изображения, таблицы, медиафайла или текста.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата X новой фигуры-заполнителя. |
| y | **float** | Координата Y новой фигуры-заполнителя. |
| width | **float** | Ширина новой фигуры-заполнителя. |
| height | **float** | Высота новой фигуры-заполнителя. |

### Возвращаемое значение

Создан [IAutoShape](../../iautoshape/) с заполнителем Content.

## Примечания

Следующий пример демонстрирует, как добавить форму заполнителя Content на слайд-макет. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAutoShape](../../iautoshape/)
* Класс [ILayoutPlaceholderManager](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)