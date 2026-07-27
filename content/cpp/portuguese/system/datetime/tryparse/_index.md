---
title: TryParse()
second_title: Referência da API Aspose.Slides para C++
description: Converte a representação em string especificada de um valor de data e hora para o objeto DateTime equivalente.
type: docs
weight: 885
url: /pt/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) method


Converte a representação em string especificada de um valor de data e hora para o objeto [DateTime](../) equivalente.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | A representação em string de um valor de data e hora a ser convertido. |
| result | [DateTime](../)\& | O argumento de saída que, se a conversão for bem-sucedida, contém o resultado da conversão. |

### Valor de Retorno

True se a conversão for bem-sucedida, caso contrário - false.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method


Converte a representação em string especificada de um valor de data e hora para o objeto [DateTime](../) equivalente usando as informações de formato específicas de cultura e estilo fornecidas.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | A representação em string de um valor de data e hora a ser convertido. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O objeto [IFormatProvider](../../iformatprovider/) que fornece informações de formato específicas de cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Uma combinação bit a bit dos valores de enumeração que fornece informações adicionais sobre **s**, sobre elementos de estilo que podem estar presentes em **s**, ou sobre a conversão de **s** para um objeto [DateTime](../). |
| result | [DateTime](../)\& | O argumento de saída que, se a conversão for bem-sucedida, contém o resultado da conversão. |

### Valor de Retorno

True se a conversão for bem-sucedida, caso contrário - false.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Veja Também

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)