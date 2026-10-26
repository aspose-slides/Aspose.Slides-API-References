---
title: Video
second_title: Referencia de API de Aspose.Slides para Java
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
| [getBinaryData()](#getBinaryData--) | Devuelve la copia de los datos de un audio. |
| [getStream()](#getStream--) | Devuelve un Stream para lectura. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Devuelve un tipo MIME de un video, codificado en (\#getBinaryData.getBinaryData). String de solo lectura.

**Devuelve:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Devuelve la copia de los datos de un audio. En caso de una gran cantidad de datos, considere usar el método \#getStream.getStream para evitar la carga innecesaria de los datos del video en memoria o incluso una OutOfMemoryException. byte[] de solo lectura.

**Devuelve:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Devuelve un Stream para lectura. Use 'using' o cierre el stream después de usarlo.

**Devuelve:**
java.io.InputStream - Stream para lectura.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve un objeto Parent_Immediate. IDOMObject de solo lectura.

**Devuelve:**
com.aspose.slides.IDOMObject