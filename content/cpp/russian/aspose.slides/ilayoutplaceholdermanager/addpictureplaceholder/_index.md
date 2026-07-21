---
title: AddPicturePlaceholder()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет новую форму-заполнитель на слайд макета для размещения изображения.
type: docs
weight: 53
url: /ru/aspose.slides/ilayoutplaceholdermanager/addpictureplaceholder/
---
## ILayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) метод

Добавляет новую форму-заполнитель в слайд макета для размещения изображения.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата X новой формы-заполнителя. |
| y | **float** | Координата Y новой формы-заполнителя. |
| width | **float** | Ширина новой формы-заполнителя. |
| height | **float** | Высота новой формы-заполнителя. |

### Возвращаемое значение

Создан [IAutoShape](../../iautoshape/) с [Picture](../../picture/) заполнителем.

## Примечания

Следующий пример показывает, как добавить форму-заполнитель [Picture](../../picture/) в слайд макета. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAutoShape](../../iautoshape/)
* Класс [ILayoutPlaceholderManager](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)