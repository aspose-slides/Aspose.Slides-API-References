---
title: IBlobManagementOptions class
second_title: Aspose.Slides 用于 Python 的 .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions 类

二进制大型对象（BLOB）是一种以单一实体存储的二进制数据——即 BLOB 可以是音频、视频或演示本身。 使用多种技术来优化在处理 BLOB 时的内存消耗——这些 BLOB 可能已经存储在演示文稿中，或以后通过编程方式添加。 使用 [`IBlobManagementOptions`](/slides/python-net/zh/aspose.slides/iblobmanagementoptions) 可以更改与 BLOB 处理相关的不同行为方面，针对 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) 实例的生命周期。

IBlobManagementOptions 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/zh/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | 此属性定义在实例生命周期内，Presentation 类的实例是否可以成为源文件 <br/>            或流的拥有者。如果实例是拥有者，它会锁定源。这有助于 <br/>            在处理 BLOB 时提升内存使用和性能，但源（流或文件） <br/>            在 Presentation 实例的生命周期内不能被更改。这是一个示例： |
| [`is_temporary_files_allowed`](/slides/python-net/zh/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | 此属性定义在处理 BLOB 时是否可以创建临时文件，这会大幅 <br/>            减少内存消耗，但需要创建文件的权限。<br/>            所有文件将在演示文稿的工作完成后被删除。 |
| [`temp_files_root_path`](/slides/python-net/zh/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | 临时文件将被创建的根路径。默认使用系统临时目录。<br/>            托管进程应拥有在该位置 <br/>            创建文件和文件夹的权限。 |
| [`max_blobs_bytes_in_memory`](/slides/python-net/zh/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | 定义所有 BLOB 在内存中可能占用的最大总大小（以字节为单位）。默认情况下，所有 BLOB <br/>            都会加载到内存中；只有当达到此限制时，才会采用替代机制（例如临时 <br/>            文件）。将 BLOB 保留在内存中可最大化性能，但可能导致内存占用过高。使用 <br/>            此属性可根据您的环境或需求定制行为。 |


### 另请参阅
* 类 [`IBlobManagementOptions`](/slides/python-net/zh/aspose.slides/iblobmanagementoptions)
* 类 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)