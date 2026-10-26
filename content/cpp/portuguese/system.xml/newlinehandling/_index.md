---
title: NewLineHandling
second_title: Referência da API Aspose.Slides for C++
description: Especifica como lidar com quebras de linha.
type: docs
weight: 690
url: /pt/system.xml/newlinehandling/
---
## NewLineHandling enum

Especifica como lidar com quebras de linha.

```cpp
enum class NewLineHandling
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Replace | 0 | Os caracteres de nova linha são substituídos para corresponder ao caractere especificado no valor [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/). |
| Entitize | 1 | Os caracteres de nova linha são convertidos em entidades. Essa configuração preserva todos os caracteres quando a saída é lida por um [XmlReader](../xmlreader/) de normalização. |
| None | 2 | Os caracteres de nova linha permanecem inalterados. A saída é a mesma que a entrada. |

## Veja Também

* Espaço de nomes [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)