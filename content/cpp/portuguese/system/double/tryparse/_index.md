---
title: TryParse()
second_title: Referência da API Aspose.Slides para C++
description: Converte a string especificada contendo a representação textual de um número para o valor equivalente de ponto flutuante de precisão dupla.
type: docs
weight: 14
url: /pt/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) método


Converte a string especificada contendo a representação textual de um número para o valor equivalente de ponto flutuante de precisão dupla.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| result | **double**\& | A referência a uma variável de ponto flutuante de precisão dupla onde o resultado da conversão é colocado. |

### Valor de Retorno

True se a conversão for bem-sucedida, caso contrário - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) método


Converte a string especificada contendo a representação textual de um número para o valor equivalente de ponto flutuante de precisão dupla usando as informações de formatação e o estilo numérico fornecidos.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores do enum NumberStyles que especifica o estilo permitido da representação textual do número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formatação da string. |
| result | **double**\& | A referência a uma variável de ponto flutuante de precisão dupla onde o resultado da conversão é colocado. |

### Valor de Retorno

True se a conversão for bem-sucedida, caso contrário - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) método




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) método




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) método




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## Veja Também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)