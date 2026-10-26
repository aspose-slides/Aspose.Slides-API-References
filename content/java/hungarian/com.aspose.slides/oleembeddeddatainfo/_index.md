---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides Java API referencia
description: Az OLE objektum beágyazott adatinformációját reprezentálja.
type: docs
url: /hu/com.aspose.slides/oleembeddeddatainfo/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Az OLE objektum beágyazott adatinformációját reprezentálja.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Új beágyazott adatinformációt hoz létre OLE objektumhoz. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Új példányt hoz létre egy beágyazott adatinformációból OLE objektumhoz. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Visszaadja a beágyazott OLE objektum fájladatait. Csak olvasható byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Visszaadja a jelenlegi beágyazott OLE objektum fájlkiterjesztését. Csak olvasható String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

Új beágyazott adatinformációt hoz létre OLE objektumhoz.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

Új példányt hoz létre egy beágyazott adatinformációból OLE objektumhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| embeddedFileData | byte[] | Beágyazott OLE objektum fájladatai byte[]. |
| embeddedFileExtension | java.lang.String | A jelenlegi beágyazott OLE objektum fájlkiterjesztése String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

Visszaadja a beágyazott OLE objektum fájladatait. Csak olvasható byte[].

**Visszatérési érték:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

Visszaadja a jelenlegi beágyazott OLE objektum fájlkiterjesztését. Csak olvasható String.

**Visszatérési érték:**
java.lang.String