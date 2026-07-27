---
title: Details_Exception
second_title: Referencia de la API de Aspose.Slides para C++
description: "Representa una excepción. Nunca cree instancias de esta clase manualmente. Use la clase Exception en su lugar. Nunca envuelva las instancias de la clase Exception en System::SmartPtr."
type: docs
weight: 417
url: /es/system/details_exception/
---
## Details_Exception clase

Representa una excepción. Nunca cree instancias de esta clase manualmente. Use la clase Exception en su lugar. Nunca envuelva las instancias de la clase Exception dentro de [System::SmartPtr](../smartptr/).

```cpp
class Details_Exception : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual void [DoThrow](./dothrow/)(const [ExceptionPtr](../exceptionptr/)\&) const | Lanza la instancia de excepción envuelta por el contenedor de excepciones. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](./get_data/)() | Devuelve un diccionario con datos de excepción personalizados. |
| **int32_t** [get_HResult](./get_hresult/)() const | Devuelve un valor entero de 32 bits que es un código HRESULT asociado con la excepción representada por el objeto actual. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](./)\> [get_InnerException](./get_innerexception/)() const | Devuelve una referencia al objeto que representa la excepción interna. |
| virtual [String](../string/) [get_Message](./get_message/)() const | Devuelve la cadena que contiene la descripción del error. |
| virtual [String](../string/) [get_StackTrace](./get_stacktrace/)() const | Devuelve la cadena que contiene el rastreo de pila. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](./)\> [GetBaseException](./getbaseexception/)() const | Devuelve una copia del objeto Exception que representa la excepción más interna. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../object/object/)([Object](../object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia constructora de subclases. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la copia constructora de subclases. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_HResult](./set_hresult/)(**int32_t**) | Establece el HRESULT, un valor numérico codificado que se asigna a una excepción específica. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Devuelve la representación en cadena del objeto actual. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa la construcción C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual const char * [what](./what/)() const | Implementa el método [what()](./what/) que es llamado por la clase [ExceptionWrapper](../exceptionwrapper/). A pesar de que esta clase no hereda de std::exception, las clases derivadas pueden usar miembros protegidos/privados para implementar su lógica. Mover la implementación de este método al [ExceptionWrapper](../exceptionwrapper/) podría romper esa lógica. |
| virtual  [~Object](../object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [Object](../object/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)