---
title: TypeInfo
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Reprezentuje konkretny typ i dostarcza informacji o nim.
type: docs
weight: 1379
url: /pl/system/typeinfo/
---
## TypeInfo klasa


Reprezentuje konkretny typ i dostarcza informacji o nim.

```cpp
class TypeInfo
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Dodaje określony atrybut do listy atrybutów typu. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Ustawia domyślny konstruktor dla typu T. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Ustawia domyślny konstruktor przy użyciu funktora, który tworzy instancję klasy. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Dodaje określony element do listy elementów typu. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Udostępnia unikalną strukturę [TypeInfo](./) dla typu **BoxedValue**, która ma być współdzielona przez wiele klas Boxed*. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | NIE ZAIMPLEMENTOWANO. Zwraca wskaźnik do zestawu, w którym zadeklarowano typ reprezentowany przez bieżący obiekt. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | NIE ZAIMPLEMENTOWANO. Zwraca w pełni kwalifikowaną nazwę, w tym nazwę zestawu, typu reprezentowanego przez bieżący obiekt. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Zwraca deskryptor typu bazowego. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Zwraca wartość wskazującą, czy bieżący obiekt Type posiada parametry typu, które nie zostały zastąpione konkretnymi typami. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Zwraca listę elementów o określonej nazwie. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Zwraca w pełni kwalifikowaną nazwę (bez nazwy zestawu) typu reprezentowanego przez bieżący obiekt. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Zwraca tablicę argumentów typów generycznych dla tego typu. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Zwraca wartość wskazującą, czy Type jest abstrakcyjny i musi być nadpisany. |
| **bool** [get_IsArray](./get_isarray/)() const | Zwraca wartość wskazującą, czy typ jest tablicą. |
| **bool** [get_IsClass](./get_isclass/)() const | Zwraca wartość wskazującą, czy Type jest klasą lub delegatem; czyli nie jest typem wartościowym ani interfejsem. |
| **bool** [get_IsEnum](./get_isenum/)() const | Zwraca wartość wskazującą, czy bieżący Type reprezentuje wyliczenie. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Zwraca wartość wskazującą, czy bieżący Type reprezentuje definicję typu generycznego, z której można konstruować inne typy generyczne. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Zwraca wartość wskazującą, czy Type jest interfejsem; czyli nie jest klasą ani typem wartościowym. |
| **bool** [get_IsSealed](./get_issealed/)() const | Zwraca wartość wskazującą, czy Type jest zadeklarowany jako sealed. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Zwraca wartość wskazującą, czy Type jest typem wartościowym. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Zwraca wartość wskazującą, czy Type może być dostępny z kodu spoza zestawu. |
| [String](../string/) [get_Name](./get_name/)() const | Zwraca nazwę typu reprezentowanego przez bieżący obiekt. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Zwraca przestrzeń nazw Type. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Wyszukuje publiczny konstruktor instancji, którego parametry pasują do typów w podanej tablicy. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Wyszukuje konstruktory zdefiniowane dla bieżącego Type, używając określonych BindingFlags. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Zwraca wszystkie publiczne konstruktory zdefiniowane dla bieżącego Type. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Wyszukuje niestandardowy atrybut o określonym typie zastosowany do typu reprezentowanego przez bieżący obiekt. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Zwraca tablicę zawierającą obiekty reprezentujące wszystkie niestandardowe atrybuty zastosowane do typu. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Zwraca tablicę zawierającą obiekty reprezentujące określone atrybuty zastosowane do typu. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | NIE ZAIMPLEMENTOWANO. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Wyszukuje określone pole, używając podanych ograniczeń wiązania. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Wyszukuje pola zdefiniowane dla bieżącego Type, używając podanych ograniczeń wiązania. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | Zwraca tablicę argumentów typów generycznych dla tego typu. |
| int [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu powiązany z tą instancją. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Zwraca wszystkie interfejsy zaimplementowane lub odziedziczone przez bieżący Type. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Zwraca listę elementów o określonej nazwie. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Zwraca metodę o określonej nazwie. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Zwraca wszystkie publiczne właściwości bieżącego Type. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Wyszukuje właściwości bieżącego Type, używając podanych ograniczeń wiązania. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Zwraca deskryptor typu parametru szablonu. |
| **uint32_t** [Hash](./hash/)() const | Zwraca wartość skrótu powiązaną z typem reprezentowanym przez bieżący obiekt. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Określa, czy instancja określonego typu może być przypisana do zmiennej bieżącego typu. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | NIE ZAIMPLEMENTOWANO. Wskazuje, czy jeden lub więcej atrybutów określonego typu lub jego typów pochodnych jest zastosowany do tego elementu. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Określa, czy podany obiekt jest instancją bieżącego typu. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Określa, czy typ reprezentowany przez bieżący obiekt jest podklasą określonej klasy. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Określa, czy bieżący i podany obiekt [TypeInfo](./) nie są równe. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Określa, czy bieżący obiekt [TypeInfo](./) nie jest obiektem null, tj. reprezentuje jakiś typ. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Określa, czy bieżący i podany obiekt [TypeInfo](./) są równe. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Określa, czy bieżący obiekt [TypeInfo](./) jest obiektem null, tzn. nie reprezentuje żadnego typu. |
| void [reset](./reset/)() | Ustawia [TypeInfo](./) na null. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Ustawia wartość wskazującą, czy Type jest typem wartościowym. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Ustawia deskryptor typu bazowego. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Ustawia deskryptor typu parametru szablonu. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Oblicza skrót dla podanego ciągu znaków. |
| [String](../string/) [ToString](./tostring/)() const | Zwraca ciąg znaków zawierający nazwę typu reprezentowanego przez bieżący obiekt. |
| static const [TypeInfo](./)\& [Type](./type/)() | Zwraca obiekt [TypeInfo](./) reprezentujący klasę [TypeInfo](./). |
|  [TypeInfo](./typeinfo/)() | Domyślny konstruktor (typ nie jest ustawiony). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | Konstruktor obiektu null (typ nie jest ustawiony). |
|  [TypeInfo](./typeinfo/)(const char_t *) | Konstruktor. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Konstruktor. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | Konstruktor. |
## Pola

| Pole | Opis |
| --- | --- |
| static [EmptyType](./emptytype/) | Stała reprezentująca pustą listę [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | Stała reprezentująca pustą listę [TypeInfo](./). |
## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Wskaźnik na funkcję służącą do konstruowania typu. |
## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)