---
title: Zip64Mode
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert wanneer ZIP64-formaatextensies voor een OpenXML-bestand moeten worden gebruikt.
type: docs
url: /nl/com.aspose.slides/zip64mode/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Specificeert wanneer ZIP64-formaatextensies voor een OpenXML-bestand moeten worden gebruikt.

--------------------

Een OpenXML-bestand is een ZIP-archief dat een limiet van 4 GB (2^32 bytes) heeft voor de ongecomprimeerde grootte van een bestand, de gecomprimeerde grootte van een bestand en de totale grootte van het archief, evenals een limiet van 65.535 (2^16-1) bestanden in het archief. ZIP64-formaatextensies verhogen de limieten tot 2^64.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Never](#Never) | Gebruik geen ZIP64-formaatextensies. |
| [IfNecessary](#IfNecessary) | Gebruik ZIP64-formaatextensies indien nodig. |
| [Always](#Always) | Gebruik altijd ZIP64-formaatextensies. |
### Nooit {#Never}
```
public static final int Never
```


Gebruik geen ZIP64-formaatextensies.

### IndienNodig {#IfNecessary}
```
public static final int IfNecessary
```


Gebruik ZIP64-formaatextensies indien nodig.

### Altijd {#Always}
```
public static final int Always
```


Gebruik altijd ZIP64-formaatextensies.