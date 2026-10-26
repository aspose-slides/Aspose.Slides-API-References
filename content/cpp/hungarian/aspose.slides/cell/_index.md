---
title: Cell
second_title: Aspose.Slides C++ API-referencia
description: A táblázat egy celláját reprezentálja.
type: docs
weight: 300
url: /hu/aspose.slides/cell/
---
## Cell osztály

Represents a cell of a table.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szintaxis használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN egyetlen értékhez sem egyenlő, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN egyetlen értékhez sem egyenlő, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | Megállapítja, hogy a szövegdoboz a cellában középre van-e igazítva. Olvas **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | Visszaadja a [CellFormat](../cellformat/) objektumot, amely a cella formázási tulajdonságait tartalmazza. Csak olvasható [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | Visszaadja a szülő táblázat táblarácsában lévő rácsoszlopok számát, amelyet az aktuális cella átfed. Ez a tulajdonság lehetővé teszi, hogy a cellák egyesítettnek tűnjenek, mivel átnyúlnak más cellák függőleges határain. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | Lekéri a cella első oszlopát. Csak olvasható [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | Visszaadja az első oszlop indexét, amelyet a cella lefed. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | Lekéri a cella első sorát. Csak olvasható [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | Visszaadja az első sor indexét, amelyet a cella lefed. Csak olvasható **int32_t**. |
| **double** [get_Height](./get_height/)() override | Visszaadja a cella magasságát. Csak olvasható **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | Igaz értéket ad vissza, ha a cella egyesített bármely módosított cellával, egyébként hamis. Csak olvasható **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Visszaadja az alsó margót a [TextFrame](../textframe/)-ban. Olvas **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Visszaadja a bal margót a [TextFrame](../textframe/)-ban. Olvas **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Visszaadja a jobb margót a [TextFrame](../textframe/)-ban. Olvas **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Visszaadja a felső margót a [TextFrame](../textframe/)-ban. Olvas **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | Visszaadja a cella minimális magasságát. Ez a cella által lefedett összes sor minimális magasságának összege. Csak olvasható **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | Visszaadja a táblázat bal oldalától a cella bal oldaláig terjedő távolságot. Csak olvasható **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | Visszaadja a táblázat felső oldalától a cella felső oldaláig terjedő távolságot. Csak olvasható **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Visszaadja a cella szülőelőadását. Csak olvasható [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | Visszaadja a sorok számát, amelyet egy egyesített cella kiterjed. Ez a vMerge attribútummal más cellákon együtt használatos a vízszintes egyesítés kezdőcellájának meghatározásához. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Visszaadja a cella szülődiapozitívját. Csak olvasható [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | Visszaadja a cellához tartozó szülő [Table](../table/) objektumot. Csak olvasható [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | Visszaadja a szövegankor típusát. Olvas [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Visszaadja a cella szövegtörzsét. Csak olvasható [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Visszaadja a függőleges szöveg típusát. Olvas [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | Visszaadja a cella szélességét. Csak olvasható **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) védőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként összehasonlítja az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | Megállapítja, hogy a szövegdoboz a cellában középre van-e igazítva. Ír **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Beállítja az alsó margót a [TextFrame](../textframe/)-ban. Ír **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Beállítja a bal margót a [TextFrame](../textframe/)-ban. Ír **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Beállítja a jobb margót a [TextFrame](../textframe/)-ban. Ír **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Beállítja a felső margót a [TextFrame](../textframe/)-ban. Ír **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | Beállítja a szövegankor típusát. Ír [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Beállítja a függőleges szöveg típusát. Ír [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók tárolókban történő weak módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; használjon intelligens mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; használjon intelligens mutatókat vagy ThisProtector-t. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | A cellát két cellára osztja az oszlopindex szerint. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | A cellát magasság szerint osztja. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | A cellát két cellára osztja a sorindex szerint. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | A cellát szélesség szerint osztja. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) védőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; használjon intelligens mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; használjon intelligens mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IDOMObject](../idomobject/)
* Osztály [ICell](../icell/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)