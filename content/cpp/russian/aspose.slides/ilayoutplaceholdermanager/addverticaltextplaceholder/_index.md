---
title: AddVerticalTextPlaceholder()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет новую форму-заполнитель на слайд макета для размещения текстового содержимого в вертикальном направлении.
type: docs
weight: 40
url: /ru/aspose.slides/ilayoutplaceholdermanager/addverticaltextplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) метод

Добавляет новую форму-заполнитель на слайд макета для размещения текстового содержимого в вертикальном направлении.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height)=0
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

В следующем примере показано, как добавить форму-заполнитель Text (Vertical) на слайд макета. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IAutoShape](../../iautoshape/)
* Класс [ILayoutPlaceholderManager](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)