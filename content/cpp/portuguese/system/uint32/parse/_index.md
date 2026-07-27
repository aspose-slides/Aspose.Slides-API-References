---
title: Parse()
second_title: Referência da API Aspose.Slides para C++
description: Converte a cadeia especificada que contém a representação textual de um número ao inteiro sem sinal de 32 bits equivalente.
type: docs
weight: 1
url: /pt/system/uint32/parse/
---
## UInt32::Parse(const String\&) método


Converte a cadeia especificada que contém a representação textual de um número ao inteiro sem sinal de 32 bits equivalente.

```cpp
static uint32_t System::UInt32::Parse(const String &value)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A cadeia a ser convertida. |

### Valor de Retorno

O inteiro sem sinal de 32 bits igual ao número representado pela cadeia especificada.

## UInt32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) método


Converte a cadeia especificada que contém a representação textual de um número ao inteiro sem sinal de 32 bits equivalente usando as informações de formatação fornecidas.

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A cadeia a ser convertida. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formato da cadeia. |

### Valor de Retorno

O inteiro sem sinal de 32 bits igual ao número representado pela cadeia especificada.

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, std::nullptr_t) método




```cpp
static uint32_t System::UInt32::Parse(const String &value, std::nullptr_t)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método


Converte a cadeia especificada que contém a representação textual de um número ao inteiro sem sinal de 32 bits equivalente usando as informações de formatação fornecidas e o estilo numérico.

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A cadeia a ser convertida. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Uma combinação bit a bit dos valores da enumeração NumberStyles que especifica o estilo permitido da representação textual de um número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um ponteiro para um objeto que contém as informações de formato da cadeia. |

### Valor de Retorno

O inteiro sem sinal de 32 bits igual ao número representado pela cadeia especificada.

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) método 




```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Veja Também

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)