---
title: BlobManagementOptions
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/blobmanagementoptions/
---

## BlobManagementOptions class

 Represents options which can be used to manage BLOB handling rules and other BLOB settings.
 
### BlobManagementOptions {#BlobManagementOptions}

| Name | Description |
| --- | --- |
| BlobManagementOptions() | Creates new default blob management options. |

 **Returns:**
BlobManagementOptions


---


### getMaxBlobsBytesInMemory {#getMaxBlobsBytesInMemory}

| Name | Description |
| --- | --- |
| getMaxBlobsBytesInMemory () | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. By default, all BLOBs are loaded into memory; only once this limit is reached are alternative mechanisms (such as temporary files) employed. Keeping BLOBs in memory maximizes performance but can lead to high memory usage. Use this property to tailor behavior to your environment or requirements. This property is ignored if #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean) is set to false, since memory is then the only storage location available and limiting in-memory BLOB usage has no effect. The default value is 629,145,600 bytes (600 MB). You may set this property to zero, but a small minimum amount of memory will still be reserved. |

 **Returns:**
long


---


### getPresentationLockingBehavior {#getPresentationLockingBehavior}

| Name | Description |
| --- | --- |
| getPresentationLockingBehavior () | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. If the instance is an owner, it locks the source. This helps to improve memory consumption and performance while working with BLOBs, but the source (stream or file) can't be changed during Presentation's instance lifetime. |

 **Returns:**
int


---


### getTempFilesRootPath {#getTempFilesRootPath}

| Name | Description |
| --- | --- |
| getTempFilesRootPath () | The root path where temporary files will be created. System temorary directory will be used by default. Hosting process should have permissions to create files and folders there. |

 **Returns:**
String


---


### isTemporaryFilesAllowed {#isTemporaryFilesAllowed}

| Name | Description |
| --- | --- |
| isTemporaryFilesAllowed () | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. All files will be deleted after work with the presentation will be finished. |

 **Returns:**
boolean


---


### setMaxBlobsBytesInMemory {#setMaxBlobsBytesInMemory}

| Name | Description |
| --- | --- |
| setMaxBlobsBytesInMemory (long) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. By default, all BLOBs are loaded into memory; only once this limit is reached are alternative mechanisms (such as temporary files) employed. Keeping BLOBs in memory maximizes performance but can lead to high memory usage. Use this property to tailor behavior to your environment or requirements. This property is ignored if #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean) is set to false, since memory is then the only storage location available and limiting in-memory BLOB usage has no effect. The default value is 629,145,600 bytes (600 MB). You may set this property to zero, but a small minimum amount of memory will still be reserved. |


---


### setPresentationLockingBehavior {#setPresentationLockingBehavior}

| Name | Description |
| --- | --- |
| setPresentationLockingBehavior (int) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. If the instance is an owner, it locks the source. This helps to improve memory consumption and performance while working with BLOBs, but the source (stream or file) can't be changed during Presentation's instance lifetime. |


---


### setTempFilesRootPath {#setTempFilesRootPath}

| Name | Description |
| --- | --- |
| setTempFilesRootPath (String) | The root path where temporary files will be created. System temorary directory will be used by default. Hosting process should have permissions to create files and folders there. |


---


### setTemporaryFilesAllowed {#setTemporaryFilesAllowed}

| Name | Description |
| --- | --- |
| setTemporaryFilesAllowed (boolean) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. All files will be deleted after work with the presentation will be finished. |


---


