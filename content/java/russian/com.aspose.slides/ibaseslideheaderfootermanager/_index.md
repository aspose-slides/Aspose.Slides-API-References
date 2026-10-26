---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides для Java: справка API
description: Представляет менеджер, который управляет поведением заполнителей нижнего колонтитула, даты-времени и номера страницы для всех типов слайдов.
type: docs
url: /ru/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Представляет менеджер, который управляет поведением заполнителей нижнего колонтитула, даты-времени и номера страницы для всех типов слайдов.
## Методы

| Метод | Описание |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Получает значение, указывающее, что заполнитель нижнего колонтитула присутствует. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Получает значение, указывающее, что заполнитель номера страницы присутствует. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Получает значение, указывающее, что заполнитель даты-времени присутствует. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Изменяет видимость заполнителя нижнего колонтитула слайда. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Изменяет видимость заполнителя номера страницы слайда. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Изменяет видимость заполнителя даты-времени слайда. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Устанавливает текст в заполнитель нижнего колонтитула слайда. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Устанавливает текст в заполнитель даты-времени слайда. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Получает значение, указывающее, что заполнитель нижнего колонтитула присутствует. Чтение boolean.

**Возвращает:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Получает значение, указывающее, что заполнитель номера страницы присутствует. Чтение boolean.

**Возвращает:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Получает значение, указывающее, что заполнитель даты-времени присутствует. Чтение boolean.

**Возвращает:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Изменяет видимость заполнителя нижнего колонтитула слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает заполнитель нижнего колонтитула видимым, иначе - скрывает его. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Изменяет видимость заполнителя номера страницы слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает заполнитель номера страницы видимым, иначе - скрывает его. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Изменяет видимость заполнителя даты-времени слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает заполнитель даты-времени видимым, иначе - скрывает его. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Устанавливает текст в заполнитель нижнего колонтитула слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Устанавливает текст в заполнитель даты-времени слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |