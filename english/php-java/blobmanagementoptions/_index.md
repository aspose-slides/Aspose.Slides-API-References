---
title: BlobManagementOptions
type: docs
weight: 0
url: /php-java/blobmanagementoptions/
---

# BlobManagementOptions class

 Represents options which can be used to manage BLOB handling rules and other BLOB settings.
 

## Constructors

| name | description |
| --- | --- |
| [BlobManagementOptions](/php-java/blobmanagementoptions/blobmanagementoptions/)() | Creates new default blob management options. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getMaxBlobsBytesInMemory](/php-java/blobmanagementoptions/getmaxblobsbytesinmemory/)() | long | A threshold that indicates the maximum amount of bytes which BLOBs can occupied in memory. After this threshold was reached, all new BLOBs will be placed in temporary files and will not affect the total memory consumption of the process. IsTemporaryFilesAllowed( #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean)) should be set to true to use this property. |
| [getPresentationLockingBehavior](/php-java/blobmanagementoptions/getpresentationlockingbehavior/)() | int | Represents the locking behavior for the presentation's source (stream or file). |
| [getTempFilesRootPath](/php-java/blobmanagementoptions/gettempfilesrootpath/)() | String | Represents the root path on the filesystem, where the temporary files will be stored. System temorary directory will be used by default. |
| [isTemporaryFilesAllowed](/php-java/blobmanagementoptions/istemporaryfilesallowed/)() | boolean | Set that using of temporary files is not allowed to optimize memory consumption while working with large amounts of data during presentation's lifetime. If false, OutOfMemoryException can be thrown. |
| [setMaxBlobsBytesInMemory](/php-java/blobmanagementoptions/setmaxblobsbytesinmemory/)(long) | void | A threshold that indicates the maximum amount of bytes which BLOBs can occupied in memory. After this threshold was reached, all new BLOBs will be placed in temporary files and will not affect the total memory consumption of the process. IsTemporaryFilesAllowed( #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean)) should be set to true to use this property. |
| [setPresentationLockingBehavior](/php-java/blobmanagementoptions/setpresentationlockingbehavior/)(int) | void | Represents the locking behavior for the presentation's source (stream or file). |
| [setTempFilesRootPath](/php-java/blobmanagementoptions/settempfilesrootpath/)(String) | void | Represents the root path on the filesystem, where the temporary files will be stored. System temorary directory will be used by default. |
| [setTemporaryFilesAllowed](/php-java/blobmanagementoptions/settemporaryfilesallowed/)(boolean) | void | Set that using of temporary files is not allowed to optimize memory consumption while working with large amounts of data during presentation's lifetime. If false, OutOfMemoryException can be thrown. |
