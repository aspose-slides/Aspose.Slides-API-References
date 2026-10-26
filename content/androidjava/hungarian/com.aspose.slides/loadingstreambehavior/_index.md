---
title: LoadingStreamBehavior
second_title: Aspose.Slides for Android Java API referencia
description: A metódusnak átadott java.io.InputStream egy Binary Large Object (BLOB), lásd a leírást.
type: docs
url: /hu/com.aspose.slides/loadingstreambehavior/
---
**Öröklődés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

A metódusnak átadott java.io.InputStream egy Binary Large Object (BLOB) (lásd [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) leírása). Ennek a felsorolásnak az értékei meghatározzák, hogyan kell kezelni a java.io.InputStream-et, amikor átadják a metódusnak. A követelményektől függően különböző döntések hozhatók a leghatékonyabb viselkedés biztosításához.
## Mezők

| Mező | Leírás |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | A folyamot a végéig olvassák, majd felszabadítják - azaz |
| [KeepLocked](#KeepLocked) | A folyamot a [IPresentation](../../com.aspose.slides/ipresentation) objektumon belül lezárják - azaz |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

A folyamot a végéig olvassák, majd felszabadítják - azaz garantált lesz, hogy ezt a folyamot a [IPresentation](../../com.aspose.slides/ipresentation) példány a jövőben nem használja. Lezárható a klienskódból, vagy bármilyen más módon felhasználható.

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

A folyamot a [IPresentation](../../com.aspose.slides/ipresentation) objektumon belül lezárják - azaz a folyam tulajdonjoga átkerül. A [IPresentation](../../com.aspose.slides/ipresentation) objektum felelős azért, hogy megfelelően felszabadítsa a folyamot, amikor ez az objektum magát is felszabadítja. Ez a viselkedés rendkívül hasznos, ha nagy BLOB fájlt (például nagy videó vagy hang -lásd [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) leírása) kell sorosítani, és meg szeretné előzni a fájl memóriába töltését vagy egyéb teljesítményproblémákat. Egyszerűen megnyithatja a java.io.FileInputStream-et ehhez a fájlhoz, és átadhatja egy metódusnak, kiválasztva a [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior-t.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Nem szabad bezárni a folyamot vagy más módon módosítani, ez hibához vezet a Save metódusban.
>    // A fileStream a mentéshez lesz használva, ami megakadályozza a magas memóriahasználatot
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```