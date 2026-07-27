---
title: TryParse()
second_title: Referência da API do Aspose.Slides para C++
description: Converte a string especificada que contém a representação em forma de string de um número para o inteiro assinado de 32 bits equivalente.
type: docs
weight: 14
url: /pt/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) método

Converte a string especificada contendo a representação em forma de string de um número para o inteiro assinado de 32 bits equivalente.

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| result | **int32_t**\& | A referência a uma variável inteira assinada de 32 bits onde o resultado da conversão será colocado. |

### Valor de Retorno

True se a conversão for bem-sucedida, caso contrário - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) método

Converte a string especificada contendo a representação em forma de string de um número para o inteiro assinado de 32 bits equivalente usando as informações de formatação fornecidas e o estilo numérico.

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores da enumeração NumberStyles que especifica o estilo permitido da representação em forma de string de um número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formatação da string. |
| result | **int32_t**\& | A referência a uma variável inteira assinada de 32 bits onde o resultado da conversão será colocado. |

### Valor de Retorno

True se a conversão for bem-sucedida, caso contrário - false.

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) método




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) método




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) método




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## Veja Também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int32](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)