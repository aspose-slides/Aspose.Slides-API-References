---
title: "System::Reflection"
second_title: Aspose.Slides pro C++ referenční příručku API
description: 
type: docs
weight: 755
url: /cs/system.reflection/
---
## Třídy

| Class | Popis |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) třída popisující sestavení. Podpora je omezená, protože pravidla se mezi C# a C++ značně liší. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [AssemblyName](./assemblyname/) | Definuje název sestavení. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton pro zaregistrování typu v běžící sestavě. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Základní typ pro singletony, které registrují typ v běžící sestavě. |
| [ConstructorInfo](./constructorinfo/) | Poskytuje přístup k metadatům konstruktoru. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException je vyvolána metodou Module.GetTypes, pokud některá z tříd v modulu selže při načítání. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu ReflectionTypeLoadException. Nikdy nezabaluje instance třídy ReflectionTypeLoadException do [System::SmartPtr](../system/smartptr/). |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException je vyvolána metodami volanými pomocí reflexe. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu TargetInvocationException. Nikdy nezabaluje instance třídy TargetInvocationException do [System::SmartPtr](../system/smartptr/). |
| [FieldInfo](./fieldinfo/) | Zjišťuje atributy pole a poskytuje přístup k metadatům pole. |
| [MemberInfo](./memberinfo/) | Poskytuje reflexní informace o členech. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [MethodBase](./methodbase/) | Základní informace o metodě. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument. |
| [MethodInfo](./methodinfo/) | Reprezentuje informace o metodě třídy. |
| [PropertyInfo](./propertyinfo/) | Reprezentuje informace o vlastnosti. |
## Výčty

| Výčet | Popis |
| --- | --- |
| [BindingFlags](./bindingflags/) | Definuje členy a režimy vyhledávání typů a vazby. |
| [FieldAttributes](./fieldattributes/) | Reflektované atributy pole. |
| [MemberTypes](./membertypes/) | Označuje každý typ členu. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException je vyvolána metodou Module.GetTypes, pokud některá z tříd v modulu selže při načítání. Nikdy nezabaluje instance třídy ReflectionTypeLoadException do [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException je vyvolána metodami volanými pomocí reflexe. Nikdy nezabaluje instance třídy TargetInvocationException do [System::SmartPtr](../system/smartptr/). |