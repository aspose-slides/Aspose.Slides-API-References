---
title: TryParse()
second_title: Referência da API Aspose.Slides para C++
description: Converte a string especificada que contém a representação textual de um número para o inteiro assinado de 16 bits equivalente.
type: docs
weight: 14
url: /pt/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) método


Converte a string especificada que contém a representação textual de um número para o inteiro assinado de 16 bits equivalente.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| result | **int16_t**\& | A referência a uma variável inteira assinada de 16 bits onde o resultado da conversão é colocado. |

### Valor de Retorno

True se a conversão for bem-sucedida, caso contrário - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) método


Converte a string especificada que contém a representação textual de um número para o inteiro assinado de 16 bits equivalente, usando as informações de formatação e o estilo numérico fornecidos.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores do enum NumberStyles que especifica o estilo permitido da representação textual de um número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formato da string. |
| result | **int16_t**\& | A referência a uma variável inteira assinada de 16 bits onde o resultado da conversão é colocado. |

### Valor de Retorno

True se a conversão for bem-sucedida, caso contrário - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) método




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) método




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) método




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## Veja Também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int16](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)