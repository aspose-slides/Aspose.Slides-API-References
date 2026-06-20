---
title: Zip64Mode
second_title: Aspose.Slides for C++ API Reference
description: Specifies when to use ZIP64 format extensions for OpenXML file.
type: docs
weight: 1119
url: /aspose.slides.export/zip64mode/
---
## Zip64Mode enum


Specifies when to use ZIP64 format extensions for OpenXML file.

```cpp
enum class Zip64Mode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Never | 0 | Do not use ZIP64 format extensions. |
| IfNecessary | 1 | Use ZIP64 format extensions if necessary. |
| Always | 2 | Always use ZIP64 format extensions. |

## Remarks


OpenXML file is a ZIP-archive that has a 4 GB (2^32 bytes) limit on uncompressed size of a file, compressed size of a file, and total size of the archive, as well as a limit of 65,535 (2^16-1) files in archive. ZIP64 format extensions increase the limits to 2^64. 
## See Also

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)