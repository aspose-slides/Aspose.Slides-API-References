---
title: IPortionFormat
second_title: Aspose.Slides для Android через справочник Java API
description: Этот класс содержит свойства форматирования текстовых фрагментов.
type: docs
url: /ru/com.aspose.slides/iportionformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Этот класс содержит свойства форматирования текстовых фрагментов. В отличие от [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), все свойства этого класса доступны для записи.

--------------------

Этот класс используется для получения и изменения свойств форматирования текстовых фрагментов, определённых для конкретного фрагмента. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [getEffective](../../com.aspose.slides/iportionformat\#getEffective), который возвращает экземпляр [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Методы

| Method | Description |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Возвращает или задаёт идентификатор закладки. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Возвращает или задаёт идентификатор закладки. |
| [getSmartTagClean()](#getSmartTagClean--) | Определяет, следует ли очистить смарт-тег. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Определяет, следует ли очистить смарт-тег. |
| [getEffective()](#getEffective--) | Получает эффективные данные форматирования части с учётом наследования. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Возвращает или задаёт идентификатор закладки. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

Возвращает или задаёт идентификатор закладки. Чтение/запись String.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Определяет, следует ли очистить смарт-тег. Наследование не применяется. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Определяет, следует ли очистить смарт-тег. Наследование не применяется. Чтение/запись boolean.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Получает эффективные данные форматирования части с учётом наследования.

**Возвращаемое значение:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).