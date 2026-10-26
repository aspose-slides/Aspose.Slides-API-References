---
title: PortionFactory
second_title: Aspose.Slides pro Java API Reference
description: Umožňuje vytvářet testovací úseky
type: docs
url: /cs/com.aspose.slides/portionfactory/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Umožňuje vytvářet testovací úseky

--------------------

Pro kompatibilitu s COM
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [createPortion()](#createPortion--) | Vytvoří prázdný textový úsek. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Vytvoří textový úsek ze zadaného řetězce. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Vytvoří úsek pomocí specifikovaných dat úseku. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


Vytvoří prázdný textový úsek.

**Vrací:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


Vytvoří textový úsek ze zadaného řetězce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| str | java.lang.String | Řetězec. |

**Vrací:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


Vytvoří úsek pomocí specifikovaných dat úseku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Úsek k použití. |

**Vrací:**
[IPortion](../../com.aspose.slides/iportion) - Portion.