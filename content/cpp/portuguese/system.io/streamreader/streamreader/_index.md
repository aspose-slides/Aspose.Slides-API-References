---
title: StreamReader()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma instância do objeto StreamReader que lê caracteres do fluxo subjacente especificado usando codificação UTF-8 e um buffer com tamanho padrão de 1024 bytes.
type: docs
weight: 1
url: /pt/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) construtor


Constrói uma instância do objeto [StreamReader](../) que lê caracteres do fluxo subjacente especificado usando codificação UTF-8 e um buffer com tamanho padrão de 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | O fluxo subjacente do qual ler caracteres |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) construtor


Constrói uma instância do objeto [StreamReader](../) que lê caracteres do fluxo subjacente especificado usando codificação UTF-8 e um buffer com tamanho padrão de 1024 bytes. Um parâmetro especifica se a detecção de marca de ordem de byte deve ser habilitada.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | O fluxo subjacente do qual ler caracteres |
| detectEncodingFromByteOrderMarks | **bool** | True para procurar marcas de ordem de byte no início do fluxo, caso contrário - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) construtor


Constrói uma instância do objeto [StreamReader](../) que lê caracteres do fluxo subjacente especificado usando a codificação especificada e um buffer com tamanho padrão de 1024 bytes.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | O fluxo subjacente do qual ler caracteres |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação a ser usada |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) construtor


Constrói uma instância do objeto [StreamReader](../) que lê caracteres do fluxo subjacente especificado usando a codificação especificada e um buffer com tamanho padrão de 1024 bytes. Um parâmetro especifica se a detecção de marca de ordem de byte deve ser habilitada.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | O fluxo subjacente do qual ler caracteres |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação a ser usada |
| detectEncodingFromByteOrderMarks | **bool** | True para procurar marcas de ordem de byte no início do fluxo, caso contrário - false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) construtor


Constrói uma instância do objeto [StreamReader](../) que lê caracteres do fluxo subjacente especificado usando a codificação especificada e um buffer do tamanho especificado. Um parâmetro especifica se a detecção de marca de ordem de byte deve ser habilitada.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | O fluxo subjacente do qual ler caracteres |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação a ser usada |
| detectEncodingFromByteOrderMarks | **bool** | True para procurar marcas de ordem de byte no início do fluxo, caso contrário - false |
| bufferSize | int | O tamanho mínimo do buffer em bytes |

## StreamReader::StreamReader(const System::String\&) construtor


Constrói uma instância do objeto [StreamReader](../) que lê caracteres do arquivo especificado usando codificação UTF-8 e um buffer com tamanho padrão de 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | O caminho do arquivo do qual ler caracteres |

## StreamReader::StreamReader(const System::String\&, bool) construtor


Constrói uma instância do objeto [StreamReader](../) que lê caracteres do arquivo especificado usando codificação UTF-8 e um buffer com tamanho padrão de 4096 bytes. Um parâmetro especifica se a detecção de marca de ordem de byte deve ser habilitada.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | O caminho do arquivo do qual ler caracteres |
| detectEncodingFromByteOrderMarks | **bool** | True para procurar marcas de ordem de byte no início do arquivo, caso contrário - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) construtor


Constrói uma instância do objeto [StreamReader](../) que lê caracteres do arquivo especificado usando a codificação especificada e um buffer com tamanho padrão de 4096 bytes.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | O caminho do arquivo do qual ler caracteres |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação a ser usada |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) construtor


Constrói uma instância do objeto [StreamReader](../) que lê caracteres do fluxo subjacente especificado usando a codificação especificada e um buffer com tamanho padrão de 4096 bytes. Um parâmetro especifica se a detecção de marca de ordem de byte deve ser habilitada.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | O caminho do arquivo do qual ler caracteres |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação a ser usada |
| detectEncodingFromByteOrderMarks | **bool** | True para procurar marcas de ordem de byte no início do arquivo, caso contrário - false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) construtor


Constrói uma instância do objeto [StreamReader](../) que lê caracteres do arquivo especificado usando a codificação especificada e um buffer do tamanho especificado. Um parâmetro especifica se a detecção de marca de ordem de byte deve ser habilitada.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | O caminho do arquivo do qual ler caracteres |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação a ser usada |
| detectEncodingFromByteOrderMarks | **bool** | True para procurar marcas de ordem de byte no início do arquivo, caso contrário - false |
| bufferSize | int | O tamanho mínimo do buffer em bytes |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [Stream](../../stream/)
* Classe [StreamReader](../)
* Classe [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)