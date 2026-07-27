---
title: NumberFormatInfo
second_title: Referencia de API de Aspose.Slides para C++
description: "Contiene información sobre cómo formatear números. Las operaciones de asignación solo están habilitadas en objetos que no son de solo lectura. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 248
url: /es/system.globalization/numberformatinfo/
---
## NumberFormatInfo clase

Contiene información sobre cómo formatear números. Las operaciones de asignación solo están habilitadas en objetos que no son de solo lectura. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarla a funciones como argumento.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Clona la información de formato. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Obtiene el número de dígitos decimales de la moneda. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Obtiene el separador decimal de la moneda. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Obtiene el separador de grupos de la moneda. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Obtiene el número de dígitos decimales de la moneda por grupo. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Obtiene el patrón negativo de la moneda. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Obtiene el patrón positivo de la moneda. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Obtiene el símbolo de la moneda. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Obtiene la información de formato numérico definida por la cultura del subproceso actual. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | Obtiene un valor que especifica cómo mostrar la forma de un dígito. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Obtiene la información de formato numérico definida por la cultura invariante. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Comprueba si el formato es de solo lectura. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Obtiene el símbolo Not-a-Number. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | Obtiene los símbolos de los dígitos (0 al 9). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Obtiene el símbolo de infinito negativo. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | Obtiene el signo negativo. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Obtiene el número de dígitos decimales. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Obtiene el separador decimal. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Obtiene el separador de grupos numéricos. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Obtiene la cantidad de dígitos por grupo. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Obtiene el patrón negativo del número. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Obtiene el número de decimales en valores de porcentaje. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Obtiene el separador decimal en valores de porcentaje. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Obtiene el separador de grupos en valores de porcentaje. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Obtiene la cantidad de dígitos por grupo de valores de porcentaje. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Obtiene el patrón negativo del porcentaje. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Obtiene el patrón positivo del porcentaje. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | Obtiene el símbolo de porcentaje. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | Obtiene el símbolo de por mil. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Obtiene el símbolo de infinito positivo. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | Obtiene el signo positivo. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Obtiene el formateador de tipo específico. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hashing de objetos personalizados. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Obtiene el formateador asociado al proveedor de formato. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Analogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Analogo del operador C# 'is'. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite la clonación de tipos personalizados. |
|   [NumberFormatInfo](./numberformatinfo/)() | Constructor predeterminado (invariante [NumberFormatInfo](./)). |
|   [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Obtiene la versión de solo lectura del formateador. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Establece el número de dígitos decimales de la moneda. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | Establece el separador decimal de la moneda. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | Establece el separador de grupos de la moneda. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Establece el número de dígitos decimales de la moneda por grupo. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Establece el patrón negativo de la moneda. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Establece el patrón positivo de la moneda. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | Establece el símbolo de la moneda. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | Establece un valor que especifica cómo mostrar la forma de un dígito. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Establece el símbolo Not-a-Number. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Establece los símbolos de los dígitos (0 al 9). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | Establece el símbolo de infinito negativo. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | Establece el signo negativo. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Establece el número de dígitos decimales. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | Establece el separador decimal. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | Establece el separador de grupos numéricos. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Establece la cantidad de dígitos por grupo. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Establece el patrón negativo del número. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Establece el número de decimales en valores de porcentaje. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | Establece el separador decimal en valores de porcentaje. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | Establece el separador de grupos en valores de porcentaje. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Establece la cantidad de dígitos por grupo de valor de porcentaje. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Establece el patrón negativo del porcentaje. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Establece el patrón positivo del porcentaje. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | Establece el símbolo de porcentaje. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | Establece el símbolo de por mil. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | Establece el símbolo de infinito positivo. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | Establece el signo positivo. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [Object](../../system/object/)
* Clase [IFormatProvider](../../system/iformatprovider/)
* Clase [ICloneable](../../system/icloneable/)
* Espacio de nombres [System::Globalization](../)
* Biblioteca [Aspose.Slides](../../)