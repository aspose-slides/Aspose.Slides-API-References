---
title: X509CertificateCollectionPtr
second_title: Referencia de API de Aspose.Slides para C++
description: Puntero a una colección de certificados X509. Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante.
type: docs
weight: 92
url: /es/system.security.cryptography.x509certificates/x509certificatecollectionptr/
---
## X509CertificateCollectionPtr clase


Puntero a una colección de certificados X509. Este tipo es un puntero para gestionar la eliminación de otro objeto. Debe asignarse en la pila y pasarse a funciones ya sea por valor o por referencia constante.

```cpp
class X509CertificateCollectionPtr : public System::SmartPtr<X509CertificateCollection>
```

## Métodos

| Método | Descripción |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Accesor para el método [begin()](../../system/smartptr/begin/) de una colección subyacente. Solo compila si SmartPtr_ es un tipo de especialización con el método [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Accesor para el método [begin()](../../system/smartptr/begin/) de una colección subyacente. Solo compila si SmartPtr_ es un tipo de especialización con el método [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convierte el puntero a su propio tipo. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convierte el puntero al tipo base usando static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convierte el puntero al tipo derivado usando dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convierte el puntero al tipo derivado usando dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Accesor para el método [cbegin()](../../system/smartptr/cbegin/) de una colección subyacente. Solo compila si SmartPtr_ es un tipo de especialización con el método [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Accesor para el método [cend()](../../system/smartptr/cend/) de una colección subyacente. Solo compila si SmartPtr_ es un tipo de especialización con el método [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando const_cast sobre el objeto apuntado. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando dynamic_cast sobre el objeto apuntado. |
| auto [end](../../system/smartptr/end/)() | Accesor para el método [end()](../../system/smartptr/end/) de una colección subyacente. Solo compila si SmartPtr_ es un tipo de especialización con el método [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Accesor para el método [end()](../../system/smartptr/end/) de una colección subyacente. Solo compila si SmartPtr_ es un tipo de especialización con el método [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Obtiene el objeto apuntado. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Obtiene el modo del puntero. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Obtiene el objeto apuntado, pero afirma que el puntero está en modo compartido. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Obtiene el número de punteros compartidos existentes al objeto referenciado, incluido el actual. Afirma que el puntero actual está en modo compartido. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Llama a [GetHashCode()](../../system/smartptr/gethashcode/) en el objeto apuntado. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Obtiene el objeto referenciado actualmente (si lo hay) o lanza una excepción. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Obtiene el objeto apuntado (si lo hay) o nullptr. Igual que [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Obtiene el objeto referenciado. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Obtiene el objeto apuntado (si lo hay) o nullptr. Igual que [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto apuntado es de un tipo específico o de su tipo hijo. Sigue la semántica 'is' de C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Comprueba si el puntero apunta a otro objeto distinto del que posee (creado por un constructor de alias). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Comprueba si el puntero está en modo compartido. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Comprueba si el puntero está en modo débil. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Comprueba si el puntero no es nulo. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Comprueba si el puntero es nulo. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Obtiene una referencia al objeto apuntado. Asegura que el puntero no es nulo. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Permite acceder a los miembros del objeto referenciado. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Proporciona semántica de comparación menor para la clase [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Proporciona semántica de comparación menor para la clase [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Asigna por movimiento el objeto [SmartPtr](../../system/smartptr/). x queda inutilizable. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Asigna por copia el objeto [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Asigna por copia el objeto [SmartPtr](../../system/smartptr/). Realiza las conversiones de tipo necesarias. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Asigna el puntero crudo al objeto [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Establece el valor del puntero a nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Comprueba si el puntero apunta a nullptr. |
| [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\& [operator[]](./operator[]/)(int) const | Accesor. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Elimina el alias (creado por un constructor de alias) del puntero, asegurando que gestiona (si es compartido) o rastrea (si es débil) el mismo objeto al que apunta. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Establece el objeto apuntado. |
| void [reset](../../system/smartptr/reset/)() | Haz que el puntero apunte a nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Establece el modo del puntero. Puede alterar los recuentos de referencias del objeto referenciado. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Llama al método SetTemplateWeakPtr() en el objeto apuntado (si lo hay). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Crea un objeto [SmartPtr](../../system/smartptr/) del modo requerido. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Crea un objeto [SmartPtr](../../system/smartptr/) de puntero nulo del modo requerido. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Crea [SmartPtr](../../system/smartptr/) que apunta al objeto especificado, o convierte el puntero crudo a [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Construye por copia el objeto [SmartPtr](../../system/smartptr/). Ambos punteros apuntan al mismo objeto después. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Construye por copia el objeto [SmartPtr](../../system/smartptr/). Ambos punteros apuntan al mismo objeto después. Realiza la conversión de tipo si está permitida. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Construye por movimiento el objeto [SmartPtr](../../system/smartptr/). Efectivamente, intercambia dos punteros, si ambos están en el mismo modo. x puede quedar inutilizable después de la llamada. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Convierte el tipo de la matriz referenciada creando una nueva matriz de tipo diferente. Útil si en C# existe un casting de tipo de matriz que no es compatible en C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Inicializa una matriz vacía. Utilizado para traducir algunas construcciones de código en C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Construye un [SmartPtr](../../system/smartptr/) que comparte la información de propiedad con el valor inicial de ptr, pero contiene un puntero p no relacionado y no administrado. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Convierte el puntero a un tipo diferente usando static_cast sobre el objeto apuntado. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Convierte cualquier tipo de puntero a un puntero a [Object](../../system/object/). No requiere que el tipo Pointee_ esté completo. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Atajo para obtener el objeto [System::TypeInfo](../../system/typeinfo/) para el tipo Pointee_. |
|  [X509CertificateCollectionPtr](./x509certificatecollectionptr/)() | Constructor de puntero nulo. |
|  [X509CertificateCollectionPtr](./x509certificatecollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509CertificateCollection](../x509certificatecollection/)\>\&) | Constructor. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Destruye el objeto [SmartPtr](../../system/smartptr/). Si es necesario, disminuye el contador de referencias del objeto apuntado y elimina el objeto. |

## Ver también

* Clase [SmartPtr](../../system/smartptr/)
* Espacio de nombres [System::Security::Cryptography::X509Certificates](../)
* Biblioteca [Aspose.Slides](../../)