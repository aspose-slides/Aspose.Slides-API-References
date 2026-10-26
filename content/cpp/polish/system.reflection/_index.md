---
title: "System::Reflection"
second_title: Aspose.Slides dla C++ Dokumentacja API
description: 
type: docs
weight: 755
url: /pl/system.reflection/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) klasa opisująca assembly. Obsługa jest ograniczona, ponieważ zasady różnią się znacznie między C# a C++. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to skutkować błędami w czasie wykonywania i/lub błędami asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [AssemblyName](./assemblyname/) | Definiuje nazwę assembly. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to skutkować błędami w czasie wykonywania i/lub błędami asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton rejestrujący typ w aktualnie wykonywanym assembly. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Typ bazowy dla singletonów rejestrujących typ w aktualnie wykonywanym assembly. |
| [ConstructorInfo](./constructorinfo/) | Zapewnia dostęp do metadanych konstruktora. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException jest rzucany przez metodę Module.GetTypes, jeśli którejkolwiek z klas w module nie uda się załadować. Nigdy nie twórz ręcznie instancji tej klasy. Użyj klasy ReflectionTypeLoadException. Nigdy nie opakowuj instancji klasy ReflectionTypeLoadException w [System::SmartPtr](../system/smartptr/). |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException jest rzucany przez metody wywoływane za pomocą refleksji. Nigdy nie twórz ręcznie instancji tej klasy. Użyj klasy TargetInvocationException. Nigdy nie opakowuj instancji klasy TargetInvocationException w [System::SmartPtr](../system/smartptr/). |
| [FieldInfo](./fieldinfo/) | Odkrywa atrybuty pola i zapewnia dostęp do metadanych pola. |
| [MemberInfo](./memberinfo/) | Zapewnia informacje refleksyjne o członkach. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to skutkować błędami w czasie wykonywania i/lub błędami asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [MethodBase](./methodbase/) | Podstawowe informacje o metodzie. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to skutkować błędami w czasie wykonywania i/lub błędami asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [MethodInfo](./methodinfo/) | Reprezentuje informacje o metodzie klasy. |
| [PropertyInfo](./propertyinfo/) | Reprezentuje informacje o właściwości. |
## Wyliczenia

| Wyliczenie | Opis |
| --- | --- |
| [BindingFlags](./bindingflags/) | Definiuje członków i tryby wyszukiwania typów oraz wiązania. |
| [FieldAttributes](./fieldattributes/) | Atrybuty pola odzwierciedlone. |
| [MemberTypes](./membertypes/) | Oznacza każdy typ członka. |
## Definicja typu

| Definicja typu | Opis |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException jest rzucany przez metodę Module.GetTypes, jeśli którejkolwiek z klas w module nie uda się załadować. Nigdy nie opakowuj instancji klasy ReflectionTypeLoadException w [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException jest rzucany przez metody wywoływane za pomocą refleksji. Nigdy nie opakowuj instancji klasy TargetInvocationException w [System::SmartPtr](../system/smartptr/). |