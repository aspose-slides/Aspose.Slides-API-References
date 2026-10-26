---
title: Audio
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un archivo de audio incrustado.
type: docs
url: /es/com.aspose.slides/audio/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Representa un archivo de audio incrustado.
## Métodos

| Método | Descripción |
| --- | --- |
| [getContentType()](#getContentType--) | Devuelve un tipo MIME de un audio, codificado en (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Devuelve un tipo MIME de un audio, codificado en (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Devuelve la copia de los datos de un audio. |
| [getStream()](#getStream--) | Devuelve Stream stream para lectura. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Devuelve un tipo MIME de un audio, codificado en (\#getBinaryData.getBinaryData). Solo lectura String.

**Devuelve:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```


Devuelve un tipo MIME de un audio, codificado en (\#getBinaryData.getBinaryData). Solo lectura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Devuelve la copia de los datos de un audio. En caso de una gran cantidad de datos, considere usar el método \#getStream.getStream para evitar la carga innecesaria de los datos del audio en memoria o incluso una OutOfMemoryException. Solo lectura byte[].

**Devuelve:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Devuelve Stream stream para lectura. Utilice 'using' o cierre el stream después de usarlo.

**Devuelve:**
java.io.InputStream - Stream para lectura.