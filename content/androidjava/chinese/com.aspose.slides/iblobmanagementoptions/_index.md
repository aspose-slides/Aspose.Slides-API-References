---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 二进制大对象（BLOB）是一种以单个实体存储的二进制数据——即
type: docs
url: /zh/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

二进制大对象（BLOB）是一种以单个实体存储的二进制数据——即 BLOB 可以是音频、视频或演示本身。

在处理 BLOB 时使用了多种技术来优化内存消耗——这些 BLOB 可以已经存储在演示文稿中，或之后通过编程方式添加。使用 [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)，您可以改变在 [IPresentation](../../com.aspose.slides/ipresentation) 实例生命周期期间对 BLOB 处理的各种行为方面。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | 此属性定义 Presentation 类的实例在其生命周期内是否可以作为源文件或流的拥有者。 |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | 此属性定义 Presentation 类的实例在其生命周期内是否可以作为源文件或流的拥有者。 |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | 此属性定义在处理 BLOB 时是否可以创建临时文件，这可大幅降低内存消耗，但需要创建文件的权限。 |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | 此属性定义在处理 BLOB 时是否可以创建临时文件，这可大幅降低内存消耗，但需要创建文件的权限。 |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | 临时文件将被创建的根路径。 |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | 临时文件将被创建的根路径。 |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | 定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。 |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | 定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。 |
### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

此属性定义 Presentation 类的实例在其生命周期内是否可以作为源文件或流的拥有者。如果实例是拥有者，它会锁定该源。这有助于在处理 BLOB 时改进内存消耗和性能，但在 Presentation 实例的生命周期内，源（流或文件）无法更改。这是一个示例：

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
>  // 在加载期间将抛出 IOException，因为 pres.pptx 在整个 Presentation 生命周期内被锁定
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // 在 Presentation 对象释放后，文件已解锁，可以被删除
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

Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. By default, all BLOBs are loaded into memory; only once this limit is reached are alternative mechanisms (such as temporary files) employed. Keeping BLOBs in memory maximizes performance but can lead to high memory usage. Use this property to tailor behavior to your environment or requirements.

--------------------

This property is ignored if \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) is set to false, since memory is then the only storage location available and limiting in-memory BLOB usage has no effect.

--------------------

The default value is 629,145,600 bytes (600 MB).

--------------------

You may set this property to zero, but a small minimum amount of memory will still be reserved.

**Returns:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)

定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。默认情况下，所有 BLOB 都会加载到内存中；仅在达到此限制后才会采用替代机制（例如临时文件）。将 BLOB 保持在内存中可最大化性能，但可能导致高内存使用。使用此属性可以根据您的环境或需求定制行为。

--------------------

如果将 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) 设置为 false，则此属性将被忽略，因为此时内存是唯一可用的存储位置，限制内存中 BLOB 的使用没有作用。

--------------------

默认值为 629,145,600 字节（600 MB）。

--------------------

您可以将此属性设置为零，但仍会保留少量的最小内存。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |