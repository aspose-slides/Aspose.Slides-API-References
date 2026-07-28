---
title: PropertyEffect
second_title: Aspose.Slides C++ API referencia
description: A tulajdonság hatás viselkedését képviseli.
type: docs
weight: 521
url: /hu/aspose.slides.animation/propertyeffect/
---
## PropertyEffect osztály

A tulajdonság hatás viselkedését képviseli.

```cpp
class PropertyEffect : public Aspose::Slides::Animation::Behavior,
                       public Aspose::Slides::Animation::IPropertyEffect
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | Jelzi, hogy az animációs viselkedések felhalmozódnak-e. Olvasás: [NullableBool](../../aspose.slides/nullablebool/). |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | Jelzi, hogy a jelenlegi animációs viselkedés kombinálódik-e más futó animációkkal. Olvasás: [BehaviorAdditiveType](../behavioradditivetype/). |
| [System::String](../../system/string/) [get_By](./get_by/)() override | Megad egy relatív eltolási értéket az animációhoz a kezdés előtti pozícióhoz képest. Olvasás: [System::String](../../system/string/). |
| [PropertyCalcModeType](../propertycalcmodetype/) [get_CalcMode](./get_calcmode/)() override | Meghatározza az animáció interpolációs módját. Olvasás: [PropertyCalcModeType](../propertycalcmodetype/). |
| [System::String](../../system/string/) [get_From](./get_from/)() override | Meghatározza az animáció kezdő értékét. Olvasás: [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPoint](../ipoint/)\> [get_Point](./get_point/)(**int32_t**) override | Visszaad egy pontot az animációból a megadott indexnél. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\> [get_Points](./get_points/)() override | Meghatározza az animáció pontjait. Olvasás: [IPointCollection](../ipointcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | Jelzi a viselkedés tulajdonságait. Csak olvasható: [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | Jelzi az effektus viselkedés időzítési tulajdonságait. Olvasás: [ITiming](../itiming/). |
| [System::String](../../system/string/) [get_To](./get_to/)() override | Meghatározza az animáció befejező értékét. Olvasás: [System::String](../../system/string/). |
| [PropertyValueType](../propertyvaluetype/) [get_ValueType](./get_valuetype/)() override | Meghatározza egy tulajdonság értékének típusát. Olvasás: [PropertyValueType](../propertyvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyéni objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy példány-e a targetType által leírt típusról. C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Végrehajtja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Átadás operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
|  [PropertyEffect](./propertyeffect/)() |  |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia módon hasonlít össze értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | Jelzi, hogy az animációs viselkedések felhalmozódnak-e. Írás: [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | Jelzi, hogy a jelenlegi animációs viselkedés kombinálódik-e más futó animációkkal. Írás: [BehaviorAdditiveType](../behavioradditivetype/). |
| void [set_By](./set_by/)([System::String](../../system/string/)) override | Megad egy relatív eltolási értéket az animációhoz a kezdés előtti pozícióhoz képest. Írás: [System::String](../../system/string/). |
| void [set_CalcMode](./set_calcmode/)([PropertyCalcModeType](../propertycalcmodetype/)) override | Meghatározza az animáció interpolációs módját. Írás: [PropertyCalcModeType](../propertycalcmodetype/). |
| void [set_From](./set_from/)([System::String](../../system/string/)) override | Meghatározza az animáció kezdő értékét. Írás: [System::String](../../system/string/). |
| void [set_Points](./set_points/)([System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\>) override | Meghatározza az animáció pontjait. Írás: [IPointCollection](../ipointcollection/). |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | Jelzi az effektus viselkedés időzítési tulajdonságait. Írás: [ITiming](../itiming/). |
| void [set_To](./set_to/)([System::String](../../system/string/)) override | Meghatározza az animáció befejező értékét. Írás: [System::String](../../system/string/). |
| void [set_ValueType](./set_valuetype/)([PropertyValueType](../propertyvaluetype/)) override | Meghatározza egy tulajdonság értékének típusát. Írás: [PropertyValueType](../propertyvaluetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a shared helyett). Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyéni objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Végrehajtja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Végrehajtja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadít minden belső adatstruktúrát. |

## Lásd még

* Osztály [Behavior](../behavior/)
* Osztály [IPropertyEffect](../ipropertyeffect/)
* Névtér [Aspose::Slides::Animation](../)
* Könyvtár [Aspose.Slides](../../)