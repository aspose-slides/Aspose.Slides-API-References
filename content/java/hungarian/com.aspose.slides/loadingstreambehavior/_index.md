---
title: LoadingStreamBehavior
second_title: Aspose.Slides for Java API referenciája
description: A metódusnak átadott java.io.InputStream-et Binary Large Object (BLOB)-ként tekintik, lásd a leírást.
type: docs
url: /hu/com.aspose.slides/loadingstreambehavior/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

A java.io.InputStream, amelyet egy metódus kap, Binary Large Object (BLOB)-ként van kezelve (lásd [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) leírás). Ennek a felsorolásnak az értékei meghatározzák, hogyan kell kezelni a java.io.InputStream-et, amikor átadják a metódusnak. A követelményeknek megfelelően különböző döntések hozhatók a leghatékonyabb viselkedés biztosítása érdekében.
## Mezők

| Field | Description |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | A folyam végéig lesz olvasva, majd felszabadítva - azaz |
| [KeepLocked](#KeepLocked) | A folyam a [IPresentation](../../com.aspose.slides/ipresentation) objektumon belül lesz zárolva, azaz |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

A folyam végéig lesz olvasva, majd felszabadítva - azaz garantált, hogy ezt a folyamatot a [IPresentation](../../com.aspose.slides/ipresentation) példány a jövőben nem fogja használni. Lezárható az ügyfél kódból, vagy bármilyen más módon felhasználható.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // a folyam lezárható, már nincs szükség rá a "pres" objektum számára.
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

A folyam a [IPresentation](../../com.aspose.slides/ipresentation) objektumon belül lesz zárolva, azaz a folyamat tulajdonjoga átadásra kerül. A [IPresentation](../../com.aspose.slides/ipresentation) objektum felelős azért, hogy helyesen megsemmisítse a folyamatot, amikor ez az objektum önmagát megsemmisíti. Ez a viselkedés különösen hasznos, ha egy nagy BLOB fájlt (például egy nagy videót vagy hangfájlt – lásd [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) leírás) kell sorosítani, és el akarja kerülni a fájl memóriába töltését vagy más teljesítményproblémákat. Egyszerűen megnyithatja a java.io.FileInputStream-et ehhez a fájlhoz, és átadhatja egy metódusnak, a [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior kiválasztásával.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Nem szabad lezárni a folyamatot vagy bármilyen más módon interakcióba lépni vele, ez hibát okoz a Save metódusban.
>    // A fileStream a mentéshez lesz használva, ami megakadályozza a nagy memóriafogyasztást
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
