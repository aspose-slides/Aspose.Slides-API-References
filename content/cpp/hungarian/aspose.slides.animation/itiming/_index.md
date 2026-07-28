---
title: ITiming
second_title: Aspose.Slides a C++ API hivatkozáshoz
description: Az animáció időzítését reprezentálja.
type: docs
weight: 443
url: /hu/aspose.slides.animation/itiming/
---
## ITiming osztály

Az animáció időzítését reprezentálja.

```cpp
class ITiming : public virtual System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika használatával hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célra. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | Leírja a időtartam gyorsulási hatásának százalékos arányát. Olvasható **float**. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | Leírja, hogy az animációt automatikusan visszafelé kell-e lejátszani az előre irányú lejátszás után. Olvasható **bool**. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | Leírja a időtartam lassulási hatásának százalékos arányát. Olvasható **float**. |
| virtual **float** [get_Duration](./get_duration/)() | Leírja az animáció hatásának időtartamát. Olvasható **float**. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | Leírja, hogy hányszor kell az effektust ismételni. Olvasható **float**. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | Leírja, hogy hányszor kell az effektust ismételni. Olvasható **float**. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | Ez az attribútum meghatározza, hogy az effektus a diát végéig ismétlődik-e. Olvasható **bool**. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | Ez az attribútum meghatározza, hogy az effektus a következő kattintásig ismétlődik-e. Olvasható **bool**. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | Megadja, hogy egy effektus teljes befejezés után újraindul-e. Olvasható [EffectRestartType](../effectrestarttype/). |
| virtual **bool** [get_Rewind](./get_rewind/)() | Ez az attribútum meghatározza, hogy az effektus lejátszás befejezésekor visszatekerődik-e. Olvasható **bool**. |
| virtual **float** [get_Speed](./get_speed/)() | Megadja az időzítés felgyorsításának (vagy lassításának) százalékos arányát. Olvasható **float**. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | Leírja a trigger után lévő késleltetési időt. Olvasható **float**. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | Leírja a trigger típusát. Olvasható [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyéni objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típusú példány-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | Leírja a időtartam gyorsulási hatásának százalékos arányát. Írható **float**. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | Leírja, hogy az animációt automatikusan visszafelé kell-e lejátszani az előre irányú lejátszás után. Írható **bool**. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | Leírja a időtartam lassulási hatásának százalékos arányát. Írható **float**. |
| virtual void [set_Duration](./set_duration/)(**float**) | Leírja az animáció hatásának időtartamát. Írható **float**. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | Leírja, hogy hányszor kell az effektust ismételni. Írható **float**. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | Leírja, hogy hányszor kell az effektust ismételni. Írható **float**. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | Ez az attribútum meghatározza, hogy az effektus a diát végéig ismétlődik-e. Írható **bool**. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | Ez az attribútum meghatározza, hogy az effektus a következő kattintásig ismétlődik-e. Írható **bool**. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | Megadja, hogy egy effektus teljes befejezés után újraindul-e. Írható [EffectRestartType](../effectrestarttype/). |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | Ez az attribútum meghatározza, hogy az effektus lejátszás befejezésekor visszatekerődik-e. Írható **bool**. |
| virtual void [set_Speed](./set_speed/)(**float**) | Megadja az időzítés felgyorsításának (vagy lassításának) százalékos arányát. Írható **float**. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | Leírja a trigger után lévő késleltetési időt. Írható **float**. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | Leírja a trigger típusát. Írható [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablon argumentumot gyenge mutatóvá (nem megosztottá) állítja be. Lehetővé teszi a mutatók konténerben való gyenge módra történő átváltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyéni objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtere [Aspose::Slides::Animation](../)
* Könyvtár [Aspose.Slides](../../)