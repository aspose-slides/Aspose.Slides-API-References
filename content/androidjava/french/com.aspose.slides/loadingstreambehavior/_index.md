---
title: LoadingStreamBehavior
second_title: Aspose.Slides pour Android via la référence API Java
description: Le java.io.InputStream passé à une méthode est considéré comme un Binary Large Object (BLOB) voir la description.
type: docs
url: /fr/com.aspose.slides/loadingstreambehavior/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

Le java.io.InputStream passé à une méthode est considéré comme un Binary Large Object (BLOB) (voir la description [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). Les valeurs de cette énumération indiquent comment le java.io.InputStream doit être traité lorsqu’il est passé à la méthode. Selon les exigences, différentes décisions peuvent être prises afin d’obtenir le comportement le plus efficace.
## Champs

| Champ | Description |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Le flux sera lu jusqu’à la fin, puis libéré - c’est-à-dire |
| [KeepLocked](#KeepLocked) | Le flux sera verrouillé à l’intérieur de l’objet [IPresentation](../../com.aspose.slides/ipresentation), c’est-à-dire |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```


Le flux sera lu jusqu’à la fin, puis libéré - c’est-à-dire qu’il sera garanti que ce flux ne sera plus utilisé par l’instance [IPresentation](../../com.aspose.slides/ipresentation) à l’avenir. Il peut être fermé par le code client ou utilisé de toute autre manière.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // the stream can be closed, it's no longer needed for the "pres" object.
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked


Le flux sera verrouillé à l’intérieur de l’objet [IPresentation](../../com.aspose.slides/ipresentation), c’est-à-dire que la propriété du flux sera transférée. L’objet [IPresentation](../../com.aspose.slides/ipresentation) sera responsable de disposer correctement du flux lorsque cet objet sera lui-même disposé. Ce comportement est extrêmement utile lorsque vous devez sérialiser un fichier BLOB volumineux (tel qu’une grande vidéo ou un fichier audio – voir la description [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) et que vous souhaitez éviter de charger ce fichier en mémoire ou d’autres problèmes de performances. Vous pouvez simplement ouvrir le java.io.FileInputStream pour ce fichier et le transmettre à une méthode, en choisissant [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // You should not close the stream or interact with it in any other way, it will lead to an error in Save method.
>    // The fileStream will be used for saving, what will prevent high memory consumption..
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```