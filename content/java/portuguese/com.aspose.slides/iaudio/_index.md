---
title: IAudio
second_title: Aspose.Slides for Java Referência da API
description: Representa um arquivo de áudio incorporado.
type: docs
url: /pt/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Representa um arquivo de áudio incorporado.
## Métodos

| Método | Descrição |
| --- | --- |
| [getContentType()](#getContentType--) | Retorna um tipo MIME de um áudio, codificado em (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Retorna a cópia dos dados de um áudio. |
| [getStream()](#getStream--) | Retorna Stream stream para leitura. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Retorna um tipo MIME de um áudio, codificado em (\#getBinaryData.getBinaryData). Somente leitura String.

**Retorna:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Retorna a cópia dos dados de um áudio. No caso de grande quantidade de dados, considere usar o método \#getStream.getStream para evitar o carregamento desnecessário dos dados do áudio na memória ou até mesmo OutOfMemoryException. Somente leitura byte[].

**Retorna:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Retorna Stream stream para leitura. Use 'using' ou feche o stream após o uso.

**Retorna:**
java.io.InputStream - Stream para leitura.