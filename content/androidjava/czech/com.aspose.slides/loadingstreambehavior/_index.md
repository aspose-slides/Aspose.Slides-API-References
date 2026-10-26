---
title: LoadingStreamBehavior
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: java.io.InputStream předaný metodě je považován za Binary Large Object BLOB (viz popis).
type: docs
url: /cs/com.aspose.slides/loadingstreambehavior/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

java.io.InputStream předaný metodě je považován za Binary Large Object (BLOB) (viz popis [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). Hodnoty tohoto výčtu určují, jak má být java.io.InputStream zpracován, když je předán metodě. V závislosti na požadavcích lze učinit různá rozhodnutí pro poskytnutí nejefektivnějšího chování.

## Pole

| Pole | Popis |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Stream bude čten až do konce a poté uvolněn - tj. |
| [KeepLocked](#KeepLocked) | Stream bude uzamčen uvnitř objektu [IPresentation](../../com.aspose.slides/ipresentation), i.e. |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Stream bude čten až do konce a poté uvolněn - i.e. bude zaručeno, že tento stream nebude v budoucnu používán instancí [IPresentation](../../com.aspose.slides/ipresentation). Může být uzavřen klientským kódem nebo použit jakýmkoli jiným způsobem.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // stream může být uzavřen, již není potřeba pro objekt "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Stream bude uzamčen uvnitř objektu [IPresentation](../../com.aspose.slides/ipresentation), i.e. vlastnictví streamu bude převedeno. Objekt [IPresentation](../../com.aspose.slides/ipresentation) bude zodpovědný za správné uvolnění streamu, když bude tento objekt sám uvolněn. Toto chování je mimořádně užitečné, když potřebujete serializovat velký BLOB soubor (například velké video nebo audio - viz popis [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) a chcete zabránit načítání tohoto souboru do paměti nebo jiným problémům s výkonem. Můžete jednoduše otevřít java.io.FileInputStream pro tento soubor a předat jej metodě, výběrem [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Neměli byste zavřít stream nebo s ním jinak manipulovat, povede to k chybě v metodě Save.
>    // fileStream bude použit pro ukládání, což zabrání vysoké spotřebě paměti
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```