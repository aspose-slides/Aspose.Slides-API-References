---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create test portions
type: docs
url: /sv/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Tillåter att skapa test Portion

--------------------

För COM-kompatibilitet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createPortion()](#createPortion--) | Skapar en tom text Portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Skapar en text Portion från specificerad sträng. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Skapar en Portion med användning av specificerad portionsdata. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


Skapar en tom text Portion.

**Returnerar:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


Skapar en text Portion från specificerad sträng.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | java.lang.String | String. |

**Returnerar:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


Skapar en Portion med användning av specificerad portionsdata.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | En Portion att använda. |

**Returnerar:**
[IPortion](../../com.aspose.slides/iportion) - Portion.