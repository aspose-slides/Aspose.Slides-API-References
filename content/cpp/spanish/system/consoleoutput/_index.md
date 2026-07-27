---
title: ConsoleOutput
second_title: Referencia de la API de Aspose.Slides para C++
description: "Representa el flujo de salida estándar. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 209
url: /es/system/consoleoutput/
---
## Clase ConsoleOutput

Representa el flujo de salida estándar. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Cierra el flujo y libera los recursos adquiridos. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Libera todos los recursos usados por el objeto actual y cierra el flujo subyacente. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compara objetos usando la semántica [Object.Equals](../object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Vacía el contenido del búfer al flujo subyacente. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Siempre devuelve la codificación ASCII. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Devuelve el objeto [IFormatProvider](../iformatprovider/) actualmente usado. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Devuelve el objeto [IFormatProvider](../iformatprovider/) actualmente usado. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Devuelve una cadena terminadora de línea. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Devuelve una cadena terminadora de línea. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Análogo al método [Object.GetHashCode()](../object/gethashcode/) de C#. Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada [System.Object.GetType()](../object/gettype/) de C#. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador `is` de C#. |
| void [Lock](../object/lock/)() | Implementa la sentencia `lock()` de C#. Llámelo directamente o use el objeto centinela [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Análogo al método [Object.MemberwiseClone()](../object/memberwiseclone/) de C#. Permite clonar tipos personalizados. |
|  [Object](../object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../object/object/)([Object](../object/) const\&) | Constructor de copia. No copia nada, simplemente inicializa un nuevo objeto y permite la copia de subclases. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de asignación. No copia nada, simplemente inicializa un nuevo objeto y permite la copia de subclases. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Establece una cadena terminadora de línea. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Asigna el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Análogo al método [Object.ToString()](../object/tostring/) de C#. Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa la construcción `typeof([System.Object](../object/))` de C#. |
| void [Unlock](../object/unlock/)() | Implementa la sentencia `lock()` de C# liberando el bloqueo. Llámelo directamente o use el objeto centinela [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [Write](./write/)(**bool**) override | Envía la representación en cadena del valor booleano especificado al flujo de salida representado por el objeto actual. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Envía la representación en cadena del objeto especificado al flujo de salida representado por el objeto actual. |
| void [Write](./write/)(char_t) override | Envía el carácter especificado al flujo de salida representado por el objeto actual. |
| void [Write](./write/)([Decimal](../decimal/)) override | Envía la representación en cadena del valor [Decimal](../decimal/) al flujo de salida representado por el objeto actual. |
| void [Write](./write/)(**double**) override | Envía la representación en cadena de un valor de punto flotante de doble precisión al flujo de salida representado por el objeto actual. |
| void [Write](./write/)(**int32_t**) override | Envía la representación en cadena de un valor entero de 32 bits al flujo de salida representado por el objeto actual. |
| void [Write](./write/)(**int64_t**) override | Envía la representación en cadena de un valor entero de 64 bits al flujo de salida representado por el objeto actual. |
| void [Write](./write/)(**float**) override | Envía la representación en cadena de un valor de punto flotante de precisión simple al flujo de salida representado por el objeto actual. |
| void [Write](./write/)(const [String](../string/)\&) override | Envía el objeto de cadena especificado al flujo de salida representado por el objeto actual. |
| void [Write](./write/)(**uint32_t**) override | Envía la representación en cadena de un entero sin signo de 32 bits al flujo de salida representado por el objeto actual. |
| void [Write](./write/)(**uint64_t**) override | Envía la representación en cadena de un entero sin signo de 64 bits al flujo de salida representado por el objeto actual. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Envía la representación en cadena del arreglo de caracteres especificado al flujo de salida representado por el objeto actual. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Envía la representación en cadena de un rango de valores del arreglo de caracteres especificado al flujo de salida representado por el objeto actual. |
| void [Write](./write/)(const char_t *) override | Envía la cadena C especificada al flujo de salida representado por el objeto actual. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Envía la representación en cadena del objeto [TypeInfo](../typeinfo/) especificado al flujo de salida representado por el objeto actual. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Escribe la representación en cadena del valor entero de 32 bits especificado al flujo. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Escribe los valores especificados formateados según el formato indicado al flujo. |
| void [WriteLine](./writeline/)() override | Envía el terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Envía la representación en cadena del objeto especificado seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(**bool**) override | Envía la representación en cadena del valor booleano especificado seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(char_t) override | Envía el carácter especificado seguido del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | Envía la representación en cadena del valor [Decimal](../decimal/) seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(**double**) override | Envía la representación en cadena de un valor de punto flotante de doble precisión seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(int) override | Envía la representación en cadena de un valor entero de 32 bits seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(**int64_t**) override | Envía la representación en cadena de un valor entero de 64 bits seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(**float**) override | Envía la representación en cadena de un valor de punto flotante de precisión simple seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Envía el objeto de cadena especificado seguido del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(**uint32_t**) override | Envía la representación en cadena de un entero sin signo de 32 bits seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(**uint64_t**) override | Envía la representación en cadena de un entero sin signo de 64 bits seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Envía la representación en cadena del arreglo de caracteres especificado seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Envía la representación en cadena de un rango de valores del arreglo de caracteres especificado seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(const char_t *) override | Envía la cadena C especificada seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Envía la representación en cadena del objeto [TypeInfo](../typeinfo/) especificado seguida del terminador de línea actual al flujo de salida representado por el objeto actual. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Escribe los valores especificados formateados según el formato indicado seguidos de los caracteres de terminación de línea al flujo. |
| virtual  [~Object](../object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Destructor. |

## Ver también

* Clase [TextWriter](../../system.io/textwriter/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)