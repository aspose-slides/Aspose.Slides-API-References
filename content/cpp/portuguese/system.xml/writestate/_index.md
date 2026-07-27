---
title: WriteState
second_title: Referência da API Aspose.Slides for C++
description: Especifica o estado do XmlWriter.
type: docs
weight: 755
url: /pt/system.xml/writestate/
---
## WriteState enum

Especifica o estado do [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Start | 0 | Indica que o método XmlWriter::Write ainda não foi chamado. |
| Prolog | 1 | Indica que o prólogo está sendo escrito. |
| Element | 2 | Indica que a tag de início de elemento está sendo escrita. |
| Attribute | 3 | Indica que um valor de atributo está sendo escrito. |
| Content | 4 | Indica que o conteúdo do elemento está sendo escrito. |
| Closed | 5 | Indica que o método [XmlWriter::Close](../xmlwriter/close/) foi chamado. |
| Error | 6 | Uma exceção foi lançada, o que deixou o [XmlWriter](../xmlwriter/) em um estado inválido. Você pode chamar o método [XmlWriter::Close](../xmlwriter/close/) para colocar o [XmlWriter](../xmlwriter/) no estado [WriteState::Closed](./). Qualquer outra chamada ao método [XmlWriter](../xmlwriter/) resulta em uma InvalidOperationException. |

## Veja também

* Namespace [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)