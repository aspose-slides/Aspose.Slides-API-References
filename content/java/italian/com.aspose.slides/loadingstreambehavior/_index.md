---
title: LoadingStreamBehavior
second_title: Riferimento API Aspose.Slides per Java
description: Il java.io.InputStream passato a un metodo è considerato un Binary Large Object (BLOB) vedi la descrizione.
type: docs
url: /it/com.aspose.slides/loadingstreambehavior/
---
**Ereditarietà:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

Il java.io.InputStream passato a un metodo è considerato un Binary Large Object (BLOB) (vedi la descrizione [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). I valori di questa enumerazione identificano come il java.io.InputStream debba essere gestito quando viene passato al metodo. A seconda dei requisiti, possono essere prese decisioni diverse per fornire il comportamento più efficiente.
## Campi

| Campo | Descrizione |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Il flusso verrà letto fino alla fine e poi rilasciato - cioè |
| [KeepLocked](#KeepLocked) | Il flusso sarà bloccato all'interno dell'oggetto [IPresentation](../../com.aspose.slides/ipresentation), cioè |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Il flusso verrà letto fino alla fine e poi rilasciato - cioè sarà garantito che questo flusso non sarà più utilizzato dall'istanza [IPresentation](../../com.aspose.slides/ipresentation) in futuro. Può essere chiuso dal codice client o utilizzato in qualsiasi altro modo.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileInputStream fileStream = new FileInputStream(new File("video.avi"));
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.ReadStreamAndRelease);
>    fileStream.close(); // il flusso può essere chiuso, non è più necessario per l'oggetto "pres".
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```


### KeepLocked {#KeepLocked}
```
public static final int KeepLocked
```

Il flusso sarà bloccato all'interno dell'oggetto [IPresentation](../../com.aspose.slides/ipresentation), cioè la proprietà del flusso sarà trasferita. L'oggetto [IPresentation](../../com.aspose.slides/ipresentation) sarà responsabile di eliminare correttamente il flusso quando questo oggetto verrà eliminato. Questo comportamento è estremamente utile quando è necessario serializzare un grande file BLOB (come un grande video o audio - vedi la descrizione [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) e si desidera evitare il caricamento di questo file in memoria o altri problemi di prestazioni. È sufficiente aprire il java.io.FileInputStream per questo file e passarlo a un metodo, scegliendo [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Non dovresti chiudere il flusso o interagire con esso in altro modo, porterà a un errore nel metodo Save.
>    // Il fileStream verrà usato per il salvataggio, il che eviterà un elevato consumo di memoria
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```
