---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an embedded audio file.
type: docs
url: /es/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Represents an embedded audio file.
## Métodos

| Método | Descripción |
| --- | --- |
| [getContentType()](#getContentType--) | Returns a MIME type of an audio, encoded in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Returns the copy of an audio's data. |
| [getStream()](#getStream--) | Returns Stream stream for reading. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Devuelve un tipo MIME de un audio, codificado en (\#getBinaryData.getBinaryData). String de solo lectura.

**Devuelve:**  
java.lang.String

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Devuelve una copia de los datos del audio. En caso de una gran cantidad de datos, considere el uso del método \#getStream.getStream para evitar la carga innecesaria de los datos del audio en la memoria o incluso una OutOfMemoryException. byte[] de solo lectura.

**Devuelve:**  
byte[]

### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Devuelve un Stream para lectura. Use 'using' o cierre el flujo después de usarlo.

**Devuelve:**  
java.io.InputStream - Stream para lectura.