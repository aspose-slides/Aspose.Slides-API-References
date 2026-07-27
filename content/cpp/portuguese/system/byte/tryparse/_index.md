---
title: TryParse()
second_title: Referência da API Aspose.Slides para C++
description: Converte a string especificada que contém a representação textual de um número para o inteiro sem sinal de 8 bits equivalente.
type: docs
weight: 14
url: /pt/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) método

Converte a string especificada que contém a representação textual de um número para o inteiro sem sinal de 8 bits equivalente.

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| result | **uint8_t**\& | A referência a uma variável inteiro sem sinal de 8 bits onde o resultado da conversão é colocado. |

### Valor de Retorno

True se a conversão for bem-sucedida, caso contrário - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) método

Converte a string especificada que contém a representação textual de um número para o inteiro sem sinal de 8 bits equivalente usando as informações de formatação fornecidas e o estilo numérico.

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores do enum NumberStyles que especifica o estilo permitido da representação textual de um número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formatação da string. |
| result | **uint8_t**\& | A referência a uma variável inteiro sem sinal de 8 bits onde o resultado da conversão é colocado. |

### Valor de Retorno

True se a conversão for bem-sucedida, caso contrário - false.

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) método

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) método

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) método

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## Ver também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Byte](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)