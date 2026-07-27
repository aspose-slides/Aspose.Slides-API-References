---
title: WriteRaw()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, grava marcação bruta manualmente a partir de um buffer de caracteres.
type: docs
weight: 287
url: /pt/system.xml/xmlwriter/writeraw/
---
## XmlWriter::WriteRaw(ArrayPtr\<char16_t\>, int32_t, int32_t) método

Quando sobrescrito em uma classe derivada, grava marcação bruta manualmente a partir de um buffer de caracteres.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Array de caracteres contendo o texto a ser gravado. |
| index | **int32_t** | A posição dentro do buffer que indica o início do texto a ser gravado. |
| count | **int32_t** | O número de caracteres a serem gravados. |

## XmlWriter::WriteRaw(const String\&) método

Quando sobrescrito em uma classe derivada, grava marcação bruta manualmente a partir de uma string.

```cpp
virtual void System::Xml::XmlWriter::WriteRaw(const String &data)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| data | const [String](../../../system/string/)\& | [String](../../../system/string/) contendo o texto a ser gravado. |

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlWriter](../)
* Classe [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)