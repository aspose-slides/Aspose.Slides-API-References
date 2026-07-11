---
title: BaseSlideHeaderFooterManager
second_title: Aspose.Slides для Android - справка по Java API
description: Представляет менеджер, который управляет поведением заполнителей нижнего колонтитула, даты-времени и номера страницы для всех типов слайдов.
type: docs
url: /ru/com.aspose.slides/baseslideheaderfootermanager/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

Представляет менеджер, который управляет поведением заполнителей нижнего колонтитула, даты-времени и номера слайда для всех типов слайдов.
## Методы

| Метод | Описание |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Gets value indicating that a footer placeholder is present. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Gets value indicating that a page number placeholder is present. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Gets value indicating that a date-time placeholder is present. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Changes slide footer placeholder visibility. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Changes slide page number placeholder visibility. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Changes slide date-time placeholder visibility. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Sets text to slide footer placeholder. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Sets text to slide date-time placeholder. |
### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```

Получает значение, указывающее, что заполнитель нижнего колонтитула присутствует. Читает логическое значение.

**Возвращаемое значение:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```

Получает значение, указывающее, что заполнитель номера страницы присутствует. Читает логическое значение.

**Возвращаемое значение:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```

Получает значение, указывающее, что заполнитель даты-времени присутствует. Читает логическое значение.

**Возвращаемое значение:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```

Изменяет видимость заполнителя нижнего колонтитула слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнитель нижнего колонтитула видимым, иначе скрывает его. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```

Изменяет видимость заполнителя номера страницы слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнитель номера страницы видимым, иначе скрывает его. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```

Изменяет видимость заполнителя даты-времени слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает заполнитель даты-времени видимым, иначе скрывает его. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```

Устанавливает текст в заполнитель нижнего колонтитула слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```

Устанавливает текст в заполнитель даты-времени слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |