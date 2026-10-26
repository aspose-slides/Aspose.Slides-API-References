---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides pro Java - referenční příručka API
description: Reprezentuje informaci o vložených datech pro objekt OLE.
type: docs
url: /cs/com.aspose.slides/oleembeddeddatainfo/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Reprezentuje informaci o vložených datech pro objekt OLE.

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Vytvoří novou informaci o vložených datech pro objekt OLE. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Vytvoří novou instanci informace o vložených datech pro objekt OLE. |

## Metody

| Metoda | Popis |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Vrací data souboru vloženého objektu OLE. Pouze pro čtení byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Vrací příponu souboru pro aktuální vložený objekt OLE. Pouze pro čtení String. |

### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

Vytvoří novou informaci o vložených datech pro objekt OLE.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

Vytvoří novou instanci informace o vložených datech pro objekt OLE.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| embeddedFileData | byte[] | Data souboru vloženého objektu OLE byte[]. |
| embeddedFileExtension | java.lang.String | Přípona souboru pro aktuální vložený objekt OLE String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

Vrací data souboru vloženého objektu OLE. Pouze pro čtení byte[].

**Vrací:**
byte[]

### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

Vrací příponu souboru pro aktuální vložený objekt OLE. Pouze pro čtení String.

**Vrací:**
java.lang.String