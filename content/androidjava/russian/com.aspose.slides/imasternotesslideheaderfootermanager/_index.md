---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет менеджер, который управляет поведением заполнителей нижнего колонтитула, даты и времени, номера страниц в слайде заметок мастера и всех дочерних заполнителей.
type: docs
url: /ru/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

Представляет менеджер, который управляет поведением нижнего колонтитула, даты и времени, номеров страниц в слайде заметок мастера, а также всех дочерних заполнителей. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

## Методы

| Method | Description |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Изменяет видимость заголовочного заполнителя слайдов заметок мастера и всех дочерних заголовочных заполнителей. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Устанавливает текст в заголовочный заполнитель слайдов заметок мастера и во все дочерние заголовочные заполнители. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Изменяет видимость заполнителя нижнего колонтитула слайдов заметок мастера и всех дочерних заполнителей нижнего колонтитула. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Изменяет видимость заполнителя номера слайда в слайде заметок мастера и всех дочерних заполнителей номеров слайдов. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Изменяет видимость заполнителя даты и времени в слайде заметок мастера и всех дочерних заполнителей даты и времени. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Устанавливает текст в заполнитель нижнего колонтитула слайдов заметок мастера и во все дочерние заполнители нижнего колонтитула. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Устанавливает текст в заполнитель даты и времени в слайде заметок мастера и во все дочерние заполнители даты и времени. |

### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Изменяет видимость заголовочного заполнителя слайдов заметок мастера и всех дочерних заголовочных заполнителей. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true — делает заголовочные заполнители видимыми, иначе — скрывает их. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

Устанавливает текст в заголовочный заполнитель слайдов заметок мастера и во все дочерние заголовочные заполнители. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Изменяет видимость заполнителя нижнего колонтитула слайдов заметок мастера и всех дочерних заполнителей нижнего колонтитула. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнители нижнего колонтитула видимыми, иначе — скрывает их. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Изменяет видимость заполнителя номера слайда в слайде заметок мастера и всех дочерних заполнителей номеров слайдов. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнители номеров слайдов видимыми, иначе — скрывает их. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Изменяет видимость заполнителя даты и времени в слайде заметок мастера и всех дочерних заполнителей даты и времени. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнители даты и времени видимыми, иначе — скрывает их. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Устанавливает текст в заполнитель нижнего колонтитула слайдов заметок мастера и во все дочерние заполнители нижнего колонтитула. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Устанавливает текст в заполнитель даты и времени в слайде заметок мастера и во все дочерние заполнители даты и времени. Дочерние заполнители означают, что заполнители находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |