---
title: DefaultBoxedValue
second_title: Referencia de la API de Aspose.Slides para C++
description: "Implementación de la clase BoxedValue. Permite que las especializaciones de BoxingValue se declaren sin duplicar código común. Los objetos de esta clase solo deben asignarse usando la función System::MakeObject(). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero System::SmartPtr y use ese puntero para pasarlo a funciones como argumento."
type: docs
weight: 274
url: /es/system/defaultboxedvalue/
---
## Clase DefaultBoxedValue


[BoxedValue](../boxedvalue/) implementación de clase. Permite que las especializaciones de BoxingValue se declaren sin duplicar código común. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../makeobject/). Nunca cree una instancia de este tipo en la pila ni usando el operador new, ya que provocará errores en tiempo de ejecución y/o fallas de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../smartptr/) y use ese puntero para pasarlo a funciones como argumento.

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
|  [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | Construye una nueva instancia de la clase [DefaultBoxedValue](./) que representa el valor especificado. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | Determina la igualdad de los valores boxed representados por el objeto actual y el especificado. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sólo para propósitos internos. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| int [GetHashCode](./gethashcode/)() const override | Devuelve un código hash para el objeto actual. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Obtiene el tipo real del objeto. |
| **bool** [is](./is/)() const | Determina si el tipo del valor boxed representado por el objeto actual es **V**. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../object/object/)([Object](../object/) const\&) | Constructor de copia. No copia nada, simplemente inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de asignación. No copia nada, simplemente inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialización de [Object::ReferenceEquals](../object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Reduce el contador de referencias compartidas en el valor especificado. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Devuelve la representación en cadena del valor boxed. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa la construcción C# typeof([System.Object](../object/)). |
| const T\& [unbox](./unbox/)() const | Desempaqueta el valor boxed. |
| void [Unlock](../object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [Object](../object/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)