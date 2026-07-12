---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides para Android mediante referencia de API Java
description: Representa información de datos incrustada para un objeto OLE.
type: docs
url: /es/com.aspose.slides/oleembeddeddatainfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Representa información de datos incrustada para un objeto OLE.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Crea una nueva información de datos incrustada para un objeto OLE. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Crea una nueva instancia de una información de datos incrustada para un objeto OLE. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Devuelve los datos del archivo de un objeto OLE incrustado. Solo lectura byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Devuelve la extensión del archivo para el objeto OLE incrustado actual. Solo lectura String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```


Crea una nueva información de datos incrustada para un objeto OLE.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```


Crea una nueva instancia de una información de datos incrustada para un objeto OLE.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| embeddedFileData | byte[] | Datos del archivo de un objeto OLE incrustado byte[]. |
| embeddedFileExtension | java.lang.String | Extensión del archivo para el objeto OLE incrustado actual String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```


Devuelve los datos del archivo de un objeto OLE incrustado. Solo lectura byte[].

**Devuelve:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```


Devuelve la extensión del archivo para el objeto OLE incrustado actual. Solo lectura String.

**Devuelve:**
java.lang.String