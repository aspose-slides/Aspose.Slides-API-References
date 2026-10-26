---
title: ToXmlString()
second_title: Referência da API Aspose.Slides para C++
description: Exporta todos os parâmetros no formato XML. Não implementado.
type: docs
weight: 157
url: /pt/system.security.cryptography/ecdsabotan/toxmlstring/
---
## ECDsaBotan::ToXmlString(bool) método

Exporta todos os parâmetros no formato XML. Não implementado.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(bool include_private_parameters) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| include_private_parameters | **bool** | True para exportar tanto parâmetros privados quanto públicos, false para exportar apenas parâmetros públicos. |

### Valor de Retorno

XML-encoded parameters.

## ECDsaBotan::ToXmlString(ECKeyXmlFormat) método

Exporta todos os parâmetros no formato XML.

```cpp
String System::Security::Cryptography::ECDsaBotan::ToXmlString(ECKeyXmlFormat format)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | [ECKeyXmlFormat](../../eckeyxmlformat/) | Formato da string XML resultante. |

### Valor de Retorno

XML-encoded parameters.

## Ver Também

* Enum [ECKeyXmlFormat](../../eckeyxmlformat/)
* Classe [String](../../../system/string/)
* Classe [ECDsaBotan](../)
* Espaço de nomes [System::Security::Cryptography](../../)
* Biblioteca [Aspose.Slides](../../../)