---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje informace o vložených datech pro OLE objekt.
type: docs
url: /cs/com.aspose.slides/oleembeddeddatainfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Představuje informace o vložených datech pro OLE objekt.

## Konstruktory

| Constructor | Description |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Vytvoří nové informace o vložených datech pro OLE objekt. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Vytvoří novou instanci informací o vložených datech pro OLE objekt. |

## Metody

| Method | Description |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Vrátí data souboru vloženého OLE objektu Pouze ke čtení byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Vrátí příponu souboru pro aktuální vložený OLE objekt Pouze ke čtení String. |

### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

Vytvoří nové informace o vložených datech pro OLE objekt.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

Vytvoří novou instanci informací o vložených datech pro OLE objekt.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| embeddedFileData | byte[] | Data souboru vloženého OLE objektu byte[]. |
| embeddedFileExtension | java.lang.String | Přípona souboru pro aktuální vložený OLE objekt String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

Vrátí data souboru vloženého OLE objektu Pouze ke čtení byte[].

**Vrací:**
byte[]

### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

Vrátí příponu souboru pro aktuální vložený OLE objekt Pouze ke čtení String.

**Vrací:**
java.lang.String