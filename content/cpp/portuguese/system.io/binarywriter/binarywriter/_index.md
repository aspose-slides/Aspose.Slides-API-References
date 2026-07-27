---
title: BinaryWriter()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma instância da classe BinaryWriter que grava dados no stream especificado usando a codificação especificada.
type: docs
weight: 1
url: /pt/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) constructor


Constrói uma instância da classe [BinaryWriter](../) que grava dados no stream especificado usando a codificação especificada.

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | O stream de saída |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | A codificação a ser usada |
| leaveopen | **bool** | Especifica se o stream **stream** deve permanecer aberto (true) após o objeto atual ser descartado ou não (false) |

## Veja Também

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [BinaryWriter](../)
* Espaço de nomes [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)