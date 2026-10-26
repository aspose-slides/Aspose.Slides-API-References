---
title: ToString()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve la representación en cadena del valor representado por el objeto.
type: docs
weight: 352
url: /es/system/decimal/tostring/
---
## Decimal::ToString() const método

Devuelve la representación en cadena del valor representado por el objeto.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const método

Convierte el objeto actual a cadena usando la información de formato específica de la cultura.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El objeto [IFormatProvider](../../iformatprovider/) que proporciona la información de formato específica de la cultura. |

### Valor devuelto

La representación en cadena del objeto actual.

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

Convierte el objeto actual a su representación en cadena usando el formato de cadena especificado y la información de formato específica de la cultura proporcionada por el objeto [IFormatProvider](../../iformatprovider/) especificado.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | const [String](../../string/)\& | El formato de cadena. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El objeto [IFormatProvider](../../iformatprovider/) que proporciona la información de formato específica de la cultura. |

### Valor devuelto

La representación en cadena del objeto actual.

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

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [Decimal](../)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)