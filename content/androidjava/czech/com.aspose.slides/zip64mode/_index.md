---
title: Zip64Mode
second_title: Aspose.Slides pro Android přes Java API Reference
description: Určuje, kdy použít rozšíření formátu ZIP64 pro soubor OpenXML.
type: docs
url: /cs/com.aspose.slides/zip64mode/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Určuje, kdy použít rozšíření formátu ZIP64 pro soubor OpenXML.

--------------------

Soubor OpenXML je ZIP archiv, který má limit 4 GB (2^32 bajtů) na nekomprimovanou velikost souboru, komprimovanou velikost souboru a celkovou velikost archivu, stejně jako limit 65 535 (2^16-1) souborů v archivu. Rozšíření formátu ZIP64 zvyšují limity na 2^64.
## Pole

| Pole | Popis |
| --- | --- |
| [Never](#Never) | Nevyužívejte rozšíření formátu ZIP64. |
| [IfNecessary](#IfNecessary) | Použijte rozšíření formátu ZIP64, pokud je to nutné. |
| [Always](#Always) | Vždy používejte rozšíření formátu ZIP64. |
### Never {#Never}
```
public static final int Never
```

Nevyužívejte rozšíření formátu ZIP64.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

Použijte rozšíření formátu ZIP64, pokud je to nutné.

### Always {#Always}
```
public static final int Always
```

Vždy používejte rozšíření formátu ZIP64.