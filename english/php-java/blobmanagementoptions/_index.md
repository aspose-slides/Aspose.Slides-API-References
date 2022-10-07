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
| [getMaxBlobsBytesInMemory](getmaxblobsbytesinmemory)() | Defines the maximum amount (in bytes) that all BLOBs in total may occupy in memory. First, all BLOBs loading into memory as default behavior and only when it reaches the limit defined by this property, other mechanisms (such as temporary files) can be involved. In terms of performance, the most efficient way is storing BLOBs in memory, but from the other side, it leads to a high memory consumption what may be undesirable. Using this property, you may set the optimal behavior for your environment or other requirements. This property will be ignored if IsTemporaryFilesAllowed( #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean)) is set to false. It makes no sense to limit the maximum BLOBs in memory, because if IsTemporaryFilesAllowed( #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean)) is set to false, the memory is the only place where BLOBs can be stored. Default value is 629,145,600 bytes (600Mb). |
| [getPresentationLockingBehavior](getpresentationlockingbehavior)() | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. If the instance is an owner, it locks the source. This helps to improve memory consumption and performance while working with BLOBs, but the source (stream or file) can't be changed during Presentation's instance lifetime. |
| [getTempFilesRootPath](gettempfilesrootpath)() | The root path where temporary files will be created. System temorary directory will be used by default. Hosting process should have permissions to create files and folders there. |
| [isTemporaryFilesAllowed](istemporaryfilesallowed)() | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. All files will be deleted after work with the presentation will be finished. |
| [setMaxBlobsBytesInMemory](setmaxblobsbytesinmemory)(long) | Defines the maximum amount (in bytes) that all BLOBs in total may occupy in memory. First, all BLOBs loading into memory as default behavior and only when it reaches the limit defined by this property, other mechanisms (such as temporary files) can be involved. In terms of performance, the most efficient way is storing BLOBs in memory, but from the other side, it leads to a high memory consumption what may be undesirable. Using this property, you may set the optimal behavior for your environment or other requirements. This property will be ignored if IsTemporaryFilesAllowed( #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean)) is set to false. It makes no sense to limit the maximum BLOBs in memory, because if IsTemporaryFilesAllowed( #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean)) is set to false, the memory is the only place where BLOBs can be stored. Default value is 629,145,600 bytes (600Mb). |
| [setPresentationLockingBehavior](setpresentationlockingbehavior)(int) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. If the instance is an owner, it locks the source. This helps to improve memory consumption and performance while working with BLOBs, but the source (stream or file) can't be changed during Presentation's instance lifetime. |
| [setTempFilesRootPath](settempfilesrootpath)(String) | The root path where temporary files will be created. System temorary directory will be used by default. Hosting process should have permissions to create files and folders there. |
| [setTemporaryFilesAllowed](settemporaryfilesallowed)(boolean) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. All files will be deleted after work with the presentation will be finished. |
