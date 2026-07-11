---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет менеджер, который управляет поведением заполнителей нижнего колонтитула, даты и времени, номера страницы мастер-слайда и всех дочерних заполнителей.
type: docs
url: /ru/com.aspose.slides/imasterslideheaderfootermanager/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Представляет менеджер, который управляет поведением заполнителей нижнего колонтитула мастер-слайда, даты и времени, номера страницы и всех дочерних заполнителей. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах макета и зависимых слайдах. Зависимые слайды макета и слайды используют и зависят от мастер-слайда.
## Методы

| Метод | Описание |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Изменяет видимость заполнителя нижнего колонтитула мастер-слайда и всех дочерних заполнителей нижнего колонтитула. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Изменяет видимость заполнителя номера страницы мастер-слайда и всех дочерних заполнителей номера страницы. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Изменяет видимость заполнителя даты и времени мастер-слайда и всех дочерних заполнителей даты и времени. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Устанавливает текст в заполнитель нижнего колонтитула мастер-слайда и все дочерние заполнители нижнего колонтитула. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Устанавливает текст в заполнитель даты и времени мастер-слайда и все дочерние заполнители даты и времени. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Изменяет видимость заполнителя нижнего колонтитула мастер-слайда и всех дочерних заполнителей нижнего колонтитула. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах макета и зависимых слайдах. Зависимые слайды макета и слайды используют и зависят от мастер-слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнители нижнего колонтитула видимыми, иначе — скрывает их. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Изменяет видимость заполнителя номера страницы мастер-слайда и всех дочерних заполнителей номера страницы. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах макета и зависимых слайдах. Зависимые слайды макета и слайды используют и зависят от мастер-слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнители номера страницы видимыми, иначе — скрывает их. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Изменяет видимость заполнителя даты и времени мастер-слайда и всех дочерних заполнителей даты и времени. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах макета и зависимых слайдах. Зависимые слайды макета и слайды используют и зависят от мастер-слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнители даты и времени видимыми, иначе — скрывает их. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Устанавливает текст в заполнитель нижнего колонтитула мастер-слайда и все дочерние заполнители нижнего колонтитула. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах макета и зависимых слайдах. Зависимые слайды макета и слайды используют и зависят от мастер-слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Устанавливает текст в заполнитель даты и времени мастер-слайда и все дочерние заполнители даты и времени. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах макета и зависимых слайдах. Зависимые слайды макета и слайды используют и зависят от мастер-слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |