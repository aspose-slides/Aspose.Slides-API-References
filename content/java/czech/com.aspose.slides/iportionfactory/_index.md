---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
description: Umožňuje vytvářet testové části
type: docs
url: /cs/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Umožňuje vytvářet testové části

--------------------

Pro kompatibilitu s COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createPortion()](#createPortion--) | Vytvoří prázdnou textovou Portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Vytvoří textovou Portion ze zadaného řetězce. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Vytvoří Portion pomocí specifikovaných dat Portion. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


Vytvoří prázdnou textovou Portion.

**Vrací:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


Vytvoří textovou Portion ze zadaného řetězce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| str | java.lang.String | String. |

**Vrací:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


Vytvoří Portion pomocí specifikovaných dat Portion.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Portion k použití. |

**Vrací:**
[IPortion](../../com.aspose.slides/iportion) - Portion.