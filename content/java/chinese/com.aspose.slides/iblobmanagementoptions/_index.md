---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API Reference
description: 二进制大对象（BLOB）是一种以单一实体存储的二进制数据——即 BLOB 可以是音频、视频或演示本身。
type: docs
url: /zh/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

二进制大对象（BLOB）是一种以单一实体存储的二进制数据——即 BLOB 可以是音频、视频或演示本身。 在处理 BLOB 时使用多种技术来优化内存消耗——无论是已经存储在演示中还是以后以编程方式添加的。 使用 [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) 可以更改与 [IPresentation](../../com.aspose.slides/ipresentation) 实例生命周期相关的 BLOB 处理的不同行为方面。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | This property defines if an instance of the Presentation class can be an owner of the source - file or stream during the instance lifetime. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | This property defines if temporary files can be created while working with BLOBs, what greatly decreases the memory consumption but requires permissions to create files. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | The root path where temporary files will be created. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | The root path where temporary files will be created. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

此属性定义 Presentation 类的实例在其生命周期内是否可以成为源（文件或流）的所有者。如果实例是所有者，它会锁定源。这有助于在处理 BLOB 时改善内存消耗和性能，但在 Presentation 实例的生命周期内，源（流或文件）无法更改。这是一个示例：

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException 将被抛出，因为 pres.pptx 在 Presentation 生命周期内被锁定
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // 在 Presentation 对象释放后，文件被解锁并可被删除
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
>  ```


**返回值:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

此属性定义 Presentation 类的实例在其生命周期内是否可以成为源（文件或流）的所有者。如果实例是所有者，它会锁定源。这有助于在处理 BLOB 时改善内存消耗和性能，但在 Presentation 实例的生命周期内，源（流或文件）无法更改。这是一个示例：

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException 将被抛出，因为 pres.pptx 在 Presentation 生命周期内被锁定
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // 在 Presentation 对象释放后，文件被解锁并且可以被删除
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
>  ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

此属性定义在处理 BLOB 时是否可以创建临时文件，这大大降低内存消耗，但需要创建文件的权限。

--------------------

在演示工作完成后，所有文件将被删除。

**返回值:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

此属性定义在处理 BLOB 时是否可以创建临时文件，这大大降低内存消耗，但需要创建文件的权限。

--------------------

在演示工作完成后，所有文件将被删除。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

临时文件将被创建的根路径。默认使用系统临时目录。托管进程应拥有在该位置创建文件和文件夹的权限。

**返回值:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

临时文件将被创建的根路径。默认使用系统临时目录。托管进程应拥有在该位置创建文件和文件夹的权限。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

此属性定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。默认情况下，所有 BLOB 都加载到内存中；只有在达到此限制后才会使用替代机制（如临时文件）。将 BLOB 保持在内存中可最大化性能，但可能导致内存使用率高。请使用此属性根据您的环境或需求定制行为。

--------------------

如果 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) 设置为 false，则此属性被忽略，因为此时内存是唯一可用的存储位置，限制内存中 BLOB 的使用没有效果。

--------------------

默认值为 629,145,600 字节（600 MB）。

--------------------

您可以将此属性设为零，但仍会保留少量最小内存。

**返回值:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

此属性定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。默认情况下，所有 BLOB 都加载到内存中；只有在达到此限制后才会使用替代机制（如临时文件）。将 BLOB 保持在内存中可最大化性能，但可能导致内存使用率高。请使用此属性根据您的环境或需求定制行为。

--------------------

如果 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) 设置为 false，则此属性被忽略，因为此时内存是唯一可用的存储位置，限制内存中 BLOB 的使用没有效果。

--------------------

默认值为 629,145,600 字节（600 MB）。

--------------------

您可以将此属性设为零，但仍会保留少量最小内存。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |