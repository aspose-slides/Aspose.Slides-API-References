---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create test portions
type: docs
url: /pl/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Umożliwia tworzenie fragmentów testowych

--------------------

Dla zgodności z COM
## Metody

| Method | Description |
| --- | --- |
| [createPortion()](#createPortion--) | Tworzy pusty fragment tekstowy Portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Tworzy fragment tekstowy Portion z określonego ciągu znaków. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Tworzy fragment Portion przy użyciu określonych danych fragmentu. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


Tworzy pusty fragment tekstowy Portion.

**Zwraca:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


Tworzy fragment tekstowy Portion z określonego ciągu znaków.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String | String. |

**Zwraca:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


Tworzy fragment Portion przy użyciu określonych danych fragmentu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Portion do użycia. |

**Zwraca:**
[IPortion](../../com.aspose.slides/iportion) - Portion.