---
title: PropertyInfo
second_title: Referencia de API de Aspose.Slides para C++
description: Representa información de la propiedad.
type: docs
weight: 144
url: /es/system.reflection/propertyinfo/
---
## PropertyInfo clase

Representa información de la propiedad.

```cpp
class PropertyInfo : public System::Reflection::MemberInfo
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [AddAttribute](../memberinfo/addattribute/)(const [ObjectPtr](../memberinfo/objectptr/)\&) | Añade atributo a la colección. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante C#-style donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante C#-style donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [TypeInfo](../../system/typeinfo/) [get_DeclaringType](../memberinfo/get_declaringtype/)() const | Obtiene el tipo declarador. |
| const [String](../../system/string/)\& [get_FullName](../memberinfo/get_fullname/)() const | Obtiene el nombre completo del miembro. Puede ser diferente en partes implementadas manualmente. |
| [MemberTypes](../membertypes/) [get_MemberType](./get_membertype/)() const override | Obtiene un valor MemberTypes que indica que este miembro es una propiedad. |
| const [String](../../system/string/)\& [get_Name](../memberinfo/get_name/)() const | Obtiene el nombre del miembro. |
| [TypeInfo](../../system/typeinfo/) [get_PropertyType](./get_propertytype/)() | Obtiene el tipo de la propiedad. |
| [TypeInfo](../../system/typeinfo/) [get_ReflectedType](../memberinfo/get_reflectedtype/)() const | Obtiene el tipo reflejado. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&, **bool**) const | Devuelve una matriz que contiene objetos que representan todos los atributos personalizados aplicados al tipo representado por el objeto actual. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(**bool**) const | Devuelve una matriz que contiene objetos que representan todos los atributos personalizados aplicados al tipo representado por el objeto actual. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [GetValue](./getvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Obtiene el valor de la propiedad de un objeto específico. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [GetValue](./getvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>) | Obtiene el valor de la propiedad de un objeto específico. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite la clonación de tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const) | Constructor. Propiedad con solo getter const. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)()) | Constructor. Propiedad con solo getter no const. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::SharedPtr](../../system/sharedptr/)\<PropertyType\>), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const) | Constructor. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Nullable](../../system/nullable/)\<NullableType\>), [System::Nullable](../../system/nullable/)\<NullableType\>(ClassType::*)()) | Constructor. [Nullable](../../system/nullable/) propiedad con setter y getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Nullable](../../system/nullable/)\<NullableType\>), [System::Nullable](../../system/nullable/)\<NullableType\>(ClassType::*)() const) | Constructor. [Nullable](../../system/nullable/) propiedad con solo getter const. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::SharedPtr](../../system/sharedptr/)\<PropertyType\>), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)()) | Constructor. [Object](../../system/object/) propiedad con solo getter. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::String](../../system/string/)), [System::String](../../system/string/)(ClassType::*)()) | Construye información de propiedad de cadena. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::String](../../system/string/)), [System::String](../../system/string/)(ClassType::*)() const) | Construye información de propiedad de cadena a partir de una clase con getter const. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Decimal](../../system/decimal/)), [System::Decimal](../../system/decimal/)(ClassType::*)()) | Construye [Decimal](../../system/decimal/) información de propiedad. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Decimal](../../system/decimal/)), [System::Decimal](../../system/decimal/)(ClassType::*)() const) | Construye [Decimal](../../system/decimal/) información de propiedad a partir de una clase con getter const. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**bool**), **bool**(ClassType::*)()) | Construye información de propiedad booleana. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**bool**), **bool**(ClassType::*)() const) | Construye información de propiedad booleana a partir de una clase con getter const. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**int64_t**), **int64_t**(ClassType::*)()) | Construye información de propiedad **int64_t**. |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**int64_t**), **int64_t**(ClassType::*)() const) | Construye información de propiedad **int64_t** a partir de una clase con getter const. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el conteo de referencias compartidas en el valor especificado. |
| void [set_PropertyType](./set_propertytype/)(const [TypeInfo](../../system/typeinfo/)\&) | Establece el tipo de esta propiedad. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| void [SetValue](./setvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Establece el valor de la propiedad a un objeto específico. |
| void [SetValue](./setvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>) | Establece el valor de la propiedad a un objeto específico. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el conteo de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el conteo de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el conteo de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el conteo de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [MemberInfo](../memberinfo/)
* Espacio de nombres [System::Reflection](../)
* Biblioteca [Aspose.Slides](../../)