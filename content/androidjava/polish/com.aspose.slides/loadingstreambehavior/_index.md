---
title: LoadingStreamBehavior
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: java.io.InputStream przekazywany do metody jest traktowany jako Binary Large Object (BLOB) - zobacz opis.
type: docs
url: /pl/com.aspose.slides/loadingstreambehavior/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

java.io.InputStream przekazywany do metody jest traktowany jako Binary Large Object (BLOB) (zobacz opis [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). Wartości tej enumeracji określają, jak java.io.InputStream powinien być traktowany, gdy jest przekazywany do metody. W zależności od wymagań można podjąć różne decyzje, aby zapewnić najbardziej efektywne zachowanie.

## Pola

| Pole | Opis |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Strumień zostanie odczytany do końca i następnie zwolniony - i.e. |
| [KeepLocked](#KeepLocked) | Strumień zostanie zablokowany wewnątrz obiektu [IPresentation](../../com.aspose.slides/ipresentation), i.e. |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Strumień zostanie odczytany do końca i następnie zwolniony - i.e. zostanie zagwarantowane, że ten strumień nie będzie używany przez instancję [IPresentation](../../com.aspose.slides/ipresentation) w przyszłości. Może zostać zamknięty przez kod klienta lub użyty w inny sposób.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // strumień można zamknąć, nie jest już potrzebny dla obiektu "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Strumień zostanie zablokowany wewnątrz obiektu [IPresentation](../../com.aspose.slides/ipresentation), i.e. własność strumienia zostanie przeniesiona. Obiekt [IPresentation](../../com.aspose.slides/ipresentation) będzie odpowiedzialny za prawidłowe zwolnienie strumienia, gdy ten obiekt zostanie sam zwolniony. To zachowanie jest niezwykle przydatne, gdy potrzebujesz serializować duży plik BLOB (na przykład duży plik wideo lub audio - zobacz opis [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) i chcesz zapobiec wczytywaniu tego pliku do pamięci lub innym problemom wydajnościowym. Możesz po prostu otworzyć java.io.FileInputStream dla tego pliku i przekazać go do metody, wybierając [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Nie należy zamykać strumienia ani wchodzić z nim w interakcję w inny sposób, spowoduje to błąd w metodzie Save.
>    // Strumień fileStream będzie używany do zapisu, co zapobiegnie dużemu zużyciu pamięci
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
