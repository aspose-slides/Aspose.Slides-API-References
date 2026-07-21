---
title: Equals()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, являются ли два экземпляра IBaseSlide равными. Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого. Два слайда считаются равными, если все фигуры, стили, тексты, анимация и другие настройки и т. д. одинаковы. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамическое содержимое, например текущее значение даты в Date Placeholder.
type: docs
weight: 170
url: /ru/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) метод

Определяет, равны ли два экземпляра [IBaseSlide](../../ibaseslide/). Возвращаемое значение рассчитывается на основе структуры слайда и статического содержимого. Два слайда считаются равными, если все фигуры, стили, текст, анимация и другие настройки и т. д. одинаковы. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамическое содержимое, например текущий датовый параметр в Date [Placeholder](../../placeholder/).

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | [IBaseSlide](../../ibaseslide/) для сравнения с текущим [IBaseSlide](../../ibaseslide/). |

### Возвращаемое значение

**true** если указанный [IBaseSlide](../../ibaseslide/) равен текущему [IBaseSlide](../../ibaseslide/); в противном случае **false**.

## Примечания

Следующий пример показывает, как сравнить два слайда.
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IBaseSlide](../../ibaseslide/)
* Класс [BaseSlide](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)