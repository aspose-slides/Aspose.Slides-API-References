---
title: Zip64Mode
second_title: Aspose.Slides Java API hivatkozás
description: Megadja, hogy mikor kell használni a ZIP64 formátumkiegészítéseket az OpenXML-fájlhoz.
type: docs
url: /hu/com.aspose.slides/zip64mode/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Megadja, hogy mikor kell használni a ZIP64 formátumkiegészítéseket az OpenXML-fájlhoz.

--------------------

Az OpenXML-fájl egy ZIP-archívum, amelynek 4 GB (2^32 bájt) korláta van a fájl tömörítetlen méretére, a fájl tömörített méretére és az archívum teljes méretére, valamint 65 535 (2^16-1) fájl korláta van az archívumban. A ZIP64 formátumkiegészítések növelik a korlátokat 2^64-re.
## Mezők

| Mező | Leírás |
| --- | --- |
| [Never](#Never) | Ne használjon ZIP64 formátumkiegészítéseket. |
| [IfNecessary](#IfNecessary) | Használja a ZIP64 formátumkiegészítéseket, ha szükséges. |
| [Always](#Always) | Mindig használja a ZIP64 formátumkiegészítéseket. |
### Never {#Never}
```
public static final int Never
```

Ne használjon ZIP64 formátumkiegészítéseket.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

Használja a ZIP64 formátumkiegészítéseket, ha szükséges.

### Always {#Always}
```
public static final int Always
```

Mindig használja a ZIP64 formátumkiegészítéseket.