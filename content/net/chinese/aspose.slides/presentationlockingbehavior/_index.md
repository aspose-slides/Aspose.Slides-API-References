---
title: PresentationLockingBehavior
second_title: Aspose.Sildes for .NET API Reference
description: 表示在加载和使用IPresentation../ipresentation实例时处理IPresentation../ipresentation源文件或流的行为。
type: docs
weight: 9360
url: /zh/aspose.slides/presentationlockingbehavior/
---

## PresentationLockingBehavior 枚举

表示在加载和使用[`IPresentation`](../ipresentation)实例时处理[`IPresentation`](../ipresentation)源（文件或流）的行为。

```csharp
public enum PresentationLockingBehavior
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| LoadAndRelease | `0` | 该源将在[`IPresentation`](../ipresentation)构造函数执行的时间内被锁定。如果[`IsTemporaryFilesAllowed`](../iblobmanagementoptions/istemporaryfilesallowed)设置为false，所有BLOB将被加载到内存中。否则，可能会使用其他方法，比如临时文件。该行为比KeepLocked慢，如果可以将源的所有权传递给[`IPresentation`](../ipresentation)，建议使用KeepLocked。 |
| KeepLocked | `1` | 该源将在[`IPresentation`](../ipresentation)实例的整个生命周期内被锁定，直到被释放。使用该行为必须将[`IsTemporaryFilesAllowed`](../iblobmanagementoptions/istemporaryfilesallowed)设置为true，否则将抛出异常。推荐使用该行为，因为它比LoadAndRelease更快且占用的内存更少。 |

### 备注

源是传递给[`IPresentation`](../ipresentation)构造函数的参数。在下面的示例中，源是"pres.pptx"文件：

```csharp
LoadOptions loadOptions = new LoadOptions { 
  BlobManagementOptions = { PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked } };
using (IPresentation pres = new Presentation("pres.pptx", loadOptions)) { }
```

对于这个示例，源（"pres.pptx"文件）将在[`IPresentation`](../ipresentation)实例的生命周期内被锁定，即不能被其他进程更改或删除。

### 另见

* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->