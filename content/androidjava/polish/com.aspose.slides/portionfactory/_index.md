---
title: PortionFactory
second_title: Referencja API Java Aspose.Slides dla Androida
description: Umożliwia tworzenie części testowych
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

Umożliwia tworzenie części testowych

--------------------

Dla zgodności z COM
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [createPortion()](#createPortion--) | Tworzy pustą tekstową Portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Tworzy Portion tekstowy z określonego ciągu znaków. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Tworzy Portion przy użyciu określonych danych Portion. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


Tworzy pustą tekstową Portion.

**Zwraca:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


Tworzy Portion tekstowy z określonego ciągu znaków.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| str | java.lang.String | String. |

**Zwraca:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


Tworzy Portion przy użyciu określonych danych Portion.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Portion do użycia. |

**Zwraca:**
[IPortion](../../com.aspose.slides/iportion) - Portion.