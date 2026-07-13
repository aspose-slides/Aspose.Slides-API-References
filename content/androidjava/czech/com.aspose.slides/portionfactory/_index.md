---
title: PortionFactory
second_title: Aspose.Slides pro Android - reference Java API
description: Umožňuje vytvářet testovací části
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

Umožňuje vytvořit testovací části

--------------------

Pro kompatibilitu s COM
## Konstruktorové metod

| Konstruktor | Popis |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [createPortion()](#createPortion--) | Vytvoří prázdnou textovou část. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Vytvoří textovou část ze zadaného řetězce. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Vytvoří část pomocí zadaných dat části. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


Vytvoří prázdnou textovou část.

**Vrací:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


Vytvoří textovou část ze zadaného řetězce.

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


Vytvoří část pomocí zadaných dat části.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Část, která se má použít. |

**Vrací:**
[IPortion](../../com.aspose.slides/iportion) - Portion.