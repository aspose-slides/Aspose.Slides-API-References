---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides voor Java API Referentie
description: Geeft embedded data info voor een OLE-object weer.
type: docs
url: /nl/com.aspose.slides/oleembeddeddatainfo/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Geeft embedded data info voor een OLE-object weer.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Maakt een nieuw embedded data info voor OLE-object aan. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Maakt een nieuw exemplaar van een embedded data info voor OLE-object aan. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Retourneert de bestandsgegevens van een embedded OLE-object Alleen-lezen byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Retourneert de bestandsextensie voor het huidige embedded OLE-object Alleen-lezen String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

Maakt een nieuw embedded data info voor OLE-object aan.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

Maakt een nieuw exemplaar van een embedded data info voor OLE-object aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| embeddedFileData | byte[] | Bestandsgegevens van een embedded OLE-object byte[]. |
| embeddedFileExtension | java.lang.String | Bestandsextensie voor het huidige embedded OLE-object String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

Retourneert de bestandsgegevens van een embedded OLE-object Alleen-lezen byte[].

**Retour:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

Retourneert de bestandsextensie voor het huidige embedded OLE-object Alleen-lezen String.

**Retour:**
java.lang.String