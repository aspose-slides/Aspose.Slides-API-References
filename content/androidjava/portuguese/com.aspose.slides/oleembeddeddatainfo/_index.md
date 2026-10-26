---
title: OleEmbeddedDataInfo
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa informações de dados incorporados para objeto OLE.
type: docs
url: /pt/com.aspose.slides/oleembeddeddatainfo/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
```
public class OleEmbeddedDataInfo implements IOleEmbeddedDataInfo
```

Representa informações de dados incorporados para objeto OLE.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [OleEmbeddedDataInfo()](#OleEmbeddedDataInfo--) | Cria uma nova informação de dados incorporados para objeto OLE. |
| [OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)](#OleEmbeddedDataInfo-byte---java.lang.String-) | Cria uma nova instância de informação de dados incorporados para objeto OLE. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getEmbeddedFileData()](#getEmbeddedFileData--) | Retorna os dados do arquivo de um objeto OLE incorporado Somente leitura byte[]. |
| [getEmbeddedFileExtension()](#getEmbeddedFileExtension--) | Retorna a extensão do arquivo para o objeto OLE incorporado atual Somente leitura String. |
### OleEmbeddedDataInfo() {#OleEmbeddedDataInfo--}
```
public OleEmbeddedDataInfo()
```


Cria uma nova informação de dados incorporados para objeto OLE.

### OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension) {#OleEmbeddedDataInfo-byte---java.lang.String-}
```
public OleEmbeddedDataInfo(byte[] embeddedFileData, String embeddedFileExtension)
```


Cria uma nova instância de informação de dados incorporados para objeto OLE.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| embeddedFileData | byte[] | Dados do arquivo de um objeto OLE incorporado byte[]. |
| embeddedFileExtension | java.lang.String | Extensão do arquivo para o objeto OLE incorporado atual String. |

### getEmbeddedFileData() {#getEmbeddedFileData--}
```
public final byte[] getEmbeddedFileData()
```


Retorna os dados do arquivo de um objeto OLE incorporado Somente leitura byte[].

**Retorno:**
byte[]
### getEmbeddedFileExtension() {#getEmbeddedFileExtension--}
```
public final String getEmbeddedFileExtension()
```


Retorna a extensão do arquivo para o objeto OLE incorporado atual Somente leitura String.

**Retorno:**
java.lang.String