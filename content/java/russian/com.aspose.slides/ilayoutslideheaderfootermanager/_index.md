---
title: ILayoutSlideHeaderFooterManager
second_title: Ссылка на API Aspose.Slides для Java
description: Представляет менеджер, который управляет поведением плейсхолдеров нижнего колонтитула, даты-времени, номера страницы макетного слайда и всех дочерних плейсхолдеров.
type: docs
url: /ru/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Представляет менеджер, который управляет поведением плейсхолдеров нижнего колонтитула, даты-времени и номера страницы макетного слайда, а также всех дочерних плейсхолдеров. Дочерние плейсхолдеры означают, что плейсхолдеры находятся на зависимых слайдах. Зависимые слайды используют и зависят от макетного слайда.
## Методы

| Метод | Описание |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Изменяет видимость плейсхолдера нижнего колонтитула макетного слайда и всех дочерних плейсхолдеров нижнего колонтитула. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Изменяет видимость плейсхолдера номера страницы макетного слайда и всех дочерних плейсхолдеров номера страницы. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Изменяет видимость плейсхолдера даты-времени макетного слайда и всех дочерних плейсхолдеров даты-времени. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Устанавливает текст в плейсхолдер нижнего колонтитула макетного слайда и все дочерние плейсхолдеры нижнего колонтитула. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Устанавливает текст в плейсхолдер даты-времени макетного слайда и все дочерние плейсхолдеры даты-времени. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Изменяет видимость плейсхолдера нижнего колонтитула макетного слайда и всех дочерних плейсхолдеров нижнего колонтитула. Дочерние плейсхолдеры означают, что плейсхолдеры находятся на зависимых слайдах. Зависимые слайды используют и зависят от мастер-слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает плейсхолдеры нижнего колонтитула видимыми, иначе — скрывает их. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Изменяет видимость плейсхолдера номера страницы макетного слайда и всех дочерних плейсхолдеров номера страницы. Дочерние плейсхолдеры означают, что плейсхолдеры находятся на зависимых слайдах. Зависимые слайды используют и зависят от макетного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает плейсхолдеры номера страницы видимыми, иначе — скрывает их. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Изменяет видимость плейсхолдера даты-времени макетного слайда и всех дочерних плейсхолдеров даты-времени. Дочерние плейсхолдеры означают, что плейсхолдеры находятся на зависимых слайдах. Зависимые слайды используют и зависят от макетного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает плейсхолдеры даты-времени видимыми, иначе — скрывает их. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Устанавливает текст в плейсхолдер нижнего колонтитула макетного слайда и все дочерние плейсхолдеры нижнего колонтитула. Дочерние плейсхолдеры означают, что плейсхолдеры находятся на зависимых слайдах. Зависимые слайды используют и зависят от макетного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Устанавливает текст в плейсхолдер даты-времени макетного слайда и все дочерние плейсхолдеры даты-времени. Дочерние плейсхолдеры означают, что плейсхолдеры находятся на зависимых слайдах. Зависимые слайды используют и зависят от макетного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |