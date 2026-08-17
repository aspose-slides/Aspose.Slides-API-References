---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides для Java — справочник API
description: Представляет менеджер, который управляет поведением заполнителей нижнего колонтитула, даты-времени, номера страницы главного слайда и всех дочерних заполнителей.
type: docs
url: /ru/com.aspose.slides/imasterslideheaderfootermanager/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Представляет менеджер, который управляет поведением заполнителей нижнего колонтитула, даты-времени, номера страницы главного слайда и всех дочерних заполнителей. Дочерние заполнители означают, что заполнители находятся на зависимых макетных слайдах и зависимых слайдах. Зависимые макетные слайды и слайды используют и зависят от главного слайда.
## Методы

| Метод | Описание |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Изменяет видимость заполнителя нижнего колонтитула главного слайда и всех дочерних заполнителей нижнего колонтитула. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Изменяет видимость заполнителя номера страницы главного слайда и всех дочерних заполнителей номера страницы. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Изменяет видимость заполнителя даты-времени главного слайда и всех дочерних заполнителей даты-времени. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Устанавливает текст в заполнитель нижнего колонтитула главного слайда и все дочерние заполнители нижнего колонтитула. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Устанавливает текст в заполнитель даты-времени главного слайда и все дочерние заполнители даты-времени. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Изменяет видимость заполнителя нижнего колонтитула главного слайда и всех дочерних заполнителей нижнего колонтитула. Дочерние заполнители означают, что заполнители находятся на зависимых макетных слайдах и зависимых слайдах. Зависимые макетные слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает заполнители нижнего колонтитула видимыми, иначе скрывает их. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Изменяет видимость заполнителя номера страницы главного слайда и всех дочерних заполнителей номера страницы. Дочерние заполнители означают, что заполнители находятся на зависимых макетных слайдах и зависимых слайдах. Зависимые макетные слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает заполнители номера страницы видимыми, иначе скрывает их. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Изменяет видимость заполнителя даты-времени главного слайда и всех дочерних заполнителей даты-времени. Дочерние заполнители означают, что заполнители находятся на зависимых макетных слайдах и зависимых слайдах. Зависимые макетные слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает заполнители даты-времени видимыми, иначе скрывает их. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Устанавливает текст в заполнитель нижнего колонтитула главного слайда и все дочерние заполнители нижнего колонтитула. Дочерние заполнители означают, что заполнители находятся на зависимых макетных слайдах и зависимых слайдах. Зависимые макетные слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Устанавливает текст в заполнитель даты-времени главного слайда и все дочерние заполнители даты-времени. Дочерние заполнители означают, что заполнители находятся на зависимых макетных слайдах и зависимых слайдах. Зависимые макетные слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |