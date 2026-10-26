---
title: TypeInfo
second_title: Referência da API Aspose.Slides para C++
description: Representa um tipo específico e fornece informações sobre ele.
type: docs
weight: 1379
url: /pt/system/typeinfo/
---
## classe TypeInfo


Representa um tipo específico e fornece informações sobre ele.

```cpp
class TypeInfo
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Adiciona o atributo especificado à lista de atributos do tipo. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Define o construtor padrão para o tipo T. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Define o construtor padrão usando o functor que cria a instância da classe. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Adiciona o membro especificado à lista de membros do tipo. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Fornece a estrutura única [TypeInfo](./) para o tipo **BoxedValue** a ser compartilhada por várias classes Boxed*. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | NÃO IMPLEMENTADO. Retorna um ponteiro para a assembly na qual o tipo representado pelo objeto atual está declarado. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | NÃO IMPLEMENTADO. Retorna o nome totalmente qualificado incluindo o nome da assembly do tipo representado pelo objeto atual. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Retorna o descritor do tipo base. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Obtém um valor que indica se o objeto Type atual tem parâmetros de tipo que não foram substituídos por tipos específicos. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Obtém a lista dos membros com o nome especificado. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Retorna o nome totalmente qualificado (mas sem o nome da assembly) do tipo representado pelo objeto atual. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Obtém um array dos argumentos de tipo genérico para este tipo. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Obtém um valor que indica se o Type é abstrato e deve ser sobrescrito. |
| **bool** [get_IsArray](./get_isarray/)() const | Obtém um valor que indica se o tipo é um array. |
| **bool** [get_IsClass](./get_isclass/)() const | Obtém um valor que indica se o Type é uma classe ou um delegate; ou seja, não é um tipo valor ou interface. |
| **bool** [get_IsEnum](./get_isenum/)() const | Obtém um valor que indica se o Type atual representa uma enumeração. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Obtém um valor que indica se o Type atual representa uma definição de tipo genérico, a partir da qual outros tipos genéricos podem ser construídos. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Obtém um valor que indica se o Type é uma interface; ou seja, não é uma classe ou um tipo valor. |
| **bool** [get_IsSealed](./get_issealed/)() const | Obtém um valor que indica se o Type é declarado sealed. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Obtém um valor que indica se o Type é um tipo valor. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Obtém um valor que indica se o Type pode ser acessado por código fora da assembly. |
| [String](../string/) [get_Name](./get_name/)() const | Retorna o nome do tipo representado pelo objeto atual. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Obtém o namespace do Type. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Procura um construtor de instância público cujos parâmetros correspondam aos tipos no array especificado. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Procura os construtores definidos para o Type atual, usando os BindingFlags especificados. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Retorna todos os construtores públicos definidos para o Type atual. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Procura o atributo personalizado aplicado que possui o tipo especificado e que é aplicado ao tipo representado pelo objeto atual. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Retorna um array contendo objetos que representam todos os atributos personalizados aplicados ao tipo. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Retorna um array contendo objetos que representam atributos específicos aplicados ao tipo. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | NÃO IMPLEMENTADO. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Procura o campo especificado, usando as restrições de vínculo especificadas. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Procura os campos definidos para o Type atual, usando as restrições de vínculo especificadas. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | Obtém um array dos argumentos de tipo genérico para este tipo. |
| int [GetHashCode](./gethashcode/)() const | Retorna um código hash associado a esta instância. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Obtém todas as interfaces implementadas ou herdadas pelo Type atual. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Obtém a lista dos membros com o nome especificado. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Obtém o método com o nome especificado. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Retorna todas as propriedades públicas do Type atual. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Procura as propriedades do Type atual, usando as restrições de vínculo especificadas. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Obtém o descritor do tipo de parâmetro de template. |
| **uint32_t** [Hash](./hash/)() const | Retorna um valor hash associado ao tipo representado pelo objeto atual. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Determina se uma instância de um tipo especificado pode ser atribuída a uma variável do tipo atual. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | NÃO IMPLEMENTADO. Indica se um ou mais atributos do tipo especificado ou de seus tipos derivados são aplicados a este membro. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Determina se o objeto especificado é uma instância do tipo atual. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Determina se o tipo representado pelo objeto atual é uma subclasse da classe especificada. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Determina se o objeto [TypeInfo](./) atual e o especificado não são iguais. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Determina se o objeto [TypeInfo](./) atual não é um objeto nulo, ou seja, representa algum tipo. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Determina se o objeto [TypeInfo](./) atual e o especificado são iguais. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Determina se o objeto [TypeInfo](./) atual é um objeto nulo, ou seja, não representa nenhum tipo. |
| void [reset](./reset/)() | Define [TypeInfo](./) como nulo. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Define um valor que indica se o Type é um tipo valor. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Define o descritor do tipo base. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Define o descritor do tipo de parâmetro de template. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Calcula o hash para a string especificada. |
| [String](../string/) [ToString](./tostring/)() const | Retorna uma string contendo o nome do tipo representado pelo objeto atual. |
| static const [TypeInfo](./)\& [Type](./type/)() | Retorna um objeto [TypeInfo](./) que representa a classe [TypeInfo](./). |
|  [TypeInfo](./typeinfo/)() | Construtor padrão (nenhum tipo definido). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | Construtor de objeto nulo (nenhum tipo definido). |
|  [TypeInfo](./typeinfo/)(const char_t *) | Construtor. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Construtor. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | Construtor. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [EmptyType](./emptytype/) | Constante que representa uma lista vazia de [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | Constante que representa uma lista vazia de [TypeInfo](./). |

## Tipos definidos

| Tipo definido | Descrição |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Ponteiro para função que constrói o tipo. |

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)