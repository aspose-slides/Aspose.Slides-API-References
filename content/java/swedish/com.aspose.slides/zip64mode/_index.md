---
title: Zip64Mode
second_title: Aspose.Slides för Java API-referens
description: Specificerar när ZIP64-formatutökningar ska användas för OpenXML-fil.
type: docs
url: /sv/com.aspose.slides/zip64mode/
---
**Arv:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Anger när ZIP64-formatutökningar ska användas för OpenXML-fil.

--------------------

En OpenXML-fil är ett ZIP-arkiv som har en gräns på 4 GB (2^32 byte) för okomprimerad storlek på en fil, komprimerad storlek på en fil och total storlek på arkivet, samt en gräns på 65 535 (2^16-1) filer i arkivet. ZIP64-formatutökningar ökar gränserna till 2^64.
## Fält

| Field | Description |
| --- | --- |
| [Never](#Never) | Använd inte ZIP64-formatutökningar. |
| [IfNecessary](#IfNecessary) | Använd ZIP64-formatutökningar om det behövs. |
| [Always](#Always) | Använd alltid ZIP64-formatutökningar. |
### Never {#Never}
```
public static final int Never
```


Använd inte ZIP64-formatutökningar.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```


Använd ZIP64-formatutökningar om det behövs.

### Always {#Always}
```
public static final int Always
```


Alltid använd ZIP64-formatutökningar.