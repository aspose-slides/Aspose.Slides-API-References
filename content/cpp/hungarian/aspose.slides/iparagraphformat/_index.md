---
title: IParagraphFormat
second_title: Aspose.Slides for C++ API referenciája
description: Ez az osztály tartalmazza a bekezdés formázási tulajdonságait. Az IParagraphFormatEffectiveData-től eltérően, ennek az osztálynak az összes tulajdonsága írható.
type: docs
weight: 3147
url: /hu/aspose.slides/iparagraphformat/
---
## IParagraphFormat osztály


Ez az osztály tartalmazza a bekezdés formázási tulajdonságait. A [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)-tól eltérően, ennek az osztálynak az összes tulajdonsága írható.

```cpp
class IParagraphFormat : public virtual System::Object
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást imitál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást imitál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Kizárólag belső használatra. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Visszaadja a szöveg igazítását a bekezdésben öröklődés nélkül. Olvasd [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | Visszaadja a bekezdés felsorolásformátumát. Csak olvasható [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Visszaadja a bekezdés alapértelmezett részformátumát. Nem alkalmazódik öröklődés. Csak olvasható [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Visszaadja az alapértelmezett tabuláció méretét öröklődés nélkül. Olvasd **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Visszaadja a bekezdés mélységét. A 0 érték meghatározatlan értéket jelent. Olvasd **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Megállapítja, hogy a kelet-ázsiai sortörést használják-e a bekezdésben. Nem alkalmazódik öröklődés. Olvasd [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Visszaadja a betűtípus igazítását a bekezdésben öröklődés nélkül. Olvasd [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Megállapítja, hogy a függő írásjelek használatban vannak-e a bekezdésben. Nem alkalmazódik öröklődés. Olvasd [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Visszaadja a bekezdés első sor behúzását/függő behúzást öröklődés nélkül. A függő behúzás negatív értékekkel definiálható. Olvasd **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Megállapítja, hogy a latin sortörést használják-e a bekezdésben. Nem alkalmazódik öröklődés. Olvasd [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Visszaadja a bal margót a bekezdésben öröklődés nélkül. Olvasd **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Visszaadja a jobb margót a bekezdésben öröklődés nélkül. Olvasd **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Megállapítja, hogy a jobbról balra írás irányát használják-e a bekezdésben. Nem alkalmazódik öröklődés. Olvasd [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Visszaadja az utolsó sor utáni térköz mennyiségét a bekezdésben öröklődés nélkül. Pozitív érték a betűméret százalékát adja meg a fehér térnek. Negatív érték a fehér tér pontméretét adja meg. Olvasd **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Visszaadja az első sor előtti térköz mennyiségét a bekezdésben öröklődés nélkül. Pozitív érték a betűméret százalékát adja meg a fehér térnek. Negatív érték a fehér tér pontméretét adja meg. Olvasd **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Visszaadja a bázissorok közötti térköz mennyiségét a bekezdésben. Pozitív érték százalék, negatív - pontban megadott méret. Nem alkalmazódik öröklődés. Olvasd **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Visszaadja a bekezdés tabulációját a megadott indexnél. Nem alkalmazódik öröklődés. Csak olvasható [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | Visszaadja a bekezdés tabulációit. Nem alkalmazódik öröklődés. Csak olvasható [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciacsökkentő adatstruktúrát. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | Lekéri a hatékony bekezdésformázási adatokat öröklődéssel. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrszem objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Engedélyezi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-összehasonlítja az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | Beállítja a szöveg igazítását a bekezdésben öröklődés nélkül. Ír [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Beállítja az alapértelmezett tabuláció méretét öröklődés nélkül. Ír **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | Beállítja a bekezdés mélységét. A 0 érték meghatározatlan értéket jelent. Ír **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | Megállapítja, hogy a kelet-ázsiai sortörést használják-e a bekezdésben. Nem alkalmazódik öröklődés. Ír [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | Beállít egy betűtípus igazítást a bekezdésben öröklődés nélkül. Ír [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | Megállapítja, hogy a függő írásjelek használatban vannak-e a bekezdésben. Nem alkalmazódik öröklődés. Ír [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Beállítja a bekezdés első sor behúzását/függő behúzást öröklődés nélkül. A függő behúzás negatív értékekkel definiálható. Ír **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | Megállapítja, hogy a latin sortörést használják-e a bekezdésben. Nem alkalmazódik öröklődés. Ír [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Beállítja a bal margót a bekezdésben öröklődés nélkül. Ír **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Beállítja a jobb margót a bekezdésben öröklődés nélkül. Ír **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | Megállapítja, hogy a jobbról balra írás irányát használják-e a bekezdésben. Nem alkalmazódik öröklődés. Ír [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Beállítja az utolsó sor utáni térköz mennyiségét a bekezdésben öröklődés nélkül. Pozitív érték a betűméret százalékát adja meg a fehér térnek. Negatív érték a fehér tér pontméretét adja meg. Ír **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Beállítja az első sor előtti térköz mennyiségét a bekezdésben öröklődés nélkül. Pozitív érték a betűméret százalékát adja meg a fehér térnek. Negatív érték a fehér tér pontméretét adja meg. Ír **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Beállítja a bázissorok közötti térköz mennyiségét a bekezdésben. Pozitív érték százalék, negatív - pontban megadott méret. Nem alkalmazódik öröklődés. Ír **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását gyengére a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciacsökkentő aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciacsökkentőt. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciacsökkentőt. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrszem objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciacsökkentőt. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciacsökkentőt. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzés


Ez az osztályt arra használják, hogy visszaadja és manipulálja a konkrét bekezdéshez definiált bekezdésformázási tulajdonságokat. Ez azt jelenti, hogy értékek lekérésekor nem alkalmazódik öröklődés, így a legtöbb esetben „nem meghatározott” értékeket kap.

Az öröklött értékeket is tartalmazó hatékony formázási paraméterértékek lekéréséhez a [IParagraphFormat::GetEffective](./geteffective/) metódust kell használni, amely egy [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) példányt ad vissza.

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)