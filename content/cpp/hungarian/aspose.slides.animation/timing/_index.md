---
title: Timing
second_title: Aspose.Slides C++ API hivatkozás
description: Animáció időzítését képviseli.
type: docs
weight: 625
url: /hu/aspose.slides.animation/timing/
---
## Timing osztály

Az animáció időzítését képviseli.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **float** [get_Accelerate](./get_accelerate/)() override | Leírja a gyorsulási viselkedés hatás időtartamának százalékos arányát. Olvas **float**. |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | Leírja, hogy az animációt automatikusan visszafelé kell-e lejátszani az előre irányú lejátszás után. Olvas **bool**. |
| **float** [get_Decelerate](./get_decelerate/)() override | Leírja a lassulási viselkedés hatás időtartamának százalékos arányát. Olvas **float**. |
| **float** [get_Duration](./get_duration/)() override | Leírja az animáció hatás időtartamát. Olvas **float**. |
| **float** [get_RepeatCount](./get_repeatcount/)() override | Leírja, hogy hányszor kell ismétlődni a hatásnak. Olvas **float**. |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | Leírja, hogy hányszor kell ismétlődni a hatásnak. Olvas **float**. |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | Ez az attribútum meghatározza, hogy a hatás a dia végéig ismétlődik-e. Olvas **bool**. |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | Ez az attribútum meghatározza, hogy a hatás a következő kattintásig ismétlődik-e. Olvas **bool**. |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | Megadja, hogy egy hatás újraindul-e a befejezés után. Olvas [EffectRestartType](../effectrestarttype/). |
| **bool** [get_Rewind](./get_rewind/)() override | Ez az attribútum meghatározza, hogy a hatás lejátszás befejezésekor visszatekerődik-e. Olvas **bool**. |
| **float** [get_Speed](./get_speed/)() override | Megadja, hogy a időzítést hány százalékban kell felgyorsítani (vagy lelassítani). Olvas **float**. |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | Leírja a trigger után lévő késleltetési időt. Olvas **float**. |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | Leírja a trigger típusát. Olvas [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus egy példányát képviseli-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az érték típusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Accelerate](./set_accelerate/)(**float**) override | Leírja a gyorsulási viselkedés hatás időtartamának százalékos arányát. Ír **float**. |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | Leírja, hogy az animációt automatikusan visszafelé kell-e lejátszani az előre irányú lejátszás után. Ír **bool**. |
| void [set_Decelerate](./set_decelerate/)(**float**) override | Leírja a lassulási viselkedés hatás időtartamának százalékos arányát. Ír **float**. |
| void [set_Duration](./set_duration/)(**float**) override | Leírja az animáció hatás időtartamát. Ír **float**. |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | Leírja, hogy hányszor kell ismétlődni a hatásnak. Ír **float**. |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | Leírja, hogy hányszor kell ismétlődni a hatásnak. Ír **float**. |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | Ez az attribútum meghatározza, hogy a hatás a dia végéig ismétlődik-e. Ír **bool**. |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | Ez az attribútum meghatározza, hogy a hatás a következő kattintásig ismétlődik-e. Ír **bool**. |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | Megadja, hogy egy hatás újraindul-e a befejezés után. Ír [EffectRestartType](../effectrestarttype/). |
| void [set_Rewind](./set_rewind/)(**bool**) override | Ez az attribútum meghatározza, hogy a hatás lejátszás befejezésekor visszatekerődik-e. Ír **bool**. |
| void [set_Speed](./set_speed/)(**float**) override | Megadja, hogy a időzítést hány százalékban kell felgyorsítani (vagy lelassítani). Ír **float**. |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | Leírja a trigger után lévő késleltetési időt. Ír **float**. |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | Leírja a trigger típusát. Ír [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóként (a shared helyett). Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [ITiming](../itiming/)
* Osztály [IDOMObject](../../aspose.slides/idomobject/)
* Névterület [Aspose::Slides::Animation](../)
* Könyvtár [Aspose.Slides](../../)