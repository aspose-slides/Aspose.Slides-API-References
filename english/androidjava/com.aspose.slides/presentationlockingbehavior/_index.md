---
title: PresentationLockingBehavior
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the behavior regarding treating the  source file or  java.io.InputStream while loading and working with an instance of .
type: docs
weight: 449
url: /androidjava/com.aspose.slides/presentationlockingbehavior/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Represents the behavior regarding treating the [IPresentation](../../com.aspose.slides/ipresentation) source (file or java.io.InputStream) while loading and working with an instance of [IPresentation](../../com.aspose.slides/ipresentation).

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

If ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) is set to false, all BLOBs will be loaded into memory. Otherwise, other means such a temporary files might be used.

--------------------

This behavior is slower than [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked), and if it is possible to pass the ownership of the source to [IPresentation](../../com.aspose.slides/ipresentation), it is recommended to use [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```


The source will be locked for a whole lifetime of [IPresentation](../../com.aspose.slides/ipresentation) instance, until it will be disposed.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) is must be set to true for using this behavior, otherwise exception will be thrown.

--------------------

This behavior is recommended, it is faster and consumes less memory than [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).

