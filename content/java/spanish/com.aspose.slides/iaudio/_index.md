---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Represents an embedded audio file.
type: docs
url: /es/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Representa un archivo de audio incrustado.
## Métodos

| Método | Descripción |
| --- | --- |
| [getContentType()](#getContentType--) | Devuelve un tipo MIME de un audio, codificado en (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Devuelve una copia de los datos de un audio. |
| [getStream()](#getStream--) | Devuelve Stream stream para lectura. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Devuelve un tipo MIME de un audio, codificado en (\#getBinaryData.getBinaryData). Solo lectura String.

**Devuelve:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Devuelve una copia de los datos de un audio. En caso de una gran cantidad de datos, considere usar el método \#getStream.getStream para evitar la carga innecesaria de los datos del audio en memoria o incluso OutOfMemoryException. Solo lectura byte[].

**Devuelve:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Devuelve Stream stream para lectura. Use 'using' o cierre el stream después de usarlo.

**Devuelve:**
java.io.InputStream - Stream para lectura.