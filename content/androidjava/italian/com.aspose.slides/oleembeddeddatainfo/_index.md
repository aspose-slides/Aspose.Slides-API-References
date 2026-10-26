---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta le informazioni sui dati incorporati per l'oggetto OLE.
type: docs
url: /it/com.aspose.slides/oleembeddeddatainfo/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Rappresenta le informazioni sui dati incorporati per l'oggetto OLE.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Crea una nuova informazione sui dati incorporati per l'oggetto OLE. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Crea una nuova istanza di informazioni sui dati incorporati per l'oggetto OLE. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Restituisce i dati del file di un oggetto OLE incorporato Solo lettura byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Restituisce l'estensione del file per l'attuale oggetto OLE incorporato Solo lettura String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

Crea una nuova informazione sui dati incorporati per l'oggetto OLE.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

Crea una nuova istanza di informazioni sui dati incorporati per l'oggetto OLE.

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