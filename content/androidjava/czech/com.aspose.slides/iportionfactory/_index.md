---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create test portions
type: docs
url: /cs/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Umožňuje vytvářet testovací části

--------------------

Pro kompatibilitu s COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createPortion()](#createPortion--) | Vytvoří prázdnou textovou část. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Vytvoří textovou část ze zadaného řetězce. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Vytvoří Portion pomocí specifikovaných dat Portion. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


Vytvoří prázdnou textovou část.

**Returns:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


Vytvoří textovou část ze zadaného řetězce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| str | java.lang.String | String. |

**Returns:**
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

**Returns:**
[IPortion](../../com.aspose.slides/iportion) - Portion.