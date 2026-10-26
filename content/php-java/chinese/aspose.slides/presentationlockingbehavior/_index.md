---
title: PresentationLockingBehavior
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior 类

 表示在加载和使用 IPresentation 实例时处理 IPresentation 源（文件或 
 java.io.InputStream）的行为。该源是传递给 IPresentation 构造函数的参数。在下面的示例中，源是 “pres.pptx” 文件：对于此示例，源（“pres.pptx” 文件）将在 IPPresentation 实例的整个生命周期内被锁定，即其他进程无法更改或删除它。 

## 常量

| 名称 | 值 | 描述 |
| --- | --- | --- |
[LoadAndRelease](#LoadAndRelease) | 0 | 源仅在 IPresentation 构造函数执行期间被锁定。如果 ( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) 设置为 false，则所有 BLOB 将被加载到内存中。否则，可能会使用临时文件等其他方式。此行为比 PresentationLockingBehavior#KeepLocked 更慢，如果可以将源的所有权传递给 IPresentation，建议使用 PresentationLockingBehavior#KeepLocked。 |
[KeepLocked](#KeepLocked) | 1 | 源将在 IPPresentation 实例的整个生命周期内被锁定，直至其被释放。使用此行为必须将 IBlobManagementOptions#isTemporaryFilesAllowed( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) 设置为 true，否则将抛出异常。此行为是推荐的，它比 PresentationLockingBehavior#LoadAndRelease 更快且占用更少的内存。 |


---


### LoadAndRelease {#LoadAndRelease}
源仅在 IPresentation 构造函数执行期间被锁定。如果 ( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) 设置为 false，则所有 BLOB 将被加载到内存中。否则，可能会使用临时文件等其他方式。此行为比 PresentationLockingBehavior#KeepLocked 更慢，如果可以将源的所有权传递给 IPresentation，建议使用 PresentationLockingBehavior#KeepLocked。

---

### KeepLocked {#KeepLocked}
源将在 IPPresentation 实例的整个生命周期内被锁定，直至其被释放。使用此行为必须将 IBlobManagementOptions#isTemporaryFilesAllowed( IBlobManagementOptions#isTemporaryFilesAllowed/ IBlobManagementOptions#setTemporaryFilesAllowed(boolean)) 设置为 true，否则将抛出异常。此行为是推荐的，它比 PresentationLockingBehavior#LoadAndRelease 更快且占用更少的内存。

---