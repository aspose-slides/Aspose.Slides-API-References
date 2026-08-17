---
title: PresentationLockingBehavior
second_title: Aspose.Slides 的 Java API 参考
description: 表示在加载和使用 实例时，处理源文件或 java.io.InputStream 的行为。
type: docs
url: /zh/com.aspose.slides/presentationlockingbehavior/
---
**继承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

表示在加载和使用 [IPresentation](../../com.aspose.slides/ipresentation) 实例时对 [IPresentation](../../com.aspose.slides/ipresentation) 源（文件或 java.io.InputStream）的处理行为。

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

源是传递给 [IPresentation](../../com.aspose.slides/ipresentation) 构造函数的参数。在下面的示例中，源是 "pres.pptx" 文件：对于此示例，源（"pres.pptx" 文件）将在 [IPresentation](../../com.aspose.slides/ipresentation) 实例的整个生命周期内被锁定，即其他进程无法更改或删除它。
## Fields

| 字段 | 描述 |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | 源仅在 [IPresentation](../../com.aspose.slides/ipresentation) 构造函数执行期间被锁定。 |
| [KeepLocked](#KeepLocked) | 源将在 [IPresentation](../../com.aspose.slides/ipresentation) 实例的整个生命周期内被锁定，直到该实例被释放。 |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

源仅在 [IPresentation](../../com.aspose.slides/ipresentation) 构造函数执行期间被锁定。

--------------------

如果 ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) 被设置为 false，则所有 BLOB 将被加载到内存中。否则，可能会使用临时文件等其他方式。

--------------------

此行为比 [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) 更慢，并且如果可以将源的所有权传递给 [IPresentation](../../com.aspose.slides/ipresentation)，建议使用 [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked)。

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

源将在 [IPresentation](../../com.aspose.slides/ipresentation) 实例的整个生命周期内被锁定，直到该实例被释放。

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) 必须设置为 true 才能使用此行为，否则将抛出异常。

--------------------

推荐使用此行为，它比 [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease) 更快并且消耗的内存更少。