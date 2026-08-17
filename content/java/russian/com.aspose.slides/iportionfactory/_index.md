---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
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

| Методы | Описание |
| --- | --- |
| [createPortion()](#createPortion--) | Создает пустой текстовый Portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Создает текстовый Portion из указанной строки. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Создает Portion, используя указанные данные Portion. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


Создает пустой текстовый Portion.

**Возвращаемое значение:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


Создает текстовый Portion из указанной строки.

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


Создает Portion, используя указанные данные Portion.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Portion для использования. |

**Возвращаемое значение:**
[IPortion](../../com.aspose.slides/iportion) - Portion.