---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: A Binary Large Object BLOB is a binary data stored as a single entity - i.e.
type: docs
weight: 670
url: /androidjava/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself. A number of techniques are used to optimize memory consumption while working with BLOBs - which was already stored in the presentation or be added later programmatically. Using [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) you can change a different behavior aspects regarding BLOBs handling for the [IPresentation](../../com.aspose.slides/ipresentation) instance lifetime.
## Methods

| Method | Description |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | The root path where temporary files will be created. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | The root path where temporary files will be created. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Defines the maximum amount (in bytes) that all BLOBs in total may occupy in memory. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Defines the maximum amount (in bytes) that all BLOBs in total may occupy in memory. |
### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```


This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. If the instance is an owner, it locks the source. This helps to improve memory consumption and performance while working with BLOBs, but the source (stream or file) can't be changed during Presentation's instance lifetime. This is an example:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException will be thrown because pres.pptx is locked for a Presentation lifetime
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // after Presentation object disposed, file is unlocked and can be deleted
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Returns:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```


This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. If the instance is an owner, it locks the source. This helps to improve memory consumption and performance while working with BLOBs, but the source (stream or file) can't be changed during Presentation's instance lifetime. This is an example:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException will be thrown because pres.pptx is locked for a Presentation lifetime
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // after Presentation object disposed, file is unlocked and can be deleted
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```


This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files.

--------------------

All files will be deleted after work with the presentation will be finished.

**Returns:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```


This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files.

--------------------

All files will be deleted after work with the presentation will be finished.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```


The root path where temporary files will be created. System temorary directory will be used by default. Hosting process should have permissions to create files and folders there.

**Returns:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```


The root path where temporary files will be created. System temorary directory will be used by default. Hosting process should have permissions to create files and folders there.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```


Defines the maximum amount (in bytes) that all BLOBs in total may occupy in memory. First, all BLOBs loading into memory as default behavior and only when it reaches the limit defined by this property, other mechanisms (such as temporary files) can be involved. In terms of performance, the most efficient way is storing BLOBs in memory, but from the other side, it leads to a high memory consumption what may be undesirable. Using this property, you may set the optimal behavior for your environment or other requirements.

--------------------

This property will be ignored if (\#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean)) is set to false. It makes no sense to limit the maximum BLOBs in memory, because if IsTemporaryFilesAllowed(\#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean)) is set to false, the memory is the only place where BLOBs can be stored.

--------------------

Default value is 629,145,600 bytes (600Mb).

**Returns:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```


Defines the maximum amount (in bytes) that all BLOBs in total may occupy in memory. First, all BLOBs loading into memory as default behavior and only when it reaches the limit defined by this property, other mechanisms (such as temporary files) can be involved. In terms of performance, the most efficient way is storing BLOBs in memory, but from the other side, it leads to a high memory consumption what may be undesirable. Using this property, you may set the optimal behavior for your environment or other requirements.

--------------------

This property will be ignored if (\#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean)) is set to false. It makes no sense to limit the maximum BLOBs in memory, because if IsTemporaryFilesAllowed(\#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean)) is set to false, the memory is the only place where BLOBs can be stored.

--------------------

Default value is 629,145,600 bytes (600Mb).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

