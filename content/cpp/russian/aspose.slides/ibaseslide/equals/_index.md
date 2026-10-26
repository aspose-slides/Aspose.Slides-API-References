---
title: Equals()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, равны ли два экземпляра IBaseSlide. Возвращаемое значение вычисляется на основе структуры слайда и статического содержимого. Два слайда считаются равными, если все формы, стили, тексты, анимация и другие настройки и т.д. равны. При сравнении не учитываются уникальные идентификаторы, например SlideId и динамическое содержимое, например текущее значение даты в Date Placeholder.
type: docs
weight: 183
url: /ru/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) method


Определяет, равны ли два экземпляра [IBaseSlide](../). Возвращаемое значение вычисляется на основе структуры слайда и статического содержимого. Два слайда считаются равными, если все формы, стили, тексты, анимация и другие настройки и т.д. равны. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамическое содержимое, например текущее значение даты в объекте Date [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | Объект [IBaseSlide](../) для сравнения с текущим [IBaseSlide](../). |

### Возвращаемое значение

**true** если указанный [IBaseSlide](../) равен текущему [IBaseSlide](../); иначе **false**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IBaseSlide](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)