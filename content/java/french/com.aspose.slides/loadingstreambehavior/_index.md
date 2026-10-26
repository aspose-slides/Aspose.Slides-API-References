---
title: LoadingStreamBehavior
second_title: Référence de l'API Aspose.Slides pour Java
description: Le java.io.InputStream passé à une méthode est considéré comme un Binary Large Object (BLOB) voir la description.
type: docs
url: /fr/com.aspose.slides/loadingstreambehavior/
---
**Héritage :**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

Le java.io.InputStream passé à une méthode est considéré comme un Binary Large Object (BLOB) (voir la description de [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). Les valeurs de cette énumération indiquent comment le java.io.InputStream doit être traité lorsqu'il est passé à la méthode. En fonction des exigences, différentes décisions peuvent être prises pour offrir le comportement le plus efficace.
## Champs

| Champ | Description |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Le flux sera lu jusqu'à la fin puis libéré - c.-à-d. |
| [KeepLocked](#KeepLocked) | Le flux sera verrouillé à l'intérieur de l'objet [IPresentation](../../com.aspose.slides/ipresentation), c.-à-d. |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Le flux sera lu jusqu'à la fin puis libéré - c.-à-d. il sera garanti que ce flux ne sera pas utilisé par l'instance [IPresentation](../../com.aspose.slides/ipresentation) à l'avenir. Il peut être fermé par le code client ou utilisé d'une autre manière.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // le flux peut être fermé, il n'est plus nécessaire pour l'objet "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Le flux sera verrouillé à l'intérieur de l'objet [IPresentation](../../com.aspose.slides/ipresentation), c.-à-d. la propriété du flux sera transférée. L'objet [IPresentation](../../com.aspose.slides/ipresentation) sera responsable de libérer correctement le flux lorsque cet objet sera lui-même libéré. Ce comportement est extrêmement utile lorsque vous devez sérialiser un fichier BLOB volumineux (tel qu'une grande vidéo ou audio -voir la description de [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) et que vous souhaitez éviter de charger ce fichier en mémoire ou d'autres problèmes de performance. Vous pouvez simplement ouvrir le java.io.FileInputStream pour ce fichier et le transmettre à une méthode, en choisissant le comportement [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Vous ne devez pas fermer le flux ou interagir avec lui d'une autre façon, cela entraînera une erreur dans la méthode Save.
>    // Le fileStream sera utilisé pour l'enregistrement, ce qui évitera une consommation élevée de mémoire
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
