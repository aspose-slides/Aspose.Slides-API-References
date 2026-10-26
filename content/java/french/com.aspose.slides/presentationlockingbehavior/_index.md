---
title: PresentationLockingBehavior
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente le comportement concernant le traitement du fichier source ou de java.io.InputStream lors du chargement et de l’utilisation d’une instance de .
type: docs
url: /fr/com.aspose.slides/presentationlockingbehavior/
---
**Héritage:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Représente le comportement concernant le traitement de la source [IPresentation](../../com.aspose.slides/ipresentation) (fichier ou java.io.InputStream) lors du chargement et de l’utilisation d’une instance de [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

La source est le paramètre passé au constructeur [IPresentation](../../com.aspose.slides/ipresentation). Dans l’exemple ci-dessous, la source est le fichier « pres.pptx » : pour cet exemple, la source (« pres.pptx ») sera verrouillée pendant toute la durée de vie d’une instance [IPresentation](../../com.aspose.slides/ipresentation), c’est-à-dire qu’elle ne pourra pas être modifiée ou supprimée par un autre processus.
## Champs

| Champ | Description |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | La source sera verrouillée uniquement pendant l’exécution du constructeur [IPresentation](../../com.aspose.slides/ipresentation). |
| [KeepLocked](#KeepLocked) | La source sera verrouillée pendant toute la durée de vie d’une instance [IPresentation](../../com.aspose.slides/ipresentation), jusqu’à ce qu’elle soit libérée. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```


La source sera verrouillée uniquement pendant l’exécution du constructeur [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

Si ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) est défini sur false, tous les BLOB seront chargés en mémoire. Sinon, d’autres moyens tels que des fichiers temporaires pourraient être utilisés.

--------------------

Ce comportement est plus lent que [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked), et s’il est possible de transférer la propriété de la source à [IPresentation](../../com.aspose.slides/ipresentation), il est recommandé d’utiliser [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```


La source sera verrouillée pendant toute la durée de vie d’une instance [IPresentation](../../com.aspose.slides/ipresentation), jusqu’à ce qu’elle soit libérée.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) doit être défini sur true pour utiliser ce comportement, sinon une exception sera levée.

--------------------

Ce comportement est recommandé, il est plus rapide et consomme moins de mémoire que [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).