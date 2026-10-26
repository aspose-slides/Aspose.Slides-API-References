---
title: "System::Reflection"
second_title: Aspose.Slides C++ API referenciája
description: 
type: docs
weight: 755
url: /hu/system.reflection/
---
## Osztályok

| Osztály | Leírás |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) osztály, amely leírja az assembly-t. A támogatás korlátozott, mivel a szabályok jelentősen eltérnek a C# és a C++ között. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen a típuson a stacken vagy az operator new használatával, mert futási időbeli hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt a [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót a függvényeknek argumentumként. |
| [AssemblyName](./assemblyname/) | Meghatározza az assembly nevét. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen a típuson a stacken vagy az operator new használatával, mert futási időbeli hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt a [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót a függvényeknek argumentumként. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton az aktuális assembly típusának regisztrálásához. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Alap típus a singletonok számára, amelyek a végrehajtott assembly típusát regisztrálják. |
| [ConstructorInfo](./constructorinfo/) | Hozzáférést biztosít a konstruktor metaadataihoz. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | A ReflectionTypeLoadException-t a Module.GetTypes metódus dobja, ha egy modulban lévő valamelyik osztály betöltése sikertelen. Soha ne hozzon létre példányt ebből az osztályból kézzel. Használja helyette a ReflectionTypeLoadException osztályt. Soha ne csomagolja be a ReflectionTypeLoadException osztálypéldányait a [System::SmartPtr](../system/smartptr/)-ba. |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | A TargetInvocationException-t a reflexióval hívott metódusok dobják. Soha ne hozzon létre példányt ebből az osztályból kézzel. Használja helyette a TargetInvocationException osztályt. Soha ne csomagolja be a TargetInvocationException osztálypéldányait a [System::SmartPtr](../system/smartptr/)-ba. |
| [FieldInfo](./fieldinfo/) | Felfedezi egy mező attribútumait, és hozzáférést biztosít a mező metaadataihoz. |
| [MemberInfo](./memberinfo/) | Reflexiós információkat nyújt a tagokról. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen a típuson a stacken vagy az operator new használatával, mert futási időbeli hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt a [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót a függvényeknek argumentumként. |
| [MethodBase](./methodbase/) | Alapinformáció a metódusról. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen a típuson a stacken vagy az operator new használatával, mert futási időbeli hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt a [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót a függvényeknek argumentumként. |
| [MethodInfo](./methodinfo/) | Az osztály metódusáról szóló információt képviseli. |
| [PropertyInfo](./propertyinfo/) | A tulajdonságról szóló információt képviseli. |
## Enumerációk

| Enumeráció | Leírás |
| --- | --- |
| [BindingFlags](./bindingflags/) | Meghatározza a tagok és típusok keresési módjait és kötéseit. |
| [FieldAttributes](./fieldattributes/) | Reflexióval lekért mezőattribútumok. |
| [MemberTypes](./membertypes/) | Megjelöli minden tag típusát. |
## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | A ReflectionTypeLoadException-t a Module.GetTypes metódus dobja, ha egy modulban lévő valamelyik osztály betöltése sikertelen. Soha ne csomagolja be a ReflectionTypeLoadException osztálypéldányait a [System::SmartPtr](../system/smartptr/)-ba. |
| [TargetInvocationException](./targetinvocationexception/) | A TargetInvocationException-t a reflexióval hívott metódusok dobják. Soha ne csomagolja be a TargetInvocationException osztálypéldányait a [System::SmartPtr](../system/smartptr/)-ba. |