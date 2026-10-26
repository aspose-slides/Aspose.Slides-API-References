---
title: TypeInfo
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een specifiek type voor en biedt er informatie over.
type: docs
weight: 1379
url: /nl/system/typeinfo/
---
## TypeInfo klasse

Stelt een specifiek type voor en biedt er informatie over.

```cpp
class TypeInfo
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Voegt het opgegeven attribuut toe aan de lijst met attributen van het type. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Stelt de standaardconstructor in voor het type T. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Stelt de standaardconstructor in via de functor die een klasse-instantie maakt. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Voegt het opgegeven lid toe aan de lijst met leden van het type. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Biedt een unieke [TypeInfo](./)-structuur voor het **BoxedValue**-type die gedeeld kan worden door meerdere Boxed*-klassen. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | NIET GEREALISEERD. Retourneert een pointer naar de assembly waarin het type dat door het huidige object wordt weergegeven, is gedeclareerd. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | NIET GEREALISEERD. Retourneert de volledig gekwalificeerde naam inclusief de assembly-naam van het type dat door het huidige object wordt weergegeven. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Retourneert de basis-type-descriptor. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Geeft een waarde terug die aangeeft of het huidige Type-object type-parameters bevat die nog niet zijn vervangen door specifieke types. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Geeft een lijst terug van de leden met de opgegeven naam. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Retourneert de volledig gekwalificeerde naam (maar zonder de assembly-naam) van het type dat door het huidige object wordt weergegeven. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Geeft een array terug van de generieke type-argumenten voor dit type. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Geeft een waarde terug die aangeeft of het Type abstract is en moet worden overschreven. |
| **bool** [get_IsArray](./get_isarray/)() const | Geeft een waarde terug die aangeeft of het type een array is. |
| **bool** [get_IsClass](./get_isclass/)() const | Geeft een waarde terug die aangeeft of het Type een klasse of een delegate is; dat wil zeggen, geen waardetype of interface. |
| **bool** [get_IsEnum](./get_isenum/)() const | Geeft een waarde terug die aangeeft of het huidige Type een enumeratie vertegenwoordigt. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Geeft een waarde terug die aangeeft of het huidige Type een generieke type-definitie vertegenwoordigt, waaruit andere generieke types kunnen worden geconstrueerd. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Geeft een waarde terug die aangeeft of het Type een interface is; dat wil zeggen, geen klasse of waardetype. |
| **bool** [get_IsSealed](./get_issealed/)() const | Geeft een waarde terug die aangeeft of het Type als sealed is gedeclareerd. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Geeft een waarde terug die aangeeft of het Type een waardetype is. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Geeft een waarde terug die aangeeft of het Type toegankelijk is voor code buiten de assembly. |
| [String](../string/) [get_Name](./get_name/)() const | Retourneert de naam van het type dat door het huidige object wordt weergegeven. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Geeft de namespace van het Type terug. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Zoekt naar een publieke instantie-constructor waarvan de parameters overeenkomen met de types in de opgegeven array. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Zoekt naar de constructors die voor het huidige Type zijn gedefinieerd, gebruikmakend van de opgegeven BindingFlags. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Retourneert alle publieke constructors die voor het huidige Type zijn gedefinieerd. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Zoekt naar het aangepaste attribuut dat van het opgegeven type is en dat is toegepast op het type dat door het huidige object wordt weergegeven. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Retourneert een array met objecten die alle toegepaste aangepaste attributen van het type vertegenwoordigen. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Retourneert een array met objecten die specifieke attributen vertegenwoordigen die op het type zijn toegepast. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | NIET GEREALISEERD. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Zoekt naar het opgegeven veld, gebruikmakend van de opgegeven bindingsbeperkingen. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Zoekt naar de velden die voor het huidige Type zijn gedefinieerd, gebruikmakend van de opgegeven bindingsbeperkingen. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | Geeft een array terug van de generieke type-argumenten voor dit type. |
| int [GetHashCode](./gethashcode/)() const | Retourneert een hash-code die aan deze instantie is gekoppeld. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Geeft alle interfaces die door het huidige Type zijn geïmplementeerd of geërfd terug. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Geeft een lijst terug van de leden met de opgegeven naam. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Geeft een methode terug met de opgegeven naam. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Retourneert alle publieke eigenschappen van het huidige Type. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Zoekt naar de eigenschappen van het huidige Type, gebruikmakend van de opgegeven bindingsbeperkingen. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Geeft de template-parameter-type-descriptor terug. |
| **uint32_t** [Hash](./hash/)() const | Retourneert een hash-waarde die aan het type dat door het huidige object wordt weergegeven, is gekoppeld. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Bepaalt of een instantie van een opgegeven type kan worden toegewezen aan een variabele van het huidige type. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | NIET GEREALISEERD. Geeft aan of een of meer attributen van het opgegeven type of van zijn afgeleide types zijn toegepast op dit lid. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Bepaalt of het opgegeven object een instantie is van het huidige type. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Bepaalt of het type dat door het huidige object wordt weergegeven, een subklasse is van de opgegeven klasse. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Bepaalt of het huidige en het opgegeven [TypeInfo](./)-object niet gelijk zijn. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Bepaalt of het huidige [TypeInfo](./)-object geen null-object is, d.w.z. dat het een type vertegenwoordigt. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Bepaalt of het huidige en het opgegeven [TypeInfo](./)-object gelijk zijn. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Bepaalt of het huidige [TypeInfo](./)-object een null-object is, d.w.z. geen enkel type vertegenwoordigt. |
| void [reset](./reset/)() | Stelt [TypeInfo](./) in op null. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Stelt een waarde in die aangeeft of het Type een waardetype is. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Stelt de basis-type-descriptor in. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Stelt de template-parameter-type-descriptor in. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Berekent een hash voor de opgegeven string. |
| [String](../string/) [ToString](./tostring/)() const | Retourneert een string die de naam van het type dat door het huidige object wordt weergegeven, bevat. |
| static const [TypeInfo](./)\& [Type](./type/)() | Retourneert een [TypeInfo](./)-object dat de [TypeInfo](./)-klasse vertegenwoordigt. |
|  [TypeInfo](./typeinfo/)() | Standaardconstructor (geen type ingesteld). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | Null-object constructor (geen type ingesteld). |
|  [TypeInfo](./typeinfo/)(const char_t *) | Constructor. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Constructor. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | Constructor. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [EmptyType](./emptytype/) | Constante die een lege lijst van [TypeInfo](./) vertegenwoordigt. |
| static [EmptyTypes](./emptytypes/) | Constante die een lege lijst van [TypeInfo](./) vertegenwoordigt. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Functie-pointer om een type te construeren. |

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)