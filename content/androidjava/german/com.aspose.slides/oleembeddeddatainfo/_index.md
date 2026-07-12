---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eingebettete Dateninfo für OLE-Objekt dar.
type: docs
url: /de/com.aspose.slides/oleembeddeddatainfo/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Stellt eingebettete Dateninfo für OLE-Objekt dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Erstellt neue eingebettete Dateninfo für OLE-Objekt. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Erstellt eine neue Instanz einer eingebetteten Dateninfo für OLE-Objekt. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Gibt die Dateidaten eines eingebetteten OLE-Objekts zurück. Nur lesend byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Gibt die Dateierweiterung für das aktuelle eingebettete OLE-Objekt zurück. Nur lesend String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```


Erstellt neue eingebettete Dateninfo für OLE-Objekt.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```


Erstellt eine neue Instanz einer eingebetteten Dateninfo für OLE-Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| embeddedFileData | byte[] | Dateidaten eines eingebetteten OLE-Objekts byte[]. |
| embeddedFileExtension | java.lang.String | Dateierweiterung für das aktuelle eingebettete OLE-Objekt String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```


Gibt die Dateidaten eines eingebetteten OLE-Objekts zurück. Nur lesend byte[].

**Rückgabewert:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```


Gibt die Dateierweiterung für das aktuelle eingebettete OLE-Objekt zurück. Nur lesend String.

**Rückgabewert:**
java.lang.String