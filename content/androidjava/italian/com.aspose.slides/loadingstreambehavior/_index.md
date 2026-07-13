---
title: LoadingStreamBehavior
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Il java.io.InputStream passato a un metodo è considerato come un Binary Large Object BLOB vedere la descrizione.
type: docs
url: /it/com.aspose.slides/loadingstreambehavior/
---
**Ereditarietà:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LoadingStreamBehavior extends System.Enum
```

Il java.io.InputStream passato a un metodo è considerato come un Binary Large Object (BLOB) (vedi la descrizione [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)). I valori di questa enumerazione identificano come il java.io.InputStream deve essere trattato quando viene passato al metodo. A seconda dei requisiti, possono essere prese decisioni diverse per fornire il comportamento più efficiente.
## Campi

| Campo | Descrizione |
| --- | --- |
| [ReadStreamAndRelease](#ReadStreamAndRelease) | Il flusso verrà letto fino alla fine e poi rilasciato - cioè |
| [KeepLocked](#KeepLocked) | Il flusso verrà bloccato all'interno dell'oggetto [IPresentation](../../com.aspose.slides/ipresentation), cioè |
### ReadStreamAndRelease {#ReadStreamAndRelease}
```
public static final int ReadStreamAndRelease
```

Il flusso verrà letto fino alla fine e poi rilasciato - cioè sarà garantito che questo flusso non sarà più usato dall'istanza [IPresentation](../../com.aspose.slides/ipresentation) in futuro. Può essere chiuso dal codice client o usato in qualsiasi altro modo.

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

Il flusso verrà bloccato all'interno dell'oggetto [IPresentation](../../com.aspose.slides/ipresentation), cioè la proprietà del flusso sarà trasferita. L'oggetto [IPresentation](../../com.aspose.slides/ipresentation) sarà responsabile di smaltire correttamente il flusso quando questo oggetto sarà smaltito da solo. Questo comportamento è estremamente utile quando è necessario serializzare un file BLOB di grandi dimensioni (come un video o un audio di grandi dimensioni - vedi la descrizione [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)) e si desidera evitare il caricamento di questo file in memoria o altri problemi di prestazioni. È sufficiente aprire il java.io.FileInputStream per questo file e passarlo a un metodo, scegliendo [KeepLocked](../../com.aspose.slides/loadingstreambehavior\#KeepLocked) LoadingStreamBehavior.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>    FileStream fileStream = new FileStream("Huge Monster Sized Video.avi", FileMode.Open);
>    pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>    // fileStream.close(); // Non dovresti chiudere lo stream o interagire con esso in alcun altro modo, ciò provocherà un errore nel metodo Save.
>    // Il fileStream verrà usato per il salvataggio, il che impedirà un elevato consumo di memoria
>    pres.save("My Presentation With Huge Monster Sized Video.pptx", SaveFormat.Pptx);
>  } finally {
>    if (pres != null) pres.dispose();
>  }
> ```