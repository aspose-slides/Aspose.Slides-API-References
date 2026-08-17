---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: Representa um vídeo incorporado em uma apresentação.
type: docs
url: /pt/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Representa um vídeo incorporado em uma apresentação.
## Métodos

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | Retorna um tipo MIME de um vídeo, codificado em (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Retorna uma cópia dos dados de um áudio. |
| [getStream()](#getStream--) | Retorna um fluxo Stream para leitura. |
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

Retorna uma cópia dos dados de um áudio. No caso de grande quantidade de dados, considere usar o método \#getStream.getStream para evitar o carregamento desnecessário dos dados do vídeo na memória ou até mesmo OutOfMemoryException. Somente leitura byte[].

**Retorna:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Retorna um fluxo Stream para leitura. Use 'using' ou feche o fluxo após o uso.

**Retorna:**
java.io.InputStream - Fluxo para leitura.