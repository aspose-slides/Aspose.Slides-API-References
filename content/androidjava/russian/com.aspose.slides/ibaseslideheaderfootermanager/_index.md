---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides для Android через справочник API Java
description: Представляет менеджер, который управляет поведением placeholders нижнего колонтитула, даты-времени и номера страницы для всех типов слайдов.
type: docs
url: /ru/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Представляет менеджер, который управляет поведением placeholders нижнего колонтитула, даты-времени и номера страницы для всех типов слайдов.
## Методы

| Метод | Описание |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Получает значение, указывающее, что placeholder нижнего колонтитула присутствует. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Получает значение, указывающее, что placeholder номера страницы присутствует. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Получает значение, указывающее, что placeholder даты-времени присутствует. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Изменяет видимость placeholder нижнего колонтитула слайда. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Изменяет видимость placeholder номера страницы слайда. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Изменяет видимость placeholder даты-времени слайда. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Устанавливает текст в placeholder нижнего колонтитула слайда. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Устанавливает текст в placeholder даты-времени слайда. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Получает значение, указывающее, что placeholder нижнего колонтитула присутствует. Читает boolean.

**Возвращаемое значение:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Получает значение, указывающее, что placeholder номера страницы присутствует. Читает boolean.

**Возвращаемое значение:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Получает значение, указывающее, что placeholder даты-времени присутствует. Читает boolean.

**Возвращаемое значение:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Изменяет видимость placeholder нижнего колонтитула слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает placeholder нижнего колонтитула видимым, иначе - скрывает его. |
### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Изменяет видимость placeholder номера страницы слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает placeholder номера страницы видимым, иначе - скрывает его. |
### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Изменяет видимость placeholder даты-времени слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает placeholder даты-времени видимым, иначе - скрывает его. |
### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Устанавливает текст в placeholder нижнего колонтитула слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |
### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Устанавливает текст в placeholder даты-времени слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |