---
title: EnumConverter
second_title: Referencia de API de Aspose.Slides para C++
description: "Clase ficticia para EnumConverter-using código traducido para compilar. Los objetos de esta clase deben asignarse únicamente usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 105
url: /es/system.componentmodel/enumconverter/
---
## EnumConverter clase

Clase ficticia para compilar con código traducido que utiliza EnumConverter. Los objetos de esta clase deben asignarse únicamente mediante la función [System::MakeObject()](../../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
class EnumConverter : public System::ComponentModel::TypeConverter
```

## Métodos

| Method | Descripción |
| --- | --- |
| **bool** [CanConvertFrom](./canconvertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) | Comprueba si los tipos son convertibles; no implementado. |
| **bool** [CanConvertTo](./canconvertto/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) | Comprueba si los tipos son convertibles; no implementado. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](./convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) override | Realiza la conversión de tipo real; no implementado. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](../typeconverter/convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Convierte objetos. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](../typeconverter/convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::String](../../system/string/)\&) | Convierte cadena a objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromInvariantString](../typeconverter/convertfrominvariantstring/)(const [System::String](../../system/string/)\&) | Convierte cadena invariante a objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromInvariantString](../typeconverter/convertfrominvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::String](../../system/string/)\&) | Convierte cadena invariante a objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../typeconverter/convertfromstring/)(const [System::String](../../system/string/)\&) | Convierte cadena a objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../typeconverter/convertfromstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::String](../../system/string/)\&) | Convierte cadena a objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../typeconverter/convertfromstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::String](../../system/string/)\&) | Convierte cadena a objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertTo](./convertto/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) override | Realiza la conversión de tipo real; no implementado. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertTo](../typeconverter/convertto/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) | Convierte objeto a tipo específico. |
| [System::String](../../system/string/) [ConvertToInvariantString](../typeconverter/converttoinvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Convierte el objeto a una cadena invariante. |
| [System::String](../../system/string/) [ConvertToInvariantString](../typeconverter/converttoinvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Convierte el objeto a una cadena invariante. |
| [System::String](../../system/string/) [ConvertToString](../typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Convierte el objeto a cadena. |
| [System::String](../../system/string/) [ConvertToString](../typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Convierte el objeto a cadena. |
| [System::String](../../system/string/) [ConvertToString](../typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Convierte el objeto a cadena. |
|  [EnumConverter](./enumconverter/)(const [System::TypeInfo](../../system/typeinfo/)\&) | Información RTTI. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| const [System::TypeInfo](../../system/typeinfo/)\& [get_EnumType](./get_enumtype/)() | Obtiene el tipo enum con el que [EnumConverter](./) está trabajando; no implementado. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoga al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Analoga a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Analoga al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o utilice el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoga al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias en subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoga al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
|  [TypeConverter](../typeconverter/typeconverter/)() | Constructor. |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o utilice el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [TypeConverter](../typeconverter/)
* Espacio de nombres [System::ComponentModel](../)
* Biblioteca [Aspose.Slides](../../)