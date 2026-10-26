---
title: BlobManagementOptions
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions 类

 Represents options which can be used to manage BLOB handling rules and other BLOB settings.
 
### BlobManagementOptions {#BlobManagementOptions}

| 名称 | 描述 |
| --- | --- |
| BlobManagementOptions() | 创建新的默认 BLOB 管理选项。 |

 **返回值:** BlobManagementOptions


---


### getMaxBlobsBytesInMemory {#getMaxBlobsBytesInMemory}

| 名称 | 描述 |
| --- | --- |
| getMaxBlobsBytesInMemory () | 定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。默认情况下，所有 BLOB 都会被加载到内存中；只有在达到此限制后才会采用替代机制（例如临时文件）。将 BLOB 保存在内存中可最大化性能，但可能导致内存使用量高。使用此属性可根据您的环境或需求定制行为。如果将 #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean) 设置为 false，则此属性将被忽略，因为此时内存是唯一可用的存储位置，限制内存中 BLOB 的使用没有效果。默认值为 629,145,600 字节（600 MB）。您可以将此属性设置为零，但仍会保留少量最小内存。 |

 **返回值:** long


---


### getPresentationLockingBehavior {#getPresentationLockingBehavior}

| 名称 | 描述 |
| --- | --- |
| getPresentationLockingBehavior () | 此属性定义 Presentation 类的实例在其生命周期内是否可以成为源（文件或流）的拥有者。如果实例是拥有者，则会锁定源。这有助于在使用 BLOB 时提升内存使用和性能，但在 Presentation 实例的生命周期内，源（流或文件）不能被更改。 |

 **返回值:** int


---


### getTempFilesRootPath {#getTempFilesRootPath}

| 名称 | 描述 |
| --- | --- |
| getTempFilesRootPath () | 临时文件将被创建的根路径。默认使用系统临时目录。托管进程应具有在该位置创建文件和文件夹的权限。 |

 **返回值:** String


---


### isTemporaryFilesAllowed {#isTemporaryFilesAllowed}

| 名称 | 描述 |
| --- | --- |
| isTemporaryFilesAllowed () | 此属性定义在使用 BLOB 时是否可以创建临时文件，这可以大幅降低内存消耗，但需要创建文件的权限。所有文件将在演示文稿工作完成后被删除。 |

 **返回值:** boolean


---


### setMaxBlobsBytesInMemory {#setMaxBlobsBytesInMemory}

| 名称 | 描述 |
| --- | --- |
| setMaxBlobsBytesInMemory (long) | 定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。默认情况下，所有 BLOB 都会被加载到内存中；只有在达到此限制后才会采用替代机制（例如临时文件）。将 BLOB 保存在内存中可最大化性能，但可能导致内存使用量高。使用此属性可根据您的环境或需求定制行为。如果将 #isTemporaryFilesAllowed/ #setTemporaryFilesAllowed(boolean) 设置为 false，则此属性将被忽略，因为此时内存是唯一可用的存储位置，限制内存中 BLOB 的使用没有效果。默认值为 629,145,600 字节（600 MB）。您可以将此属性设置为零，但仍会保留少量最小内存。 |

 **返回值:** void


---


### setPresentationLockingBehavior {#setPresentationLockingBehavior}

| 名称 | 描述 |
| --- | --- |
| setPresentationLockingBehavior (int) | 此属性定义 Presentation 类的实例在其生命周期内是否可以成为源（文件或流）的拥有者。如果实例是拥有者，则会锁定源。这有助于在使用 BLOB 时提升内存使用和性能，但在 Presentation 实例的生命周期内，源（流或文件）不能被更改。 |

 **返回值:** void


---


### setTempFilesRootPath {#setTempFilesRootPath}

| 名称 | 描述 |
| --- | --- |
| setTempFilesRootPath (String) | 临时文件将被创建的根路径。默认使用系统临时目录。托管进程应具有在该位置创建文件和文件夹的权限。 |

 **返回值:** void


---


### setTemporaryFilesAllowed {#setTemporaryFilesAllowed}

| 名称 | 描述 |
| --- | --- |
| setTemporaryFilesAllowed (boolean) | 此属性定义在使用 BLOB 时是否可以创建临时文件，这可以大幅降低内存消耗，但需要创建文件的权限。所有文件将在演示文稿工作完成后被删除。 |

 **返回值:** void


---