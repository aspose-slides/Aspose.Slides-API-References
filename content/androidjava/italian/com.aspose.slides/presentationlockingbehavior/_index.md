---
title: PresentationLockingBehavior
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta il comportamento relativo al trattamento del  file di origine o  java.io.InputStream durante il caricamento e l'utilizzo di un'istanza di .
type: docs
url: /it/com.aspose.slides/presentationlockingbehavior/
---
**Ereditarietà:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Rappresenta il comportamento relativo al trattamento della [IPresentation](../../com.aspose.slides/ipresentation) (file o java.io.InputStream) durante il caricamento e l'utilizzo di un'istanza di [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
>  ```


--------------------

La sorgente è il parametro passato al costruttore [IPresentation](../../com.aspose.slides/ipresentation). Nell'esempio seguente, la sorgente è il file "pres.pptx": per questo esempio, la sorgente (file "pres.pptx") sarà bloccata per tutta la durata di un'istanza [IPresentation](../../com.aspose.slides/ipresentation), cioè non potrà essere modificata o eliminata da altri processi.
## Campi

| Campo | Descrizione |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | La sorgente sarà bloccata solo per il tempo di esecuzione del costruttore [IPresentation](../../com.aspose.slides/ipresentation). |
| [KeepLocked](#KeepLocked) | La sorgente sarà bloccata per l'intera durata di un'istanza [IPresentation](../../com.aspose.slides/ipresentation), fino a quando non verrà eliminata. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```


La sorgente sarà bloccata solo per il tempo di esecuzione del costruttore [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

Se ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) è impostato a false, tutti i BLOB verranno caricati in memoria. In caso contrario, potrebbero essere utilizzati altri mezzi come file temporanei.

--------------------

Questo comportamento è più lento di [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) e, se è possibile trasferire la proprietà della sorgente a [IPresentation](../../com.aspose.slides/ipresentation), si consiglia di utilizzare [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```


La sorgente sarà bloccata per l'intera durata di un'istanza [IPresentation](../../com.aspose.slides/ipresentation), fino a quando non verrà eliminata.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) deve essere impostato a true per utilizzare questo comportamento, altrimenti verrà sollevata un'eccezione.

--------------------

Questo comportamento è consigliato, è più veloce e consuma meno memoria di [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).