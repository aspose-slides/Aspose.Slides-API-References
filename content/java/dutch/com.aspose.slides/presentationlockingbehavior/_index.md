---
title: PresentationLockingBehavior
second_title: Aspose.Slides voor Java API-referentie
description: Stelt het gedrag voor met betrekking tot het behandelen van het  bronbestand of  java.io.InputStream tijdens het laden en werken met een instantie van .
type: docs
url: /nl/com.aspose.slides/presentationlockingbehavior/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Geeft het gedrag weer met betrekking tot het behandelen van de [IPresentation](../../com.aspose.slides/ipresentation) bron (bestand of java.io.InputStream) tijdens het laden en werken met een instantie van [IPresentation](../../com.aspose.slides/ipresentation).

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```


--------------------

De bron is de parameter die wordt doorgegeven aan de [IPresentation](../../com.aspose.slides/ipresentation) constructor. In het onderstaande voorbeeld is de bron het bestand "pres.pptx": Voor dit voorbeeld wordt de bron (bestand "pres.pptx") vergrendeld voor de levensduur van een [IPresentation](../../com.aspose.slides/ipresentation) instantie, d.w.z. kan niet worden gewijzigd of verwijderd door een ander proces.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | De bron wordt alleen vergrendeld gedurende de uitvoering van de [IPresentation](../../com.aspose.slides/ipresentation) constructor. |
| [KeepLocked](#KeepLocked) | De bron wordt vergrendeld voor de volledige levensduur van een [IPresentation](../../com.aspose.slides/ipresentation) instantie, totdat deze wordt ontmanteld. |
### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

De bron wordt alleen vergrendeld gedurende de uitvoering van de [IPresentation](../../com.aspose.slides/ipresentation) constructor.

--------------------

Als ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) op false is ingesteld, worden alle BLOB's in het geheugen geladen. Anders kunnen andere middelen, zoals tijdelijke bestanden, worden gebruikt.

--------------------

Dit gedrag is langzamer dan [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked), en als het mogelijk is om het eigendom van de bron over te dragen aan [IPresentation](../../com.aspose.slides/ipresentation), wordt aanbevolen om [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) te gebruiken.

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

De bron wordt vergrendeld voor de volledige levensduur van een [IPresentation](../../com.aspose.slides/ipresentation) instantie, totdat deze wordt ontmanteld.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) moet op true worden gezet om dit gedrag te gebruiken, anders wordt er een uitzondering gegooid.

--------------------

Dit gedrag wordt aanbevolen, het is sneller en verbruikt minder geheugen dan [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).