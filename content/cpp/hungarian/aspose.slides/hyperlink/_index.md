---
title: Hyperlink
second_title: Aspose.Slides C++ API-referencia
description: Egy hiperhivatkozást reprezentál.
type: docs
weight: 1236
url: /hu/aspose.slides/hyperlink/
---
## Hyperlink osztály

Egy hiperhivatkozást reprezentál.

```cpp
class Hyperlink : public Aspose::Slides::PVIObject,
                  public Aspose::Slides::IHyperlink
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Megállapítja, hogy a két [Hyperlink](./) példány egyenlő-e. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() override | Visszaadja a [Hyperlink](./) műveletének típusát. Csak olvasható [HyperlinkActionType](../hyperlinkactiontype/). |
| [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() override | Képviseli a hiperhivatkozás színforrását – legyen az stílus vagy részformátum. Olvas [HyperlinkColorSource](../hyperlinkcolorsource/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_EndShow](./get_endshow/)() | Visszaad egy hiperhivatkozást, amely befejezi a bemutatót. Csak olvasható [Hyperlink](./). |
| [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() override | Megadja a külső URL-t. Csak olvasható [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() override | Képviseli azt a hiperhivatkozást, amely ezt a részt anélkül állítja be, hogy figyelembe venné a rész tényleges tartalmát. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_FirstSlide](./get_firstslide/)() | Visszaad egy hiperhivatkozást az előadás első diájára. Csak olvasható [Hyperlink](./). |
| **bool** [get_HighlightClick](./get_highlightclick/)() override | Megállapítja, hogy a hiperhivatkozás kattintáskor ki legyen-e emelve. Olvas **bool**. |
| **bool** [get_History](./get_history/)() override | Megállapítja, hogy a szülő hiperhivatkozás célja hozzá legyen-e adva a megtekintett hiperhivatkozások listájához, amikor meghívják. Olvas **bool**. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastSlide](./get_lastslide/)() | Visszaad egy hiperhivatkozást a bemutató utolsó diájára. Csak olvasható [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastVievedSlide](./get_lastvievedslide/)() | Visszaad egy hiperhivatkozást az utoljára megtekintett diára. Csak olvasható [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_Media](./get_media/)() | Visszaad egy speciális "play mediafile" hiperhivatkozást. [AudioFrame](../audioframe/) és [VideoFrame](../videoframe/)-ban használatos. Csak olvasható [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NextSlide](./get_nextslide/)() | Visszaad egy hiperhivatkozást a következő diára. Csak olvasható [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NoAction](./get_noaction/)() | Visszaad egy speciális "do nothing" hiperhivatkozást. Csak olvasható [Hyperlink](./). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Visszaadja a szülő [IPresentationComponent](../ipresentationcomponent/)-t. Csak olvasható [IPresentationComponent](../ipresentationcomponent/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_PreviousSlide](./get_previousslide/)() | Visszaad egy hiperhivatkozást az előző diára. Csak olvasható [Hyperlink](./). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() override | Képviseli a hiperhivatkozás lejátszott hangját. Olvas [IAudio](../iaudio/). |
| **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() override | Megállapítja, hogy a hang le legyen-e állítva a hiperhivatkozás kattintásakor. Olvas **bool**. |
| [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() override | Visszaadja a szülő HTML keretcsoportban a szülő hiperhivatkozás céljának keretét, ha létezik. Olvas/írás [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | Ha a [Hyperlink](./) egy adott diát céloz, visszaadja ezt a diát. Csak olvasható [ISlide](../islide/). |
| [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() override | Visszaadja a sztringet, amely a felhasználói felületen megjelenhet, és a szülő hiperhivatkozáshoz kapcsolódik. Olvas [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja a objektumhoz kapcsolódó referencia számláló adatstruktúrát. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Hash függvényként szolgál egy adott típushoz, alkalmas hash algoritmusokban és adatstruktúrákban, például hash táblában való használatra. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| [Hyperlink](./hyperlink/)([System::String](../../system/string/)) | Létrehoz egy hiperhivatkozás példányát. |
| [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | Létrehoz egy hiperhivatkozás példányát, amely egy adott diára mutat. Megjegyzés: a létrehozott hiperhivatkozást a bemutató ugyanabból a prezentációból származó objektumhoz kell rendelni, különben a link NoActionként lesz mentve. |
| [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\>, [System::String](../../system/string/), [System::String](../../system/string/), **bool**, **bool**, **bool**) | Létrehoz egy hiperhivatkozás példányát egy másik hiperhivatkozás forrásaként, felülírva a másodlagos tulajdonságokat. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy olyan példány-e, amely a targetType által leírt típusba tartozik. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őr objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Referencia szerint hasonlítja össze az objektumokat. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Referencia szerint hasonlítja össze az objektumokat. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) override | Képviseli a hiperhivatkozás színforrását – legyen az stílus vagy részformátum. Írás [HyperlinkColorSource](../hyperlinkcolorsource/). |
| void [set_HighlightClick](./set_highlightclick/)(**bool**) override | Megállapítja, hogy a hiperhivatkozás kattintáskor ki legyen-e emelve. Írás **bool**. |
| void [set_History](./set_history/)(**bool**) override | Megállapítja, hogy a szülő hiperhivatkozás célja hozzá legyen-e adva a megtekintett hiperhivatkozások listájához, amikor meghívják. Írás **bool**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Képviseli a hiperhivatkozás lejátszott hangját. Írás [IAudio](../iaudio/). |
| void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) override | Megállapítja, hogy a hang le legyen-e állítva a hiperhivatkozás kattintásakor. Írás **bool**. |
| void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) override | Visszaadja a szülő HTML keretcsoportban a szülő hiperhivatkozás céljának keretét, ha létezik. Olvas/írás [System::String](../../system/string/). |
| void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) override | Visszaadja a sztringet, amely a felhasználói felületen megjelenhet, és a szülő hiperhivatkozáshoz kapcsolódik. Írás [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablon argumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók konténerekben weak módra cserélését. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őr objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [PVIObject](../pviobject/)
* Osztály [IHyperlink](../ihyperlink/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)