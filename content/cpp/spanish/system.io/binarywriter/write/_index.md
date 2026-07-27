---
title: Write()
second_title: Referencia de API de Aspose.Slides para C++
description: Escribe el valor entero sin signo de 8 bits especificado al flujo de salida.
type: docs
weight: 92
url: /es/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) método

Escribe el valor entero sin signo de 8 bits especificado al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **uint8_t** | El valor a escribir |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) método

Escribe el subrango especificado de bytes del arreglo de bytes especificado al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | El arreglo que contiene los bytes a escribir |
| index | int | Un índice basado en cero del elemento en **buffer** donde comienza el subrango a escribir |
| count | int | El número de elementos en el subrango a escribir; -1 indica que el subrango termina donde termina el arreglo **buffer** |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) método

Escribe el subrango especificado de caracteres UTF-16 del arreglo de caracteres especificado al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | El arreglo que contiene los caracteres a escribir |
| index | int | Un índice basado en cero del elemento en **buffer** donde comienza el subrango a escribir |
| count | int | El número de caracteres en el subrango a escribir; -1 indica que el subrango termina donde termina el arreglo **buffer** |

## BinaryWriter::Write(bool) método

Escribe un solo byte con valor 0 si **value** es 'true' y 1 si **value** es 'false' al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **bool** | El valor booleano que especifica el valor del byte a escribir al flujo de salida |

## BinaryWriter::Write(char16_t) método

Escribe el valor del carácter de 16 bits especificado al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char16_t | El valor a escribir |

## BinaryWriter::Write(int16_t) método

Escribe el valor entero de 16 bits especificado al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **int16_t** | El valor a escribir |

## BinaryWriter::Write(int) método

Escribe el valor entero de 32 bits especificado al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int | El valor a escribir |

## BinaryWriter::Write(int64_t) método

Escribe el valor entero de 64 bits especificado al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **int64_t** | El valor a escribir |

## BinaryWriter::Write(uint16_t) método

Escribe el valor entero sin signo de 16 bits especificado al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **uint16_t** | El valor a escribir |

## BinaryWriter::Write(uint32_t) método

Escribe el valor entero sin signo de 32 bits especificado al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **uint32_t** | El valor a escribir |

## BinaryWriter::Write(uint64_t) método

Escribe el valor entero sin signo de 64 bits especificado al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **uint64_t** | El valor a escribir |

## BinaryWriter::Write(float) método

Escribe el valor de punto flotante de precisión simple especificado al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **float** | El valor a escribir |

## BinaryWriter::Write(double) método

Escribe el valor de punto flotante de precisión doble especificado al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | **double** | El valor a escribir |

## BinaryWriter::Write(const Decimal\&) método

Escribe la representación en bytes del valor [Decimal](../../../system/decimal/) especificado al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | El valor a escribir |

## BinaryWriter::Write(const String\&) método

Escribe una cadena con prefijo de longitud en la codificación actual al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La cadena a escribir |

## BinaryWriter::Write(const char_t *) método

Escribe una cadena con prefijo de longitud en la codificación actual al flujo de salida.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const char_t * | La cadena C a escribir |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [BinaryWriter](../)
* Clase [Decimal](../../../system/decimal/)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::IO](../../)
* Library [Aspose.Slides](../../../)