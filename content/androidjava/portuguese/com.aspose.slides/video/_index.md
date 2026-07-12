---
title: Video
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma imagem incorporada em uma apresentação.
type: docs
url: /pt/com.aspose.slides/video/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Representa uma imagem incorporada em uma apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getContentType()](#getContentType--) | Retorna um tipo MIME de um vídeo, codificado em (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Retorna a cópia dos dados de um áudio. |
| [getStream()](#getStream--) | Retorna fluxo Stream para leitura. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Retorna um tipo MIME de um vídeo, codificado em (\#getBinaryData.getBinaryData). Somente leitura String.

**Retorna:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Retorna a cópia dos dados de um áudio. No caso de grande quantidade de dados, considere usar o método \#getStream.getStream para evitar o carregamento desnecessário dos dados do vídeo na memória ou até mesmo OutOfMemoryException. Somente leitura byte[].

**Retorna:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Retorna fluxo Stream para leitura. Use 'using' ou feche o fluxo após o uso.

**Retorna:**
java.io.InputStream - Stream for reading.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retorna objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject