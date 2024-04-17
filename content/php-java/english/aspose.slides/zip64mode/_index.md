---
title: Zip64Mode
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/zip64mode/
---

## Zip64Mode class

 Specifies when to use ZIP64 format extensions for OpenXML file.
 
 OpenXML file is a ZIP-archive that has a 4 GB (2^32 bytes) limit on uncompressed size of a file, 
 compressed size of a file, and total size of the archive, as well as a limit of 65,535 (2^16-1) files in archive. 
 ZIP64 format extensions increase the limits to 2^64.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
[Never](#Never) | 0 | Do not use ZIP64 format extensions. |
[IfNecessary](#IfNecessary) | 1 | Use ZIP64 format extensions if necessary. |
[Always](#Always) | 2 | Always use ZIP64 format extensions. |


---


### Never {#Never}
Do not use ZIP64 format extensions.

---

### IfNecessary {#IfNecessary}
Use ZIP64 format extensions if necessary.

---

### Always {#Always}
Always use ZIP64 format extensions.

---


