---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Representa um vídeo incorporado em uma apresentação.
type: docs
url: /pt/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Representa um vídeo incorporado em uma apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getContentType()](#getContentType--) | Retorna um tipo MIME de um vídeo, codificado em (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Retorna a cópia dos dados de um áudio. |
| [getStream()](#getStream--) | Retorna um Stream para leitura. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Retorna um tipo MIME de um vídeo, codificado em (\#getBinaryData.getBinaryData). Somente leitura String.

**Retorna:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Retorna a cópia dos dados de um áudio. Em caso de grande quantidade de dados, considere usar o método \#getStream.getStream para evitar o carregamento desnecessário dos dados do vídeo na memória ou até mesmo uma OutOfMemoryException. Somente leitura byte[].

**Retorna:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Retorna um Stream para leitura. Use 'using' ou feche o stream após o uso.

**Retorna:**
java.io.InputStream - Stream para leitura.