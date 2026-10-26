---
title: Audio
second_title: Referência da API do Aspose.Slides para Java
description: Representa um arquivo de áudio incorporado.
type: docs
url: /pt/com.aspose.slides/audio/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Representa um arquivo de áudio incorporado.
## Métodos

| Método | Descrição |
| --- | --- |
| [getContentType()](#getContentType--) | Retorna um tipo MIME de um áudio, codificado em (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Retorna um tipo MIME de um áudio, codificado em (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Retorna a cópia dos dados de um áudio. |
| [getStream()](#getStream--) | Retorna Stream stream para leitura. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Retorna um tipo MIME de um áudio, codificado em (\#getBinaryData.getBinaryData). Somente leitura String.

**Retorna:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Retorna um tipo MIME de um áudio, codificado em (\#getBinaryData.getBinaryData). Somente leitura String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Retorna a cópia dos dados de um áudio. No caso de grande quantidade de dados, considere usar o método \#getStream.getStream para evitar o carregamento desnecessário dos dados do áudio na memória ou mesmo OutOfMemoryException. Somente leitura byte[].

**Retorna:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Retorna Stream stream para leitura. Use 'using' ou feche o stream após o uso.

**Retorna:**
java.io.InputStream - Stream para leitura.