---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt ingesloten gegevensinfo voor een OLE-object voor.
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

Representatief voor ingesloten gegevensinfo voor een OLE-object.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Maakt een nieuwe ingesloten gegevensinfo voor OLE-object aan. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Maakt een nieuw exemplaar van een ingesloten gegevensinfo voor OLE-object. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Retourneert de bestandsgegevens van een ingesloten OLE-object. Alleen-lezen byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Retourneert de bestandsextensie van het huidige ingesloten OLE-object. Alleen-lezen String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```


Maakt een nieuwe ingesloten gegevensinfo voor OLE-object aan.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```


Maakt een nieuw exemplaar van een ingesloten gegevensinfo voor OLE-object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| embeddedFileData | byte[] | Bestandsgegevens van een ingesloten OLE-object byte[]. |
| embeddedFileExtension | java.lang.String | Bestandsextensie voor het huidige ingesloten OLE-object String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```


Retourneert de bestandsgegevens van een ingesloten OLE-object. Alleen-lezen byte[].

**Retour:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```


Retourneert de bestandsextensie van het huidige ingesloten OLE-object. Alleen-lezen String.

**Retour:**
java.lang.String