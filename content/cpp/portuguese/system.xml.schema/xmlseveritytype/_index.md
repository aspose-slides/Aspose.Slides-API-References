---
title: XmlSeverityType
second_title: Referência da API Aspose.Slides para C++
description: Representa a gravidade do evento de validação.
type: docs
weight: 1080
url: /pt/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enum

Representa a gravidade do evento de validação.

```cpp
enum class XmlSeverityType
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Error | 0 | Indica que ocorreu um erro de validação ao validar o documento de instância. Isso se aplica a definições de tipo de documento (DTDs) e a esquemas de linguagem de definição XML [Schema](../) (XSD). As restrições de validade do World Wide [Web](../../system.web/) Consortium (W3C) são consideradas erros. Se nenhum manipulador de evento de validação for criado, os erros geram uma exceção. |
| Warning | 1 | Indica que ocorreu um evento de validação que não é um erro. Um aviso geralmente é emitido quando não há DTD, ou XML [Schema](../) para validar um determinado elemento ou atributo. Ao contrário dos erros, avisos não geram uma exceção se não houver manipulador de evento de validação. |

## Veja Também

* Espaço de nomes [System::Xml::Schema](../)
* Biblioteca [Aspose.Slides](../../)