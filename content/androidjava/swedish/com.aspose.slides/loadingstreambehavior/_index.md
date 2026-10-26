---
title: LoadingStreamBehavior
second_title: Aspose.Slides för Android via Java API-referens
description: Den java.io.InputStream som skickas till en metod betraktas som ett Binary Large Object (BLOB) se beskrivning.
type: docs
url: /sv/com.aspose.slides/loadingstreambehavior/
---
**Arv:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

Den java.io.InputStream som skickas till en metod betraktas som ett Binary Large Object (BLOB) (se [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)-beskrivning). Värdena i denna uppräkning identifierar hur java.io.InputStream ska behandlas när den skickas till metoden. Beroende på kraven kan olika beslut fattas för att ge bästa möjliga prestanda.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Strömmen kommer att läsas till slutet och sedan frigöras - d.v.s. |
| [KeepLocked](#KeepLocked) | Strömmen kommer att låsas inuti [IPresentation](../../com.aspose.slides/ipresentation)-objektet, d.v.s. |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Strömmen kommer att läsas till slutet och sedan frigöras - d.v.s. det kommer att garanteras att denna ström inte kommer att användas av [IPresentation](../../com.aspose.slides/ipresentation)-instansen i framtiden. Den kan stängas av klientkoden eller användas på annat sätt.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // strömmen kan stängas, den behövs inte längre för "pres"-objektet.
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Strömmen kommer att låsas inuti [IPresentation](../../com.aspose.slides/ipresentation)-objektet, d.v.s. äganderätten till strömmen kommer att överföras. [IPresentation](../../com.aspose.slides/ipresentation)-objektet kommer att vara ansvarigt för att korrekt avyttra strömmen när detta objekt själv avyttras. Detta beteende är extremt användbart när du behöver serialisera en stor BLOB-fil (såsom en stor video eller ljud - se [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)-beskrivning) och vill förhindra att denna fil laddas in i minnet eller andra prestandaproblem. Du kan helt enkelt öppna java.io.FileInputStream för denna fil och skicka den till en metod, genom att välja [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Du bör inte stänga strömmen eller interagera med den på något annat sätt, det kommer att leda till ett fel i Save-metoden.
>    // Strömmen kommer att användas för sparande, vilket kommer att förhindra hög minnesförbrukning
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
