---
title: BlobManagementOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 表示可用于管理 BLOB 处理规则和其他 BLOB 设置的选项。
type: docs
url: /zh/com.aspose.slides/blobmanagementoptions/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)  
```
public class BlobManagementOptions implements IBlobManagementOptions
```

表示可用于管理 BLOB 处理规则和其他 BLOB 设置的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | 创建新的默认 Blob 管理选项。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | 此属性定义 Presentation 类的实例在其生命周期内是否可以成为源（文件或流）的拥有者。如果实例是拥有者，它会锁定源。这有助于在处理 BLOB 时降低内存消耗并提升性能，但在 Presentation 实例的生命周期内，源（流或文件）无法更改。 |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | 此属性定义 Presentation 类的实例在其生命周期内是否可以成为源（文件或流）的拥有者。如果实例是拥有者，它会锁定源。这有助于在处理 BLOB 时降低内存消耗并提升性能，但在 Presentation 实例的生命周期内，源（流或文件）无法更改。 |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | 此属性定义在处理 BLOB 时是否可以创建临时文件，这会大幅降低内存消耗，但需要文件创建权限。 |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | 此属性定义在处理 BLOB 时是否可以创建临时文件，这会大幅降低内存消耗，但需要文件创建权限。 |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | 临时文件将被创建的根路径。 |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | 临时文件将被创建的根路径。 |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | 定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。 |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | 定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。 |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

创建新的默认 Blob 管理选项。

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

此属性定义 Presentation 类的实例在其生命周期内是否可以成为源（文件或流）的拥有者。如果实例是拥有者，它会锁定源。这有助于在处理 BLOB 时降低内存消耗并提升性能，但在 Presentation 实例的生命周期内，源（流或文件）无法更改。

**返回值:**  
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

此属性定义 Presentation 类的实例在其生命周期内是否可以成为源（文件或流）的拥有者。如果实例是拥有者，它会锁定源。这有助于在处理 BLOB 时降低内存消耗并提升性能，但在 Presentation 实例的生命周期内，源（流或文件）无法更改。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

此属性定义在处理 BLOB 时是否可以创建临时文件，这会大幅降低内存消耗，但需要文件创建权限。

--------------------

在演示文稿工作完成后，所有文件将被删除。

**返回值:**  
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

此属性定义在处理 BLOB 时是否可以创建临时文件，这会大幅降低内存消耗，但需要文件创建权限。

--------------------

在演示文稿工作完成后，所有文件将被删除。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

临时文件将被创建的根路径。默认使用系统临时目录。托管进程应具备在该位置创建文件和文件夹的权限。

**返回值:**  
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

临时文件将被创建的根路径。默认使用系统临时目录。托管进程应具备在该位置创建文件和文件夹的权限。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。默认情况下，所有 BLOB 都会加载到内存中；仅当达到此限制时，才会采用其他机制（例如临时文件）。将 BLOB 保持在内存中可最大化性能，但可能导致较高的内存使用。使用此属性可根据您的环境或需求调整行为。

--------------------

如果 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) 设置为 false，则此属性会被忽略，因为此时内存是唯一可用的存储位置，限制内存中 BLOB 的使用没有效果。

--------------------

默认值为 629,145,600 字节（600 MB）。

--------------------

您可以将此属性设为零，但仍会保留少量最小内存。

**返回值:**  
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。默认情况下，所有 BLOB 都会加载到内存中；仅当达到此限制时，才会采用其他机制（例如临时文件）。将 BLOB 保持在内存中可最大化性能，但可能导致较高的内存使用。使用此属性可根据您的环境或需求调整行为。

--------------------

如果 \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) 设置为 false，则此属性会被忽略，因为此时内存是唯一可用的存储位置，限制内存中 BLOB 的使用没有效果。

--------------------

默认值为 629,145,600 字节（600 MB）。

--------------------

您可以将此属性设为零，但仍会保留少量最小内存。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |