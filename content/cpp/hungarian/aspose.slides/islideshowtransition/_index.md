---
title: ISlideShowTransition
second_title: Aspose.Slides C++ API Referencia
description: Diaátmenetet képviseli.
type: docs
weight: 3810
url: /hu/aspose.slides/islideshowtransition/
---
## ISlideShowTransition osztály

A diavetítés átmenetet képviseli.

```cpp
class ISlideShowTransition : public virtual System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika alapján. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual **bool** [get_AdvanceAfter](./get_advanceafter/)() | Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. Olvasható **bool**. |
| virtual **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() | Megadja az azt az időt (ezredmásodpercben), amely után a átmenetnek el kell indulnia. Ez a beállítás az advClick attribútummal együtt használható. Ha ez az attribútum nincs megadva, akkor feltételezzük, hogy nincs automatikus előrehaladás. Olvasható **uint32_t**. |
| virtual **bool** [get_AdvanceOnClick](./get_advanceonclick/)() | Meghatározza, hogy az egérkattintás előreviszi-e a diát vagy sem. Ha ez az attribútum nincs megadva, akkor igaz értéket feltételezünk. Olvasható **bool**. |
| virtual **int32_t** [get_Duration](./get_duration/)() | Megkapja a diaátmenet effektus időtartamát ezredmásodpercben. Olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | Visszaadja a beágyazott hangadatokat. Olvasható [IAudio](../iaudio/). |
| virtual **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() | Meghatározza, hogy ez a hang beépített hang-e vagy sem. Ha ez az attribútum igazra van állítva, akkor a generáló alkalmazás értesül, hogy ellenőrizze a hanghoz megadott name attribútumot a beépített hangok listájában, és szükség szerint egyedi nevet vagy felhasználói felületet jeleníthet meg. Olvasható **bool**. |
| virtual **bool** [get_SoundLoop](./get_soundloop/)() | Ez az attribútum meghatározza, hogy a hang ismétlődik-e, amíg a diavetítésben a következő hangesemény nem következik be. Olvasható **bool**. |
| virtual [SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) [get_SoundMode](./get_soundmode/)() | Beállítja vagy visszaadja a hangmódot a diaátmenethez. Olvasható [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual [System::String](../../system/string/) [get_SoundName](./get_soundname/)() | Megadja a diátmenet hangjának ember által olvasható nevét. A [ISlideShowTransition::set_Sound](./set_sound/)-t meg kell adni a hangnév lekéréséhez vagy beállításához. Olvasható [System::String](../../system/string/). |
| virtual [SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) [get_Speed](./get_speed/)() | Meghatározza a sebességet, amelyet a jelenlegi diáról a következőre történő átmenetkor használni kell. Olvasható [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual [SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/) [get_Type](./get_type/)() | Az átmenet típusa. Olvasható [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)\> [get_Value](./get_value/)() | [Slide](../slide/) bemutatja az átmenet értékét. Csak olvasható [SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja a objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást zárásra. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_AdvanceAfter](./set_advanceafter/)(**bool**) | Ez az attribútum meghatározza, hogy a diavetítés egy bizonyos idő után a következő diára lép-e. Írható **bool**. |
| virtual void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) | Megadja azt az időt (ezredmásodpercben), amely után az átmenetnek el kell indulnia. Ez a beállítás az advClick attribútummal együtt használható. Ha ez az attribútum nincs megadva, feltételezzük, hogy nem lesz automatikus előrehaladás. Írható **uint32_t**. |
| virtual void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) | Meghatározza, hogy egy egérkattintás előreviszi-e a diát vagy sem. Ha ez az attribútum nincs megadva, akkor igaz értéket feltételezünk. Írható **bool**. |
| virtual void [set_Duration](./set_duration/)(**int32_t**) | Beállítja a diaátmenet effektus időtartamát ezredmásodpercben. Írható **int32_t**. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Beállítja a beágyazott hangadatokat. Írja [IAudio](../iaudio/). |
| virtual void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) | Meghatározza, hogy ez a hang beépített hang-e vagy sem. Ha ez az attribútum igazra van állítva, a generáló alkalmazás értesül, hogy ellenőrizze a hanghoz megadott name attribútumot a beépített hangok listájában, és szükség szerint egyedi nevet vagy UI-t jeleníthet meg. Írható **bool**. |
| virtual void [set_SoundLoop](./set_soundloop/)(**bool**) | Ez az attribútum meghatározza, hogy a hang ismétlődik-e, amíg a diavetítésben a következő hangesemény nem következik be. Írható **bool**. |
| virtual void [set_SoundMode](./set_soundmode/)([SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)) | Beállítja vagy visszaadja a hangmódot a diaátmenethez. Írja [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) | Megadja a diaátmenet hangjának ember által olvasható nevét. A [ISlideShowTransition::set_Sound](./set_sound/)-t meg kell adni a hangnév lekéréséhez vagy beállításához. Írja [System::String](../../system/string/). |
| virtual void [set_Speed](./set_speed/)([SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)) | Meghatározza a sebességet, amelyet a jelenlegi diáról a következőre történő átmenetkor használni kell. Írja [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual void [set_Type](./set_type/)([SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/)) | Az átmenet típusa. Írja [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók átkapcsolását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtere [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)