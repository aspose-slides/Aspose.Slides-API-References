---
title: GetDateTimeFormats()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una matriz de cadenas donde cada elemento es la representación en cadena del objeto actual formateado con uno de los especificadores estándar de fecha y hora.
type: docs
weight: 547
url: /es/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const método

Devuelve una matriz de cadenas donde cada elemento es la representación en cadena del objeto actual formateado con uno de los especificadores estándar de fecha y hora.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const método

Devuelve una matriz de cadenas donde cada elemento es la representación en cadena del objeto actual formateado con el especificador estándar de fecha y hora especificado.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | char_t | Especificador estándar de fecha y hora. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const método

Devuelve una matriz de cadenas donde cada elemento es la representación en cadena del objeto actual formateado con uno de los especificadores estándar de fecha y hora y el proveedor de formato especificado.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Proveedor de formato. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const método

Devuelve una matriz de cadenas donde cada elemento es la representación en cadena del objeto actual formateado con el especificador estándar de fecha y hora especificado y el proveedor de formato.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | char_t | Especificador estándar de fecha y hora. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Proveedor de formato. |

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)