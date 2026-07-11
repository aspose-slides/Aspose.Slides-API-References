---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет менеджер, который управляет поведением заполнителей подвала главного слайда, даты-времени, номеров страниц и всех дочерних заполнителей.
type: docs
url: /ru/com.aspose.slides/masterslideheaderfootermanager/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
```
public final class MasterSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IMasterSlideHeaderFooterManager
```

Представляет менеджер, который управляет поведением подвала главного слайда, заполнителями даты-времени, номеров страниц и всех дочерних заполнителей. Дочерние заполнители означают, что заполнители находятся на зависимых от макета слайдах и зависимых слайдах. Зависимые от макета слайды и слайды используют и зависят от главного слайда.
## Методы

| Метод | Описание |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Изменяет видимость заполнителя подвала главного слайда и всех дочерних заполнителей подвала. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Изменяет видимость заполнителя номера страницы главного слайда и всех дочерних заполнителей номеров страниц. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Изменяет видимость заполнителя даты-времени главного слайда и всех дочерних заполнителей даты-времени. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Устанавливает текст в заполнитель подвала главного слайда и все дочерние заполнители подвала. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Устанавливает текст в заполнитель даты-времени главного слайда и все дочерние заполнители даты-времени. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Изменяет видимость заполнителя подвала главного слайда и всех дочерних заполнителей подвала. Дочерние заполнители означают, что заполнители находятся на зависимых от макета слайдах и зависимых слайдах. Зависимые от макета слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнители подвала видимыми, иначе — скрывает их. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Изменяет видимость заполнителя номера страницы главного слайда и всех дочерних заполнителей номеров страниц. Дочерние заполнители означают, что заполнители находятся на зависимых от макета слайдах и зависимых слайдах. Зависимые от макета слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнители номеров страниц видимыми, иначе — скрывает их. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Изменяет видимость заполнителя даты-времени главного слайда и всех дочерних заполнителей даты-времени. Дочерние заполнители означают, что заполнители находятся на зависимых от макета слайдах и зависимых слайдах. Зависимые от макета слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнители даты-времени видимыми, иначе — скрывает их. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Устанавливает текст в заполнитель подвала главного слайда и все дочерние заполнители подвала. Дочерние заполнители означают, что заполнители находятся на зависимых от макета слайдах и зависимых слайдах. Зависимые от макета слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Устанавливает текст в заполнитель даты-времени главного слайда и все дочерние заполнители даты-времени. Дочерние заполнители означают, что заполнители находятся на зависимых от макета слайдах и зависимых слайдах. Зависимые от макета слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |