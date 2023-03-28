---
title: TypeInfo
second_title: Aspose.Slides for C++ API Reference
description: Represents a particular type and provides information about it.
type: docs
weight: 1249
url: /cpp/system/typeinfo/
---
## TypeInfo class


Represents a particular type and provides information about it.

```cpp
class TypeInfo
```

## Methods

| Method | Description |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Adds the specified attribute to the list of type's attributes. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Sets default constructor for the type T. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Sets default constructor by the functor that creates class instanse. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Adds the specified member to the list of type's members. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Provides unique [TypeInfo](./) structure for **BoxedValue** type to be shared by multiple Boxed* classes. |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | NOT IMPLEMENTED. Returns a pointer to the assembly in which the type represented by the current object is declared. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | NOT IMPLEMENTED. Returns the fully qualified name including the assembly name of the type represented by the current object. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Returns base type descritor. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Gets a value indicating whether the current Type object has type parameters that have not been replaced by specific types. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Gets list of the members with specified name. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Returns the fully qualified name (but without the assembly name) of the type represented by the current object. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Gets an array of the generic type arguments for this type. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Gets a value indicating whether the Type is abstract and must be overridden. |
| **bool** [get_IsArray](./get_isarray/)() const | Gets a value that indicates whether the type is an array. |
| **bool** [get_IsClass](./get_isclass/)() const | Gets a value indicating whether the Type is a class or a delegate; that is, not a value type or interface. |
| **bool** [get_IsEnum](./get_isenum/)() const | Gets a value indicating whether the current Type represents an enumeration. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Gets a value indicating whether the current Type represents a generic type definition, from which other generic types can be constructed. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Gets a value indicating whether the Type is an interface; that is, not a class or a value type. |
| **bool** [get_IsSealed](./get_issealed/)() const | Gets a value indicating whether the Type is declared sealed. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Gets a value indicating whether the Type is a value type. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Gets a value indicating whether the Type can be accessed by code outside the assembly. |
| [String](../string/) [get_Name](./get_name/)() const | Returns the name of the type represented by the current object. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Gets the namespace of the Type. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Searches for a public instance constructor whose parameters match the types in the specified array. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | searches for the constructors defined for the current Type, using the specified BindingFlags. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Returns all the public constructors defined for the current Type. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Searches for the custom attribute applied having the specified type and applied to the type reprsented by the current object. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Returns an array containing objects that represent all custom attributes applied to the type. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Returns an array containing objects that represent specific attributes applied to the type. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | NOT IMPLEMENTED. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Searches for the fields defined for the current Type, using the specified binding constraints. |
| int [GetHashCode](./gethashcode/)() const | Returns a hash code associated with this instance. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Gets all the interfaces implemented or inherited by the current Type. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Gets list of the members with specified name. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Gets method with specified name. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Returns all the public properties of the current Type. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Searches for the properties of the current Type, using the specified binding constraints. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Gets template parameter type descritor. |
| **uint32_t** [Hash](./hash/)() const | Returns a hash value associated with the type represented by the current object. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Determines whether an instance of a specified type can be assigned to a variable of the current type. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Determines whether the specified object is an instance of the current type. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Determines whether the type represented by the current object is a subclass of the specified class. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Determines if the current and the specified [TypeInfo](./) objects are not equal. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Determines if the current [TypeInfo](./) object is not a null-object, i.e. it represents some type. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Determines if the current and the specified [TypeInfo](./) objects are equal. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Determines if the current [TypeInfo](./) object is a null-object, i.e. does not represent any type. |
| void [reset](./reset/)() | Sets [TypeInfo](./) to null. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Sets a value indicating whether the Type is a value type. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Sets base type descritor. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Sets template parameter type descritor. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Calculates hash for specified string. |
| [String](../string/) [ToString](./tostring/)() const | Returns a string containing the name of the type represented by the current object. |
| static const [TypeInfo](./)\& [Type](./type/)() | Returns a [TypeInfo](./) object that represent [TypeInfo](./) class. |
|  [TypeInfo](./typeinfo/)() | Default constructor (no type is set). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | Null object constructor (no type is set). |
|  [TypeInfo](./typeinfo/)(const char_t *) | Constructor. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Constructor. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | Constructor. |
## Fields

| Field | Description |
| --- | --- |
| static [EmptyTypes](./emptytypes/) | Constant representing empty list of [TypeInfo](./). |
## Typedefs

| Typedef | Description |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Function pointer to construct type. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
