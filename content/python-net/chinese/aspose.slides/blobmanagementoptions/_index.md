---
title: BlobManagementOptions class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions 类

Represents options which can be used to manage BLOB handling rules and other BLOB settings.

The BlobManagementOptions type exposes the following members:

## 构造函数

| 构造函数 | 描述 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh/aspose.slides/blobmanagementoptions/__init__/#) | 创建新的默认 blob 管理选项。 |

## 属性

| 属性 | 描述 |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/zh/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | 此属性定义 Presentation 类的实例在其生命周期内是否可以成为源文件 <br/>            或流的所有者。若实例是所有者，则会锁定源。这有助于在使用 BLOB 时提升内存消耗和性能，但在 Presentation 实例的生命周期内，源（流或文件）无法更改。 |
| [`is_temporary_files_allowed`](/slides/python-net/zh/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | 此属性定义在使用 BLOB 时是否可以创建临时文件，这会大幅降低内存消耗，但需要创建文件的权限。<br/>            所有文件将在演示文稿工作完成后被删除。 |
| [`temp_files_root_path`](/slides/python-net/zh/aspose.slides/blobmanagementoptions/temp_files_root_path/) | 将创建临时文件的根路径。默认使用系统临时目录。<br/>            托管进程应具备在此处创建文件和文件夹的权限。 |
| [`max_blobs_bytes_in_memory`](/slides/python-net/zh/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | 定义所有 BLOB 在内存中可能占用的最大总大小（字节）。默认情况下，所有 BLOB<br/>            都加载到内存中；仅当达到此上限时才会使用替代机制（例如临时文件）。将 BLOB 保持在内存中可最大化性能，但可能导致高内存使用。使用<br/>            此属性可根据您的环境或需求定制行为。 |


### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)