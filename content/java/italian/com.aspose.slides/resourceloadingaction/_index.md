---
title: ResourceLoadingAction
second_title: Riferimento API Aspose.Slides per Java
description: Specifica la modalità di caricamento delle risorse esterne.
type: docs
url: /it/com.aspose.slides/resourceloadingaction/
---
**Eredità:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Specifica la modalità di caricamento delle risorse esterne.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Default](#Default) | Aspose.Slides caricherà la risorsa esterna come di consueto. |
| [Skip](#Skip) | Aspose.Slides ometterà il caricamento della risorsa esterna. |
| [UserProvided](#UserProvided) | Aspose.Slides utilizzerà l'array di byte fornito dall'utente in [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) come dati dell'immagine. |
### Default {#Default}
```
public static final int Default
```

Aspose.Slides caricherà la risorsa esterna come di consueto.

### Skip {#Skip}
```
public static final int Skip
```

Aspose.Slides ometterà il caricamento della risorsa esterna. Verrà memorizzato solo il collegamento senza dati per un'immagine.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides utilizzerà l'array di byte fornito dall'utente in [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) come dati dell'immagine.