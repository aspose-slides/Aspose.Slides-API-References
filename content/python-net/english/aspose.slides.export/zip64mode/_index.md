---
title: Zip64Mode enumeration
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/zip64mode/
---


## Zip64Mode enumeration

Specifies when to use ZIP64 format extensions for OpenXML file.

The Zip64Mode type exposes the following members:

## Fields

| Field | Description |
| :- | :- |
| NEVER | Do not use ZIP64 format extensions. |
| IF_NECESSARY | Use ZIP64 format extensions if necessary. |
| ALWAYS | Always use ZIP64 format extensions. |


### Remarks

OpenXML file is a ZIP-archive that has a 4 GB (2^32 bytes) limit on uncompressed size of a file, 
            compressed size of a file, and total size of the archive, as well as a limit of 65,535 (2^16-1) files in archive. 
            ZIP64 format extensions increase the limits to 2^64.


### See Also
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

