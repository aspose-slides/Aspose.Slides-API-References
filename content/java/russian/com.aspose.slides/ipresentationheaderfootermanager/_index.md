---
title: IPresentationHeaderFooterManager
second_title: Справочник API Aspose.Slides для Java
description: Представляет менеджер, который управляет поведением всех заполнителей нижних колонтитулов, даты и времени и номеров страниц презентации.
type: docs
url: /ru/com.aspose.slides/ipresentationheaderfootermanager/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Представляет менеджер, который управляет поведением всех заполнителей нижнего колонтитула, даты и времени и номеров страниц презентации.

## Методы

| Метод | Описание |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Изменяет видимость всех заполнителей верхних колонтитулов, включая мастер заметок, слайды заметок и мастер раздаточных материалов. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Изменяет видимость всех заполнителей нижних колонтитулов, включая главные слайды, слайды макета и обычные слайды. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Изменяет видимость всех заполнителей номеров страниц, включая главные слайды, слайды макета и обычные слайды. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Изменяет видимость всех заполнителей даты и времени, включая главные слайды, слайды макета и обычные слайды. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Устанавливает текст для всех заполнителей верхних колонтитулов, включая мастер заметок, слайды заметок и мастер раздаточных материалов. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Устанавливает текст для всех заполнителей нижних колонтитулов, включая главные слайды, слайды макета и обычные слайды. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Устанавливает текст для всех заполнителей даты и времени, включая главные слайды, слайды макета и обычные слайды. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Меняет видимость заполнителей нижнего колонтитула, даты и времени и номеров страниц для всех титульных слайдов и для первого слайда макета. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Изменяет видимость всех заполнителей верхних колонтитулов, включая мастер заметок, слайды заметок и мастер раздаточных материалов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true – делает заполнители верхних колонтитулов видимыми, иначе – скрывает их. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Изменяет видимость всех заполнителей нижних колонтитулов, включая главные слайды, слайды макета и обычные слайды.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true – делает заполнители нижних колонтитулов видимыми, иначе – скрывает их. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Изменяет видимость всех заполнителей номеров страниц, включая главные слайды, слайды макета и обычные слайды.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true – делает заполнители номеров страниц видимыми, иначе – скрывает их. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Изменяет видимость всех заполнителей даты и времени, включая главные слайды, слайды макета и обычные слайды.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true – делает заполнители даты и времени видимыми, иначе – скрывает их. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Устанавливает текст для всех заполнителей верхних колонтитулов, включая мастер заметок, слайды заметок и мастер раздаточных материалов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Устанавливает текст для всех заполнителей нижних колонтитулов, включая главные слайды, слайды макета и обычные слайды.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Устанавливает текст для всех заполнителей даты и времени, включая главные слайды, слайды макета и обычные слайды.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Меняет видимость заполнителей нижнего колонтитула, даты и времени и номеров страниц для всех титульных слайдов и для первого слайда макета. Титульные слайды – слайды, основанные на первом слайде макета (независимо от типа этого первого макета).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true – делает заполнители видимыми, иначе – скрывает их. |