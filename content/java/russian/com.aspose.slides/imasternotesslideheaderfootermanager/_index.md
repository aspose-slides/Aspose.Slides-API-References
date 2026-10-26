---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides для Java API Справочник
description: Представляет менеджер, который содержит поведение подложек нижнего колонтитула, даты-времени и номера страницы слайда заметок мастера, а также всех дочерних подложек.
type: docs
url: /ru/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

Представляет менеджер, который содержит логику подложек нижнего колонтитула, даты-времени и номера страницы слайдов заметок мастера, а также всех дочерних подложек. Дочерние подложки означают, что подложки находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.
## Методы

| Метод | Описание |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Изменяет видимость подложки заголовка слайда заметок мастера и всех дочерних подложек заголовка. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Устанавливает текст в подложку заголовка слайда заметок мастера и все дочерние подложки заголовка. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Изменяет видимость подложки нижнего колонтитула слайда заметок мастера и всех дочерних подложек нижнего колонтитула. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Изменяет видимость подложки номера страницы слайда заметок мастера и всех дочерних подложек номера страницы. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Изменяет видимость подложки даты-времени слайда заметок мастера и всех дочерних подложек даты-времени. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Устанавливает текст в подложку нижнего колонтитула слайда заметок мастера и все дочерние подложки нижнего колонтитула. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Устанавливает текст в подложку даты-времени слайда заметок мастера и все дочерние подложки даты-времени. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```

Изменяет видимость подложки заголовка слайда заметок мастера и всех дочерних подложек заголовка. Дочерние подложки означают, что подложки находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает подложки заголовка видимыми, иначе - скрывает их. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```

Устанавливает текст в подложку заголовка слайда заметок мастера и все дочерние подложки заголовка. Дочерние подложки означают, что подложки находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Изменяет видимость подложки нижнего колонтитула слайда заметок мастера и всех дочерних подложек нижнего колонтитула. Дочерние подложки означают, что подложки находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает подложки нижнего колонтитула видимыми, иначе - скрывает их. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Изменяет видимость подложки номера страницы слайда заметок мастера и всех дочерних подложек номера страницы. Дочерние подложки означают, что подложки находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает подложки номера страницы видимыми, иначе - скрывает их. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Изменяет видимость подложки даты-времени слайда заметок мастера и всех дочерних подложек даты-времени. Дочерние подложки означают, что подложки находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает подложки даты-времени видимыми, иначе - скрывает их. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Устанавливает текст в подложку нижнего колонтитула слайда заметок мастера и все дочерние подложки нижнего колонтитула. Дочерние подложки означают, что подложки находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Устанавливает текст в подложку даты-времени слайда заметок мастера и все дочерние подложки даты-времени. Дочерние подложки означают, что подложки находятся на зависимых слайдах заметок. Зависимые слайды заметок используют и зависят от слайда заметок мастера.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |