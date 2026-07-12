---
title: Zip64Mode
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Megadja, hogy mikor kell használni a ZIP64 formátum kiterjesztéseket az OpenXML fájlhoz.
type: docs
url: /hu/com.aspose.slides/zip64mode/
---
**Öröklődés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Megadja, hogy mikor kell használni a ZIP64 formátum kiterjesztéseket az OpenXML fájlhoz.

--------------------

Az OpenXML fájl egy ZIP-archívum, amelynek 4 GB (2^32 bájt) korlátja van a fájl tömörítetlen méretére, a fájl tömörített méretére és az archívum teljes méretére, valamint 65 535 (2^16-1) fájlra az archívumban. A ZIP64 formátum kiterjesztések a korlátokat 2^64-re növelik.
## Mezők

| Mező | Leírás |
| --- | --- |
| [Never](#Never) | Ne használjon ZIP64 formátum kiterjesztéseket. |
| [IfNecessary](#IfNecessary) | Használjon ZIP64 formátum kiterjesztéseket, ha szükséges. |
| [Always](#Always) | Mindig használjon ZIP64 formátum kiterjesztéseket. |
### Never {#Never}
```
public static final int Never
```

Ne használjon ZIP64 formátum kiterjesztéseket.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

Használjon ZIP64 formátum kiterjesztéseket, ha szükséges.

### Always {#Always}
```
public static final int Always
```

Mindig használjon ZIP64 formátum kiterjesztéseket.