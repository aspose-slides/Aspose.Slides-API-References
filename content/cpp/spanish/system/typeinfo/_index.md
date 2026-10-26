---
title: TypeInfo
second_title: Referencia de API de Aspose.Slides para C++
description: Representa un tipo particular y proporciona información sobre él.
type: docs
weight: 1379
url: /es/system/typeinfo/
---
## TypeInfo clase

Representa un tipo particular y proporciona información sobre él.

```cpp
class TypeInfo
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Agrega el atributo especificado a la lista de atributos del tipo. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Establece el constructor predeterminado para el tipo T. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Establece el constructor predeterminado mediante el functor que crea la instancia de la clase. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Agrega el miembro especificado a la lista de miembros del tipo. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Proporciona una estructura [TypeInfo](./) única para el tipo **BoxedValue** que será compartida por múltiples clases Boxed*. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | NO IMPLEMENTADO. Devuelve un puntero al ensamblado en el que se declara el tipo representado por el objeto actual. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | NO IMPLEMENTADO. Devuelve el nombre completamente calificado, incluido el nombre del ensamblado, del tipo representado por el objeto actual. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Devuelve el descriptor del tipo base. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Obtiene un valor que indica si el objeto Type actual tiene parámetros de tipo que no han sido reemplazados por tipos específicos. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Obtiene la lista de los miembros con el nombre especificado. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Devuelve el nombre completamente calificado (pero sin el nombre del ensamblado) del tipo representado por el objeto actual. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Obtiene una matriz de los argumentos de tipo genérico para este tipo. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Obtiene un valor que indica si el Type es abstracto y debe ser sobrescrito. |
| **bool** [get_IsArray](./get_isarray/)() const | Obtiene un valor que indica si el tipo es una matriz. |
| **bool** [get_IsClass](./get_isclass/)() const | Obtiene un valor que indica si el Type es una clase o un delegado; es decir, que no es un tipo de valor o una interfaz. |
| **bool** [get_IsEnum](./get_isenum/)() const | Obtiene un valor que indica si el Type actual representa una enumeración. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Obtiene un valor que indica si el Type actual representa una definición de tipo genérico, a partir de la cual se pueden construir otros tipos genéricos. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Obtiene un valor que indica si el Type es una interfaz; es decir, que no es una clase o un tipo de valor. |
| **bool** [get_IsSealed](./get_issealed/)() const | Obtiene un valor que indica si el Type está declarado sellado. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Obtiene un valor que indica si el Type es un tipo de valor. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Obtiene un valor que indica si el Type puede ser accedido por código fuera del ensamblado. |
| [String](../string/) [get_Name](./get_name/)() const | Devuelve el nombre del tipo representado por el objeto actual. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Obtiene el espacio de nombres del Type. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Busca un constructor de instancia pública cuyos parámetros coincidan con los tipos en la matriz especificada. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Busca los constructores definidos para el Type actual, utilizando los BindingFlags especificados. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Devuelve todos los constructores públicos definidos para el Type actual. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Busca el atributo personalizado aplicado que tenga el tipo especificado y que esté aplicado al tipo representado por el objeto actual. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Devuelve una matriz que contiene objetos que representan todos los atributos personalizados aplicados al tipo. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Devuelve una matriz que contiene objetos que representan atributos específicos aplicados al tipo. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | NO IMPLEMENTADO. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Busca el campo especificado, usando las restricciones de enlace especificadas. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Busca los campos definidos para el Type actual, usando las restricciones de enlace especificadas. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | Obtiene una matriz de los argumentos de tipo genérico para este tipo. |
| int [GetHashCode](./gethashcode/)() const | Devuelve un código hash asociado a esta instancia. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Obtiene todas las interfaces implementadas o heredadas por el Type actual. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Obtiene la lista de los miembros con el nombre especificado. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Obtiene el método con el nombre especificado. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Devuelve todas las propiedades públicas del Type actual. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Busca las propiedades del Type actual, usando las restricciones de enlace especificadas. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Obtiene el descriptor del tipo de parámetro de plantilla. |
| **uint32_t** [Hash](./hash/)() const | Devuelve un valor hash asociado al tipo representado por el objeto actual. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Determina si una instancia de un tipo especificado puede asignarse a una variable del tipo actual. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | NO IMPLEMENTADO. Indica si uno o más atributos del tipo especificado o de sus tipos derivados están aplicados a este miembro. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Determina si el objeto especificado es una instancia del tipo actual. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Determina si el tipo representado por el objeto actual es una subclase de la clase especificada. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Determina si el objeto actual y el objeto [TypeInfo](./) especificado no son iguales. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Determina si el objeto [TypeInfo](./) actual no es un objeto nulo, es decir, representa algún tipo. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Determina si el objeto actual y el objeto [TypeInfo](./) especificado son iguales. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Determina si el objeto [TypeInfo](./) actual es un objeto nulo, es decir, no representa ningún tipo. |
| void [reset](./reset/)() | Establece [TypeInfo](./) a nulo. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Establece un valor que indica si el Type es un tipo de valor. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Establece el descriptor del tipo base. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Establece el descriptor del tipo de parámetro de plantilla. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Calcula el hash para la cadena especificada. |
| [String](../string/) [ToString](./tostring/)() const | Devuelve una cadena que contiene el nombre del tipo representado por el objeto actual. |
| static const [TypeInfo](./)\& [Type](./type/)() | Devuelve un objeto [TypeInfo](./) que representa la clase [TypeInfo](./). |
| [TypeInfo](./typeinfo/)() | Constructor predeterminado (no se establece tipo). |
| [TypeInfo](./typeinfo/)(std::nullptr_t) | Constructor de objeto nulo (no se establece tipo). |
| [TypeInfo](./typeinfo/)(const char_t *) | Constructor. |
| [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Constructor. |
| [TypeInfo](./typeinfo/)(const std::type_info\&) | Constructor. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [EmptyType](./emptytype/) | Constante que representa una lista vacía de [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | Constante que representa una lista vacía de [TypeInfo](./). |

## Definiciones de tipo

| Typedef | Descripción |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Puntero a función para construir el tipo. |

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)