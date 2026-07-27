---
title: ToString()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a representação em string do valor de data e hora representado pelo objeto atual usando as convenções de formatação definidas pela cultura atual.
type: docs
weight: 482
url: /pt/system/datetime/tostring/
---
## DateTime::ToString() const method

Retorna a representação em string do valor de data e hora representado pelo objeto atual usando as convenções de formatação definidas pela cultura atual.

```cpp
String System::DateTime::ToString() const
```

### Valor de Retorno

A representação em string do valor representado pelo objeto atual

## DateTime::ToString(const String\&) const method

Retorna uma representação em string do valor de data e hora representado pelo objeto atual usando o formato especificado e as convenções de formatação definidas pela cultura atual.

```cpp
String System::DateTime::ToString(const String &format) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | const [String](../../string/)\& | Uma string de formato |

### Valor de Retorno

A representação em string do valor representado pelo objeto atual formatada de acordo com o formato definido por **format** e a cultura atual.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const method

Retorna uma representação em string do valor de data e hora representado pelo objeto atual usando as informações de formato especificadas.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um objeto que representa as informações de formatação |

### Valor de Retorno

A representação em string do valor representado pelo objeto atual formatada de acordo com as informações de formato fornecidas por **formatProvider**.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const method




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const method




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const method




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const method

Retorna uma representação em string do valor de data e hora representado pelo objeto atual usando as informações de formato especificadas.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | const [String](../../string/)\& | Uma string de formato |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Um objeto que representa as informações de formatação |

### Valor de Retorno

A representação em string do valor representado pelo objeto atual formatada de acordo com as informações de formato fornecidas por **provider** e a string de formato **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const method




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const method




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const method




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [DateTime](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Espaço de nomes [System](../../)
* Library [Aspose.Slides](../../../)