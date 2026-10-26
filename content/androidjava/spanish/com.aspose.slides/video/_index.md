---
title: Video
second_title: Aspose.Slides para Android vía referencia de API Java
description: Representa una imagen incrustada en una presentación.
type: docs
url: /es/com.aspose.slides/video/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Representa una imagen incrustada en una presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getContentType()](#getContentType--) | Devuelve un tipo MIME de un video, codificado en (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Devuelve una copia de los datos de un audio. |
| [getStream()](#getStream--) | Devuelve Stream stream para lectura. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Devuelve un tipo MIME de un video, codificado en (\#getBinaryData.getBinaryData). Solo lectura String.

**Devuelve:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Devuelve una copia de los datos de un audio. En caso de una gran cantidad de datos, considere usar el método \#getStream.getStream para evitar la carga innecesaria de los datos del video en memoria o incluso una OutOfMemoryException. Solo lectura byte[].

**Devuelve:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Devuelve Stream stream para lectura. Use 'using' o cierre el stream después de usar.

**Devuelve:**
java.io.InputStream - Stream para lectura.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent\_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject