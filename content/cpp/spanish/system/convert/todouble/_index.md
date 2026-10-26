---
title: ToDouble()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el valor booleano especificado a un número de punto flotante de doble precisión equivalente.
type: docs
weight: 222
url: /es/system/convert/todouble/
---
## Convert::ToDouble(bool) método

Convierte el valor booleano especificado a un número de punto flotante de doble precisión equivalente.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) método

Convierte el entero sin signo de 8 bits especificado a un número de punto flotante de doble precisión equivalente.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) método

Convierte el entero con signo de 8 bits especificado a un número de punto flotante de doble precisión equivalente.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) método

Convierte el entero sin signo de 16 bits especificado a un número de punto flotante de doble precisión equivalente.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) método

Convierte el entero con signo de 16 bits especificado a un número de punto flotante de doble precisión equivalente.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) método

Convierte el entero sin signo de 32 bits especificado a un número de punto flotante de doble precisión equivalente.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) método

Convierte el entero con signo de 32 bits especificado a un número de punto flotante de doble precisión equivalente.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) método

Convierte el entero sin signo de 64 bits especificado a un número de punto flotante de doble precisión equivalente.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) método

Convierte el entero con signo de 64 bits especificado a un número de punto flotante de doble precisión equivalente.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) método

Convierte el número de precisión simple especificado a un número de punto flotante de doble precisión equivalente.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) método

Devuelve el número double especificado.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) método

Convierte el número Decimal especificado a un número de punto flotante de doble precisión equivalente.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) método

La conversión no está soportada. Siempre lanza InvalidCastException.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) método

La conversión no está soportada. Siempre lanza InvalidCastException.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) método

Convierte la cadena nula especificada al valor de punto flotante de doble precisión equivalente.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```


### Valor devuelto

Cero.

## Convert::ToDouble(const char_t *) método

Convierte la c-string especificada que contiene la representación textual de un número al valor de punto flotante de doble precisión equivalente.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const char_t * | La c-string a convertir |

### Valor devuelto

El valor de punto flotante de doble precisión igual al número representado por la c-string especificada

## Convert::ToDouble(const String\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de doble precisión equivalente.

```cpp
static double System::Convert::ToDouble(const String &value)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |

### Valor devuelto

El valor de punto flotante de doble precisión igual al número representado por la cadena especificada

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de doble precisión equivalente utilizando la información de formato proporcionada.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena |

### Valor devuelto

El valor de punto flotante de doble precisión igual al número representado por la cadena especificada

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) método

```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de doble precisión equivalente utilizando la información de formato y el estilo de número proporcionados.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de valores del enumerado NumberStyles que especifica el estilo permitido de la representación textual de un número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena |

### Valor devuelto

El valor de punto flotante de doble precisión igual al número representado por la cadena especificada

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) método

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte el valor boxed especificado a un valor de punto flotante de doble precisión. Si el tipo del valor boxed es [String](../../string/), se utiliza el formato de cadena especificado durante la conversión.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | El shared pointer al objeto que contiene el valor a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | El formato de cadena a usar si el tipo del valor boxed es [String](../../string/) |

### Valor devuelto

Un valor de punto flotante de doble precisión equivalente al valor boxed especificado

## Ver también

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [Decimal](../../decimal/)
* Clase [DateTime](../../datetime/)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Clase [Object](../../object/)
* Struct [Convert](../)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)