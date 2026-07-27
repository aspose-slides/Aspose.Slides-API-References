---
title: TryParse()
second_title: Referência da API Aspose.Slides para C++
description: Converte a string especificada contendo a representação textual de um número para o inteiro assinado de 64 bits equivalente.
type: docs
weight: 14
url: /pt/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) método


Converte a string especificada contendo a representação textual de um número para o inteiro assinado de 64 bits equivalente.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| result | **int64_t**\& | A referência a uma variável inteira assinada de 64 bits onde o resultado da conversão será colocado. |

### Valor de Retorno

True se a conversão teve sucesso, caso contrário - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) método


Converte a string especificada contendo a representação textual de um número para o inteiro assinado de 64 bits equivalente usando as informações de formatação fornecidas e o estilo numérico.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores da enumeração NumberStyles que especifica o estilo permitido da representação textual de um número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formato da string. |
| result | **int64_t**\& | A referência a uma variável inteira assinada de 64 bits onde o resultado da conversão será colocado. |

### Valor de Retorno

True se a conversão teve sucesso, caso contrário - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) método




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) método




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) método




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Veja Também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Int64](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)