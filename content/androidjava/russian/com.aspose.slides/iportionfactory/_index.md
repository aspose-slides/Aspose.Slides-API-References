---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Позволяет создавать тестовые части
type: docs
url: /ru/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Позволяет создавать тестовые части

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createPortion()](#createPortion--) | Создаёт пустую текстовую часть. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Создаёт текстовую часть из указанной строки. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Создаёт часть, используя указанные данные части. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


Создаёт пустую текстовую часть.

**Возвращаемое значение:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


Создаёт текстовую часть из указанной строки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| str | java.lang.String | String. |

**Возвращаемое значение:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


Создаёт часть, используя указанные данные части.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Часть для использования. |

**Возвращаемое значение:**
[IPortion](../../com.aspose.slides/iportion) - Portion.