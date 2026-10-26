---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: Representa un video incrustado en una presentación.
type: docs
url: /es/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Representa un video incrustado en una presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getContentType()](#getContentType--) | Devuelve un tipo MIME de un video, codificado en (\#getBinaryData.getBinaryData). Solo lectura String. |
| [getBinaryData()](#getBinaryData--) | Devuelve una copia de los datos de un audio. |
| [getStream()](#getStream--) | Devuelve un Stream para leer. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Devuelve un tipo MIME de un video, codificado en (\#getBinaryData.getBinaryData). Solo lectura String.

**Devuelve:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Devuelve una copia de los datos de un audio. En caso de una gran cantidad de datos, considere usar el método \#getStream.getStream para evitar la carga innecesaria de los datos del video en memoria o incluso una OutOfMemoryException. Solo lectura byte[].

**Devuelve:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Devuelve un Stream para leer. Use 'using' o cierre el stream después de usarlo.

**Devuelve:**
java.io.InputStream - Stream para leer.