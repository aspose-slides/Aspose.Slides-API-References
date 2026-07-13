---
title: PortionFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa testdelar
type: docs
url: /sv/com.aspose.slides/portionfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Tillåter att skapa testdelar

--------------------

För COM-kompatibilitet
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createPortion()](#createPortion--) | Skapar en tom textdel. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Skapar en textdel från angiven sträng. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Skapar en del med användning av specificerade deldata. |

### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```

### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```

Skapar en tom textdel.

**Returnerar:**
[IPortion](../../com.aspose.slides/iportion) - Portion.

### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```

Skapar en textdel från angiven sträng.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | java.lang.String | Sträng. |

**Returnerar:**
[IPortion](../../com.aspose.slides/iportion) - Portion.

### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```

Skapar en del med användning av specificerade deldata.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | En del att använda. |

**Returnerar:**
[IPortion](../../com.aspose.slides/iportion) - Portion.