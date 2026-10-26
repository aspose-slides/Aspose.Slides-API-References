---
title: OleEmbeddedDataInfo
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta le informazioni dei dati incorporati per un oggetto OLE.
type: docs
url: /it/com.aspose.slides/oleembeddeddatainfo/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Rappresenta le informazioni dei dati incorporati per un oggetto OLE.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Crea nuove informazioni di dati incorporati per un oggetto OLE. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Crea una nuova istanza di informazioni sui dati incorporati per un oggetto OLE. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Restituisce i dati del file di un oggetto OLE incorporato Solo lettura byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Restituisce l'estensione del file per l'attuale oggetto OLE incorporato Solo lettura String. |

### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

Crea nuove informazioni di dati incorporati per un oggetto OLE.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

Crea una nuova istanza di informazioni sui dati incorporati per un oggetto OLE.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| embeddedFileData | byte[] | Dati del file di un oggetto OLE incorporato byte[]. |
| embeddedFileExtension | java.lang.String | Estensione del file per l'attuale oggetto OLE incorporato String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

Restituisce i dati del file di un oggetto OLE incorporato Solo lettura byte[].

**Restituisce:**
byte[]

### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

Restituisce l'estensione del file per l'attuale oggetto OLE incorporato Solo lettura String.

**Restituisce:**
java.lang.String