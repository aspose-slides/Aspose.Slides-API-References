---
title: "System::Reflection"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 755
url: /de/system.reflection/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) Klasse, die eine Assembly beschreibt. Die Unterstützung ist begrenzt, da die Regeln zwischen C# und C++ stark unterschiedlich sind. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../system/makeobject/) Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [AssemblyName](./assemblyname/) | Definiert den Namen der Assembly. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../system/makeobject/) Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton zum Registrieren eines Typs in der ausführenden Assembly. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Basistyp für Singletons zum Registrieren eines Typs in der ausführenden Assembly. |
| [ConstructorInfo](./constructorinfo/) | Stellt Zugriff auf Konstruktormetadaten bereit. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException wird von der Methode Module.GetTypes ausgelöst, wenn eine der Klassen in einem Modul nicht geladen werden kann. Erstellen Sie niemals Instanzen dieser Klasse manuell. Verwenden Sie stattdessen die Klasse ReflectionTypeLoadException. Wickeln Sie die Instanzen der Klasse ReflectionTypeLoadException niemals in [System::SmartPtr](../system/smartptr/). |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException wird von Methoden ausgelöst, die über Reflexion aufgerufen werden. Erstellen Sie niemals Instanzen dieser Klasse manuell. Verwenden Sie stattdessen die Klasse TargetInvocationException. Wickeln Sie die Instanzen der Klasse TargetInvocationException niemals in [System::SmartPtr](../system/smartptr/). |
| [FieldInfo](./fieldinfo/) | Ermittelt die Attribute eines Feldes und stellt Zugriff auf Feldmetadaten bereit. |
| [MemberInfo](./memberinfo/) | Stellt Reflexionsinformationen über Member bereit. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../system/makeobject/) Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [MethodBase](./methodbase/) | Basisinformation zu einer Methode. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../system/makeobject/) Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [MethodInfo](./methodinfo/) | Stellt Informationen über Klassenmethoden bereit. |
| [PropertyInfo](./propertyinfo/) | Stellt Property-Informationen bereit. |
## Aufzählungen

| Aufzählung | Beschreibung |
| --- | --- |
| [BindingFlags](./bindingflags/) | Definiert Mitglieder- und Typnachschlageverfahren sowie Bindungen. |
| [FieldAttributes](./fieldattributes/) | Reflektierte Feldattribute. |
| [MemberTypes](./membertypes/) | Kennzeichnet jede Art von Member. |
## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException wird von der Methode Module.GetTypes ausgelöst, wenn eine der Klassen in einem Modul nicht geladen werden kann. Wickeln Sie die Instanzen der Klasse ReflectionTypeLoadException niemals in [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException wird von Methoden ausgelöst, die über Reflexion aufgerufen werden. Wickeln Sie die Instanzen der Klasse TargetInvocationException niemals in [System::SmartPtr](../system/smartptr/). |