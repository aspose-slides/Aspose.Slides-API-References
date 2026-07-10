---
title: PresentationLockingBehavior
second_title: Aspose.Slides for Android via Java API 参考
description: 表示在加载和使用实例时，处理源文件或 java.io.InputStream 的行为。
type: docs
url: /zh/com.aspose.slides/presentationlockingbehavior/
---
**继承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

表示在加载和使用 [IPresentation](../../com.aspose.slides/ipresentation) 实例时，处理 [IPresentation](../../com.aspose.slides/ipresentation) 源（文件或 java.io.InputStream）的行为。

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

The source is the parameter passed to the [IPresentation](../../com.aspose.slides/ipresentation) constructor. In the example below, the source is the "pres.pptx" file: For this example, the source ("pres.pptx" file) will be locked for a [IPresentation](../../com.aspose.slides/ipresentation) instance lifetime, i.e. can't be changed or deleted by the other process.
## Fields

| Field | Description |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | The source will be locked only for a time of [IPresentation](../../com.aspose.slides/ipresentation) constructor execution. |
| [KeepLocked](#KeepLocked) | The source will be locked for a whole lifetime of [IPresentation](../../com.aspose.slides/ipresentation) instance, until it will be disposed. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

The source will be locked only for a time of [IPresentation](../../com.aspose.slides/ipresentation) constructor execution.

--------------------

If ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions#setTemporaryFilesAllowed-boolean-)) is set to false, all BLOBs will be loaded into memory. Otherwise, other means such a temporary files might be used.

--------------------

This behavior is slower than [KeepLocked](../../com.aspose.slides/presentationlockingbehavior#KeepLocked), and if it is possible to pass the ownership of the source to [IPresentation](../../com.aspose.slides/ipresentation), it is recommended to use [KeepLocked](../../com.aspose.slides/presentationlockingbehavior#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked

[IPresentation](../../com.aspose.slides/ipresentation) 实例的整个生命周期内，源将被锁定，直到该实例被释放。

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) 必须设置为 true 才能使用此行为，否则会抛出 `exception`。

--------------------

推荐使用此行为，它比 [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease) 更快且占用的内存更少。