---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior 枚举

表示在加载并使用 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) 实例时处理 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) 源（文件或 **io.RawIOBase**）的行为。

PresentationLockingBehavior 类型公开以下成员：

## 字段

| 字段 | 描述 |
| :- | :- |
| LOAD_AND_RELEASE | 在 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) 构造函数执行期间，源仅会被锁定。<br/>如果 [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/zh/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) 设置为 false，所有 BLOB 将被加载到内存中。<br/>否则，可能会使用其他方式，例如临时文件。此行为比 [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/zh/aspose.slides/presentationlockingbehavior/KEEP_LOCKED) 更慢，并且如果可以将源的 <br/>所有权传递给 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)，建议使用 [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/zh/aspose.slides/presentationlockingbehavior/KEEP_LOCKED)。 |
| KEEP_LOCKED | 源将在 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) 实例的整个生命周期内被锁定，直至其 <br/>被释放。<br/>[`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/zh/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) 必须设置为 true 才能使用 <br/>此行为，否则将抛出异常。推荐使用此行为，它比 [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/zh/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE) 更快且消耗的内存更少。 |

### 备注

源是传递给 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) 构造函数的参数。在下面的示例中，源是 "pres.pptx" 文件：

对于此示例，源（"pres.pptx" 文件）将在 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) 实例的生命周期内被锁定，即其他进程无法更改或删除它。

### 另请参阅
* 类 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)