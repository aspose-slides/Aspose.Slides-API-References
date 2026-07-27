---
title: IComparable
second_title: Referencia de la API de Aspose.Slides para C++
description: "Define un método que compara dos objetos. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila o usando operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase dentro de un puntero System::SmartPtr y utilice ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 924
url: /es/system/icomparable/
---
## IComparable clase

Define un método que compara dos objetos. Los objetos de esta clase solo deben asignarse mediante la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila o usando operator new, ya que provocará errores de tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase dentro de un puntero [System::SmartPtr](../smartptr/) y utilice ese puntero para pasarla a funciones como argumento.

```cpp
template<typename T>class IComparable : public virtual System::Object
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | El tipo de los objetos con los que se compara el objeto actual |

## Métodos

| Método | Descripción |
| --- | --- |
| virtual int [CompareTo](./compareto/)(T) | Compara el objeto actual con el objeto especificado. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sólo para uso interno. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogo del método C# [Object.GetHashCode()](../object/gethashcode/). Permite generar hash de objetos personalizados. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtiene el tipo real del objeto. Analogo de la llamada C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Analogo del operador C# 'is'. |
| void [Lock](../object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogo del método C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../object/object/)([Object](../object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de string y nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analogo del método C# [Object.ToString()](../object/tostring/). Permite convertir objetos personalizados a string. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa la construcción C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámelo directamente o use el objeto centinela [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [Object](../object/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)