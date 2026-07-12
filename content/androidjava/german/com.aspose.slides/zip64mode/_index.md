---
title: Zip64Mode
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Gibt an, wann ZIP64-Format-Erweiterungen für OpenXML-Dateien verwendet werden sollen.
type: docs
url: /de/com.aspose.slides/zip64mode/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Gibt an, wann ZIP64-Format-Erweiterungen für OpenXML-Datei verwendet werden sollen.

--------------------

Eine OpenXML-Datei ist ein ZIP-Archiv, das ein Limit von 4 GB (2^32 Byte) für die unkomprimierte Größe einer Datei, die komprimierte Größe einer Datei und die Gesamtegröße des Archivs hat, sowie ein Limit von 65 535 (2^16-1) Dateien im Archiv. ZIP64-Format-Erweiterungen erhöhen die Grenzen auf 2^64.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Never](#Never) | ZIP64-Format-Erweiterungen nicht verwenden. |
| [IfNecessary](#IfNecessary) | ZIP64-Format-Erweiterungen bei Bedarf verwenden. |
| [Always](#Always) | ZIP64-Format-Erweiterungen immer verwenden. |
### Never {#Never}
```
public static final int Never
```


ZIP64-Format-Erweiterungen nicht verwenden.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```


ZIP64-Format-Erweiterungen bei Bedarf verwenden.

### Always {#Always}
```
public static final int Always
```


Immer ZIP64-Format-Erweiterungen verwenden.