---
title: Parse()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte la representación en cadena de un número decimal en una instancia equivalente de la clase Decimal.
type: docs
weight: 469
url: /es/system/decimal/parse/
---
## Decimal::Parse(const String\&) method

Convierte la representación en cadena de un número decimal en una instancia equivalente de la clase [Decimal](../).

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../string/)\& | La representación en cadena de un número |

### Valor devuelto

Una nueva instancia de la clase [Decimal](../) que representa un valor equivalente al representado por la cadena especificada.

## Decimal::Parse(const String\&, Globalization::NumberStyles) method

Convierte la representación en cadena de un número decimal en una instancia equivalente de la clase [Decimal](../) usando el estilo especificado.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../string/)\& | La representación en cadena de un valor decimal a convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación a nivel de bits de los valores de enumeración que proporciona información adicional sobre **s**, sobre los elementos de estilo que pueden estar presentes en **s**, o sobre la conversión de **s** a un objeto [Decimal](../) |

### Valor devuelto

Una nueva instancia de la clase [Decimal](../) que representa un valor equivalente al representado por la cadena especificada.

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method

Convierte la representación en cadena de un número decimal en una instancia equivalente de la clase [Decimal](../) usando el proveedor de formato especificado.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../string/)\& | La representación en cadena de un valor decimal a convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Proveedor de formato |

### Valor devuelto

Una nueva instancia de la clase [Decimal](../) que representa un valor equivalente al representado por la cadena especificada.

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

Convierte la representación en cadena de un número decimal en una instancia equivalente de la clase [Decimal](../) usando el estilo y el proveedor de formato especificados.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| s | const [String](../../string/)\& | La representación en cadena de un valor decimal a convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación a nivel de bits de los valores de enumeración que proporciona información adicional sobre **s**, sobre los elementos de estilo que pueden estar presentes en **s**, o sobre la conversión de **s** a un objeto [Decimal](../) |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Proveedor de formato |

### Valor devuelto

Una nueva instancia de la clase [Decimal](../) que representa un valor equivalente al representado por la cadena especificada.

## Ver también

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [Decimal](../)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)