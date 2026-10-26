---
title: Zip64Mode
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies when to use ZIP64 format extensions for OpenXML file.
type: docs
url: /com.aspose.slides/zip64mode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Specifies when to use ZIP64 format extensions for OpenXML file.

--------------------

OpenXML file is a ZIP-archive that has a 4 GB (2^32 bytes) limit on uncompressed size of a file, compressed size of a file, and total size of the archive, as well as a limit of 65,535 (2^16-1) files in archive. ZIP64 format extensions increase the limits to 2^64.
## Fields

| Field | Description |
| --- | --- |
| [Never](#Never) | Do not use ZIP64 format extensions. |
| [IfNecessary](#IfNecessary) | Use ZIP64 format extensions if necessary. |
| [Always](#Always) | Always use ZIP64 format extensions. |
### Never {#Never}
```
public static final int Never
```


Do not use ZIP64 format extensions.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```


Use ZIP64 format extensions if necessary.

### Always {#Always}
```
public static final int Always
```


Always use ZIP64 format extensions.

