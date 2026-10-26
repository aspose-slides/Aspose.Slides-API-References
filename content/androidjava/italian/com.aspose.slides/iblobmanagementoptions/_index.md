---
title: IBlobManagementOptions
second_title: Aspose.Slides for Android via Java API Reference
description: A Binary Large Object BLOB is a binary data stored as a single entity - i.e.
type: docs
url: /it/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Un Binary Large Object (BLOB) è un dato binario memorizzato come un'unica entità – cioè un BLOB può essere un audio, un video o la presentazione stessa. Diverse tecniche sono utilizzate per ottimizzare il consumo di memoria durante la manipolazione dei BLOB — che siano già contenuti nella presentazione o aggiunti successivamente in modo programmatico. Utilizzando [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) è possibile modificare diversi aspetti del comportamento relativi alla gestione dei BLOB per la durata dell'istanza [IPresentation](../../com.aspose.slides/ipresentation).

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente — file o stream — per tutta la durata dell'istanza. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente — file o stream — per tutta la durata dell'istanza. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Questa proprietà definisce se è possibile creare file temporanei durante la manipolazione dei BLOB, il che riduce notevolmente il consumo di memoria ma richiede i permessi per creare file. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Questa proprietà definisce se è possibile creare file temporanei durante la manipolazione dei BLOB, il che riduce notevolmente il consumo di memoria ma richiede i permessi per creare file. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Il percorso radice dove verranno creati i file temporanei. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Il percorso radice dove verranno creati i file temporanei. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. |
### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente — file o stream — per tutta la durata dell'istanza. Se l'istanza è proprietaria, blocca la sorgente. Questo aiuta a migliorare il consumo di memoria e le prestazioni durante la manipolazione dei BLOB, ma la sorgente (stream o file) non può essere modificata durante la durata dell'istanza di Presentation. Questo è un esempio:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Verrà lanciata un'IOException perché pres.pptx è bloccato per tutta la durata di una Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // dopo che l'oggetto Presentation è stato eliminato, il file è sbloccato e può essere cancellato
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Restituisce:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente — file o stream — per tutta la durata dell'istanza. Se l'istanza è proprietaria, blocca la sorgente. Questo aiuta a migliorare il consumo di memoria e le prestazioni durante la manipolazione dei BLOB, ma la sorgente (stream o file) non può essere modificata durante la durata dell'istanza di Presentation. Questo è un esempio:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Verrà lanciata un'IOException perché pres.pptx è bloccato per tutta la durata di una Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // dopo che l'oggetto Presentation è stato eliminato, il file è sbloccato e può essere cancellato
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Questa proprietà definisce se è possibile creare file temporanei durante la manipolazione dei BLOB, il che riduce notevolmente il consumo di memoria ma richiede i permessi per creare file.

--------------------

Tutti i file saranno eliminati una volta terminato il lavoro con la presentazione.

**Restituisce:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Questa proprietà definisce se è possibile creare file temporanei durante la manipolazione dei BLOB, il che riduce notevolmente il consumo di memoria ma richiede i permessi per creare file.

--------------------

Tutti i file saranno eliminati una volta terminato il lavoro con la presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

Il percorso radice dove verranno creati i file temporanei. Per impostazione predefinita verrà usata la directory temporanea di sistema. Il processo di hosting deve disporre dei permessi per creare file e cartelle in tale posizione.

**Restituisce:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

Il percorso radice dove verranno creati i file temporanei. Per impostazione predefinita verrà usata la directory temporanea di sistema. Il processo di hosting deve disporre dei permessi per creare file e cartelle in tale posizione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita tutti i BLOB vengono caricati in memoria; solo quando questo limite viene superato vengono impiegati meccanismi alternativi (come file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può portare a un elevato utilizzo di memoria. Utilizza questa proprietà per adattare il comportamento al tuo ambiente o alle tue esigenze.

--------------------

Questa proprietà è ignorata se \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) è impostata a false, poiché in tal caso la memoria è l'unica sede di archiviazione disponibile e limitare l'uso di BLOB in memoria non ha effetto.

--------------------

Il valore predefinito è 629.145.600 byte (600 MB).

--------------------

Puoi impostare questa proprietà a zero, ma verrà comunque riservata una piccola quantità minima di memoria.

**Restituisce:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita tutti i BLOB vengono caricati in memoria; solo quando questo limite viene superato vengono impiegati meccanismi alternativi (come file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può portare a un elevato utilizzo di memoria. Utilizza questa proprietà per adattare il comportamento al tuo ambiente o alle tue esigenze.

--------------------

Questa proprietà è ignorata se \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) è impostata a false, poiché in tal caso la memoria è l'unica sede di archiviazione disponibile e limitare l'uso di BLOB in memoria non ha effetto.

--------------------

Il valore predefinito è 629.145.600 byte (600 MB).

--------------------

Puoi impostare questa proprietà a zero, ma verrà comunque riservata una piccola quantità minima di memoria.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |