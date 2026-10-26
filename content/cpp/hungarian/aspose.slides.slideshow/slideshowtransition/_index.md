---
title: SlideShowTransition
second_title: Aspose.Slides C++ API referenciája
description: A diavetítés átmenetét reprezentálja.
type: docs
weight: 404
url: /hu/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition osztály


A diavetítés átmenetét reprezentálja.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## Metódusok

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Megállapítja, hogy a két [SlideShowTransition](./) példány egyenlő-e. Olvasás/írás **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Ugyanúgy utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Ugyanúgy utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. Olvas **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | Megadja azt az időt ezredmásodpercben, amely után az átmenetnek el kell indulnia. Ez a beállítás az advClick attribútummal együtt használható. Ha ez az attribútum nincs megadva, akkor feltételezzük, hogy nem lesz automatikus előrehaladás. Olvas **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | Megadja, hogy egérkattintás előre lépteti-e a diát vagy sem. Ha ez az attribútum nincs megadva, akkor az igaz érték feltételezett. Olvas **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | Megkapja a diaátmenet hatás időtartamát ezredmásodpercben. Olvas **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | Visszaadja a beágyazott hang adatokat. Olvas [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | Megadja, hogy ez a hang beépített hang-e vagy sem. Ha ez az attribútum igaz értékre van állítva, akkor a generáló alkalmazás értesül a hang nevére vonatkozó name attribútum ellenőrzéséről a beépített hangok listájában, és szükség szerint egy egyéni nevet vagy UI-t jeleníthet meg. Olvas **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | Ez az attribútum meghatározza, hogy a hang addig ismétlődik-e, amíg a következő hangesemény a diavetítésben nem következik be. Olvas **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | Beállítja vagy visszaadja a hang módot a diaátmenethez. Olvas [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | Megadja a tranzíció hangjának ember által olvasható nevét. A [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/)-t kell hozzárendelni a hangnév lekéréséhez vagy beállításához. Olvas [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | Megadja az átmenet sebességét, amelyet a jelenlegi dia a következőre való átmenethez használ. Olvas [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | Az átmenet típusa. Olvas [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) mutassa az átmenet értékét. Csak olvasható [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Hash függvényként szolgál egy adott típushoz, amely alkalmas hash algoritmusok és olyan adatstruktúrák, mint a hash tábla használatára. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az érték típusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. Írás **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | Megadja azt az időt ezredmásodpercben, amely után az átmenetnek el kell indulnia. Ez a beállítás az advClick attribútummal együtt használható. Ha ez az attribútum nincs megadva, akkor feltételezzük, hogy nem lesz automatikus előrehaladás. Írás **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | Megadja, hogy egérkattintás előre lépteti-e a diát vagy sem. Ha ez az attribútum nincs megadva, akkor az igaz érték feltételezett. Írás **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | Beállítja a diaátmenet hatás időtartamát ezredmásodpercben. Írás **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | Beállítja a beágyazott hang adatokat. Írás [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | Megadja, hogy ez a hang beépített hang-e vagy sem. Ha ez az attribútum igaz értékre van állítva, akkor a generáló alkalmazás értesül a hang nevére vonatkozó name attribútum ellenőrzéséről a beépített hangok listájában, és szükség szerint egy egyéni nevet vagy UI-t jeleníthet meg. Írás **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | Ez az attribútum meghatározza, hogy a hang addig ismétlődik-e, amíg a következő hangesemény a diavetítésben nem következik be. Írás **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | Beállítja vagy visszaadja a hang módot a diaátmenethez. Írás [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | Megadja a tranzíció hangjának ember által olvasható nevét. A [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/)-t kell hozzárendelni a hangnév lekéréséhez vagy beállításához. Írás [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | Megadja az átmenet sebességét, amelyet a jelenlegi dia a következőre való átmenethez használ. Írás [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | Az átmenet típusa. Írás [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Beállítja a n-edik sablon argumentumot gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók átkapcsolását a gyenge módba a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [DomObject](../../aspose.slides/domobject/)
* Osztály [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* Névtér [Aspose::Slides::SlideShow](../)
* Könyvtár [Aspose.Slides](../../)