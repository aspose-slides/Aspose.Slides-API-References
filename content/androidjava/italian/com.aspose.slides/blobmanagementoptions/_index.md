---
title: BlobManagementOptions
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta le opzioni che possono essere utilizzate per gestire le regole di gestione dei BLOB e altre impostazioni dei BLOB.
type: docs
url: /it/com.aspose.slides/blobmanagementoptions/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Rappresenta le opzioni che possono essere utilizzate per gestire le regole di gestione dei BLOB e altre impostazioni dei BLOB.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Crea nuove opzioni di gestione dei blob predefinite. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente - file o stream durante la durata dell'istanza. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente - file o stream durante la durata dell'istanza. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Questa proprietà definisce se i file temporanei possono essere creati durante il lavoro con i BLOB, riducendo notevolmente il consumo di memoria ma richiedendo i permessi per creare file. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Questa proprietà definisce se i file temporanei possono essere creati durante il lavoro con i BLOB, riducendo notevolmente il consumo di memoria ma richiedendo i permessi per creare file. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | Il percorso radice dove verranno creati i file temporanei. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | Il percorso radice dove verranno creati i file temporanei. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. |
### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Crea nuove opzioni di gestione dei blob predefinite.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente - file o stream durante la durata dell'istanza. Se l'istanza è proprietaria, blocca la sorgente. Questo aiuta a migliorare il consumo di memoria e le prestazioni durante il lavoro con i BLOB, ma la sorgente (stream o file) non può essere modificata durante la durata dell'istanza di Presentation.

**Restituisce:**
int
### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente - file o stream durante la durata dell'istanza. Se l'istanza è proprietaria, blocca la sorgente. Questo aiuta a migliorare il consumo di memoria e le prestazioni durante il lavoro con i BLOB, ma la sorgente (stream o file) non può essere modificata durante la durata dell'istanza di Presentation.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Questa proprietà definisce se i file temporanei possono essere creati durante il lavoro con i BLOB, riducendo notevolmente il consumo di memoria ma richiedendo i permessi per creare file.

--------------------

Tutti i file verranno eliminati al termine del lavoro con la presentazione.

**Restituisce:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Questa proprietà definisce se i file temporanei possono essere creati durante il lavoro con i BLOB, riducendo notevolmente il consumo di memoria ma richiedendo i permessi per creare file.

--------------------

Tutti i file verranno eliminati al termine del lavoro con la presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

Il percorso radice dove verranno creati i file temporanei. Per impostazione predefinita verrà utilizzata la directory temporanea del sistema. Il processo di hosting deve avere i permessi per creare file e cartelle lì.

**Restituisce:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

Il percorso radice dove verranno creati i file temporanei. Per impostazione predefinita verrà utilizzata la directory temporanea del sistema. Il processo di hosting deve avere i permessi per creare file e cartelle lì.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita tutti i BLOB vengono caricati in memoria; solo quando questo limite è raggiunto vengono impiegati meccanismi alternativi (come i file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può portare a un elevato utilizzo di memoria. Usa questa proprietà per adattare il comportamento al tuo ambiente o alle tue esigenze.

--------------------

Questa proprietà è ignorata se \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) è impostata su false, poiché la memoria è allora l'unica posizione di archiviazione disponibile e limitare l'uso dei BLOB in memoria non ha effetto.

--------------------

Il valore predefinito è 629.145.600 byte (600 MB).

--------------------

Puoi impostare questa proprietà a zero, ma verrà comunque riservata una piccola quantità minima di memoria.

**Restituisce:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita tutti i BLOB vengono caricati in memoria; solo quando questo limite è raggiunto vengono impiegati meccanismi alternativi (come i file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può portare a un elevato utilizzo di memoria. Usa questa proprietà per adattare il comportamento al tuo ambiente o alle tue esigenze.

--------------------

Questa proprietà è ignorata se \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) è impostata su false, poiché la memoria è allora l'unica posizione di archiviazione disponibile e limitare l'uso dei BLOB in memoria non ha effetto.

--------------------

Il valore predefinito è 629.145.600 byte (600 MB).

--------------------

Puoi impostare questa proprietà a zero, ma verrà comunque riservata una piccola quantità minima di memoria.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |