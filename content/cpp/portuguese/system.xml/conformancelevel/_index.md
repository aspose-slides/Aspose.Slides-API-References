---
title: ConformanceLevel
second_title: Referência da API Aspose.Slides para C++
description: Especifica a quantidade de verificação de entrada ou saída que os objetos XmlReader e XmlWriter realizam.
type: docs
weight: 625
url: /pt/system.xml/conformancelevel/
---
## ConformanceLevel enum

Especifica a quantidade de verificação de entrada ou saída que os objetos [XmlReader](../xmlreader/) e [XmlWriter](../xmlwriter/) realizam.

```cpp
enum class ConformanceLevel
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Auto | 0 | O objeto [XmlReader](../xmlreader/) ou [XmlWriter](../xmlwriter/) detecta automaticamente se a verificação deve ser feita em nível de documento ou de fragmento, e realiza a verificação apropriada. Se você estiver envolvendo outro objeto [XmlReader](../xmlreader/) ou [XmlWriter](../xmlwriter/), o objeto externo não realiza verificações de conformidade adicionais. A verificação de conformidade fica a cargo do objeto subjacente. |
| Fragment | 1 | Os dados XML são um [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities), conforme definido pela W3C. Esse nível de conformidade representa um documento XML que pode não ter um elemento raiz, mas que é bem formado. Esse nível de verificação garante que o fluxo sendo lido ou gravado pode ser consumido por qualquer processador como um [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | Os dados XML estão em conformidade com as regras para um [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) bem formado, conforme definido pela W3C. Esse nível de verificação garante que o fluxo sendo lido ou gravado pode ser consumido por qualquer processador como um [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## Veja Também

* Namespace [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)