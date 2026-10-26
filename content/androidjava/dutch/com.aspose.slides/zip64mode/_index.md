---
title: Zip64Mode
second_title: Aspose.Slides voor Android via Java API-referentie
description: Geeft aan wanneer ZIP64-formaatuitbreidingen moeten worden gebruikt voor een OpenXML-bestand.
type: docs
url: /nl/com.aspose.slides/zip64mode/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Geeft aan wanneer ZIP64-formaatuitbreidingen moeten worden gebruikt voor een OpenXML-bestand.

--------------------

Een OpenXML-bestand is een ZIP-archief dat een limiet van 4 GB (2^32 bytes) heeft voor de ongecomprimeerde bestandsgrootte, de gecomprimeerde bestandsgrootte en de totale grootte van het archief, evenals een limiet van 65.535 (2^16-1) bestanden in het archief. ZIP64-formaatuitbreidingen verhogen de limieten tot 2^64.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Never](#Never) | Gebruik ZIP64-formaatuitbreidingen niet. |
| [IfNecessary](#IfNecessary) | Gebruik ZIP64-formaatuitbreidingen indien nodig. |
| [Always](#Always) | Gebruik ZIP64-formaatuitbreidingen altijd. |
### Never {#Never}
```
public static final int Never
```

Gebruik ZIP64-formaatuitbreidingen niet.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

Gebruik ZIP64-formaatuitbreidingen indien nodig.

### Always {#Always}
```
public static final int Always
```

Gebruik ZIP64-formaatuitbreidingen altijd.