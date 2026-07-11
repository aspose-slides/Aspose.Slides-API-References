---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет менеджер, который управляет поведением всех заполнителей нижних колонтитулов, даты и времени и номеров страниц презентации.
type: docs
url: /ru/com.aspose.slides/ipresentationheaderfootermanager/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Представляет менеджер, который управляет поведением всех заполнителей нижних колонтитулов, даты и времени и номеров страниц презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Изменяет видимость всех заполнителей заголовков, включая мастер заметок, слайды заметок и мастер раздаточных материалов. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Изменяет видимость всех заполнителей нижних колонтитулов, включая слайды-мастера, слайды-макета и слайды. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Изменяет видимость всех заполнителей номеров страниц, включая слайды-мастера, слайды-макета и слайды. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Изменяет видимость всех заполнителей даты и времени, включая слайды-мастера, слайды-макета и слайды. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Устанавливает текст во все заполнители заголовков, включая мастер заметок, слайды заметок и мастер раздаточных материалов. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Устанавливает текст во все заполнители нижних колонтитулов, включая слайды-мастера, слайды-макета и слайды. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Устанавливает текст во все заполнители даты и времени, включая слайды-мастера, слайды-макета и слайды. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Изменяет видимость заполнителей нижних колонтитулов, даты и времени и номеров страниц для всех титульных слайдов и для первого слайда-макета. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Изменяет видимость всех заполнителей заголовков, включая мастер заметок, слайды заметок и мастер раздаточных материалов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает заполнители заголовков видимыми, иначе скрывает их. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Изменяет видимость всех заполнителей нижних колонтитулов, включая слайды-мастера, слайды-макета и слайды.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает заполнители нижних колонтитулов видимыми, иначе скрывает их. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Изменяет видимость всех заполнителей номеров страниц, включая слайды-мастера, слайды-макета и слайды.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает заполнители номеров страниц видимыми, иначе скрывает их. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Изменяет видимость всех заполнителей даты и времени, включая слайды-мастера, слайды-макета и слайды.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает заполнители даты и времени видимыми, иначе скрывает их. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Устанавливает текст во все заполнители заголовков, включая мастер заметок, слайды заметок и мастер раздаточных материалов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Устанавливает текст во все заполнители нижних колонтитулов, включая слайды-мастера, слайды-макета и слайды.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Устанавливает текст во все заполнители даты и времени, включая слайды-мастера, слайды-макета и слайды.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Изменяет видимость заполнителей нижних колонтитулов, даты и времени и номеров страниц для всех титульных слайдов и для первого слайда-макета. Титульные слайды — слайды, основанные на первом слайде-макете (независимо от типа этого первого макета).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает заполнители видимыми, иначе скрывает их. |