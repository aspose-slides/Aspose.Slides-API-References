---
title: WeakPtr
second_title: Referencia de la API de Aspose.Slides para C++
description: "Subclase de System::SmartPtr que se establece en modo débil en la construcción. Tenga en cuenta que esta clase no garantiza que su instancia permanezca siempre en modo débil ya que set_Mode() sigue siendo accesible. Este tipo es un puntero para gestionar la eliminación de otros objetos. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante."
type: docs
weight: 1496
url: /es/system/weakptr/
---
## WeakPtr clase

Subclase de [System::SmartPtr](../smartptr/) que se establece en modo débil en la construcción. Tenga en cuenta que esta clase no garantiza que su instancia permanezca siempre en modo débil ya que [set_Mode()](../smartptr/set_mode/) sigue siendo accesible. Este tipo es un puntero para administrar la eliminación de objetos externos. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo al que apunta. |

## Métodos

| Método | Descripción |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Accesor del método [begin()](../smartptr/begin/) de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Accesor del método [begin()](../smartptr/begin/) de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convierte el puntero a su propio tipo. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convierte el puntero al tipo base usando static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convierte el puntero al tipo derivado usando dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convierte el puntero al tipo derivado usando dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Accesor del método [cbegin()](../smartptr/cbegin/) de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Accesor del método [cend()](../smartptr/cend/) de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando const_cast en el objeto apuntado. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando dynamic_cast en el objeto apuntado. |
| auto [end](../smartptr/end/)() | Accesor del método [end()](../smartptr/end/) de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Accesor del método [end()](../smartptr/end/) de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método [end()](../smartptr/end/). |
| **bool** [expired](./expired/)() const | Comprueba si el objeto referenciado ya fue eliminado. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Obtiene el objeto apuntado. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Obtiene el modo del puntero. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Obtiene el objeto apuntado, pero asegura que el puntero está en modo compartido. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Obtiene el número de punteros compartidos que existen al objeto referenciado, incluido el actual. Asegura que el puntero actual está en modo compartido. |
| [Object](../object/) * [get_weak](./get_weak/)() const | Obtiene el objeto referenciado. Asegura que el puntero está en modo débil. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Llama a [GetHashCode()](../smartptr/gethashcode/) en el objeto apuntado. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Obtiene el objeto referenciado actualmente (si lo hay) o lanza una excepción. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Obtiene el objeto apuntado (si lo hay) o nullptr. Igual que [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Obtiene el objeto referenciado. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Obtiene el objeto apuntado (si lo hay) o nullptr. Igual que [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Comprueba si el objeto apuntado es de un tipo específico o de su tipo hijo. Sigue la semántica 'is' de C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Comprueba si el puntero apunta a otro objeto distinto al propio (creado por un constructor de alias). |
| **bool** [IsShared](../smartptr/isshared/)() const | Comprueba si el puntero está en modo compartido. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Comprueba si el puntero está en modo débil. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Comprueba si el puntero no es nulo. |
| **bool** [operator!](../smartptr/operator_not/)() const | Comprueba si el puntero es nulo. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Obtiene una referencia al objeto apuntado. Asegura que el puntero no sea nulo. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Permite acceder a los miembros del objeto referenciado. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Proporciona la semántica de comparación menor para la clase [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Proporciona la semántica de comparación menor para la clase [SmartPtr](../smartptr/). |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | Asigna un valor al puntero débil. Llama al operador de asignación específico de SmartPtr_. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Asignación por movimiento del objeto [SmartPtr](../smartptr/). x queda inusable. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Asignación por copia del objeto [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Asignación por copia del objeto [SmartPtr](../smartptr/). Realiza las conversiones de tipo necesarias. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | Asigna un puntero crudo al objeto [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | Establece el valor del puntero a nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Comprueba si el puntero débil es nulo. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Elimina el alias (creado por un constructor de alias) del puntero, asegurándose de que gestiona (si es compartido) o rastrea (si es débil) el mismo objeto al que apunta. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Establece el objeto apuntado. |
| void [reset](../smartptr/reset/)() | Hace que el puntero apunte a nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Establece el modo del puntero. Puede alterar los contadores de referencia del objeto referenciado. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Llama al método SetTemplateWeakPtr() en el objeto apuntado (si lo hay). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Crea un objeto [SmartPtr](../smartptr/) del modo requerido. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Crea un objeto [SmartPtr](../smartptr/) de puntero nulo del modo requerido. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Crea un [SmartPtr](../smartptr/) que apunta al objeto especificado, o convierte un puntero crudo a [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Construye por copia un objeto [SmartPtr](../smartptr/). Ambos punteros apuntan al mismo objeto después. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Construye por copia un objeto [SmartPtr](../smartptr/). Ambos punteros apuntan al mismo objeto después. Realiza la conversión de tipos si está permitida. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Construye por movimiento un objeto [SmartPtr](../smartptr/). En esencia, intercambia dos punteros, si ambos están en el mismo modo. x puede quedar inusable después de la llamada. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Convierte el tipo del arreglo referenciado creando un nuevo arreglo de tipo diferente. Útil si en C# hay una conversión de tipo de arreglo que no está soportada en C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Inicializa un arreglo vacío. Utilizado para traducir algunas construcciones de código C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Construye un [SmartPtr](../smartptr/) que comparte información de propiedad con el valor inicial de ptr, pero mantiene un puntero no relacionado y no gestionado p. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando static_cast en el objeto apuntado. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Convierte cualquier tipo de puntero a un puntero a [Object](../object/). No requiere que el tipo Pointee_ esté completo. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Acceso rápido para obtener el objeto [System::TypeInfo](../typeinfo/) para el tipo Pointee_. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | Crea un puntero nulo. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | Crea un puntero débil al objeto dado. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Crea un puntero débil que referencia el mismo puntero al que apunta ptr. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Crea un puntero débil que referencia el mismo puntero al que apunta x. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | Construye por copia un puntero débil. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | Construye por copia un puntero débil. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Construye por movimiento un puntero débil. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Destruye el objeto [SmartPtr](../smartptr/). Si es necesario, disminuye el contador de referencias del objeto apuntado y elimina el objeto. |

## Tipos definidos

| Typedef | Descripción |
| --- | --- |
| [SmartPtr_](./smartptr_/) | Alias para la clase [SmartPtr](../smartptr/) correspondiente. |
| [WeakPtr_](./weakptr_/) | Alias para el tipo propio. |
| [Pointee_](./pointee_/) | Tipo apuntado. |

## Ver también

* Clase [SmartPtr](../smartptr/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)