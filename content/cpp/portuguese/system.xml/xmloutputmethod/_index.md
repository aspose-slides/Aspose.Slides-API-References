---
title: XmlOutputMethod
second_title: Referência da API Aspose.Slides para C++
description: Especifica o método usado para serializar a saída XmlWriter.
type: docs
weight: 846
url: /pt/system.xml/xmloutputmethod/
---
## XmlOutputMethod enum


Especifica o método usado para serializar a saída [XmlWriter](../xmlwriter/).

```cpp
enum class XmlOutputMethod
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Xml | 0 | Serializa de acordo com as regras XML 1.0. |
| Html | 1 | Serializa de acordo com as regras HTML especificadas por XSLT. |
| Text | 2 | Serializa apenas blocos de texto. |
| AutoDetect | 3 | Usa as regras XSLT para escolher entre os métodos de saída [XmlOutputMethod::Xml](./) e [XmlOutputMethod::Html](./) em tempo de execução. |

## Ver também

* Namespace [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)