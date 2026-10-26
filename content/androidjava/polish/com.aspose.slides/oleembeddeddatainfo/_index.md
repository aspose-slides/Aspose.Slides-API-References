---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Reprezentuje informacje o osadzonych danych dla obiektu OLE.
type: docs
url: /pl/com.aspose.slides/oleembeddeddatainfo/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Reprezentuje informacje o osadzonych danych dla obiektu OLE.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Creates new embedded data info for OLE object. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Tworzy nową instancję informacji o osadzonych danych dla obiektu OLE. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Zwraca dane pliku osadzonego obiektu OLE. Tylko do odczytu byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Zwraca rozszerzenie pliku dla bieżącego osadzonego obiektu OLE. Tylko do odczytu String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```

Tworzy nowe informacje o osadzonych danych dla obiektu OLE.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```

Tworzy nową instancję informacji o osadzonych danych dla obiektu OLE.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| embeddedFileData | byte[] | Dane pliku osadzonego obiektu OLE byte[]. |
| embeddedFileExtension | java.lang.String | Rozszerzenie pliku dla bieżącego osadzonego obiektu OLE String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```

Zwraca dane pliku osadzonego obiektu OLE. Tylko do odczytu byte[].

**Zwraca:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```

Zwraca rozszerzenie pliku dla bieżącego osadzonego obiektu OLE. Tylko do odczytu String.

**Zwraca:**
java.lang.String