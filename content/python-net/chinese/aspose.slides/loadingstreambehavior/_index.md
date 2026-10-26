---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior 枚举

The **io.RawIOBase** passed to a method is considered as a Binary Large Object (BLOB) (see 
            [`IBlobManagementOptions`](/slides/python-net/zh/aspose.slides/iblobmanagementoptions) description). Values of this enumeration identify how 
            the **io.RawIOBase** should be treated when it passed to the method. Depending on the 
            requirements, different decisions could be made to provide the most efficient behavior.

The LoadingStreamBehavior type exposes the following members:

## 字段

| 字段 | 描述 |
| :- | :- |
| READ_STREAM_AND_RELEASE | 流将在读取到末尾后被释放——即保证此流 <br/>            在未来不会被 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) 实例使用。它可以由客户端代码 <br/>            关闭或以其他任何方式使用。 |
| KEEP_LOCKED | 流将在 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) 对象内部被锁定，即所有权 <br/>            的流将被转移。[`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation) 对象将负责在该对象自身被释放时 <br/>            正确释放流。<br/>            当您需要序列化大型 BLOB 文件（例如大型 <br/>            视频或音频——参见 [`IBlobManagementOptions`](/slides/python-net/zh/aspose.slides/iblobmanagementoptions) 描述）并希望防止将此文件加载到内存或其他性能问题时，此行为极其有用。您可以仅打开 **System.IO.FileStream** <br/>            并将其传递给方法，选择 [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/zh/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior。 |

### 另请参见
* 类 [`IBlobManagementOptions`](/slides/python-net/zh/aspose.slides/iblobmanagementoptions)
* 类 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)