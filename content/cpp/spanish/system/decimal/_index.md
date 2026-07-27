---
title: Decimal
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un número decimal. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 261
url: /es/system/decimal/
---
## Clase Decimal


Representa un número decimal. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca use la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class Decimal
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | Suma dos valores [Decimal](./) especificados. |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | Devuelve el valor entero más pequeño que es mayor o igual al valor especificado. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | Determina si el valor representado por el primer objeto [Decimal](./) es menor, igual o mayor que el valor representado por el segundo objeto [Decimal](./). |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | Determina si el valor representado por el objeto actual es menor, igual o mayor que el valor representado por el objeto especificado. |
| [Decimal](./decimal/)() | Construye una instancia que representa 0. |
| [Decimal](./decimal/)(std::int8_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(std::int16_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(std::int32_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(std::int64_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(std::uint8_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(std::uint16_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(std::uint32_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(std::uint64_t) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(**float**) | Construye una instancia que representa el valor especificado. |
| [Decimal](./decimal/)(**double**) | Construye una instancia que representa el valor especificado. |
| explicit  [Decimal](./decimal/)(const std::string\&) | Construye una instancia que representa un valor cuya representación en cadena se especifica como una instancia de la clase std::string. |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | Construye un objeto [Decimal](./) a partir de los componentes especificados. |
| [Decimal](./decimal/)(const [Decimal](./)\&) | Construye una instancia de la clase [Decimal](./) que representa el mismo número que el objeto [Decimal](./) especificado. |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | Construye una instancia de la clase [Decimal](./) a partir de una matriz de enteros que contiene una representación binaria. |
| [Decimal](./decimal/)(std::nullptr_t) | Siempre lanza ArgumentNullException. |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | Construye una instancia de la clase [Decimal](./) que representa el valor especificado. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | Divide dos valores [Decimal](./) especificados. |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | Determina si los valores representados por el objeto actual y el objeto especificado son iguales. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Determina si los valores representados por el objeto actual y el objeto especificado son iguales. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | Determina si los valores representados por los objetos especificados son iguales. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | Devuelve el valor entero más grande que es menor o igual al valor especificado. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) el valor de moneda OLE especificado al valor equivalente [Decimal](./). NOT IMPLEMENTED. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | Convierte el objeto [Decimal](./) especificado en la representación binaria del valor que representa. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) el valor [Decimal](./) especificado a una matriz de bytes. |
| int [GetHashCode](./gethashcode/)() const | Devuelve un código hash para el objeto actual. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Obtiene el código de tipo del objeto. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | Multiplica dos valores [Decimal](./) especificados. |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | Devuelve una nueva instancia de la clase [Decimal](./) que representa un valor que resulta de la negación del valor representado por el objeto especificado. |
| explicit  [operator bool](./operator_bool/)() const | Convierte el valor representado por el objeto actual a un valor booleano. |
| explicit  [operator double](./operator_double/)() const | Convierte el valor representado por el objeto actual a un valor de coma flotante de doble precisión. |
| explicit  [operator float](./operator_float/)() const | Convierte el valor representado por el objeto actual a un valor de coma flotante de precisión simple. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | Determina si los valores representados por el objeto actual y el objeto especificado no son iguales. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Determina si el valor representado por el objeto actual es diferente de 0. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | Devuelve una nueva instancia de la clase [Decimal](./) que representa un valor que es el resultado de una operación módulo con los valores representados por el objeto actual y el objeto especificado. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | Asigna al objeto actual un nuevo valor que es el resultado de una operación módulo con los valores representados por el objeto actual y el objeto especificado. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | Devuelve una nueva instancia de la clase [Decimal](./) que representa un valor que es el resultado de la multiplicación de los valores representados por los objetos actual y especificado. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | Asigna al objeto actual un nuevo valor que es el resultado de la multiplicación de los valores representados por los objetos actual y especificado. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | Devuelve una nueva instancia de la clase [Decimal](./) que representa un valor que es la suma de los valores representados por los objetos actual y especificado. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | Incrementa el valor representado por el objeto actual. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | Asigna al objeto actual un nuevo valor que es la suma de los valores representados por los objetos actual y especificado. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | Devuelve una nueva instancia de la clase [Decimal](./) que representa un valor que es el resultado de restar el valor representado por el objeto especificado del valor representado por el objeto actual. |
| [Decimal](./) [operator-](./operator_minus/)() const | Devuelve una nueva instancia de la clase [Decimal](./) que representa un valor que resulta de la negación del valor representado por el objeto actual. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | Decrementa el valor representado por el objeto actual. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | Asigna al objeto actual un nuevo valor que es el resultado de restar el valor representado por el objeto especificado del valor representado por el objeto actual. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | Devuelve una nueva instancia de la clase [Decimal](./) que representa un valor que es el resultado de dividir el valor representado por el objeto actual entre el valor representado por el objeto especificado. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | Asigna al objeto actual un nuevo valor que es el resultado de dividir el valor representado por el objeto actual entre el valor representado por el objeto especificado. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | Determina si el valor representado por el objeto actual es menor que el valor representado por el objeto especificado. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | Determina si el valor representado por el objeto actual es menor o igual que el valor representado por el objeto especificado. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | Asigna al objeto actual el valor representado por el objeto especificado. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | Determina si los valores representados por el objeto actual y el objeto especificado son iguales. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Determina si el valor representado por el objeto actual es 0. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | Determina si el valor representado por el objeto actual es mayor que el valor representado por el objeto especificado. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | Determina si el valor representado por el objeto actual es mayor o igual que el valor representado por el objeto especificado. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | Convierte la representación en cadena de un número decimal en una instancia equivalente de la clase [Decimal](./). |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | Convierte la representación en cadena de un número decimal en una instancia equivalente de la clase [Decimal](./) usando el estilo especificado. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la representación en cadena de un número decimal en una instancia equivalente de la clase [Decimal](./) usando el proveedor de formato especificado. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Convierte la representación en cadena de un número decimal en una instancia equivalente de la clase [Decimal](./) usando el estilo y el proveedor de formato especificados. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | Calcula el resto después de dividir dos valores [Decimal](./). |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | Redondea el valor especificado al número entero más cercano. Un parámetro especifica el comportamiento de la función si el valor especificado está a la misma distancia de dos números más cercanos. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | Redondea el valor especificado al valor más cercano con el número especificado de dígitos fraccionarios. Un parámetro especifica el comportamiento de la función si el valor especificado está a la misma distancia de dos números más cercanos. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | Resta un valor [Decimal](./) especificado de otro. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | Convierte el valor [Decimal](./) a un entero sin signo de 8 bits. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | Convierte el valor [Decimal](./) a un número de coma flotante de doble precisión. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | Convierte el valor [Decimal](./) a un entero con signo de 16 bits. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | Convierte el valor [Decimal](./) a un entero con signo de 32 bits. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | Convierte el valor [Decimal](./) a un entero con signo de 64 bits. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) el valor [Decimal](./) especificado al valor de moneda OLE equivalente. NOT IMPLEMENTED. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | Convierte el valor [Decimal](./) a un entero con signo de 8 bits. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | Convierte el valor [Decimal](./) a un número de coma flotante de precisión simple. |
| std::string [ToStdString](./tostdstring/)() const | Devuelve una instancia de std::string que contiene la representación en cadena del valor representado por el objeto. |
| [String](../string/) [ToString](./tostring/)() const | Devuelve la representación en cadena del valor representado por el objeto. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Convierte el objeto actual a una cadena usando la información de formato específica de la cultura. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Convierte el objeto actual a su representación en cadena usando el formato de cadena especificado y la información de formato específica de la cultura proporcionada por el objeto [IFormatProvider](../iformatprovider/) especificado. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | Devuelve la representación en cadena del valor representado por el objeto. Para uso interno. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | Convierte el valor [Decimal](./) a un entero sin signo de 16 bits. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | Convierte el valor [Decimal](./) a un entero sin signo de 32 bits. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | Convierte el valor [Decimal](./) a un entero sin signo de 64 bits. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | Devuelve el objeto [Decimal](./) que representa un valor cuyo parte entera es igual a la del valor representado por el objeto [Decimal](./) especificado, con todos los dígitos fraccionarios descartados. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al valor [Decimal](./) equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | Convierte la cadena especificada que contiene la representación en cadena de un número al valor [Decimal](./) equivalente usando la información de formato y estilo numérico proporcionados. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Devuelve una referencia al objeto [TypeInfo](../typeinfo/) que representa la información de tipo de la clase [Decimal](./). |
| [~Decimal](./~decimal/)() | Destructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [MaxValue](./maxvalue/) | Representa el número más grande que puede ser representado por la clase [Decimal](./). |
| static [MinusOne](./minusone/) | Representa el número -1. |
| static [MinValue](./minvalue/) | Representa el número más pequeño que puede ser representado por la clase [Decimal](./). |
| static [One](./one/) | Representa el número 1. |
| static [Zero](./zero/) | Representa el número 0. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [number_type](./number_type/) | Un alias de Detail::decimal_number_type. |
## Observaciones



```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)