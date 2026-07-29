---
title: "System::Reflection"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 755
url: /sv/system.reflection/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) klass som beskriver samling. Stödet är begränsat eftersom reglerna är ganska olika mellan C# och C++. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../system/makeobject/) funktion. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrappa alltid denna klass i [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [AssemblyName](./assemblyname/) | Definierar samlingsnamn. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../system/makeobject/) funktion. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrappa alltid denna klass i [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton för att registrera typ i den körande samlingen. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Grundtyp för singletons att registrera typ i den körande samlingen. |
| [ConstructorInfo](./constructorinfo/) | Tillhandahåller åtkomst till konstruktormetadata. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException kastas av Module.GetTypes-metoden om någon av klasserna i en modul misslyckas med att laddas. Skapa aldrig instanser av denna klass manuellt. Använd ReflectionTypeLoadException-klassen istället. Wrappa aldrig ReflectionTypeLoadException-klassinstanser i [System::SmartPtr](../system/smartptr/). |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException kastas av metoder som anropas via reflektion. Skapa aldrig instanser av denna klass manuellt. Använd TargetInvocationException-klassen istället. Wrappa aldrig TargetInvocationException-klassinstanser i [System::SmartPtr](../system/smartptr/). |
| [FieldInfo](./fieldinfo/) | Upptäcker attributen för ett fält och tillhandahåller åtkomst till fältmetadata. |
| [MemberInfo](./memberinfo/) | Tillhandahåller reflektioninformation om medlemmar. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../system/makeobject/) funktion. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrappa alltid denna klass i [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [MethodBase](./methodbase/) | Grundinformation om metod. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../system/makeobject/) funktion. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrappa alltid denna klass i [System::SmartPtr](../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [MethodInfo](./methodinfo/) | Representerar information om klassmetod. |
| [PropertyInfo](./propertyinfo/) | Representerar egenskapsinformation. |

## Enum

| Enum | Beskrivning |
| --- | --- |
| [BindingFlags](./bindingflags/) | Definierar medlemmar och typer för uppslagningslägen och bindningar. |
| [FieldAttributes](./fieldattributes/) | Reflekterade fältattribut. |
| [MemberTypes](./membertypes/) | Markerar varje typ av medlem. |

## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException kastas av Module.GetTypes-metoden om någon av klasserna i en modul misslyckas med att laddas. Wrappa aldrig ReflectionTypeLoadException-klassinstanser i [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException kastas av metoder som anropas via reflektion. Wrappa aldrig TargetInvocationException-klassinstanser i [System::SmartPtr](../system/smartptr/). |