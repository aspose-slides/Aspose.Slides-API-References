---
title: Zip64Mode
second_title: Aspose.Slides für Java API-Referenz
description: Gibt an, wann ZIP64-Format-Erweiterungen für OpenXML-Dateien verwendet werden sollen.
type: docs
url: /de/com.aspose.slides/zip64mode/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Gibt an, wann ZIP64-Format-Erweiterungen für OpenXML-Dateien verwendet werden sollen.

--------------------

Eine OpenXML-Datei ist ein ZIP-Archiv, das ein Limit von 4 GB (2^32 Bytes) für die unkomprimierte Dateigröße, die komprimierte Dateigröße und die Gesamtheit des Archivs hat sowie ein Limit von 65 535 (2^16-1) Dateien im Archiv. ZIP64-Format-Erweiterungen erhöhen die Grenzen auf 2^64.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Never](#Never) | Verwenden Sie keine ZIP64-Format-Erweiterungen. |
| [IfNecessary](#IfNecessary) | Verwenden Sie ZIP64-Format-Erweiterungen, falls erforderlich. |
| [Always](#Always) | Verwenden Sie stets ZIP64-Format-Erweiterungen. |
### Never {#Never}
```
public static final int Never
```

Verwenden Sie keine ZIP64-Format-Erweiterungen.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

Verwenden Sie ZIP64-Format-Erweiterungen, falls erforderlich.

### Always {#Always}
```
public static final int Always
```

Verwenden Sie stets ZIP64-Format-Erweiterungen.