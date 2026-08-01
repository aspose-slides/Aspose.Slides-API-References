---
title: "System::Reflection"
second_title: Aspose.Slides voor C++ API Referentie
description: 
type: docs
weight: 755
url: /nl/system.reflection/
---
## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) klasse die assembly beschrijft. Ondersteuning is beperkt omdat de regels behoorlijk verschillen tussen C# en C++. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [AssemblyName](./assemblyname/) | Definieert de naam van de assembly. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton om een type te registreren in de actieve assembly. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Basistype voor singletons om een type te registreren in de actieve assembly. |
| [ConstructorInfo](./constructorinfo/) | Biedt toegang tot constructor-metadata. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException wordt gegooid door de Module.GetTypes-methode als een van de klassen in een module niet geladen kan worden. Maak nooit handmatig instanties van deze klasse. Gebruik in plaats daarvan de ReflectionTypeLoadException-klasse. Verpak de ReflectionTypeLoadException-klasse-instanties nooit in [System::SmartPtr](../system/smartptr/). |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException wordt gegooid door methoden die via reflectie worden aangeroepen. Maak nooit handmatig instanties van deze klasse. Gebruik in plaats daarvan de TargetInvocationException-klasse. Verpak de TargetInvocationException-klasse-instanties nooit in [System::SmartPtr](../system/smartptr/). |
| [FieldInfo](./fieldinfo/) | Ontdekt de attributen van een veld en biedt toegang tot veld-metadata. |
| [MemberInfo](./memberinfo/) | Biedt reflectie-informatie over leden. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [MethodBase](./methodbase/) | Basisinformatie over een methode. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Verpak deze klasse altijd in een [System::SmartPtr](../system/smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven. |
| [MethodInfo](./methodinfo/) | Vertegenwoordigt informatie over een klasse-methode. |
| [PropertyInfo](./propertyinfo/) | Vertegenwoordigt eigenschapsinformatie. |
## Enums

| Enum | Beschrijving |
| --- | --- |
| [BindingFlags](./bindingflags/) | Definieert leden en types lookup-modi en bindings. |
| [FieldAttributes](./fieldattributes/) | Gereflecteerde veld-attributen. |
| [MemberTypes](./membertypes/) | Markeert elk type lid. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException wordt gegooid door de Module.GetTypes-methode als een van de klassen in een module niet geladen kan worden. Verpak de ReflectionTypeLoadException-klasse-instanties nooit in [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException wordt gegooid door methoden die via reflectie worden aangeroepen. Verpak de TargetInvocationException-klasse-instanties nooit in [System::SmartPtr](../system/smartptr/). |