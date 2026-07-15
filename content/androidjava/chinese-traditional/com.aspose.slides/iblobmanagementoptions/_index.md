---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: 二进制大型对象 BLOB 是一种作为单一实体存储的二进制数据 - 即
type: docs
url: /zh-hant/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

二进制大型对象（BLOB）是一种作为单一实体存储的二进制数据 - 即 BLOB 可以是音频、视频或演示文稿本身。使用多种技术来优化使用 BLOB 时的内存消耗 - 无论是已存储在演示文稿中还是稍后通过程序添加的。使用 [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) 您可以更改与 [IPresentation](../../com.aspose.slides/ipresentation) 实例生命周期相关的 BLOB 处理行为方面。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | 此属性定义在实例生命周期内，Presentation 类的实例是否可以成为来源 - 文件或流的所有者。 |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | 此属性定义在实例生命周期内，Presentation 类的实例是否可以成为来源 - 文件或流的所有者。 |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | 此属性定义在使用 BLOB 时是否可以创建临时文件，这能显著降低内存消耗，但需要创建文件的权限。 |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | 此属性定义在使用 BLOB 时是否可以创建临时文件，这能显著降低内存消耗，但需要创建文件的权限。 |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | 临时文件将被创建的根路径。 |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | 临时文件将被创建的根路径。 |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | 定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。 |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | 定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。 |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

此属性定义在实例生命周期内，Presentation 类的实例是否可以成为来源 - 文件或流的所有者。如果实例是所有者，它会锁定来源。这有助于在使用 BLOB 时改善内存消耗和性能，但在 Presentation 实例生命周期内，来源（流或文件）无法更改。这是一个示例：

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException 將會被拋出，因為 pres.pptx 在 Presentation 的生命週期內被鎖定
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // 在 Presentation 物件釋放後，檔案將被解鎖並可被刪除
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**返回值:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

此属性定义在实例生命周期内，Presentation 类的实例是否可以成为来源 - 文件或流的所有者。如果实例是所有者，它会锁定来源。这有助于在使用 BLOB 时改善内存消耗和性能，但在 Presentation 实例生命周期内，来源（流或文件）无法更改。这是一个示例：

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // IOException 將會拋出，因為 pres.pptx 在 Presentation 的生命週期內被鎖定
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // 在 Presentation 物件釋放後，檔案將被解鎖並且可以刪除
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

此属性定义在使用 BLOB 时是否可以创建临时文件，这能显著降低内存消耗，但需要创建文件的权限。

--------------------

在演示文稿工作完成后，所有文件将被删除。

**返回值:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

此属性定义在使用 BLOB 时是否可以创建临时文件，这能显著降低内存消耗，但需要创建文件的权限。

--------------------

在演示文稿工作完成后，所有文件将被删除。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

临时文件将被创建的根路径。系统临时目录将作为默认使用。宿主进程应拥有在该位置创建文件和文件夹的权限。

**返回值:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

临时文件将被创建的根路径。系统临时目录将作为默认使用。宿主进程应拥有在该位置创建文件和文件夹的权限。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

此属性定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。默认情况下，所有 BLOB 都会被加载到内存中；仅当达到此限制时，才会采用替代机制（如临时文件）。将 BLOB 保持在内存中可最大化性能，但可能导致高内存使用。使用此属性可根据您的环境或需求调整行为。

--------------------

如果将 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) 设置为 false，则此属性将被忽略，因为此时内存是唯一可用的存储位置，限制内存中 BLOB 的使用无效。

--------------------

默认值为 629,145,600 字节（600 MB）。

--------------------

您可以将此属性设为零，但仍会保留少量的最小内存。

**返回值:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

此属性定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。默认情况下，所有 BLOB 都会被加载到内存中；仅当达到此限制时，才会采用替代机制（如临时文件）。将 BLOB 保持在内存中可最大化性能，但可能导致高内存使用。使用此属性可根据您的环境或需求调整行为。

--------------------

如果将 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) 设置为 false，则此属性将被忽略，因为此时内存是唯一可用的存储位置，限制内存中 BLOB 的使用无效。

--------------------

默认值为 629,145,600 字节（600 MB）。

--------------------

您可以将此属性设为零，但仍会保留少量的最小内存。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |