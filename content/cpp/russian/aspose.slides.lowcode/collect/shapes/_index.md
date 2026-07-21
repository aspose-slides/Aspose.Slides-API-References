---
title: Shapes()
second_title: Aspose.Slides для C++ справочник API
description: Собирает все экземпляры Shape в Presentation.
type: docs
weight: 1
url: /ru/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) метод


Собирает все экземпляры [Shape](../../../aspose.slides/shape/) в [Presentation](../../../aspose.slides/presentation/).

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) для сбора фигур |

### Возвращаемое значение

Коллекция всех фигур, содержащихся в презентации
## Примечания




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // если shape является AutoShape, добавить черную сплошную границу
    if (System::ObjectExt::Is<AutoShape>(shape))
    {
        auto autoShape = System::AsCast<AutoShape>(shape);
        autoShape->get_LineFormat()->set_Style(LineStyle::Single);
        autoShape->get_LineFormat()->set_Width(10.0f);
        autoShape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::Solid);
        autoShape->get_LineFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Black());
    }
}

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```




## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IEnumerable](../../../system.collections.generic/ienumerable/)
* Класс [Shape](../../../aspose.slides/shape/)
* Класс [Presentation](../../../aspose.slides/presentation/)
* Класс [Collect](../)
* Пространство имён [Aspose::Slides::LowCode](../../)
* Библиотека [Aspose.Slides](../../../)