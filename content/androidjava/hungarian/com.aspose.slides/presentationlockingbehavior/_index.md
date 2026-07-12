---
title: PresentationLockingBehavior
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Representálja azt a viselkedést, amely a forrásfájlt vagy a java.io.InputStream-et kezeli egy példány betöltése és használata közben.
type: docs
url: /hu/com.aspose.slides/presentationlockingbehavior/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

A viselkedést írja le a [IPresentation](../../com.aspose.slides/ipresentation) forrás (fájl vagy java.io.InputStream) kezelésekor egy [IPresentation](../../com.aspose.slides/ipresentation) példány betöltése és használata közben.

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
>  ```


--------------------

A forrás a [IPresentation](../../com.aspose.slides/ipresentation) konstruktorba átadott paraméter. Az alábbi példában a forrás a "pres.pptx" fájl: Ebben a példában a forrás ("pres.pptx" fájl) a [IPresentation](../../com.aspose.slides/ipresentation) példány élettartama alatt zárolva lesz, azaz a másik folyamat nem módosíthatja vagy törölheti.

## Mezők

| Mező | Leírás |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | A forrás csak a [IPresentation](../../com.aspose.slides/ipresentation) konstruktor végrehajtásának ideje alatt lesz zárolva. |
| [KeepLocked](#KeepLocked) | A forrás a [IPresentation](../../com.aspose.slides/ipresentation) példány teljes életciklusa során lesz zárolva, amíg az nem lesz eldobva. |

### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

A forrás csak a [IPresentation](../../com.aspose.slides/ipresentation) konstruktor végrehajtásának ideje alatt lesz zárolva.

--------------------

Ha ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) false értékre van állítva, akkor az összes BLOB memóriába lesz betöltve. Ellenkező esetben más módok, például ideiglenes fájlok is használhatók.

--------------------

Ez a viselkedés lassabb, mint a [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked), és ha lehetséges a forrás tulajdonjogát átadni a [IPresentation](../../com.aspose.slides/ipresentation)-nak, akkor ajánlott a [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) használata.

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

A forrás a [IPresentation](../../com.aspose.slides/ipresentation) példány teljes életciklusa során lesz zárolva, amíg az nem lesz eldobva.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) értékét true-ra kell állítani ezen viselkedés használatához, különben kivétel keletkezik.

--------------------

Ez a viselkedés ajánlott, gyorsabb és kevesebb memóriát fogyaszt, mint a [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).