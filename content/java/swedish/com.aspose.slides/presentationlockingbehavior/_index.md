---
title: PresentationLockingBehavior
second_title: Aspose.Slides för Java API-referens
description: Representerar beteendet när man hanterar källfilen eller java.io.InputStream vid inläsning och arbete med en instans av.
type: docs
url: /sv/com.aspose.slides/presentationlockingbehavior/
---
**Arv:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Representerar beteendet när man hanterar [IPresentation](../../com.aspose.slides/ipresentation) källan (fil eller java.io.InputStream) under inläsning och arbete med en instans av [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

Källan är den parameter som skickas till [IPresentation](../../com.aspose.slides/ipresentation)-konstruktorn. I exemplet nedan är källan filen "pres.pptx": För detta exempel kommer källan ("pres.pptx" filen) att vara låst under en [IPresentation](../../com.aspose.slides/ipresentation)-instans livstid, dvs. den kan inte ändras eller tas bort av en annan process.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | Källan kommer att vara låst endast under en tid av [IPresentation](../../com.aspose.slides/ipresentation)-konstruktorns exekvering. |
| [KeepLocked](#KeepLocked) | Källan kommer att vara låst under hela livstiden för [IPresentation](../../com.aspose.slides/ipresentation)-instansen, tills den har frigjorts. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

Källan kommer att vara låst endast under en tid av [IPresentation](../../com.aspose.slides/ipresentation)-konstruktorns exekvering.

--------------------

Om ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) är satt till false kommer alla BLOB:er att laddas in i minnet. Annars kan andra metoder, såsom temporära filer, användas.

--------------------

Detta beteende är långsammare än [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked), och om det är möjligt att överföra äganderätten till källan till [IPresentation](../../com.aspose.slides/ipresentation), rekommenderas att använda [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked).

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Källan kommer att vara låst under hela livstiden för [IPresentation](../../com.aspose.slides/ipresentation)-instansen, tills den har frigjorts.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) måste sättas till true för att använda detta beteende, annars kommer ett undantag att kastas.

--------------------

Detta beteende rekommenderas, det är snabbare och använder mindre minne än [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).