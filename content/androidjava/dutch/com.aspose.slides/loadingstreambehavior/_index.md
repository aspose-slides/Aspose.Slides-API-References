---
title: LoadingStreamBehavior
second_title: Aspose.Slides voor Android via Java API-referentie
description: De java.io.InputStream die aan een methode wordt doorgegeven, wordt beschouwd als een Binary Large Object (BLOB); zie  beschrijving.
type: docs
url: /nl/com.aspose.slides/loadingstreambehavior/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

The java.io.InputStream passed to a method is considered as a Binary Large Object (BLOB) (see [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) description). Values of this enumeration identify how the java.io.InputStream should be treated when it passed to the method. Depending on the requirements, different decisions could be made to provide the most efficient behavior.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | De stream wordt tot het einde gelezen en vervolgens vrijgegeven - d.w.z. |
| [KeepLocked](#KeepLocked) | De stream wordt vergrendeld binnen het [IPresentation](../../com.aspose.slides/ipresentation) object, d.w.z. |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```


De stream wordt tot het einde gelezen en vervolgens vrijgegeven - d.w.z. er wordt gegarandeerd dat deze stream in de toekomst niet door een [IPresentation](../../com.aspose.slides/ipresentation) instantie zal worden gebruikt. Hij kan worden gesloten door de clientcode of op andere wijze worden gebruikt.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // de stroom kan worden gesloten, het is niet meer nodig voor het "pres" object.
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```


De stream wordt vergrendeld binnen het [IPresentation](../../com.aspose.slides/ipresentation) object, d.w.z. het eigendom van de stream wordt overgedragen. Het [IPresentation](../../com.aspose.slides/ipresentation) object is verantwoordelijk om de stream correct te verwijderen wanneer dit object zelf wordt verwijderd. Dit gedrag is uiterst nuttig wanneer u een groot BLOB-bestand moet serialiseren (zoals een grote video of audio - zie [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) beschrijving) en wilt voorkomen dat dit bestand in het geheugen wordt geladen of andere prestatieproblemen veroorzaakt. U kunt eenvoudig de java.io.FileInputStream voor dit bestand openen en aan een methode doorgeven, door [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior te kiezen.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Je moet de stroom niet sluiten of er op een andere manier mee interacteren, dit zal leiden tot een fout in de Save-methode.
>    // De fileStream zal worden gebruikt voor opslaan, wat een hoog geheugenverbruik voorkomt
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
