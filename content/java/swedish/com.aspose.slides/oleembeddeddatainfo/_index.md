---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides för Java API-referens
description: Representerar inbäddad datainformation för OLE-objekt.
type: docs
url: /sv/com.aspose.slides/oleembeddeddatainfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Representerar inbäddad datainformation för OLE-objekt.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Skapar ny inbäddad datainformation för OLE-objekt. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Skapar en ny instans av en inbäddad datainformation för OLE-objekt. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Returnerar fildata för ett inbäddat OLE-objekt Endast läsning byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Returnerar filändelsen för det aktuella inbäddade OLE-objektet Endast läsning String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```


Skapar ny inbäddad datainformation för OLE-objekt.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```


Skapar en ny instans av en inbäddad datainformation för OLE-objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| embeddedFileData | byte[] | Fildata för ett inbäddat OLE-objekt byte[]. |
| embeddedFileExtension | java.lang.String | Filändelse för det aktuella inbäddade OLE-objektet String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```


Returnerar fildata för ett inbäddat OLE-objekt Endast läsning byte[].

**Returnerar:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```


Returnerar filändelsen för det aktuella inbäddade OLE-objektet Endast läsning String.

**Returnerar:**
java.lang.String