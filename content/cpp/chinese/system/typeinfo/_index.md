---
title: TypeInfo
second_title: Aspose.Slides for C++ API 参考
description: 表示特定类型并提供其相关信息。
type: docs
weight: 1353
url: /zh/system/typeinfo/
---
## TypeInfo 类

表示特定类型并提供其相关信息。

```cpp
class TypeInfo
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | 将指定属性添加到类型属性列表中。 |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | 为类型 T 设置默认构造函数。 |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | 通过创建类实例的函数对象设置默认构造函数。 |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | 将指定成员添加到类型成员列表中。 |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | 提供唯一的 [TypeInfo](./) 结构，用于 **BoxedValue** 类型，以便多个 Boxed* 类共享。 |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | 未实现。返回指向当前对象所表示类型声明所在程序集的指针。 |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | 未实现。返回包含程序集名称的完全限定名称，表示当前对象所表示的类型。 |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | 返回基类型描述符。 |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | 获取一个值，指示当前 Type 对象是否具有尚未被特定类型替换的类型参数。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | 获取具有指定名称的成员列表。 |
| [String](../string/) [get_FullName](./get_fullname/)() const | 返回当前对象所表示类型的完全限定名称（但不包括程序集名称）。 |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | 获取此类型的泛型类型参数数组。 |
| **bool** [get_IsAbstract](./get_isabstract/)() const | 获取一个值，指示该 Type 是否是抽象的且必须被重写。 |
| **bool** [get_IsArray](./get_isarray/)() const | 获取一个值，指示该类型是否为数组。 |
| **bool** [get_IsClass](./get_isclass/)() const | 获取一个值，指示该 Type 是否为类或委托；即不是值类型或接口。 |
| **bool** [get_IsEnum](./get_isenum/)() const | 获取一个值，指示当前 Type 是否表示枚举。 |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | 获取一个值，指示当前 Type 是否表示通用类型定义，可用于构造其他通用类型。 |
| **bool** [get_IsInterface](./get_isinterface/)() const | 获取一个值，指示该 Type 是否为接口；即不是类或值类型。 |
| **bool** [get_IsSealed](./get_issealed/)() const | 获取一个值，指示该 Type 是否声明为 sealed。 |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | 获取一个值，指示该 Type 是否为值类型。 |
| **bool** [get_IsVisible](./get_isvisible/)() const | 获取一个值，指示该 Type 是否可以被程序集外的代码访问。 |
| [String](../string/) [get_Name](./get_name/)() const | 返回当前对象所表示类型的名称。 |
| [String](../string/) [get_Namespace](./get_namespace/)() const | 获取该 Type 的命名空间。 |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | 搜索公共实例构造函数，其参数与指定数组中的类型匹配。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 使用指定的 BindingFlags 搜索当前 Type 定义的构造函数。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | 返回当前 Type 定义的所有公共构造函数。 |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | 搜索应用了指定类型且应用于当前对象所表示类型的自定义属性。 |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | 返回包含表示已应用于该类型的所有自定义属性的对象数组。 |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | 返回包含表示已应用于该类型的特定属性的对象数组。 |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | 未实现。 |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 使用指定的绑定约束搜索指定字段。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 使用指定的绑定约束搜索当前 Type 定义的字段。 |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | 获取此类型的泛型类型参数数组。 |
| int [GetHashCode](./gethashcode/)() const | 返回与此实例关联的哈希码。 |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | 获取当前 Type 实现或继承的所有接口。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | 获取具有指定名称的成员列表。 |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | 获取具有指定名称的方法。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | 返回当前 Type 的所有公共属性。 |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | 使用指定的绑定约束搜索当前 Type 的属性。 |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | 获取模板参数类型描述符。 |
| **uint32_t** [Hash](./hash/)() const | 返回与当前对象所表示类型关联的哈希值。 |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | 确定指定类型的实例是否可以赋值给当前类型的变量。 |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | 未实现。指示是否已将指定类型或其派生类型的一个或多个属性应用于此成员。 |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 确定指定对象是否是当前类型的实例。 |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | 确定当前对象所表示的类型是否是指定类的子类。 |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | 确定当前对象与指定的 [TypeInfo](./) 对象是否不相等。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 确定当前 [TypeInfo](./) 对象是否不是空对象，即它表示某种类型。 |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | 确定当前对象与指定的 [TypeInfo](./) 对象是否相等。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 确定当前 [TypeInfo](./) 对象是否为空对象，即不表示任何类型。 |
| void [reset](./reset/)() | 将 [TypeInfo](./) 设为 null。 |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | 设置一个值，指示 Type 是否为值类型。 |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | 设置基类型描述符。 |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | 设置模板参数类型描述符。 |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | 计算指定字符串的哈希值。 |
| [String](../string/) [ToString](./tostring/)() const | 返回包含当前对象所表示类型名称的字符串。 |
| static const [TypeInfo](./)\& [Type](./type/)() | 返回表示 [TypeInfo](./) 类的 [TypeInfo](./) 对象。 |
|  [TypeInfo](./typeinfo/)() | 默认构造函数（未设置类型）。 |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | 空对象构造函数（未设置类型）。 |
|  [TypeInfo](./typeinfo/)(const char_t *) | 构造函数。 |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | 构造函数。 |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | 构造函数。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [EmptyType](./emptytype/) | 表示空 [TypeInfo](./) 列表的常量。 |
| static [EmptyTypes](./emptytypes/) | 表示空 [TypeInfo](./) 列表的常量。 |

## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | 用于构造类型的函数指针。 |

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)