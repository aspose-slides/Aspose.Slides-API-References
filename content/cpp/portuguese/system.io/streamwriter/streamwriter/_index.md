---
title: StreamWriter()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma instância do objeto StreamWriter que grava caracteres no fluxo subjacente especificado usando codificação UTF-8 e um buffer com tamanho padrão de 1024 bytes.
type: docs
weight: 1
url: /pt/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) construtor


Constrói uma instância do objeto [StreamWriter](../) que grava caracteres no fluxo subjacente especificado usando codificação UTF-8 e um buffer com tamanho padrão de 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | O fluxo subjacente onde os caracteres serão gravados |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) construtor


Constrói uma instância do objeto [StreamWriter](../) que grava caracteres no fluxo subjacente especificado usando a codificação especificada e um buffer com tamanho padrão de 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | O fluxo subjacente onde os caracteres serão gravados |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação a ser usada |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) construtor


Constrói uma instância do objeto [StreamWriter](../) que grava caracteres no fluxo subjacente especificado usando a codificação especificada e um buffer do tamanho especificado. Um parâmetro indica se o fluxo subjacente deve ser fechado quando o objeto [StreamWriter](../) for descartado.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | O fluxo subjacente onde os caracteres serão gravados |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação a ser usada |
| buffer_size | int | O tamanho mínimo do buffer em bytes |
| leave_open | **bool** | Especifica se o fluxo subjacente deve permanecer aberto após o objeto [StreamWriter](../) atual ser descartado |

## StreamWriter::StreamWriter(const String\&) construtor


Constrói uma instância do objeto [StreamWriter](../) que grava caracteres no arquivo especificado usando codificação UTF-8 e um buffer com tamanho padrão de 1024 bytes.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo onde os caracteres serão gravados |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) construtor


Constrói uma instância do objeto [StreamWriter](../) que grava caracteres no arquivo especificado usando a codificação especificada e um buffer com tamanho padrão de 1024 bytes. Um parâmetro indica se os dados devem ser acrescentados ao arquivo ou se o arquivo deve ser sobrescrito.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo onde os caracteres serão gravados |
| append | **bool** | Especifica se os dados devem ser acrescentados ao arquivo especificado (true) ou se o arquivo deve ser sobrescrito (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação a ser usada |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) construtor


Constrói uma instância do objeto [StreamWriter](../) que grava caracteres no arquivo especificado usando a codificação especificada e tamanho de buffer. Um parâmetro indica se os dados devem ser acrescentados ao arquivo ou se o arquivo deve ser sobrescrito.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | O caminho do arquivo onde os caracteres serão gravados |
| append | **bool** | Especifica se os dados devem ser acrescentados ao arquivo especificado (true) ou se o arquivo deve ser sobrescrito (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação a ser usada |
| buffer_size | int | O tamanho do buffer a ser usado |

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [Stream](../../stream/)
* Classe [StreamWriter](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [System::IO](../../)
* Library [Aspose.Slides](../../../)