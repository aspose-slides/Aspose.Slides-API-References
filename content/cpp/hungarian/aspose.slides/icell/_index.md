---
title: ICell
second_title: Aspose.Slides C++ API referencia
description: Egy cellát képvisel egy táblázatban.
type: docs
weight: 1639
url: /hu/aspose.slides/icell/
---
## ICell osztály

Egy cellát képvisel egy táblázatban.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | Megállapítja, hogy a szövegmező középre van-e helyezve a cellán belül. Olvasás **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | Visszaadja a [CellFormat](../cellformat/) objektumot, amely a cella formázási tulajdonságait tartalmazza. Csak olvasható [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | Visszaadja a szülő táblázat táblázatrácsának azon oszlopainak számát, amelyet az aktuális cella átfog. Ez a tulajdonság lehetővé teszi, hogy a cellák egyesültnek tűnjenek, mivel átfogják más cellák függőleges határait a táblázatban. Csak olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | Lekéri a cella első oszlopát. Csak olvasható [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | Visszaadja az első oszlop indexét, amelyet a cella lefed. Csak olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | Lekéri a cella első sorát. Csak olvasható [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | Visszaadja az első sor indexét, amelyet a cella lefed. Csak olvasható **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | Visszaadja a cella magasságát. Csak olvasható **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | Igaz értéket ad vissza, ha a cella egy bármely módosított cellával össze van olvasztva, ellenkező esetben hamis. Csak olvasható **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Visszaadja az alsó margót egy [TextFrame](../textframe/)-ben. Olvasás **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Visszaadja a bal margót egy [TextFrame](../textframe/)-ben. Olvasás **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Visszaadja a jobb margót egy [TextFrame](../textframe/)-ben. Olvasás **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Visszaadja a felső margót egy [TextFrame](../textframe/)-ben. Olvasás **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | Visszaadja a cella minimális magasságát. Ez a cella által lefedett összes sor minimális magasságainak összege. Csak olvasható **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | Visszaadja a táblázat bal oldalától a cella bal oldaláig terjedő távolságot. Csak olvasható **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | Visszaadja a táblázat felső oldalától a cella felső oldaláig terjedő távolságot. Csak olvasható **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Visszaadja a prezentációt. Csak olvasható [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | Visszaadja a sorok számát, amelyet egy összeolvasztott cella átfog. Ez a vMerge attribútummal együtt használható más cellákon, hogy meghatározza a vízszintes összefűzés kezdőcelláját. Csak olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Visszaadja az alapdiát. Csak olvasható [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | Visszaadja a cella szülő [Table](../table/) objektumát. Csak olvasható [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | Visszaadja a szöveghorgony típusát. Olvasás [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Visszaadja a cella szövegkeretét. Csak olvasható [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Visszaadja a függőleges szöveg típusát. Olvasás [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | Visszaadja a cella szélességét. Csak olvasható **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatszerkezetet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit sem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja az értéktípusú objektumot a nullptr-hez. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | Megállapítja, hogy a szövegmező középre van-e helyezve a cellán belül. Írás **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Beállítja az alsó margót egy [TextFrame](../textframe/)-ben. Írás **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Beállítja a bal margót egy [TextFrame](../textframe/)-ben. Írás **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Beállítja a jobb margót egy [TextFrame](../textframe/)-ben. Írás **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Beállítja a felső margót egy [TextFrame](../textframe/)-ben. Írás **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | Beállítja a szöveghorgony típusát. Írás [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Beállítja a függőleges szöveg típusát. Írás [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge pointerre (a megosztott helyett) állítja. Lehetővé teszi a pointerek átváltását gyenge módra konténereken belül. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használj okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használj okos pointereket vagy ThisProtector-t. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | Felosztja a cellát két cellára az oszlop indexe alapján. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | Felosztja a cellát magasság alapján. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | Felosztja a cellát két cellára a sor indexe alapján. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | Felosztja a cellát szélesség alapján. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használj okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használj okos pointereket vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatszerkezetet. |

## Lásd még

* Osztály [ISlideComponent](../islidecomponent/)
* Névtere [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)