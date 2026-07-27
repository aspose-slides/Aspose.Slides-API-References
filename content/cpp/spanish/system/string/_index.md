---
title: String
second_title: Referencia de la API de Aspose.Slides para C++
description: "Clase String utilizada en toda la biblioteca. Es un sustituto de C# System.String al traducir código. Por razones de optimización, no se considera una subclase de Object. Este tipo debe asignarse en la pila y pasarse a funciones por valor o por referencia. Nunca utilice la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 1275
url: /es/system/string/
---
## Clase String


[String](./) clase utilizada en toda la biblioteca. Es un sustituto de C# [System.String](./) al traducir código. Por razones de optimización, no se considera una subclase de [Object](../object/). Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca utilice la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
class String
```

## Métodos

| Método | Descripción |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) es un tipo de valor en el lado C++ que implícitamente (sin herencia) implementa algunas interfaces. |
| const UChar * [begin](./begin/)() const | Devuelve un puntero al comienzo del búfer de cadena real. Nunca vuelve a asignar nada. No garantiza que el búfer esté terminado en nulo. |
| [String](./) [Clone](./clone/)() const | Crea una copia de la cadena actual. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | Compara dos subcadenas con menor-igual-mayor. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Compara dos subcadenas con menor-igual-mayor. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Compara dos cadenas con menor-igual-mayor. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | Compara dos cadenas con menor-igual-mayor. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | Compara dos cadenas con menor-igual-mayor. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Compara dos cadenas con menor-igual-mayor. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Compara dos cadenas con menor-igual-mayor usando modo ordinal. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Compara dos cadenas con menor-igual-mayor usando modo ordinal. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | Compara dos cadenas en estilo 'menos-igual-más'. Usa la cultura actual. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Concatena cadenas. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Concatena cadenas. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Concatena cadenas. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Concatena cadenas. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | Comprueba si str es una subcadena de la cadena actual. |
| **bool** [Contains](./contains/)(char16_t) const | Comprueba si la cadena contiene el carácter dado. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Crea una copia de la cadena. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Copia los caracteres de la cadena en elementos de arreglo existentes. No se realiza redimensionamiento. |
| const UChar * [end](./end/)() const | Devuelve un puntero al final del búfer de cadena real. Nunca vuelve a asignar nada. No garantiza que el búfer esté terminado en nulo. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Comprueba si la cadena termina con la subcadena especificada. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Comprueba si la cadena termina con la subcadena especificada. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Comprueba si la cadena termina con la subcadena especificada. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) comparación de igualdad. Se admiten varios modos provistos por la enumeración StringComparison. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) comparación de igualdad. Usa el modo de comparación [System::StringComparison::Ordinal](../stringcomparison/). |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Compara dos cadenas por igualdad usando el modo de comparación ordinal. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Compara dos cadenas por igualdad. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Intenta convertir un [String](./) a una cadena ASCII. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Da formato a la cadena al estilo C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Da formato a la cadena al estilo C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Da formato a la cadena al estilo C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Da formato a la cadena al estilo C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Da formato a la cadena al estilo C#. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | Crea [String](./) a partir de una cadena ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | Crea [String](./) a partir de una cadena ASCII. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | Crea [String](./) a partir de una cadena ASCII. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | Crea [String](./) a partir de una cadena utf16. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | Crea [String](./) a partir de una cadena utf32. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | Crea [String](./) a partir de una cadena utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | Crea [String](./) a partir de una cadena utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | Crea [String](./) a partir de una cadena utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | Crea [String](./) a partir de una cadena utf8. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | Crea [String](./) a partir de una cadena ancha. |
| int [get_Length](./get_length/)() const | Obtiene la longitud de la cadena. |
| int [GetHashCode](./gethashcode/)() const | Calcula el hash de la cadena contenida. Implementado en ICU, no coincide con los hashes en C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Búsqueda hacia adelante de subcadena. |
| int [IndexOf](./indexof/)(char_t, int) const | Búsqueda hacia adelante de carácter. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Búsqueda hacia adelante de carácter en subcadena. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Búsqueda hacia adelante de subcadena. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Búsqueda hacia adelante de subcadena. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Búsqueda hacia adelante de subcadena. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Búsqueda hacia adelante de subcadena. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Búsqueda hacia adelante de carácter. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Busca consecuentemente todos los caracteres de str en esto. Si se encuentra el primer carácter, se devuelve su posición; de lo contrario se busca el segundo y así sucesivamente. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Busca cualquiera de los caracteres pasados en toda la cadena. Compara el primer carácter de la cadena con todos los caracteres en anyOf, luego compara el segundo y así sucesivamente. Devuelve el índice del primero que coincide con cualquiera de los caracteres objetivo. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Busca cualquiera de los caracteres pasados en la subcadena. Compara el primer carácter de la cadena con todos los caracteres en anyOf, luego compara el segundo y así sucesivamente. Devuelve el índice del primero que coincide con cualquiera de los caracteres objetivo. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Busca cualquiera de los caracteres pasados en la subcadena. Compara el primer carácter de la cadena con todos los caracteres en anyOf, luego compara el segundo y así sucesivamente. Devuelve el índice del primero que coincide con cualquiera de los caracteres objetivo. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Inserta una subcadena en la posición especificada. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Comprueba si el objeto cadena es del tipo especificado por [TypeInfo](../typeinfo/) pasado. |
| **bool** [IsAsciiString](./isasciistring/)() const | Indica si un [String](./) contiene solo símbolos ASCII. |
| **bool** [IsEmpty](./isempty/)() const | Comprueba si la cadena es no nula y está vacía. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Comprueba si la cadena Unicode está normalizada usando la forma de normalización especificada. |
| **bool** [IsNull](./isnull/)() const | Comprueba si la cadena se considera nula. [String](./) es nula solo si se construye mediante el constructor [String()](./string/), se mueve, copia o asigna desde una cadena nula o se llama al método [reset()](./reset/). |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Comprueba si la cadena está vacía o se considera nula. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Comprueba si la cadena pasada es nula o está vacía. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Indica si una cadena especificada es nula, está vacía o consta solo de caracteres de espacio en blanco. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Une una matriz usando la cadena como separador. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Une una matriz usando la cadena como separador. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Une una matriz usando la cadena como separador. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Une una matriz usando la cadena como separador. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Búsqueda hacia atrás de subcadena. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Búsqueda hacia atrás de subcadena. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Búsqueda hacia atrás de subcadena. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Búsqueda hacia atrás de subcadena. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Búsqueda hacia atrás de carácter. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Búsqueda hacia atrás de carácter. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Búsqueda hacia atrás de carácter. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Busca cualquiera de los caracteres pasados en toda la cadena de forma retroactiva. Compara el último carácter de la cadena con todos los caracteres en anyOf, luego compara el anterior y así sucesivamente. Devuelve el índice de la primera coincidencia encontrada. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Busca cualquiera de los caracteres pasados en la subcadena de forma retroactiva. Compara el último carácter de la cadena con todos los caracteres en anyOf, luego compara el anterior y así sucesivamente. Devuelve el índice de la primera coincidencia encontrada. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Busca cualquiera de los caracteres pasados en la subcadena de forma retroactiva. Compara el último carácter de la cadena con todos los caracteres en anyOf, luego compara el anterior y así sucesivamente. Devuelve el índice de la primera coincidencia encontrada. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Normaliza la cadena Unicode usando la forma de normalización especificada. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | Convierte la cadena a un span solo de lectura. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Operador de comparación de desigualdad. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Comprueba si la cadena no es nula. Aplica la misma lógica que la llamada [IsNull()](./isnull/). |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) operador de concatenación. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) concatenación con literal de cadena o puntero a cadena de caracteres. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Añade un carácter al final de la cadena. |
| [String](./) [operator+](./operator_plus/)(int) const | Añade la representación en cadena de un valor entero al final de la cadena. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Añade la representación en cadena de un valor entero sin signo al final de la cadena. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Añade la representación en cadena de un valor de punto flotante al final de la cadena. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | Añade la representación en cadena de un valor entero al final de la cadena. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Añade la representación en cadena de un objeto de tipo referencia al final de la cadena. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Añade la representación en cadena de un objeto de tipo referencia al final de la cadena. |
| [String](./) [operator+](./operator_plus/)(T) const | Añade la representación en cadena de un valor booleano al final de la cadena. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Operador de asignación por concatenación. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Operador de asignación por concatenación. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Operador de asignación por concatenación. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Operador de asignación por concatenación.
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Operador de asignación de concatenación. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Operador de asignación de concatenación. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Operador de asignación de concatenación. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Operador de asignación de concatenación. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Operador de asignación de concatenación. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Operador de asignación de concatenación. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Operador de asignación de concatenación. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Compara el orden de las cadenas. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Operador de asignación. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Operador de asignación por movimiento. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Operador de comparación de igualdad. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Comprueba si la cadena es nula. Aplica la misma lógica que la llamada [IsNull()](./isnull/). |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | Compara el orden de las cadenas. |
| char_t [operator[]](./operator[]/)(int) const | Obtiene el carácter en la posición especificada. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Agrega relleno a la izquierda de la cadena original. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Agrega relleno a la derecha de la cadena original. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Devuelve un iterador inverso al último carácter (si lo hay) del búfer de cadena actual. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Extrae todo excepto la subcadena de la cadena actual. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Devuelve un iterador inverso al carácter anterior al primero (si lo hay) del búfer de cadena actual. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Reemplaza todas las apariciones del carácter en la cadena. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Reemplaza todas las apariciones de la búsqueda en esta cadena. |
| [String](./)\& [reset](./reset/)() | Establece la cadena a nula. Es análogo a 'string_variable_name = null' en C#. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | Establece el carácter en la posición especificada. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Divide la cadena por carácter. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Divide la cadena por carácter. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Divide la cadena por uno de dos caracteres. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Divide la cadena por uno de los caracteres especificados. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Divide la cadena por uno de los caracteres especificados. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Divide la cadena por subcadena. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Divide la cadena por subcadena. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Divide la cadena por subcadena. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Divide la cadena por subcadena. Actualmente, sólo admite una matriz de separadores de cero o un elemento. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Comprueba si la cadena comienza con la subcadena especificada. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Comprueba si la cadena comienza con la subcadena especificada. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Comprueba si la cadena comienza con la subcadena especificada. |
|  [String](./string/)() | Constructor por defecto. Crea un objeto cadena que se considera nulo. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | Construye una cadena a partir de un literal de cadena. Considera el literal como una cadena terminada en nulo, calcula la longitud de la cadena objetivo basándose en el tamaño del literal. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | Construye una cadena a partir de un puntero a cadena de caracteres. Trata la cadena apuntada como terminada en nulo, calcula la longitud de la cadena objetivo basándose en el carácter nulo. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | Construye una cadena a partir de un literal de cadena. Considera el literal como una cadena terminada en nulo en UTF8, calcula la longitud de la cadena objetivo basándose en el tamaño del literal. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | Construye una cadena a partir de un puntero a cadena de caracteres. Trata la cadena apuntada como terminada en nulo en UTF8, calcula la longitud de la cadena objetivo basándose en el carácter nulo. |
|  [String](./string/)(const char16_t *, int) | Construye una cadena a partir de un puntero a cadena de caracteres y una longitud explícita. |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | Inicializa una nueva instancia de la clase [System.String](./) con los caracteres Unicode indicados en el span de solo lectura especificado. |
|  [String](./string/)(const char *, int) | Construye una cadena a partir de un puntero a cadena de caracteres y una longitud explícita. |
|  [String](./string/)(const char16_t *, int, int) | Construye una cadena a partir de un puntero a cadena de caracteres desde la posición inicial usando la longitud. |
| explicit  [String](./string/)(const char16_t, int) | Constructor de relleno. |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Constructor nullptr. Declarado como plantilla para resolver prioridades con otros constructores plantilla. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | Construye una cadena a partir de un literal de cadena ancha. Considera el literal como una cadena terminada en nulo, calcula la longitud de la cadena objetivo basándose en el tamaño del literal. La conversión desde **wchar_t** es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | Construye una cadena a partir de un puntero a cadena ancha. Trata la cadena apuntada como terminada en nulo, calcula la longitud de la cadena objetivo basándose en el carácter nulo. La conversión desde **wchar_t** es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas. |
| explicit  [String](./string/)(const **wchar_t** *, int) | Construye una cadena a partir de un puntero a cadena ancha y una longitud explícita. La conversión desde **wchar_t** es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas. |
| explicit  [String](./string/)(const **wchar_t**, int) | Constructor de relleno. La conversión desde **wchar_t** es lenta en algunas plataformas, por lo que no se permiten conversiones implícitas. |
|  [String](./string/)(const [String](./)\&) | Constructor de copia. |
|  [String](./string/)([String](./)\&&) | Constructor de movimiento. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | Convierte todo el arreglo de caracteres a cadena. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | Convierte un subrango del arreglo de caracteres a cadena. Si los parámetros están fuera de los límites del arreglo, se construye una cadena vacía. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | Envuelve UnicodeString en [String](./). |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | Constructor de movimiento. |
| explicit  [String](./string/)(const std::wstring\&) | Crea [String](./) a partir de una cadena ancha. |
| explicit  [String](./string/)(const std::u16string\&) | Crea [String](./) a partir de una cadena utf16. |
| explicit  [String](./string/)(const std::string\&) | Crea [String](./) a partir de una cadena std::string presentada en formato UTF-8. |
| explicit  [String](./string/)(const std::u32string\&) | Crea [String](./) a partir de una cadena std::u32string. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Extrae subcadena. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Extrae subcadena. |
| std::string [ToAsciiString](./toasciistring/)() const | Convierte la cadena a std::string. Usa codificación ASCII. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Convierte la cadena o subcadena a un arreglo de bytes. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Convierte la cadena o subcadena a un arreglo de caracteres. |
| [String](./) [ToLower](./tolower/)() const | Convierte todos los caracteres de la cadena a minúsculas. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Convierte todos los caracteres de la cadena a minúsculas usando una cultura específica. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Convierte todos los caracteres de la cadena a minúsculas usando la cultura invariante. |
| [String](./) [ToString](./tostring/)() const | Contenedor para manejar la clase [String](./) en contextos donde [ToString()](./tostring/) se llama en objetos de tipo valor. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Contenedor para manejar la clase [String](./) en contextos donde [ToString()](./tostring/) se llama en objetos de tipo valor. |
| std::u16string [ToU16Str](./tou16str/)() const | Convierte la cadena a std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | Convierte la cadena a std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | Convierte todos los caracteres de la cadena a mayúsculas. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Convierte todos los caracteres de la cadena a mayúsculas usando una cultura específica. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Convierte todos los caracteres de la cadena a mayúsculas usando la cultura invariante. |
| std::string [ToUtf8String](./toutf8string/)() const | Convierte la cadena a std::string. Usa codificación UTF-8. |
| std::wstring [ToWCS](./towcs/)() const | Convierte la cadena a std::wstring. |
| [String](./) [Trim](./trim/)() const | Elimina todos los caracteres de espacio en blanco del inicio y final de la cadena. |
| [String](./) [Trim](./trim/)(char_t) const | Elimina todas las apariciones del carácter pasado del inicio y final de la cadena. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Elimina todas las apariciones de los caracteres pasados del inicio y final de la cadena. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Elimina todas las apariciones de los caracteres pasados del inicio y final de la cadena. |
| [String](./) [TrimEnd](./trimend/)() const | Elimina todos los caracteres de espacio en blanco del final de la cadena. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Elimina todas las apariciones del carácter pasado del final de la cadena. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Elimina todas las apariciones de los caracteres pasados del final de la cadena. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Elimina todas las apariciones de los caracteres pasados del final de la cadena. |
| [String](./) [TrimStart](./trimstart/)() const | Elimina todos los caracteres de espacio en blanco del comienzo de la cadena. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Elimina todas las apariciones del carácter pasado del comienzo de la cadena. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Elimina todas las apariciones de los caracteres pasados del comienzo de la cadena. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Elimina todas las apariciones de los caracteres pasados del comienzo de la cadena. |
| const UChar * [u_str](./u_str/)() const | Devuelve un búfer terminado en nulo con estilo ICU. Puede reasignar la cadena. |
|  [~String](./~string/)() | Destructor. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Cadena vacía. |
| static [Null](./null/) | Cadena nula. |
## Definiciones de tipo

| Typedef | Descripción |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Tipo de iterador inverso. |
## Observaciones



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Construya una cadena a partir del arreglo de caracteres y muéstrela.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Construya una cadena a partir del arreglo de bytes y muéstrela.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Recorte la cadena a continuación y muéstrela.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Imprima el número de palabras en el .
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## Véase también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)