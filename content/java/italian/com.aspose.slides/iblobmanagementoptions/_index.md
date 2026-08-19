---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API Reference
description: A Binary Large Object BLOB is a binary data stored as a single entity - i.e.
type: docs
url: /it/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Un Binary Large Object (BLOB) è un dato binario memorizzato come un'entità singola - ad esempio un BLOB può essere un audio, un video o la presentazione stessa. Vengono utilizzate numerose tecniche per ottimizzare il consumo di memoria durante il lavoro con i BLOB - già presenti nella presentazione o aggiunti successivamente in modo programmatico. Utilizzando [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) è possibile modificare diversi aspetti del comportamento relativi alla gestione dei BLOB per la durata dell'istanza [IPresentation](../../com.aspose.slides/ipresentation).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente - file o stream durante la durata dell'istanza. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente - file o stream durante la durata dell'istanza. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Questa proprietà definisce se è possibile creare file temporanei durante il lavoro con i BLOB, il che riduce notevolmente il consumo di memoria ma richiede permessi per creare file. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Questa proprietà definisce se è possibile creare file temporanei durante il lavoro con i BLOB, il che riduce notevolmente il consumo di memoria ma richiede permessi per creare file. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Il percorso radice dove verranno creati i file temporanei. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Il percorso radice dove verranno creati i file temporanei. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. |
### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```


Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente - file o stream durante la durata dell'istanza. Se l'istanza è un proprietario, blocca la sorgente. Ciò aiuta a migliorare il consumo di memoria e le prestazioni durante il lavoro con i BLOB, ma la sorgente (stream o file) non può essere cambiata durante la durata dell'istanza di Presentation. Questo è un esempio:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Verrà sollevata un'IOException perché pres.pptx è bloccato per tutta la durata della Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // dopo che l'oggetto Presentation è stato smaltito, il file è sbloccato e può essere eliminato
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```

**Restituisce:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```


Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente - file o stream durante la durata dell'istanza. Se l'istanza è un proprietario, blocca la sorgente. Ciò aiuta a migliorare il consumo di memoria e le prestazioni durante il lavoro con i BLOB, ma la sorgente (stream o file) non può essere cambiata durante la durata dell'istanza di Presentation. Questo è un esempio:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Verrà sollevata un'IOException perché pres.pptx è bloccato per tutta la durata della Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // dopo che l'oggetto Presentation è stato smaltito, il file è sbloccato e può essere eliminato
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


Questa proprietà definisce se è possibile creare file temporanei durante il lavoro con i BLOB, il che riduce notevolmente il consumo di memoria ma richiede permessi per creare file.

--------------------

Tutti i file verranno eliminati al termine del lavoro con la presentazione.

**Restituisce:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```


Questa proprietà definisce se è possibile creare file temporanei durante il lavoro con i BLOB, il che riduce notevolmente il consumo di memoria ma richiede permessi per creare file.

--------------------

Tutti i file verranno eliminati al termine del lavoro con la presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```


Il percorso radice dove verranno creati i file temporanei. Per impostazione predefinita verrà utilizzata la directory temporanea di sistema. Il processo di hosting deve avere permessi per creare file e cartelle lì.

**Restituisce:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```


Il percorso radice dove verranno creati i file temporanei. Per impostazione predefinita verrà utilizzata la directory temporanea di sistema. Il processo di hosting deve avere permessi per creare file e cartelle lì.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```


Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB vengono caricati in memoria; solo quando questo limite viene raggiunto vengono impiegati meccanismi alternativi (come i file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può portare a un elevato utilizzo di memoria. Utilizza questa proprietà per adattare il comportamento al tuo ambiente o alle tue esigenze.

--------------------

Questa proprietà è ignorata se \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) è impostata su false, poiché la memoria è allora l'unica posizione di archiviazione disponibile e limitare l'uso dei BLOB in memoria non ha effetto.

--------------------

Il valore predefinito è 629,145,600 byte (600 MB).

--------------------

È possibile impostare questa proprietà a zero, ma verrà comunque riservata una piccola quantità minima di memoria.

**Restituisce:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```


Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB vengono caricati in memoria; solo quando questo limite viene raggiunto vengono impiegati meccanismi alternativi (come i file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può portare a un elevato utilizzo di memoria. Utilizza questa proprietà per adattare il comportamento al tuo ambiente o alle tue esigenze.

--------------------

Questa proprietà è ignorata se \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) è impostata su false, poiché la memoria è allora l'unica posizione di archiviazione disponibile e limitare l'uso dei BLOB in memoria non ha effetto.

--------------------

Il valore predefinito è 629,145,600 byte (600 MB).

--------------------

È possibile impostare questa proprietà a zero, ma verrà comunque riservata una piccola quantità minima di memoria.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |