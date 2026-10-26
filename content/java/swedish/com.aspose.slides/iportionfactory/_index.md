---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
description: Tillåter att skapa testportioner
type: docs
url: /sv/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Tillåter att skapa testportioner

--------------------

För COM-kompatibilitet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createPortion()](#createPortion--) | Skapar en tom textportion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Skapar en textportion från angiven sträng. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Skapar en portion genom att använda specificerad portionsdata. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

Skapar en tom textportion.

**Returnerar:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

Skapar en textportion från angiven sträng.

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

Skapar en portion genom att använda specificerad portionsdata.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | En portion att använda. |

**Returnerar:**
[IPortion](../../com.aspose.slides/iportion) - Portion.