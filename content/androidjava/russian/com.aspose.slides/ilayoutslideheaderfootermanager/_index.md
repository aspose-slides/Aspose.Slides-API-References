---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет менеджер, который хранит поведение заполнителей нижнего колонтитула, даты-времени, номера страницы макета слайда и всех дочерних заполнителей.
type: docs
url: /ru/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Представляет менеджер, который хранит поведение заполнителей нижнего колонтитула, даты-времени и номера страницы макета слайдов, а также всех дочерних заполнителей. Дочерние заполнители означают, что заполнители содержатся на зависимых слайдах. Зависимые слайды используют и зависят от макета слайда.
## Методы

| Метод | Описание |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Изменяет видимость заполнителя нижнего колонтитула макета слайда и всех дочерних заполнителей нижнего колонтитула. Дочерние заполнители означают, что заполнители содержатся на зависимых слайдах. Зависимые слайды используют и зависят от главного слайда. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Изменяет видимость заполнителя номера страницы макета слайда и всех дочерних заполнителей номеров страниц. Дочерние заполнители означают, что заполнители содержатся на зависимых слайдах. Зависимые слайды используют и зависят от макета слайда. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Изменяет видимость заполнителя даты-времени макета слайда и всех дочерних заполнителей даты-времени. Дочерние заполнители означают, что заполнители содержатся на зависимых слайдах. Зависимые слайды используют и зависят от макета слайда. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Устанавливает текст в заполнитель нижнего колонтитула макета слайда и все дочерние заполнители нижнего колонтитула. Дочерние заполнители означают, что заполнители содержатся на зависимых слайдах. Зависимые слайды используют и зависят от макета слайда. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Устанавливает текст в заполнитель даты-времени макета слайда и все дочерние заполнители даты-времени. Дочерние заполнители означают, что заполнители содержатся на зависимых слайдах. Зависимые слайды используют и зависят от макета слайда. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Изменяет видимость заполнителя нижнего колонтитула макета слайда и всех дочерних заполнителей нижнего колонтитула. Дочерние заполнители означают, что заполнители содержатся на зависимых слайдах. Зависимые слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнители нижнего колонтитула видимыми, иначе — скрывает их. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Изменяет видимость заполнителя номера страницы макета слайда и всех дочерних заполнителей номеров страниц. Дочерние заполнители означают, что заполнители содержатся на зависимых слайдах. Зависимые слайды используют и зависят от макета слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнители номеров страниц видимыми, иначе — скрывает их. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Изменяет видимость заполнителя даты-времени макета слайда и всех дочерних заполнителей даты-времени. Дочерние заполнители означают, что заполнители содержатся на зависимых слайдах. Зависимые слайды используют и зависят от макета слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнители даты-времени видимыми, иначе — скрывает их. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Устанавливает текст в заполнитель нижнего колонтитула макета слайда и все дочерние заполнители нижнего колонтитула. Дочерние заполнители означают, что заполнители содержатся на зависимых слайдах. Зависимые слайды используют и зависят от макета слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Устанавливает текст в заполнитель даты-времени макета слайда и все дочерние заполнители даты-времени. Дочерние заполнители означают, что заполнители содержатся на зависимых слайдах. Зависимые слайды используют и зависят от макета слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |