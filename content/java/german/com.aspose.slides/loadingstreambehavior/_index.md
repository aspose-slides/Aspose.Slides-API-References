---
title: LoadingStreamBehavior
second_title: Aspose.Slides für Java API-Referenz
description: Der java.io.InputStream, der an eine Methode übergeben wird, wird als Binary Large Object (BLOB) betrachtet, siehe Beschreibung.
type: docs
url: /de/com.aspose.slides/loadingstreambehavior/
---
**Vererbung:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

Der java.io.InputStream, der an eine Methode übergeben wird, wird als Binary Large Object (BLOB) betrachtet (siehe [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) Beschreibung). Die Werte dieser Aufzählung geben an, wie der java.io.InputStream behandelt werden soll, wenn er an die Methode übergeben wird. Abhängig von den Anforderungen können unterschiedliche Entscheidungen getroffen werden, um das effizienteste Verhalten zu gewährleisten.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Der Stream wird bis zum Ende gelesen und dann freigegeben – d. h. |
| [KeepLocked](#KeepLocked) | Der Stream wird im [IPresentation](../../com.aspose.slides/ipresentation)-Objekt gesperrt, d. h. |

### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Der Stream wird bis zum Ende gelesen und dann freigegeben – d. h. es wird garantiert, dass dieser Stream in Zukunft nicht von einer [IPresentation](../../com.aspose.slides/ipresentation)-Instanz verwendet wird. Er kann vom Client-Code geschlossen oder auf andere Weise verwendet werden.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // Der Stream kann geschlossen werden, er wird für das "pres"-Objekt nicht mehr benötigt.
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```

### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Der Stream wird im [IPresentation](../../com.aspose.slides/ipresentation)-Objekt gesperrt, d. h. das Eigentum am Stream wird übertragen. Das [IPresentation](../../com.aspose.slides/ipresentation)-Objekt ist dafür verantwortlich, den Stream korrekt zu entsorgen, wenn dieses Objekt selbst entsorgt wird. Dieses Verhalten ist äußerst nützlich, wenn Sie eine große BLOB-Datei (wie ein großes Video oder Audio – siehe [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) Beschreibung) serialisieren müssen und dabei das Laden dieser Datei in den Speicher oder andere Leistungsprobleme vermeiden wollen. Sie können einfach den java.io.FileInputStream für diese Datei öffnen und an eine Methode übergeben, indem Sie [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior wählen.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Sie sollten den Stream nicht schließen oder anderweitig damit interagieren, da dies im Save-Verfahren zu einem Fehler führt.
>    // Der fileStream wird zum Speichern verwendet, was einen hohen Speicherverbrauch verhindert.
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```