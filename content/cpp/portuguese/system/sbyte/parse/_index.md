---
title: Parse()
second_title: Aspose.Slides for C++ Referência da API
description: Converte a string especificada que contém a representação textual de um número para o inteiro assinado de 8 bits equivalente.
type: docs
weight: 1
url: /pt/system/sbyte/parse/
---
## SByte::Parse(const String\&) método

Converte a string especificada que contém a representação textual de um número para o inteiro assinado de 8 bits equivalente.

```cpp
static int8_t System::SByte::Parse(const String &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |

### Valor de Retorno

O inteiro assinado de 8 bits igual ao número representado pela string especificada.

## SByte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Converte a string especificada que contém a representação textual de um número para o inteiro assinado de 8 bits equivalente usando as informações de formatação fornecidas.

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formatação da string. |

### Valor de Retorno

O inteiro assinado de 8 bits igual ao número representado pela string especificada.

## SByte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, std::nullptr_t) método




```cpp
static int8_t System::SByte::Parse(const String &value, std::nullptr_t)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

Converte a string especificada que contém a representação textual de um número para o inteiro assinado de 8 bits equivalente usando as informações de formatação e o estilo numérico fornecidos.

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores da enumeração NumberStyles que especifica o estilo permitido da representação textual de um número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formatação da string. |

### Valor de Retorno

O inteiro assinado de 8 bits igual ao número representado pela string especificada.

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) método




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Veja Também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)