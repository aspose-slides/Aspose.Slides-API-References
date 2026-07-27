---
title: BinaryReader()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma instância da classe BinaryReader que lê dados do fluxo especificado usando codificação UTF-8.
type: docs
weight: 1
url: /pt/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) constructor

Constrói uma instância da classe [BinaryReader](../) que lê dados do fluxo especificado usando codificação UTF-8.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | O fluxo de entrada |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor

Constrói uma instância da classe [BinaryReader](../) que lê dados do fluxo especificado usando a codificação especificada.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | O fluxo de entrada |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | A codificação a ser usada |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) constructor

Constrói uma instância da classe [BinaryReader](../) que lê dados do fluxo especificado usando a codificação especificada.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | O fluxo de entrada |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | A codificação a ser usada |
| leaveOpen | **bool** | Especifica se o fluxo **input** deve permanecer aberto (true) após o objeto atual ter sido descartado ou não (false) |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../stream/)
* Classe [BinaryReader](../)
* Classe [Encoding](../../../system.text/encoding/)
* Espaço de nomes [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)