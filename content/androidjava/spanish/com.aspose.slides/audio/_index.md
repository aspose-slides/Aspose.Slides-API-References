---
title: Audio
second_title: Aspose.Slides para Android a través de la Referencia de la API Java
description: Representa un archivo de audio incrustado.
type: docs
url: /es/com.aspose.slides/audio/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Representa un archivo de audio incrustado.
## Métodos

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Devuelve un tipo MIME de un audio, codificado en (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Devuelve un tipo MIME de un audio, codificado en (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Devuelve una copia de los datos de un audio. |
| [getStream()](#getStream--) | Devuelve un Stream para leer. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Devuelve un tipo MIME de un audio, codificado en (\#getBinaryData.getBinaryData). String de solo lectura.

**Devuelve:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Devuelve un tipo MIME de un audio, codificado en (\#getBinaryData.getBinaryData). String de solo lectura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Devuelve una copia de los datos de un audio. En caso de una gran cantidad de datos, considere usar el método \#getStream.getStream para evitar la carga innecesaria de los datos del audio en memoria o incluso una OutOfMemoryException. byte[] de solo lectura.

**Devuelve:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Devuelve un Stream para leer. Use 'using' o cierre el stream después de usarlo.

**Devuelve:**
java.io.InputStream - Stream para lectura.