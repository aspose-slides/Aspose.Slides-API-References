---
title: IPortionFactory
second_title: Aspose.Slides dla Android za pomocą Java API
description: Umożliwia tworzenie fragmentów testowych
type: docs
url: /pl/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Umożliwia tworzenie fragmentów testowych

--------------------

Dla zgodności z COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createPortion()](#createPortion--) | Tworzy pusty fragment tekstu. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Tworzy fragment tekstowy z określonego łańcucha. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Tworzy fragment przy użyciu określonych danych fragmentu. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


Tworzy pusty fragment tekstu.

**Zwraca:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


Tworzy fragment tekstowy z określonego łańcucha.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| str | java.lang.String | String. |

**Zwraca:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


Tworzy fragment przy użyciu określonych danych fragmentu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Portion do użycia. |

**Zwraca:**
[IPortion](../../com.aspose.slides/iportion) - Portion.