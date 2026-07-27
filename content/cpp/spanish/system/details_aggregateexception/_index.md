---
title: Details_AggregateException
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa una excepción que contiene múltiples excepciones internas.
type: docs
weight: 300
url: /es/system/details_aggregateexception/
---
## Details_AggregateException clase


Representa una excepción que contiene múltiples excepciones internas.

```cpp
class Details_AggregateException : public System::Details_Exception
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para propósitos internos. |
| [AggregateException](../aggregateexception/) [Flatten](./flatten/)() | Aplana la excepción agregada desenrollando todas las AggregateExceptions anidadas en una lista de un solo nivel. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Devuelve un diccionario con datos de excepción personalizados. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Devuelve un valor entero de 32 bits que es un código HRESULT asociado con la excepción representada por el objeto actual. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Devuelve una referencia al objeto que representa la excepción interna. |
| **int32_t** [get_InnerExceptionCount](./get_innerexceptioncount/)() | Obtiene el número de excepciones internas contenidas en esta excepción agregada. |
| [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[Exception](../exception/)\>\> [get_InnerExceptions](./get_innerexceptions/)() | Obtiene una colección de solo lectura de las excepciones internas. |
| const [ArrayPtr](../arrayptr/)\<[Exception](../exception/)\>\& [get_InternalInnerExceptions](./get_internalinnerexceptions/)() | Devuelve el arreglo interno de excepciones internas. |
| [String](../string/) [get_Message](./get_message/)() const override | Sobrescribe el mensaje base para incluir información agregada de todas las excepciones internas. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Devuelve la cadena que contiene la traza de pila. |
| [Exception](../exception/) [GetBaseException](./getbaseexception/)() const override | Devuelve la excepción causa raíz desenrollando recursivamente las excepciones internas. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../object/gettype/). |
| void [Handle](./handle/)(const [Func](../func/)\<[Exception](../exception/), **bool**\>\&) | Invoca una función manejadora en cada excepción interna y vuelve a lanzar cualquier excepción no manejada. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../object/lock/)() | Implementa la instrucción C# lock() bloqueando. Llámela directamente o use el objeto centinela [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../object/object/)() | Crea el objeto. Inicializa todas las estructuras internas de datos. |
|  [Object](../object/object/)([Object](../object/) const\&) | Constructor de copia. No copia nada, realmente, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de asignación. No copia nada, realmente, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Establece HRESULT, un valor numérico codificado que se asigna a una excepción específica. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Devuelve una representación en cadena de la excepción, incluyendo todas las excepciones internas. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa la construcción C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa la instrucción C# lock() desbloqueando. Llámela directamente o use el objeto centinela [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implementa el método [what()](../details_exception/what/) que es llamado por la clase [ExceptionWrapper](../exceptionwrapper/). A pesar de que esta clase no hereda de std::exception, las clases derivadas pueden usar miembros protegidos/privados para implementar su lógica. Mover la implementación de este método al [ExceptionWrapper](../exceptionwrapper/) podría romper esa lógica. |
| virtual  [~Object](../object/~object/)() | Destruye el objeto. Libera todas las estructuras internas de datos. |

## Observaciones


Esta clase se usa típicamente para agrupar varias excepciones que ocurren simultáneamente, como en escenarios de procesamiento paralelo o ejecución de tareas asíncronas. Permite a los usuarios examinar, aplanar o manejar selectivamente las excepciones contenidas. 
## Ver también

* Clase [Details_Exception](../details_exception/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)