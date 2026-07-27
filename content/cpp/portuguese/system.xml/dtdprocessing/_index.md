---
title: DtdProcessing
second_title: Referência da API Aspose.Slides para C++
description: Especifica as opções para o processamento de DTDs. A enumeração DtdProcessing é usada pela classe XmlReaderSettings.
type: docs
weight: 638
url: /pt/system.xml/dtdprocessing/
---
## DtdProcessing enum

Especifica as opções para o processamento de DTDs. A enumeração DtdProcessing é usada pela classe [XmlReaderSettings](../xmlreadersettings/).

```cpp
enum class DtdProcessing
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Prohibit | 0 | Especifica que, quando um DTD é encontrado, uma XmlException é lançada com uma mensagem que indica que DTDs são proibidos. Este é o comportamento padrão. |
| Ignore | 1 | Faz com que o elemento DOCTYPE seja ignorado. Nenhum processamento de DTD ocorre, e o DTD/DOCTYPE é perdido na saída. |
| Parse | 2 | Usado para analisar DTDs. |

## Veja Também

* Espaço de nomes [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)