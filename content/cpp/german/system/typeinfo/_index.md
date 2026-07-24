---
title: TypeInfo
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen bestimmten Typ dar und liefert Informationen darüber.
type: docs
weight: 1379
url: /de/system/typeinfo/
---
## TypeInfo Klasse

Stellt einen bestimmten Typ dar und liefert Informationen darüber.

```cpp
class TypeInfo
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Fügt das angegebene Attribut zur Liste der Attribute des Typs hinzu. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Setzt den Standardkonstruktor für den Typ T. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Setzt den Standardkonstruktor über den Funktor, der die Klasseninstanz erzeugt. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Fügt das angegebene Mitglied zur Liste der Mitglieder des Typs hinzu. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Stellt eine eindeutige [TypeInfo](./)-Struktur für den Typ **BoxedValue** bereit, die von mehreren Boxed*-Klassen gemeinsam genutzt wird. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | NICHT IMPLEMENTIERT. Gibt einen Zeiger auf die Assembly zurück, in der der vom aktuellen Objekt dargestellte Typ deklariert ist. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | NICHT IMPLEMENTIERT. Gibt den vollständig qualifizierten Namen einschließlich des Assembly-Namens des vom aktuellen Objekt dargestellten Typs zurück. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Gibt den Basis-Typ-Deskriptor zurück. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Ermittelt einen Wert, der angibt, ob das aktuelle Type-Objekt Typ-Parameter hat, die nicht durch konkrete Typen ersetzt wurden. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Gibt eine Liste der Mitglieder mit dem angegebenen Namen zurück. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Gibt den vollständig qualifizierten Namen (ohne den Assembly-Namen) des vom aktuellen Objekt dargestellten Typs zurück. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Gibt ein Array der generischen Typ-Argumente für diesen Typ zurück. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Ermittelt einen Wert, der angibt, ob der Typ abstrakt ist und überschrieben werden muss. |
| **bool** [get_IsArray](./get_isarray/)() const | Ermittelt einen Wert, der angibt, ob der Typ ein Array ist. |
| **bool** [get_IsClass](./get_isclass/)() const | Ermittelt einen Wert, der angibt, ob der Typ eine Klasse oder ein Delegat ist; das heißt, kein Werttyp oder Interface. |
| **bool** [get_IsEnum](./get_isenum/)() const | Ermittelt einen Wert, der angibt, ob das aktuelle Type eine Aufzählung darstellt. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Ermittelt einen Wert, der angibt, ob das aktuelle Type eine generische Typdefinition darstellt, aus der andere generische Typen konstruiert werden können. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Ermittelt einen Wert, der angibt, ob der Typ ein Interface ist; das heißt, keine Klasse oder ein Werttyp. |
| **bool** [get_IsSealed](./get_issealed/)() const | Ermittelt einen Wert, der angibt, ob der Typ als versiegelt deklariert ist. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Ermittelt einen Wert, der angibt, ob der Typ ein Werttyp ist. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Ermittelt einen Wert, der angibt, ob auf den Typ von Code außerhalb der Assembly zugegriffen werden kann. |
| [String](../string/) [get_Name](./get_name/)() const | Gibt den Namen des vom aktuellen Objekt dargestellten Typs zurück. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Ermittelt den Namespace des Typs. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Sucht einen öffentlichen Instanzkonstruktor, dessen Parameter mit den Typen im angegebenen Array übereinstimmen. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Durchsucht die für den aktuellen Typ definierten Konstruktoren unter Verwendung der angegebenen BindingFlags. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Gibt alle öffentlichen Konstruktoren zurück, die für den aktuellen Typ definiert sind. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Sucht nach dem benutzerdefinierten Attribut mit dem angegebenen Typ, das auf den vom aktuellen Objekt dargestellten Typ angewendet wurde. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Gibt ein Array zurück, das Objekte enthält, die alle auf den Typ angewendeten benutzerdefinierten Attribute darstellen. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Gibt ein Array zurück, das Objekte enthält, die bestimmte auf den Typ angewendete Attribute darstellen. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | NICHT IMPLEMENTIERT. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Sucht das angegebene Feld unter Verwendung der angegebenen Bindungsbeschränkungen. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Durchsucht die für den aktuellen Typ definierten Felder unter Verwendung der angegebenen Bindungsbeschränkungen. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | Gibt ein Array der generischen Typ-Argumente für diesen Typ zurück. |
| int [GetHashCode](./gethashcode/)() const | Gibt einen Hash-Code zurück, der mit dieser Instanz verknüpft ist. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Gibt alle vom aktuellen Typ implementierten oder geerbten Interfaces zurück. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Gibt eine Liste der Mitglieder mit dem angegebenen Namen zurück. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Gibt die Methode mit dem angegebenen Namen zurück. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Gibt alle öffentlichen Eigenschaften des aktuellen Typs zurück. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Durchsucht die Eigenschaften des aktuellen Typs unter Verwendung der angegebenen Bindungsbeschränkungen. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Ermittelt den Deskriptor des Template-Parameter-Typs. |
| **uint32_t** [Hash](./hash/)() const | Gibt einen Hash-Wert zurück, der mit dem vom aktuellen Objekt dargestellten Typ verknüpft ist. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Bestimmt, ob eine Instanz eines angegebenen Typs einer Variable des aktuellen Typs zugewiesen werden kann. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | NICHT IMPLEMENTIERT. Gibt an, ob ein oder mehrere Attribute des angegebenen Typs oder seiner abgeleiteten Typen auf dieses Mitglied angewendet werden. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Bestimmt, ob das angegebene Objekt eine Instanz des aktuellen Typs ist. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Typ eine Unterklasse der angegebenen Klasse ist. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Bestimmt, ob das aktuelle und das angegebene [TypeInfo](./)-Objekt nicht gleich sind. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Bestimmt, ob das aktuelle [TypeInfo](./)-Objekt kein Null-Objekt ist, d. h. es einen Typ darstellt. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Bestimmt, ob das aktuelle und das angegebene [TypeInfo](./)-Objekt gleich sind. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Bestimmt, ob das aktuelle [TypeInfo](./)-Objekt ein Null-Objekt ist, d. h. keinen Typ darstellt. |
| void [reset](./reset/)() | Setzt [TypeInfo](./) auf null. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Setzt einen Wert, der angibt, ob der Typ ein Werttyp ist. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Setzt den Basis-Typ-Deskriptor. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Setzt den Deskriptor des Template-Parameter-Typs. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Berechnet den Hash für die angegebene Zeichenkette. |
| [String](../string/) [ToString](./tostring/)() const | Gibt eine Zeichenkette zurück, die den Namen des vom aktuellen Objekt dargestellten Typs enthält. |
| static const [TypeInfo](./)\& [Type](./type/)() | Gibt ein [TypeInfo](./)-Objekt zurück, das die Klasse [TypeInfo](./) repräsentiert. |
|  [TypeInfo](./typeinfo/)() | Standardkonstruktor (kein Typ gesetzt). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | Null-Objekt-Konstruktor (kein Typ gesetzt). |
|  [TypeInfo](./typeinfo/)(const char_t *) | Konstruktor. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Konstruktor. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | Konstruktor. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [EmptyType](./emptytype/) | Konstante, die eine leere Liste von [TypeInfo](./) darstellt. |
| static [EmptyTypes](./emptytypes/) | Konstante, die eine leere Liste von [TypeInfo](./) darstellt. |

## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Funktionszeiger zum Erzeugen des Typs. |

## Siehe auch

* Namespace [System](../)
* Library [Aspose.Slides](../../)