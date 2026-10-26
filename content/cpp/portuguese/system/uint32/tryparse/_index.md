---
title: TryParse()
second_title: Referência da API Aspose.Slides para C++
description: Converte a string especificada que contém a representação textual de um número para o inteiro sem sinal de 32 bits equivalente.
type: docs
weight: 14
url: /pt/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) método

Converte a string especificada que contém a representação textual de um número para o inteiro sem sinal de 32 bits equivalente.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| result | **uint32_t**\& | A referência a uma variável inteira sem sinal de 32 bits onde o resultado da conversão é colocado. |

### Valor de Retorno

True se a conversão for bem-sucedida, caso contrário - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) método

Converte a string especificada que contém a representação textual de um número para o inteiro sem sinal de 32 bits equivalente usando as informações de formatação e o estilo numérico fornecidos.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores da enumeração NumberStyles que especifica o estilo permitido da representação textual de um número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formatação da string. |
| result | **uint32_t**\& | A referência a uma variável inteira sem sinal de 32 bits onde o resultado da conversão é colocado. |

### Valor de Retorno

True se a conversão for bem-sucedida, caso contrário - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) método




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) método




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) método




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## Veja Também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)