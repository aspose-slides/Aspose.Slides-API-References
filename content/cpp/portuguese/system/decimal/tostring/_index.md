---
title: ToString()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a representação em string do valor representado pelo objeto.
type: docs
weight: 352
url: /pt/system/decimal/tostring/
---
## Decimal::ToString() const método


Retorna a representação em string do valor representado pelo objeto.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const método


Converte o objeto atual para string usando as informações de formato específicas da cultura.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O objeto [IFormatProvider](../../iformatprovider/) que fornece as informações de formato específicas da cultura. |

### Valor de Retorno

A representação em string do objeto atual.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const método




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const método




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const método




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const método


Converte o objeto atual para sua representação em string usando o formato de string especificado e as informações de formato específicas da cultura fornecidas pelo objeto [IFormatProvider](../../iformatprovider/) especificado.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | const [String](../../string/)\& | O formato de string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | O objeto [IFormatProvider](../../iformatprovider/) que fornece as informações de formato específicas da cultura. |

### Valor de Retorno

A representação em string do objeto atual.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const método




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const método




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const método




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## Ver Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Decimal](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)