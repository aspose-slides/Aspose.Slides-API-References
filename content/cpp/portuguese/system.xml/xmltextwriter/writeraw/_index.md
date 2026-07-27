---
title: WriteRaw()
second_title: Referência da API do Aspose.Slides para C++
description: Escreve marcação bruta manualmente a partir de um buffer de caracteres.
type: docs
weight: 417
url: /pt/system.xml/xmltextwriter/writeraw/
---
## XmlTextWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) método

Escreve marcação bruta manualmente a partir de um buffer de caracteres.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Array de caracteres contendo o texto a ser escrito. |
| index | **int32_t** | A posição dentro do buffer que indica o início do texto a ser escrito. |
| count | **int32_t** | O número de caracteres a ser escrito. |

## XmlTextWriter::WriteRaw(const String\&) método

Escreve marcação bruta manualmente a partir de uma string.

```cpp
void System::Xml::XmlTextWriter::WriteRaw(const String &data) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) contendo o texto a ser escrito. |

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlTextWriter](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [System::Xml](../../)
* Library [Aspose.Slides](../../../)