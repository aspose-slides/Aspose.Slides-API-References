---
title: IMasterTheme
second_title: Справочник API Aspose.Slides для Java
description: Представляет мастер-тему.
type: docs
url: /ru/com.aspose.slides/imastertheme/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Представляет мастер-тему.
## Методы

| Метод | Описание |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Возвращает коллекцию дополнительных схем цвета. |
| [getName()](#getName--) | Возвращает имя темы. |
| [setName(String value)](#setName-java.lang.String-) | Возвращает имя темы. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```


Возвращает коллекцию дополнительных схем цвета. Эти схемы не влияют на внешний вид презентации, их можно выбрать в качестве основной схемы цвета для слайда. Только для чтения [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Возвращаемое значение:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```


Возвращает имя темы. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Возвращает имя темы. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |