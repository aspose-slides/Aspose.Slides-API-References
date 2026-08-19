---
title: LoadingStreamBehavior
second_title: Aspose.Slides voor Java API-referentie
description: De java.io.InputStream die aan een methode wordt doorgegeven, wordt beschouwd als een Binary Large Object (BLOB); zie de beschrijving.
type: docs
url: /nl/com.aspose.slides/loadingstreambehavior/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

De java.io.InputStream die aan een methode wordt doorgegeven, wordt beschouwd als een Binary Large Object (BLOB) (zie [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) beschrijving). Waarden van deze enumeratie geven aan hoe de java.io.InputStream moet worden behandeld wanneer deze aan de methode wordt doorgegeven. Afhankelijk van de eisen kunnen verschillende beslissingen worden genomen om het meest efficiënte gedrag te bieden.

## Velden

| Veld | Beschrijving |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | De stream wordt tot het einde gelezen en daarna vrijgegeven - d.w.z. |
| [KeepLocked](#KeepLocked) | De stream wordt vergrendeld binnen het [IPresentation](../../com.aspose.slides/ipresentation)-object, d.w.z. |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

De stream wordt tot het einde gelezen en daarna vrijgegeven - d.w.z. er wordt gegarandeerd dat deze stream in de toekomst niet door een [IPresentation](../../com.aspose.slides/ipresentation)-instance zal worden gebruikt. Hij kan door de clientcode worden gesloten of op een andere manier worden gebruikt.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // de stream kan worden gesloten, hij is niet meer nodig voor het "pres" object.
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

De stream wordt vergrendeld binnen het [IPresentation](../../com.aspose.slides/ipresentation)-object, d.w.z. het eigendom van de stream wordt overgedragen. Het [IPresentation](../../com.aspose.slides/ipresentation)-object is verantwoordelijk om de stream correct te verwijderen wanneer dit object zelf wordt verwijderd. Dit gedrag is bijzonder nuttig wanneer u een groot BLOB-bestand moet serialiseren (zoals een grote video of audio - zie [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) beschrijving) en wilt voorkomen dat dit bestand in het geheugen wordt geladen of andere prestatieproblemen veroorzaakt. U kunt eenvoudig de java.io.FileInputStream voor dit bestand openen en doorgeven aan een methode, waarbij u [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior kiest.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Je mag de stream niet sluiten of er op een andere manier mee communiceren, dit zal leiden tot een fout in de Save-methode.
>    // De fileStream zal worden gebruikt voor het opslaan, wat hoog geheugenverbruik voorkomt
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```