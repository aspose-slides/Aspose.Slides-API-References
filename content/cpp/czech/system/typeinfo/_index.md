---
title: TypeInfo
second_title: Aspose.Slides pro C++ - reference API
description: Representuje konkrétní typ a poskytuje o něm informace.
type: docs
weight: 1379
url: /cs/system/typeinfo/
---
## TypeInfo třída

Represents a particular type and provides information about it.

```cpp
class TypeInfo
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Přidá zadaný atribut do seznamu atributů typu. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Nastaví výchozí konstruktor pro typ T. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Nastaví výchozí konstruktor pomocí funktoru, který vytváří instanci třídy. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Přidá zadaný člen do seznamu členů typu. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Poskytuje jedinečnou strukturu [TypeInfo](./) pro typ **BoxedValue**, která má být sdílena více třídami Boxed*. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | NEIMPLEMENTOVÁNO. Vrátí ukazatel na sestavení, ve kterém je typ reprezentovaný aktuálním objektem deklarován. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | NEIMPLEMENTOVÁNO. Vrátí plně kvalifikovaný název včetně názvu sestavení typu reprezentovaného aktuálním objektem. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Vrací deskriptor základního typu. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Získá hodnotu označující, zda objekt Type má typové parametry, které nebyly nahrazeny konkrétními typy. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Získá seznam členů se zadaným názvem. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Vrátí plně kvalifikovaný název (bez názvu sestavení) typu reprezentovaného aktuálním objektem. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Získá pole generických typových argumentů pro tento typ. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Získá hodnotu indikující, zda je typ abstraktní a musí být přepsán. |
| **bool** [get_IsArray](./get_isarray/)() const | Získá hodnotu, která označuje, zda je typ pole. |
| **bool** [get_IsClass](./get_isclass/)() const | Získá hodnotu indikující, zda je typ třídou nebo delegátem; tedy není typem hodnoty ani rozhraním. |
| **bool** [get_IsEnum](./get_isenum/)() const | Získá hodnotu indikující, zda aktuální typ představuje výčtový typ. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Získá hodnotu indikující, že aktuální typ představuje definici generického typu, ze které lze vytvořit jiné generické typy. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Získá hodnotu indikující, že typ je rozhraním; tedy není třídou ani typem hodnoty. |
| **bool** [get_IsSealed](./get_issealed/)() const | Získá hodnotu indikující, že typ je deklarován jako sealed. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Získá hodnotu indikující, že typ je typ hodnoty. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Získá hodnotu, která označuje, zda lze typ přistupovat z kódu mimo sestavení. |
| [String](../string/) [get_Name](./get_name/)() const | Vrátí název typu reprezentovaného aktuálním objektem. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Získá jmenný prostor typu. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Vyhledá veřejný konstruktor instance, jehož parametry odpovídají typům v zadaném poli. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | vyhledá konstruktory definované pro aktuální typ pomocí zadaných BindingFlags. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Vrátí všechny veřejné konstruktory definované pro aktuální typ. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Vyhledá vlastní atribut aplikovaný se zadaným typem a aplikovaný na typ reprezentovaný aktuálním objektem. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Vrátí pole obsahující objekty představující všechny vlastní atributy aplikované na typ. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Vrátí pole obsahující objekty představující konkrétní atributy aplikované na typ. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | NEIMPLEMENTOVÁNO. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Vyhledá zadané pole pomocí specifikovaných vázacích omezení. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Vyhledá pole definovaná pro aktuální typ pomocí specifikovaných vázacích omezení. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | Získá pole generických typových argumentů pro tento typ. |
| int [GetHashCode](./gethashcode/)() const | Vrátí hash kód spojený s touto instancí. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Získá všechny rozhraní implementovaná nebo zděděná aktuálním typem. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Získá seznam členů se zadaným názvem. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Získá metodu se zadaným názvem. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Vrátí všechny veřejné vlastnosti aktuálního typu. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Vyhledá vlastnosti aktuálního typu pomocí specifikovaných vázacích omezení. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Získá deskriptor typu šablonového parametru. |
| **uint32_t** [Hash](./hash/)() const | Vrátí hash hodnotu spojenou s typem reprezentovaným aktuálním objektem. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Určuje, zda instance zadaného typu může být přiřazena proměnné aktuálního typu. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | NEIMPLEMENTOVÁNO. Indikuje, zda je na tento člen aplikován jeden nebo více atributů zadaného typu nebo jeho odvozených typů. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Určuje, zda je zadaný objekt instancí aktuálního typu. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Určuje, zda typ reprezentovaný aktuálním objektem je podtřídou zadané třídy. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Určuje, zda aktuální a zadané objekty [TypeInfo](./) nejsou rovny. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Určuje, zda aktuální objekt [TypeInfo](./) není null-objekt, tj. představuje nějaký typ. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Určuje, zda aktuální a zadané objekty [TypeInfo](./) jsou rovny. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Určuje, zda aktuální objekt [TypeInfo](./) je null-objekt, tj. nepředstavuje žádný typ. |
| void [reset](./reset/)() | Nastaví [TypeInfo](./) na null. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Nastaví hodnotu indikující, zda je typ typem hodnoty. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Nastaví deskriptor základního typu. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Nastaví deskriptor typu šablonového parametru. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Vypočítá hash pro zadaný řetězec. |
| [String](../string/) [ToString](./tostring/)() const | Vrátí řetězec obsahující název typu reprezentovaného aktuálním objektem. |
| static const [TypeInfo](./)\& [Type](./type/)() | Vrátí objekt [TypeInfo](./), který představuje třídu [TypeInfo](./). |
|  [TypeInfo](./typeinfo/)() | Výchozí konstruktor (není nastaven typ). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | Konstruktor null objektu (není nastaven typ). |
|  [TypeInfo](./typeinfo/)(const char_t *) | Konstruktor. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Konstruktor. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | Konstruktor. |

## Pole

| Pole | Popis |
| --- | --- |
| static [EmptyType](./emptytype/) | Konstantní hodnota představující prázdný seznam [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | Konstantní hodnota představující prázdný seznam [TypeInfo](./). |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Ukazatel na funkci pro konstrukci typu. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)