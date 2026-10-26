---
title: PresentationLockingBehavior
second_title: Aspose.Slides for Java API referenciája
description: Ábrázolja a viselkedést a forrásfájl vagy a java.io.InputStream kezelése során, amikor betöltünk és dolgozunk egy példányon.
type: docs
url: /hu/com.aspose.slides/presentationlockingbehavior/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PresentationLockingBehavior extends System.Enum
```

Ábrázolja a [IPresentation](../../com.aspose.slides/ipresentation) forrás (fájl vagy java.io.InputStream) kezelésével kapcsolatos viselkedést, amikor betöltünk és dolgozunk egy [IPresentation](../../com.aspose.slides/ipresentation) példánnyal.

--------------------

> ```
> BlobManagementOptions blobOptions = new BlobManagementOptions();
>  blobOptions.setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setBlobManagementOptions(blobOptions);
>  IPresentation pres = new Presentation("pres.pptx", loadOptions);
> ```

--------------------

A forrás a [IPresentation](../../com.aspose.slides/ipresentation) konstruktorba átadott paraméter. Az alábbi példában a forrás a "pres.pptx" fájl: Ebben a példában a forrás ("pres.pptx" fájl) egy [IPresentation](../../com.aspose.slides/ipresentation) példány élettartama alatt lesz zárolva, azaz a másik folyamat nem módosíthatja vagy törölheti.

## Mezők

| Mező | Leírás |
| --- | --- |
| [LoadAndRelease](#LoadAndRelease) | A forrás csak a [IPresentation](../../com.aspose.slides/ipresentation) konstruktor végrehajtásának ideje alatt lesz zárolva. |
| [KeepLocked](#KeepLocked) | A forrás a teljes [IPresentation](../../com.aspose.slides/ipresentation) példány élettartama alatt lesz zárolva, amíg el nem lesz dobva. |

### LoadAndRelease {#LoadAndRelease}
```
public static final int LoadAndRelease
```

A forrás csak a [IPresentation](../../com.aspose.slides/ipresentation) konstruktor végrehajtásának ideje alatt lesz zárolva.

--------------------

Ha a ([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) értéke false, minden BLOB memóriába lesz betöltve. Ellenkező esetben más módszerek, például ideiglenes fájlok használhatók.

--------------------

Ez a viselkedés lassabb, mint a [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked), és ha lehetséges a forrás tulajdonjogát átadni a [IPresentation](../../com.aspose.slides/ipresentation)-nek, ajánlott a [KeepLocked](../../com.aspose.slides/presentationlockingbehavior\#KeepLocked) használata.

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

A forrás a teljes [IPresentation](../../com.aspose.slides/ipresentation) példány élettartama alatt lesz zárolva, amíg el nem lesz dobva.

--------------------

[IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)([IBlobManagementOptions.isTemporaryFilesAllowed](../../com.aspose.slides/iblobmanagementoptions\#isTemporaryFilesAllowed)/[IBlobManagementOptions.setTemporaryFilesAllowed(boolean)](../../com.aspose.slides/iblobmanagementoptions\#setTemporaryFilesAllowed-boolean-)) értéke true-ra kell legyen állítva ennek a viselkedésnek a használatához, ellenkező esetben kivétel lesz dobva.

--------------------

Ez a viselkedés ajánlott, gyorsabb és kevesebb memóriát fogyaszt, mint a [LoadAndRelease](../../com.aspose.slides/presentationlockingbehavior\#LoadAndRelease).