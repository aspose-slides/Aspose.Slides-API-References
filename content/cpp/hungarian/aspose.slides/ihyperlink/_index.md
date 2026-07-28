---
title: IHyperlink
second_title: Aspose.Slides for C++ API referencia
description: Egy hiperhivatkozást képvisel.
type: docs
weight: 2523
url: /hu/aspose.slides/ihyperlink/
---
## IHyperlink osztály

Egy hiperhivatkozást képvisel.

```cpp
class IHyperlink : public virtual System::Object
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantikai szabályok szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C# stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C# stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() | Visszaadja a HyperLinkEx műveletének típusát. Csak olvasható [HyperlinkActionType](../hyperlinkactiontype/). |
| virtual [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() | Képviseli a hiperhivatkozás színének forrását – vagy a stílusokat, vagy a szakaszformátumot. Olvas [HyperlinkColorSource](../hyperlinkcolorsource/). |
| virtual [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() | Meghatározza a külső URL-t. Ha ez a tulajdonság nem null, akkor a TargetSlide tulajdonság null lesz. Csak olvasható [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() | Képviseli a hiperhivatkozást, amely ehhez a részhez van beállítva a rész tényleges tartalmától függetlenül. |
| virtual **bool** [get_HighlightClick](./get_highlightclick/)() | Meghatározza, hogy a hiperhivatkozást ki kell-e emelni kattintáskor. Olvas **bool**. |
| virtual **bool** [get_History](./get_history/)() | Meghatározza, hogy a szülő hiperhivatkozás célja hozzáadódjon-e a megtekintett hiperhivatkozások listájához, amikor meghívják. Olvas **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | Képviseli a hiperhivatkozás lejátszott hangját. Olvas [IAudio](../iaudio/). |
| virtual **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() | Meghatározza, hogy a hangot le kell-e állítani a hiperhivatkozás kattintásakor. Olvas **bool**. |
| virtual [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() | Visszaadja a szülő HTML keretcsoportban a szülő hiperhivatkozás céljának megfelelő keretet, ha létezik. Olvas [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() | Ha a HyperlinkEx egy adott diát céloz, visszaadja ezt a diát. Ha a tulajdonság nem null, akkor az ExternalUrl tulajdonság null lesz. Csak olvasható [ISlide](../islide/). |
| virtual [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() | Visszaad egy karakterláncot, amely a felhasználói felületen megjelenhet a szülő hiperhivatkozással összefüggésben. Olvas [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri a objektumhoz kapcsolódó referenciakszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül, vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozással hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozással hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámláló értékét a megadott értékkel. |
| virtual void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) | Képviseli a hiperhivatkozás színének forrását – vagy a stílusokat, vagy a szakaszformátumot. Írás [HyperlinkColorSource](../hyperlinkcolorsource/). |
| virtual void [set_HighlightClick](./set_highlightclick/)(**bool**) | Meghatározza, hogy a hiperhivatkozást ki kell-e emelni kattintáskor. Írás **bool**. |
| virtual void [set_History](./set_history/)(**bool**) | Meghatározza, hogy a szülő hiperhivatkozás célja hozzáadódjon-e a megtekintett hiperhivatkozások listájához, amikor meghívják. Írás **bool**. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Képviseli a hiperhivatkozás lejátszott hangját. Írás [IAudio](../iaudio/). |
| virtual void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) | Meghatározza, hogy a hangot le kell-e állítani a hiperhivatkozás kattintásakor. Írás **bool**. |
| virtual void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) | Visszaadja a szülő HTML keretcsoportban a szülő hiperhivatkozás céljának megfelelő keretet, ha létezik. Írás [System::String](../../system/string/). |
| virtual void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) | Visszaad egy karakterláncot, amely a felhasználói felületen megjelenhet a szülő hiperhivatkozással összefüggésben. Írás [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók konténerekben gyenge módra való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámláló értékét. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámláló értékét. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül, vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámláló értékét. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámláló értékét. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtere [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)