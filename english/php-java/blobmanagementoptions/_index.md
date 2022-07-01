---
title: BlobManagementOptions
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/blobmanagementoptions/
---

## BlobManagementOptions class

 Represents options which can be used to manage BLOB handling rules and other BLOB settings.
 

## Constructors

| Name | Description |
| --- | --- |
| [BlobManagementOptions](blobmanagementoptions)() | Creates new default blob management options. |

## Methods

| Name | Description |
| --- | --- |
| [getMaxBlobsBytesInMemory](getmaxblobsbytesinmemory)() | A threshold that indicates the maximum amount of bytes which BLOBs can occupied in memory. After this threshold was reached, all new BLOBs will be placed in temporary files and will not affect the total memory consumption of the process. IsTemporaryFilesAllowed( #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean)) should be set to true to use this property. |
| [getPresentationLockingBehavior](getpresentationlockingbehavior)() | Represents the locking behavior for the presentation's source (stream or file). |
| [getTempFilesRootPath](gettempfilesrootpath)() | Represents the root path on the filesystem, where the temporary files will be stored. System temorary directory will be used by default. |
| [isTemporaryFilesAllowed](istemporaryfilesallowed)() | Set that using of temporary files is not allowed to optimize memory consumption while working with large amounts of data during presentation's lifetime. If false, OutOfMemoryException can be thrown. |
| [setMaxBlobsBytesInMemory](setmaxblobsbytesinmemory)(long) | A threshold that indicates the maximum amount of bytes which BLOBs can occupied in memory. After this threshold was reached, all new BLOBs will be placed in temporary files and will not affect the total memory consumption of the process. IsTemporaryFilesAllowed( #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean)) should be set to true to use this property. |
| [setPresentationLockingBehavior](setpresentationlockingbehavior)(int) | Represents the locking behavior for the presentation's source (stream or file). |
| [setTempFilesRootPath](settempfilesrootpath)(String) | Represents the root path on the filesystem, where the temporary files will be stored. System temorary directory will be used by default. |
| [setTemporaryFilesAllowed](settemporaryfilesallowed)(boolean) | Set that using of temporary files is not allowed to optimize memory consumption while working with large amounts of data during presentation's lifetime. If false, OutOfMemoryException can be thrown. |
