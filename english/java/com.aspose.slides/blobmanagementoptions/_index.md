---
title: BlobManagementOptions
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents options which can be used to manage BLOB handling rules and other BLOB settings.
type: docs
weight: 57
url: /java/com.aspose.slides/blobmanagementoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Represents options which can be used to manage BLOB handling rules and other BLOB settings.
## Constructors

| Constructor | Description |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Creates new default blob management options. |
## Methods

| Method | Description |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Represents the locking behavior for the presentation's source (stream or file). |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Represents the locking behavior for the presentation's source (stream or file). |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Set that using of temporary files is not allowed to optimize memory consumption while working with large amounts of data during presentation's lifetime. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Set that using of temporary files is not allowed to optimize memory consumption while working with large amounts of data during presentation's lifetime. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Represents the root path on the filesystem, where the temporary files will be stored. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Represents the root path on the filesystem, where the temporary files will be stored. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | A threshold that indicates the maximum amount of bytes which BLOBs can occupied in memory. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | A threshold that indicates the maximum amount of bytes which BLOBs can occupied in memory. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```


Creates new default blob management options.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```


Represents the locking behavior for the presentation's source (stream or file).

**Returns:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```


Represents the locking behavior for the presentation's source (stream or file).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```


Set that using of temporary files is not allowed to optimize memory consumption while working with large amounts of data during presentation's lifetime. If false, OutOfMemoryException can be thrown.

**Returns:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```


Set that using of temporary files is not allowed to optimize memory consumption while working with large amounts of data during presentation's lifetime. If false, OutOfMemoryException can be thrown.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```


Represents the root path on the filesystem, where the temporary files will be stored. System temorary directory will be used by default.

**Returns:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```


Represents the root path on the filesystem, where the temporary files will be stored. System temorary directory will be used by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```


A threshold that indicates the maximum amount of bytes which BLOBs can occupied in memory. After this threshold was reached, all new BLOBs will be placed in temporary files and will not affect the total memory consumption of the process. IsTemporaryFilesAllowed(\#isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean)) should be set to true to use this property.

**Returns:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```


A threshold that indicates the maximum amount of bytes which BLOBs can occupied in memory. After this threshold was reached, all new BLOBs will be placed in temporary files and will not affect the total memory consumption of the process. IsTemporaryFilesAllowed(\#isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean)) should be set to true to use this property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

