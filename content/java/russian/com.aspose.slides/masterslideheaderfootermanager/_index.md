---
title: MasterSlideHeaderFooterManager
second_title: Справочник API Aspose.Slides для Java
description: Представляет менеджер, который управляет поведением подстановок нижнего колонтитула, даты и времени, номера страницы главного слайда и всех дочерних подстановок.
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

Представляет менеджер, который управляет поведением подстановок нижнего колонтитула главного слайда, даты и времени, номеров страниц и всех дочерних подстановок. Дочерние подстановки означают, что подстановки находятся на зависящих от макета слайдах и зависимых слайдах. Зависящие от макета слайды и слайды используют и зависят от главного слайда.

## Методы

| Метод | Описание |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Изменяет видимость подстановки нижнего колонтитула главного слайда и всех дочерних подстановок нижнего колонтитула. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Изменяет видимость подстановки номера страницы главного слайда и всех дочерних подстановок номеров страниц. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Изменяет видимость подстановки даты и времени главного слайда и всех дочерних подстановок даты и времени. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Устанавливает текст в подстановку нижнего колонтитула главного слайда и все дочерние подстановки нижнего колонтитула. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Устанавливает текст в подстановку даты и времени главного слайда и все дочерние подстановки даты и времени. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Изменяет видимость подстановки нижнего колонтитула главного слайда и всех дочерних подстановок нижнего колонтитула. Дочерние подстановки означают, что подстановки находятся на зависящих от макета слайдах и зависимых слайдах. Зависящие от макета слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает подстановки нижнего колонтитула видимыми, иначе скрывает их. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Изменяет видимость подстановки номера страницы главного слайда и всех дочерних подстановок номеров страниц. Дочерние подстановки означают, что подстановки находятся на зависящих от макета слайдах и зависимых слайдах. Зависящие от макета слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает подстановки номера страницы видимыми, иначе скрывает их. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Изменяет видимость подстановки даты и времени главного слайда и всех дочерних подстановок даты и времени. Дочерние подстановки означают, что подстановки находятся на зависящих от макета слайдах и зависимых слайдах. Зависящие от макета слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает подстановки даты и времени видимыми, иначе скрывает их. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Устанавливает текст в подстановку нижнего колонтитула главного слайда и все дочерние подстановки нижнего колонтитула. Дочерние подстановки означают, что подстановки находятся на зависящих от макета слайдах и зависимых слайдах. Зависящие от макета слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Устанавливает текст в подстановку даты и времени главного слайда и все дочерние подстановки даты и времени. Дочерние подстановки означают, что подстановки находятся на зависящих от макета слайдах и зависимых слайдах. Зависящие от макета слайды и слайды используют и зависят от главного слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |