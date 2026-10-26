---
title: WriteSurrogateCharEntity()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, gera e grava a entidade de caractere substituto para o par de caracteres substitutos.
type: docs
weight: 261
url: /pt/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) método

Quando substituído em uma classe derivada, gera e grava a entidade de caractere substituto para o par de caracteres substitutos.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lowChar | char16_t | O substituto baixo. Deve ser um valor entre 0xDC00 e 0xDFFF. |
| highChar | char16_t | O substituto alto. Deve ser um valor entre 0xD800 e 0xDBFF. |

## Veja Também

* Classe [XmlWriter](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)