---
title: PresentationLockingBehavior
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente le comportement concernant le traitement du  fichier source ou  java.io.InputStream lors du chargement et de l'utilisation d'une instance de .
type: docs
url: /fr/com.aspose.slides/presentationlockingbehavior/
---
**Héritage :**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Représente le comportement concernant le traitement de la source [IPresentation](../../com.aspose.slides/ipresentation) (fichier ou java.io.InputStream) lors du chargement et de l'utilisation d'une instance de [IPresentation](../../com.aspose.slides/ipresentation).

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

La source sera verrouillée pendant toute la durée de vie de l'instance [IPresentation](../../com.aspose.slides/ipresentation), jusqu'à ce qu'elle soit libérée.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) doit être réglé sur true pour utiliser ce comportement, sinon une exception sera levée.

--------------------

Ce comportement est recommandé, il est plus rapide et consomme moins de mémoire que [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).