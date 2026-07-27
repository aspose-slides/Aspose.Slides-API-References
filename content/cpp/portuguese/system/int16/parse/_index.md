---
title: Parse()
second_title: Referência da API Aspose.Slides para C++
description: Converte a string especificada contendo a representação textual de um número para o inteiro assinado de 16 bits equivalente.
type: docs
weight: 1
url: /pt/system/int16/parse/
---
## Int16::Parse(const String\&) método


Converte a string especificada contendo a representação textual de um número para o inteiro assinado de 16 bits equivalente.

```cpp
static int16_t System::Int16::Parse(const String &value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |

### Valor de Retorno

O inteiro assinado de 16 bits equivalente ao número representado pela string especificada.

## Int16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) método


Converte a string especificada contendo a representação textual de um número para o inteiro assinado de 16 bits equivalente usando as informações de formatação fornecidas.

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formato da string. |

### Valor de Retorno

O inteiro assinado de 16 bits equivalente ao número representado pela string especificada.

## Int16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, std::nullptr_t) método




```cpp
static int16_t System::Int16::Parse(const String &value, std::nullptr_t)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método


Converte a string especificada contendo a representação textual de um número para o inteiro assinado de 16 bits equivalente usando as informações de formatação fornecidas e o estilo numérico.

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | A string a ser convertida. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores da enumeração NumberStyles que especifica o estilo permitido da representação textual de um número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formato da string. |

### Valor de Retorno

O inteiro assinado de 16 bits equivalente ao número representado pela string especificada.

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) método




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Veja Também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Int16](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)