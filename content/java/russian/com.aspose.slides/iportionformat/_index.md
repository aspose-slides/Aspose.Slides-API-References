---
title: IPortionFormat
second_title: Aspose.Slides для Java справочник API
description: Этот класс содержит свойства форматирования текстовой части.
type: docs
url: /ru/com.aspose.slides/iportionformat/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Этот класс содержит свойства форматирования текстовых частей. В отличие от [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), все свойства этого класса доступны для записи.

--------------------

Этот класс используется для получения и изменения свойств форматирования текстовой части, определённых для конкретной части. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить эффективные значения параметров форматирования, включая наследованные, необходимо использовать метод [getEffective](../../com.aspose.slides/iportionformat\#getEffective), который возвращает экземпляр [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Методы

| Метод | Описание |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Возвращает или задаёт идентификатор закладки. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Возвращает или задаёт идентификатор закладки. |
| [getSmartTagClean()](#getSmartTagClean--) | Определяет, следует ли очищать смарт-тег. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Определяет, следует ли очищать смарт-тег. |
| [getEffective()](#getEffective--) | Получает эффективные данные форматирования части с применённым наследованием. |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Определяет, следует ли очищать смарт-тег. Наследование не применяется. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Определяет, следует ли очищать смарт-тег. Наследование не применяется. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Получает эффективные данные форматирования части с применённым наследованием.

**Возвращаемое значение:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) — экземпляр [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).