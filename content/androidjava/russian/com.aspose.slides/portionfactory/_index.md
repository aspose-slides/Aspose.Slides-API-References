---
title: PortionFactory
second_title: Aspose.Slides для Android через справку Java API
description: Позволяет создавать тестовые части
type: docs
url: /ru/com.aspose.slides/portionfactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Позволяет создавать тестовые части

--------------------

Для совместимости с COM
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createPortion()](#createPortion--) | Создает пустую текстовую часть. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Создает текстовую часть из указанной строки. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Создает часть, используя данные указанной части. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


Создает пустую текстовую часть.

**Возвращаемое значение:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


Создает текстовую часть из указанной строки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| str | java.lang.String | String. |

**Возвращаемое значение:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


Создает часть, используя данные указанной части.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Часть для использования. |

**Возвращаемое значение:**
[IPortion](../../com.aspose.slides/iportion) - Portion.