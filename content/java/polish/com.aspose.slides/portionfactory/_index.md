---
title: PortionFactory
second_title: Aspose.Slides dla Java - Referencja API
description: Umożliwia tworzenie testowych fragmentów
type: docs
url: /pl/com.aspose.slides/portionfactory/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Umożliwia tworzenie testowych fragmentów

--------------------

Dla zgodności z COM
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [createPortion()](#createPortion--) | Tworzy pusty fragment tekstu. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Tworzy fragment tekstu z podanego łańcucha. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Tworzy fragment przy użyciu określonych danych fragmentu. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```

### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```

Tworzy pusty fragment tekstu.

**Zwraca:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```

Tworzy fragment tekstu z podanego łańcucha.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| str | java.lang.String | Łańcuch. |

**Zwraca:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```

Tworzy fragment przy użyciu określonych danych fragmentu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Fragment do użycia. |

**Zwraca:**
[IPortion](../../com.aspose.slides/iportion) - Portion.