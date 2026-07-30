---
title: XmlOutputMethod
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica il metodo usato per serializzare l'output di XmlWriter.
type: docs
weight: 846
url: /it/system.xml/xmloutputmethod/
---
## XmlOutputMethod enum

Specifica il metodo usato per serializzare l'output [XmlWriter](../xmlwriter/).

```cpp
enum class XmlOutputMethod
```

### Valori

| Name | Value | Description |
| --- | --- | --- |
| Xml | 0 | Serializza secondo le regole XML 1.0. |
| Html | 1 | Serializza secondo le regole HTML specificate da XSLT. |
| Text | 2 | Serializza solo blocchi di testo. |
| AutoDetect | 3 | Utilizza le regole XSLT per scegliere tra i metodi di output [XmlOutputMethod::Xml](./) e [XmlOutputMethod::Html](./) a runtime. |

## Vedi anche

* Namespace [System::Xml](../)
* Libreria [Aspose.Slides](../../)