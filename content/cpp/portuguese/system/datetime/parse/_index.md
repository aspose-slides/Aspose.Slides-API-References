---
title: Parse()
second_title: Referência da API Aspose.Slides para C++
description: Converte a representação em string especificada de um valor de data e hora para o objeto DateTime equivalente.
type: docs
weight: 859
url: /pt/system/datetime/parse/
---
## DateTime::Parse(const String\&) method


Converte a representação em string especificada de um valor de data e hora para o objeto [DateTime](../) equivalente.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../string/)\& | A representação em string de um valor de data e hora a ser convertido. |

### Valor de Retorno

Uma nova instância da classe [DateTime](../) que representa o valor de data e hora equivalente ao representado pela string especificada.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) method


Converte a representação em string especificada de um valor de data e hora para o objeto [DateTime](../) equivalente usando informações de formato específicas da cultura.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| s | const [String](../../string/)\& | A representação em string de um valor de data e hora a ser convertido. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O objeto [IFormatProvider](../../iformatprovider/) que fornece informações de formato específicas da cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Uma combinação bit a bit dos valores da enumeração que fornece informações adicionais sobre **s**, sobre elementos de estilo que podem estar presentes em **s**, ou sobre a conversão de **s** para um objeto [DateTime](../). |

### Valor de Retorno

Uma nova instância da classe [DateTime](../) que representa o valor de data e hora equivalente ao representado pela string especificada.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) method




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Veja Também

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [DateTime](../)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)