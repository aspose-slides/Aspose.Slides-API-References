---
title: ParagraphFormat
second_title: Aspose.Slides for C++ API referenciája
description: Ez az osztály tartalmazza a bekezdésformázási tulajdonságokat. A IParagraphFormatEffectiveData-től eltérően, az osztály összes tulajdonsága írható.
type: docs
weight: 4668
url: /hu/aspose.slides/paragraphformat/
---
## ParagraphFormat osztály

Ez az osztály tartalmazza a bekezdés formázási tulajdonságait. A [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)-tól eltérően az osztály összes tulajdonsága írható.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Összehasonlítja a megadott objektummal. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célra. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | Visszaadja a szöveg igazítását egy bekezdésben öröklődés nélkül. Olvasd [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | Visszaadja az alapértelmezett tabulálás méretét öröklődés nélkül. Olvasd **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | Megállapítja, hogy a kelet-ázsiai sortörés használatban van-e egy bekezdésben. Nincs alkalmazva öröklődés. Olvasd [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | Visszaadja a betűtípus igazítását egy bekezdésben öröklődés nélkül. Olvasd [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | Megállapítja, hogy függő írásjelek vannak-e használatban egy bekezdésben. Nincs alkalmazva öröklődés. Olvasd [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | Visszaadja a bekezdés első sor behúzását/függő behúzást öröklődés nélkül. A függő behúzás negatív értékekkel is definiálható. Olvasd **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | Megállapítja, hogy a latin sortörés használatban van-e egy bekezdésben. Nincs alkalmazva öröklődés. Olvasd [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | Visszaadja a bal margót egy bekezdésben öröklődés nélkül. Olvasd **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | Visszaadja a jobb margót egy bekezdésben öröklődés nélkül. Olvasd **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Visszaadja a Parent_Immediate objektumot. Csak olvasható [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Visszaadja a szülő [IPresentationComponent](../ipresentationcomponent/) objektumot. Csak olvasható [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | Megállapítja, hogy jobbról balra írás használatban van-e egy bekezdésben. Nincs alkalmazva öröklődés. Olvasd [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | Visszaadja az utolsó sor után lévő térköz mennyiségét egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékában adja meg a fehér tér méretét. A negatív érték a térköz pontméretét adja meg. Olvasd **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | Visszaadja az első sor előtt lévő térköz mennyiségét egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékában adja meg a fehér tér méretét. A negatív érték a térköz pontméretét adja meg. Olvasd **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | Visszaadja az alapvonalak közötti térköz mennyiségét egy bekezdésben. A pozitív érték százalékot jelent, a negatív - pontban mért méretet. Nincs alkalmazva öröklődés. Olvasd **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | Visszaadja egy bekezdés tabulációját a megadott indexnél. Nincs alkalmazva öröklődés. Csak olvasható [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | Visszaadja egy bekezdés tabulációit. Nincs alkalmazva öröklődés. Csak olvasható [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | Megkapja a hatékony bekezdésformázási adatokat az öröklődés alkalmazásával. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Visszaadja a hash kódot. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másoló konstrukcióját. |
|  [ParagraphFormat](./paragraphformat/)() | Inicializál egy új példányt a [ParagraphFormat](./) osztályból. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat összehasonlít referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat összehasonlít referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | Beállítja a szöveg igazítását egy bekezdésben öröklődés nélkül. Írj [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | Beállítja az alapértelmezett tabuláció méretét öröklődés nélkül. Írj **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy a kelet-ázsiai sortörés használatban van-e egy bekezdésben. Nincs alkalmazva öröklődés. Írj [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | Beállítja a betűtípus igazítását egy bekezdésben öröklődés nélkül. Írj [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy függő írásjelek használatban vannak-e egy bekezdésben. Nincs alkalmazva öröklődés. Írj [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | Beállítja a bekezdés első sor behúzását/függő behúzást öröklődés nélkül. A függő behúzás negatív értékekkel is definiálható. Írj **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy a latin sortörés használatban van-e egy bekezdésben. Nincs alkalmazva öröklődés. Írj [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | Beállítja a bal margót egy bekezdésben öröklődés nélkül. Írj **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | Beállítja a jobb margót egy bekezdésben öröklődés nélkül. Írj **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | Megállapítja, hogy jobbról balra írás használatban van-e egy bekezdésben. Nincs alkalmazva öröklődés. Írj [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | Beállítja az utolsó sor után lévő térköz mennyiségét egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékában adja meg a fehér tér méretét. A negatív érték a térköz pontméretét adja meg. Írj **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | Beállítja az első sor előtt lévő térköz mennyiségét egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékában adja meg a fehér tér méretét. A negatív érték a térköz pontméretét adja meg. Írj **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | Beállítja az alapvonalak közötti térköz mennyiségét egy bekezdésben. A pozitív érték százalékot jelent, a negatív - pontban mért méretet. Nincs alkalmazva öröklődés. Írj **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók átváltását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használj okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használj okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használj okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használj okos pointereket vagy ThisProtector-t. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések

Ez az osztály a konkrét bekezdésre definiált bekezdésformázási tulajdonságok visszaadására és manipulálására szolgál. Ez azt jelenti, hogy értékek lekérdezésekor nincs alkalmazva öröklődés, így a legtöbb esetben az értékek a "nem definiált" állapotot jelentik.

A hatékony formázási paraméterértékek, beleértve az örökölt értékeket, lekéréséhez a [ParagraphFormat::GetEffective](./geteffective/) metódust kell használni, amely egy [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) példányt ad vissza.

## Lásd még

* Osztály [PVIObject](../pviobject/)
* Osztály [IParagraphFormat](../iparagraphformat/)
* Osztály [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)