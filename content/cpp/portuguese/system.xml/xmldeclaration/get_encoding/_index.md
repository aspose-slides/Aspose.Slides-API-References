---
title: get_Encoding()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o nível de codificação do documento XML.
type: docs
weight: 14
url: /pt/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() método

Retorna o nível de codificação do documento XML.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### Valor de Retorno

O nome de codificação de caracteres válido.

## Observações

Os nomes de codificação de caracteres mais suportados para XML são os seguintes:

| Categoria | Nomes de Codificação |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (where "n" is a digit from 1 to 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

Este valor é opcional. Se nenhum valor for definido, este método retorna [String::Empty](../../../system/string/empty/). Se um atributo de codificação não for incluído, assume-se a codificação UTF-8 quando o documento é escrito ou salvo.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlDeclaration](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)