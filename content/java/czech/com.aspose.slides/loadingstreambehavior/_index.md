---
title: LoadingStreamBehavior
second_title: Aspose.Slides pro Java - API reference
description: java.io.InputStream předaný metodě je považován za Binary Large Object (BLOB) viz popis.
type: docs
url: /cs/com.aspose.slides/loadingstreambehavior/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

java.io.InputStream předaný metodě je považován za Binary Large Object (BLOB) (viz [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) popis). Hodnoty tohoto výčtu určují, jak má být java.io.InputStream při předání metodě zpracován. V závislosti na požadavcích lze učinit různé rozhodnutí pro dosažení nejefektivnějšího chování.
## Pole

| Field | Description |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Proud bude čten až do konce a následně uvolněn – tj. |
| [KeepLocked](#KeepLocked) | Proud bude uzamčen uvnitř objektu [IPresentation](../../com.aspose.slides/ipresentation), tj. |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Proud bude čten až do konce a následně uvolněn – tj. bude zaručeno, že tento proud v budoucnu nebude použit instancí [IPresentation](../../com.aspose.slides/ipresentation). Může být uzavřen klientským kódem nebo použit jiným způsobem.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // proud může být uzavřen, už není potřeba pro objekt "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Proud bude uzamčen uvnitř objektu [IPresentation](../../com.aspose.slides/ipresentation), tj. vlastnictví proudu bude převedeno. Objekt [IPresentation](../../com.aspose.slides/ipresentation) bude zodpovědný za správné uvolnění proudu, když bude tento objekt sám uvolněn. Toto chování je mimořádně užitečné, když potřebujete serializovat velký soubor BLOB (například velké video nebo audio - viz [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) popis) a chcete zabránit načtení tohoto souboru do paměti či dalším problémům s výkonem. Můžete jednoduše otevřít java.io.FileInputStream pro tento soubor a předat jej metodě, volbou [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Neměli byste uzavřít proud ani s ním jinak manipulovat, povede to k chybě v metodě Save.
>    // Souborový proud bude použit pro ukládání, což zabrání vysoké spotřebě paměti
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
