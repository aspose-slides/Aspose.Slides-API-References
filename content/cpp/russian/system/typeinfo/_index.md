---
title: TypeInfo
second_title: Справочник API Aspose.Slides для C++
description: Представляет определённый тип и предоставляет информацию о нём.
type: docs
weight: 1353
url: /ru/system/typeinfo/
---
## TypeInfo класс

Представляет определённый тип и предоставляет информацию о нём.

```cpp
class TypeInfo
```

## Методы

| Method | Description |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Добавляет указанный атрибут в список атрибутов типа. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Устанавливает конструктор по умолчанию для типа T. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Устанавливает конструктор по умолчанию с помощью функторa, создающего экземпляр класса. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Добавляет указанный член в список членов типа. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Предоставляет уникальную структуру [TypeInfo](./) для типа **BoxedValue**, которой могут пользоваться несколько классов Boxed*. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | НЕ РЕАЛИЗОВАНО. Возвращает указатель на сборку, в которой объявлен тип, представленный текущим объектом. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | НЕ РЕАЛИЗОВАНО. Возвращает полное квалифицированное имя, включая имя сборки, типа, представленного текущим объектом. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Возвращает дескриптор базового типа. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Возвращает значение, указывающее, содержит ли текущий объект Type параметр типа, который не заменён конкретными типами. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Возвращает список членов с указанным именем. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Возвращает полное квалифицированное имя (без имени сборки) типа, представленного текущим объектом. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Возвращает массив параметров обобщённого типа для данного типа. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Возвращает значение, указывающее, является ли Type абстрактным и требует переопределения. |
| **bool** [get_IsArray](./get_isarray/)() const | Возвращает значение, указывающее, является ли тип массивом. |
| **bool** [get_IsClass](./get_isclass/)() const | Возвращает значение, указывающее, является ли Type классом или делегатом; то есть не типом-значением или интерфейсом. |
| **bool** [get_IsEnum](./get_isenum/)() const | Возвращает значение, указывающее, представляет ли текущий Type перечисление. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Возвращает значение, указывающее, представляет ли текущий Type определение обобщённого типа, из которого могут быть построены другие обобщённые типы. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Возвращает значение, указывающее, является ли Type интерфейсом; то есть не классом и не типом-значением. |
| **bool** [get_IsSealed](./get_issealed/)() const | Возвращает значение, указывающее, объявлен ли Type как sealed. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Возвращает значение, указывающее, является ли Type типом-значением. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Возвращает значение, указывающее, может ли Type быть доступен из кода вне сборки. |
| [String](../string/) [get_Name](./get_name/)() const | Возвращает имя типа, представленного текущим объектом. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Возвращает пространство имён Type. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Ищет открытый конструктор экземпляра, параметры которого соответствуют типам в указанном массиве. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Ищет конструкторы, определённые для текущего Type, используя указанные BindingFlags. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Возвращает все публичные конструкторы, определённые для текущего Type. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Ищет пользовательский атрибут указанного типа, применённый к типу, представленному текущим объектом. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Возвращает массив объектов, представляющих все пользовательские атрибуты, применённые к типу. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Возвращает массив объектов, представляющих конкретные атрибуты, применённые к типу. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | НЕ РЕАЛИЗОВАНО. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Ищет указанный поле, используя указанные ограничения привязки. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Ищет поля, определённые для текущего Type, используя указанные ограничения привязки. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | Возвращает массив параметров обобщённого типа для данного типа. |
| int [GetHashCode](./gethashcode/)() const | Возвращает хеш-код, связанный с этим экземпляром. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Возвращает все интерфейсы, реализованные или унаследованные текущим Type. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Возвращает список членов с указанным именем. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Возвращает метод с указанным именем. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Возвращает все публичные свойства текущего Type. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Ищет свойства текущего Type, используя указанные ограничения привязки. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Возвращает дескриптор типа параметра шаблона. |
| **uint32_t** [Hash](./hash/)() const | Возвращает хеш-значение, связанное с типом, представляемым текущим объектом. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Определяет, может ли экземпляр указанного типа быть присвоен переменной текущего типа. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | НЕ РЕАЛИЗОВАНО. Указывает, применяется ли один или несколько атрибутов указанного типа или его производных к этому члену. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Определяет, является ли указанный объект экземпляром текущего типа. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Определяет, является ли тип, представленный текущим объектом, подклассом указанного класса. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Определяет, не равны ли текущий объект и указанный объект [TypeInfo](./). |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Определяет, не является ли текущий объект [TypeInfo](./) нулевым объектом, т.е. представляет ли какой-то тип. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Определяет, равны ли текущий объект и указанный объект [TypeInfo](./). |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Определяет, является ли текущий объект [TypeInfo](./) нулевым объектом, т.е. не представляет ни один тип. |
| void [reset](./reset/)() | Устанавливает [TypeInfo](./) в null. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Устанавливает значение, указывающее, является ли Type типом-значением. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Устанавливает дескриптор базового типа. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Устанавливает дескриптор типа параметра шаблона. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Вычисляет хеш для указанной строки. |
| [String](../string/) [ToString](./tostring/)() const | Возвращает строку, содержащую имя типа, представленного текущим объектом. |
| static const [TypeInfo](./)\& [Type](./type/)() | Возвращает объект [TypeInfo](./), представляющий класс [TypeInfo](./). |
|  [TypeInfo](./typeinfo/)() | Конструктор по умолчанию (тип не установлен). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | Конструктор нулевого объекта (тип не установлен). |
|  [TypeInfo](./typeinfo/)(const char_t *) | Конструктор. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Конструктор. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | Конструктор. |

## Поля

| Field | Description |
| --- | --- |
| static [EmptyType](./emptytype/) | Константа, представляющая пустой список [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | Константа, представляющая пустой список [TypeInfo](./). |

## Типedefы

| Typedef | Description |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Указатель на функцию для создания типа. |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)