---
title: ToString()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve la representación en cadena del valor de fecha y hora representado por el objeto actual usando las convenciones de formato definidas por la cultura actual.
type: docs
weight: 482
url: /es/system/datetime/tostring/
---
## DateTime::ToString() const método

Devuelve la representación en cadena del valor de fecha y hora representado por el objeto actual usando las convenciones de formato definidas por la cultura actual.

```cpp
String System::DateTime::ToString() const
```

### Valor devuelto

La representación en cadena del valor representado por el objeto actual

## DateTime::ToString(const String\&) const método

Devuelve una representación en cadena del valor de fecha y hora representado por el objeto actual usando el formato especificado y las convenciones de formato definidas por la cultura actual.

```cpp
String System::DateTime::ToString(const String &format) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | const [String](../../string/)\& | Una cadena de formato |

### Valor devuelto

La representación en cadena del valor representado por el objeto actual formateada según **format** y la cultura actual.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const método

Devuelve una representación en cadena del valor de fecha y hora representado por el objeto actual usando la información de formato especificada.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un objeto que representa la información de formato |

### Valor devuelto

La representación en cadena del valor representado por el objeto actual formateada según la información de formato proporcionada por **formatProvider**.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const método




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const método




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const método




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const método

Devuelve una representación en cadena del valor de fecha y hora representado por el objeto actual usando la información de formato especificada.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | const [String](../../string/)\& | Una cadena de formato |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un objeto que representa la información de formato |

### Valor devuelto

La representación en cadena del valor representado por el objeto actual formateada según la información de formato proporcionada por **provider** y la cadena de formato **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const método




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const método




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const método




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## Véase también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [DateTime](../)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)