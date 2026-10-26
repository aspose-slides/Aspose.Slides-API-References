---
title: TypeInfo
second_title: Aspose.Slides for C++ API-referencia
description: Egy adott típust képvisel, és információkat ad róla.
type: docs
weight: 1379
url: /hu/system/typeinfo/
---
## TypeInfo osztály


Represents a particular type and provides information about it.

```cpp
class TypeInfo
```

## Módszerek

| Method | Description |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Hozzáadja a megadott attribútumot a típus attribútumlistájához. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Beállítja az alapértelmezett konstruktort a T típushoz. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Beállítja az alapértelmezett konstruktort egy funktor segítségével, amely osztálypéldányt hoz létre. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Hozzáadja a megadott tagot a típus taglistájához. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Egyedi [TypeInfo](./) struktúrát biztosít a **BoxedValue** típushoz, amelyet több Boxed* osztály megoszthat. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | NINCS MEGVALÓSÍTVA. Visszaad egy mutatót az assembly-re, amelyben a jelenlegi objektum által képviselt típus deklarálva van. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | NINCS MEGVALÓSÍTVA. Visszaadja a teljesen kvalifikált nevet, beleértve az assembly nevét, a jelenlegi objektum által képviselt típusra. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Visszaadja az alap típus leírót. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Visszaad egy értéket, amely azt jelzi, hogy a jelenlegi Type objektumnak vannak-e típusparaméterei, amelyeket még nem helyettesítettek konkrét típusokkal. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Visszaadja a megadott névvel rendelkező tagok listáját. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Visszaadja a teljesen kvalifikált nevet (de az assembly név nélkül) a jelenlegi objektum által képviselt típusra. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Visszaad egy tömböt a generikus típusargumentumokkal ehhez a típushoz. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Visszaad egy értéket, amely azt jelzi, hogy a Type absztrakt-e és felül kell-e írásra kerülni. |
| **bool** [get_IsArray](./get_isarray/)() const | Visszaad egy értéket, amely azt jelzi, hogy a típus tömb-e. |
| **bool** [get_IsClass](./get_isclass/)() const | Visszaad egy értéket, amely azt jelzi, hogy a Type osztály vagy delegate, vagyis nem értéktípus vagy interfész. |
| **bool** [get_IsEnum](./get_isenum/)() const | Visszaad egy értéket, amely azt jelzi, hogy a jelenlegi Type felsorolást (enumeration) képvisel. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Visszaad egy értéket, amely azt jelzi, hogy a jelenlegi Type generikus típusdefiníció, amelyből más generikus típusok építhetők. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Visszaad egy értéket, amely azt jelzi, hogy a Type interfész-e; vagyis nem osztály vagy értéktípus. |
| **bool** [get_IsSealed](./get_issealed/)() const | Visszaad egy értéket, amely azt jelzi, hogy a Type sealed-ként van deklarálva. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Visszaad egy értéket, amely azt jelzi, hogy a Type értéktípus. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Visszaad egy értéket, amely azt jelzi, hogy a Type elérhető-e a kódból az assembly-n kívül. |
| [String](../string/) [get_Name](./get_name/)() const | Visszaadja a jelenlegi objektum által képviselt típus nevét. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Visszaadja a Type névterületét. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Keres egy nyilvános példánykonstruktort, amelynek paraméterei egyeznek a megadott tömb típusával. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Keres a jelenlegi Type számára definiált konstruktort a megadott BindingFlags használatával. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Visszaadja a jelenlegi Type számára definiált összes nyilvános konstruktort. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Keres egy olyan egyedi attribútumot, amelynek típusa megegyezik a megadottal, és amely a jelenlegi objektum által képviselt típusra van alkalmazva. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Visszaad egy tömböt, amely objektumokat tartalmaz, amelyek az összes a típusra alkalmazott egyedi attribútumot képviselik. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Visszaad egy tömböt, amely objektumokat tartalmaz, amelyek a típusra alkalmazott specifikus attribútumokat képviselik. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | NINCS MEGVALÓSÍTVA. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Keres egy megadott mezőt a megadott kötési korlátozások alapján. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Keres a jelenlegi Type számára definiált mezőket a megadott kötési korlátozások alapján. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | Visszaad egy tömböt a generikus típusargumentumokkal ehhez a típushoz. |
| int [GetHashCode](./gethashcode/)() const | Visszaad egy hash kódot, amely ehhez a példányhoz tartozik. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Visszaadja az összes interfészt, amelyet a jelenlegi Type megvalósít vagy örököl. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Visszaadja a megadott névvel rendelkező tagok listáját. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Visszaad egy metódust a megadott névvel. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Visszaadja a jelenlegi Type összes nyilvános tulajdonságát. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Keres a jelenlegi Type tulajdonságait a megadott kötési korlátozások alapján. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Visszaadja a sablonparaméter típus leírót. |
| **uint32_t** [Hash](./hash/)() const | Visszaad egy hash értéket, amely a jelenlegi objektum által képviselt típushoz tartozik. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Meghatározza, hogy egy megadott típusú példány hozzárendelhető-e a jelenlegi típusú változóhoz. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | NINCS MEGVALÓSÍTVA. Jelzi, hogy a megadott típus vagy annak származtatott típusai egy vagy több attribútuma alkalmazva van-e erre a tagra. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Meghatározza, hogy a megadott objektum a jelenlegi típus példánya-e. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Meghatározza, hogy a jelenlegi objektum által képviselt típus alosztálya-e a megadott osztálynak. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Meghatározza, hogy a jelenlegi és a megadott [TypeInfo](./) objektum nem egyenlő-e. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Meghatározza, hogy a jelenlegi [TypeInfo](./) objektum nem null-objektum-e, azaz képvisel-e valamilyen típust. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Meghatározza, hogy a jelenlegi és a megadott [TypeInfo](./) objektum egyenlő-e. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Meghatározza, hogy a jelenlegi [TypeInfo](./) objektum null-objektum-e, azaz nem képvisel semmilyen típust. |
| void [reset](./reset/)() | Beállítja a [TypeInfo](./) null értékre. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Beállít egy értéket, amely azt jelzi, hogy a Type értéktípus-e. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Beállítja az alap típus leírót. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Beállítja a sablonparaméter típus leírót. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Kiszámítja a megadott karakterlánc hash értékét. |
| [String](../string/) [ToString](./tostring/)() const | Visszaad egy karakterláncot, amely a jelenlegi objektum által képviselt típus nevét tartalmazza. |
| static const [TypeInfo](./)\& [Type](./type/)() | Visszaad egy [TypeInfo](./) objektumot, amely a [TypeInfo](./) osztályt képviseli. |
|  [TypeInfo](./typeinfo/)() | Alapértelmezett konstruktor (nincs beállítva típus). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | Null objektum konstruktor (nincs beállítva típus). |
|  [TypeInfo](./typeinfo/)(const char_t *) | Konstruktor. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Konstruktor. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | Konstruktor. |
## Mezők

| Field | Description |
| --- | --- |
| static [EmptyType](./emptytype/) | Állandó, amely az üres [TypeInfo](./) listát képviseli. |
| static [EmptyTypes](./emptytypes/) | Állandó, amely az üres [TypeInfo](./) listát képviseli. |
## Típusdefiníciók

| Typedef | Description |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Függvénymutató a típus létrehozásához. |
## Lásd még

* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)