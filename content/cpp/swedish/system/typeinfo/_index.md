---
title: TypeInfo
second_title: Aspose.Slides för C++ API-referens
description: Representerar en specifik typ och tillhandahåller information om den.
type: docs
weight: 1379
url: /sv/system/typeinfo/
---
## TypeInfo klass

Representerar en specifik typ och tillhandahåller information om den.

```cpp
class TypeInfo
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Lägger till det angivna attributet till listan med typens attribut. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Ställer in standardkonstruktor för typen T. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Ställer in standardkonstruktor via funktorn som skapar klassinstansen. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Lägger till den angivna medlemmen till listan med typens medlemmar. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Tillhandahåller unik [TypeInfo](./)-struktur för **BoxedValue**-typen som kan delas av flera Boxed*-klasser. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | INTE IMPLEMENTERAD. Returnerar en pekare till den samling där typen som representeras av det aktuella objektet är deklarerad. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | INTE IMPLEMENTERAD. Returnerar det fullständigt kvalificerade namnet inklusive samlingsnamnet för typen som representeras av det aktuella objektet. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Returnerar bastypens beskrivare. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Hämtar ett värde som indikerar om det aktuella Type-objektet har typparametrar som inte har ersatts av specifika typer. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Hämtar en lista över medlemmarna med angivet namn. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Returnerar det fullständigt kvalificerade namnet (men utan samlingsnamnet) för typen som representeras av det aktuella objektet. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Hämtar en array med de generiska typargumenten för denna typ. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Hämtar ett värde som indikerar om Type är abstrakt och måste överskrivas. |
| **bool** [get_IsArray](./get_isarray/)() const | Hämtar ett värde som indikerar om typen är en array. |
| **bool** [get_IsClass](./get_isclass/)() const | Hämtar ett värde som indikerar om Type är en klass eller en delegat; det vill säga inte en värdetyp eller ett gränssnitt. |
| **bool** [get_IsEnum](./get_isenum/)() const | Hämtar ett värde som indikerar om den aktuella Type representerar en uppräkning. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Hämtar ett värde som indikerar om den aktuella Type representerar en generisk typdefinition, från vilken andra generiska typer kan konstrueras. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Hämtar ett värde som indikerar om Type är ett gränssnitt; det vill säga inte en klass eller en värdetyp. |
| **bool** [get_IsSealed](./get_issealed/)() const | Hämtar ett värde som indikerar om Type är deklarerad som förseglad. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Hämtar ett värde som indikerar om Type är en värdetyp. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Hämtar ett värde som indikerar om Type kan nås av kod utanför samlingen. |
| [String](../string/) [get_Name](./get_name/)() const | Returnerar namnet på typen som representeras av det aktuella objektet. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Hämtar namnrymden för Type. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Söker efter en offentlig instanskonstruktor vars parametrar matchar typerna i den angivna arrayen. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Söker efter konstruktorerna som definierats för den aktuella Type, med hjälp av de angivna BindingFlags. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Returnerar alla offentliga konstruktorer som definierats för den aktuella Type. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Söker efter det anpassade attributet som har den angivna typen och som är applicerat på typen som representeras av det aktuella objektet. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Returnerar en array som innehåller objekt som representerar alla anpassade attribut som applicerats på typen. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Returnerar en array som innehåller objekt som representerar specifika attribut som applicerats på typen. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | INTE IMPLEMENTERAD. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Söker efter det angivna fältet, med de angivna bindningsrestriktionerna. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Söker efter fälten som definierats för den aktuella Type, med de angivna bindningsrestriktionerna. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | Hämtar en array med de generiska typargumenten för denna typ. |
| int [GetHashCode](./gethashcode/)() const | Returnerar en hashkod som är associerad med detta instans. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Hämtar alla gränssnitt som implementerats eller ärvts av den aktuella Type. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Hämtar en lista över medlemmarna med angivet namn. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Hämtar metod med angivet namn. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Returnerar alla offentliga egenskaper för den aktuella Type. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Söker efter egenskaperna för den aktuella Type, med de angivna bindningsrestriktionerna. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Hämtar typbeskrivare för mallparametern. |
| **uint32_t** [Hash](./hash/)() const | Returnerar ett hashvärde som är associerat med typen som representeras av det aktuella objektet. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Avgör om en instans av en specificerad typ kan tilldelas en variabel av den aktuella typen. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | INTE IMPLEMENTERAD. Indikerar om ett eller flera attribut av den specificerade typen eller dess deriverade typer är applicerade på detta medlem. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Avgör om det specificerade objektet är en instans av den aktuella typen. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Avgör om typen som representeras av det aktuella objektet är en underklass till den specificerade klassen. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Avgör om det aktuella och det specificerade [TypeInfo](./)-objekten inte är lika. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Avgör om det aktuella [TypeInfo](./)-objektet inte är ett null-objekt, d.v.s. det representerar någon typ. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Avgör om det aktuella och det specificerade [TypeInfo](./)-objekten är lika. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Avgör om det aktuella [TypeInfo](./)-objektet är ett null-objekt, d.v.s. inte representerar någon typ. |
| void [reset](./reset/)() | Sätter [TypeInfo](./) till null. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Sätter ett värde som indikerar om Type är en värdetyp. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Sätter bastypens beskrivare. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Sätter typbeskrivare för mallparameter. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Beräknar hash för den specificerade strängen. |
| [String](../string/) [ToString](./tostring/)() const | Returnerar en sträng som innehåller namnet på den typ som representeras av det aktuella objektet. |
| static const [TypeInfo](./)\& [Type](./type/)() | Returnerar ett [TypeInfo](./)-objekt som representerar [TypeInfo](./)-klassen. |
|  [TypeInfo](./typeinfo/)() | Standardkonstruktor (ingen typ är angiven). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | Null-objektkonstruktor (ingen typ är angiven). |
|  [TypeInfo](./typeinfo/)(const char_t *) | Konstruktor. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Konstruktor. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | Konstruktor. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [EmptyType](./emptytype/) | Konstant som representerar en tom lista av [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | Konstant som representerar en tom lista av [TypeInfo](./). |

## Typdefinitioner

| Typedef | Beskrivning |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Funktionspekare för att konstruera typ. |

## Se också

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)