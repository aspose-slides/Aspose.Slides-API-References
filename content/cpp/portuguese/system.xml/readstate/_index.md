---
title: ReadState
second_title: Referência da API Aspose.Slides para C++
description: Especifica o estado do leitor.
type: docs
weight: 703
url: /pt/system.xml/readstate/
---
## ReadState enum

Especifica o estado do leitor.

```cpp
enum class ReadState
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Initial | 0 | O método [XmlReader::Read](../xmlreader/read/) não foi chamado. |
| Interactive | 1 | O método [XmlReader::Read](../xmlreader/read/) foi chamado. Métodos adicionais podem ser chamados no leitor. |
| Error | 2 | Ocorreu um erro que impede a continuação da operação de leitura. |
| EndOfFile | 3 | O final do arquivo foi alcançado com sucesso. |
| Closed | 4 | O método [XmlReader::Close](../xmlreader/close/) foi chamado. |

## Veja Também

* Namespace [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)