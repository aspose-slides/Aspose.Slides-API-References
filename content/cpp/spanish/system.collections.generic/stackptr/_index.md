---
title: StackPtr
second_title: Referencia de API de Aspose.Slides para C++
description: Puntero de pila. Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante.
type: docs
weight: 612
url: /es/system.collections.generic/stackptr/
---
## Clase StackPtr

[Stack](../stack/) puntero. Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante.

```cpp
template<typename T>class StackPtr : public System::SmartPtr<Stack<T>>
```

### Parámetros de plantilla

| Parameter | Description |
| --- | --- |
| T | Element type. |

## Métodos

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Accesor del método [begin()](../../system/smartptr/begin/) de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Accesor del método [begin()](../../system/smartptr/begin/) de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convierte el puntero a su propio tipo. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convierte el puntero al tipo base usando static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convierte el puntero al tipo derivado usando dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convierte el puntero al tipo derivado usando dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Accesor del método [cbegin()](../../system/smartptr/cbegin/) de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Accesor del método [cend()](../../system/smartptr/cend/) de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando const_cast sobre el objeto apuntado. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando dynamic_cast sobre el objeto apuntado. |
| auto [end](../../system/smartptr/end/)() | Accesor del método [end()](../../system/smartptr/end/) de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Accesor del método [end()](../../system/smartptr/end/) de una colección subyacente. Solo se compila si SmartPtr_ es un tipo de especialización con el método [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Obtiene el objeto apuntado. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Obtiene el modo del puntero. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Obtiene el objeto apuntado, pero afirma que el puntero está en modo compartido. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Obtiene el número de punteros compartidos que existen al objeto referenciado, incluyendo el actual. Afirma que el puntero actual está en modo compartido. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Invoca [GetHashCode()](../../system/smartptr/gethashcode/) en el objeto apuntado. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Obtiene el objeto referenciado actualmente (si existe) o lanza una excepción. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Obtiene el objeto apuntado (si existe) o nullptr. Igual que [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Obtiene el objeto referenciado. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Obtiene el objeto apuntado (si existe) o nullptr. Igual que [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto apuntado es de un tipo específico o de su tipo hijo. Sigue la semántica 'is' de C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Comprueba si el puntero apunta a otro objeto distinto al propio (creado por un constructor alias). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Comprueba si el puntero está en modo compartido. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Comprueba si el puntero está en modo débil. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Comprueba si el puntero no es nulo. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Comprueba si el puntero es nulo. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Obtiene una referencia al objeto apuntado. Afirma que el puntero no es nulo. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Permite acceder a los miembros del objeto referenciado. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Proporciona semántica de comparación menor para la clase [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Proporciona semántica de comparación menor para la clase [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Asigna por movimiento el objeto [SmartPtr](../../system/smartptr/). x queda inutilizable. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Asigna por copia el objeto [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Asigna por copia el objeto [SmartPtr](../../system/smartptr/). Realiza las conversiones de tipo necesarias. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Asigna un puntero crudo al objeto [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Establece el valor del puntero a nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Comprueba si el puntero apunta a nullptr. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Elimina el alias (creado por un constructor alias) del puntero, asegurando que gestiona (si es compartido) o rastrea (si es débil) el mismo objeto al que apunta. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Establece el objeto apuntado. |
| void [reset](../../system/smartptr/reset/)() | Hace que el puntero apunte a nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Establece el modo del puntero. Puede alterar los conteos de referencias del objeto referenciado. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Invoca el método SetTemplateWeakPtr() en el objeto apuntado (si existe). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Crea un objeto [SmartPtr](../../system/smartptr/) del modo requerido. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Crea un objeto [SmartPtr](../../system/smartptr/) de puntero nulo del modo requerido. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Crea un [SmartPtr](../../system/smartptr/) que apunta al objeto especificado, o convierte un puntero crudo a [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Construye por copia un objeto [SmartPtr](../../system/smartptr/). Ambos punteros apuntan al mismo objeto posteriormente. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Construye por copia un objeto [SmartPtr](../../system/smartptr/). Ambos punteros apuntan al mismo objeto posteriormente. Realiza conversión de tipo si está permitida. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Construye por movimiento un objeto [SmartPtr](../../system/smartptr/). Efectivamente, intercambia dos punteros, si ambos están en el mismo modo. x puede quedar inutilizable después de la llamada. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Convierte el tipo del array referenciado creando un nuevo array de tipo diferente. Útil si en C# hay un casting de tipo de array que no está soportado en C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Inicializa un array vacío. Utilizado para traducir ciertos constructos de código C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Construye un [SmartPtr](../../system/smartptr/) que comparte información de propiedad con el valor inicial de ptr, pero posee un puntero no relacionado y no gestionado p. |
|  [StackPtr](./stackptr/)() | Construye un puntero nulo. |
|  [StackPtr](./stackptr/)(const [SharedPtr](../../system/sharedptr/)\<[Stack](../stack/)\<T\>\>\&) | Construye un puntero que referencia una pila específica. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando static_cast sobre el objeto apuntado. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Convierte cualquier tipo de puntero a puntero a [Object](../../system/object/). No requiere que el tipo Pointee_ esté completo. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Acceso directo para obtener el objeto [System::TypeInfo](../../system/typeinfo/) del tipo Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Destruye el objeto [SmartPtr](../../system/smartptr/). Si es necesario, disminuye el contador de referencias del objeto apuntado y elimina el objeto. |

## Ver también

* Clase [SmartPtr](../../system/smartptr/)
* Espacio de nombres [System::Collections::Generic](../)
* Biblioteca [Aspose.Slides](../../)