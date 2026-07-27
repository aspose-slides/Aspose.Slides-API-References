---
title: Parse()
second_title: Referência da API Aspose.Slides para C++
description: Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente.
type: docs
weight: 1
url: /pt/system/double/parse/
---
## Double::Parse(const String\&) método


Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente.

```cpp
static double System::Double::Parse(const String &value)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |

### Valor de Retorno

O valor de ponto flutuante de dupla precisão equivalente ao número representado pela string especificada.

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) método


Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente usando as informações de formatação fornecidas.

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formatação da string. |

### Valor de Retorno

O valor de ponto flutuante de dupla precisão equivalente ao número representado pela string especificada.

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) método




```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método


Converte a string especificada que contém a representação textual de um número para o valor de ponto flutuante de dupla precisão equivalente usando as informações de formatação e o estilo numérico fornecidos.

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores da enumeração NumberStyles que especifica o estilo permitido da representação textual de um número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formatação da string. |

### Valor de Retorno

O valor de ponto flutuante de dupla precisão equivalente ao número representado pela string especificada.

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) método




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Veja Também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)