---
title: WriteSurrogateCharEntity()
second_title: Referência da API Aspose.Slides para C++
description: Gera e grava a entidade de caractere substituto para o par de caracteres substitutos.
type: docs
weight: 391
url: /pt/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) método

Gera e grava a entidade de caractere substituto para o par de caracteres substitutos.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lowChar | char16_t | O substituto baixo. Deve ser um valor entre **0xDC00** e **0xDFFF**. |
| highChar | char16_t | O substituto alto. Deve ser um valor entre **0xD800** e **0xDBFF**. |

## Veja Também

* Classe [XmlTextWriter](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)