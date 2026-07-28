---
title: IChartParagraphFormat
second_title: Aspose.Slides for C++ API referenciája
description: A diagram bekezdésformázási tulajdonságait reprezentálja.
type: docs
weight: 781
url: /hu/aspose.slides.charts/ichartparagraphformat/
---
## IChartParagraphFormat osztály

A diagram bekezdésformázási tulajdonságait reprezentálja.

```cpp
class IChartParagraphFormat : public virtual System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual [TextAlignment](../../aspose.slides/textalignment/) [get_Alignment](./get_alignment/)() | Visszaadja egy bekezdés szövegigazítását. Olvasd el [TextAlignment](../../aspose.slides/textalignment/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Visszaadja az alapértelmezett tabuláció méretét. Olvasd el **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Megállapítja, hogy egy bekezdésben kelet-ázsiai sortörést használnak-e. Olvasd el [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Visszaadja egy bekezdés betűtípusigazítását. Olvasd el [Slides::FontAlignment](../../aspose.slides/fontalignment/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Megállapítja, hogy egy bekezdésben függőleges írásjelek használata engedélyezett-e. Olvasd el [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Visszaadja a bekezdés első sor behúzását/függő behúzást. A függő behúzás negatív értékekkel is meghatározható. Olvasd el **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Megállapítja, hogy egy bekezdésben latin sortörést használnak-e. Olvasd el [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Visszaadja a bal margót egy bekezdésben. Olvasd el **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Visszaadja a jobb margót egy bekezdésben. Olvasd el **float**. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Megállapítja, hogy egy bekezdésben jobbról balra írás irányt használnak-e. Olvasd el [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Visszaadja az utolsó sor utáni térközt egy bekezdésben. Olvasd el **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Visszaadja az első sor előtti térközt egy bekezdésben. Olvasd el **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Visszaadja az alapvonalak közti távolságot egy bekezdésben. Olvasd el **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../../aspose.slides/itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Visszaadja egy bekezdés tabulációját a megadott indexen. Csak olvasható [Aspose::Slides::ITab](../../aspose.slides/itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../../aspose.slides/itabcollection/)\> [get_Tabs](./get_tabs/)() | Visszaadja egy bekezdés tabulációit. Csak olvasható [ITabCollection](../../aspose.slides/itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus megfelelője. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás megfelelője. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor megfelelője. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus megfelelője. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak újat inicializál, és lehetővé teszi az alosztályok másolási konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak újat inicializál, és lehetővé teszi az alosztályok másolási konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípust hivatkozás alapján hasonlít össze a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámlálót a megadott értékkel. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../../aspose.slides/textalignment/)) | Beállítja egy bekezdés szövegigazítását. Írj [TextAlignment](../../aspose.slides/textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Beállítja az alapértelmezett tabuláció méretét. Írj **float**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | Megállapítja, hogy egy bekezdésben kelet-ázsiai sortörést használnak-e. Írj [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../../aspose.slides/fontalignment/)) | Beállítja egy bekezdés betűtípusigazítását. Írj [Slides::FontAlignment](../../aspose.slides/fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../../aspose.slides/nullablebool/)) | Megállapítja, hogy egy bekezdésben függő írásjelek használata engedélyezett-e. Írj [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Beállítja a bekezdés első sor behúzását/függő behúzást. A függő behúzás negatív értékekkel is meghatározható. Írj **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../../aspose.slides/nullablebool/)) | Megállapítja, hogy egy bekezdésben latin sortörést használnak-e. Írj [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Beállítja a bal margót egy bekezdésben. Írj **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Beállítja a jobb margót egy bekezdésben. Írj **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../../aspose.slides/nullablebool/)) | Megállapítja, hogy egy bekezdésben jobbról balra írás irányt használnak-e. Írj [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Beállítja az utolsó sor utáni térközt egy bekezdésben. Írj **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Beállítja az első sor előtti térközt egy bekezdésben. Írj **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Beállítja az alapvonalak közti térközt egy bekezdésben. Írj **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóként állítja be (a megosztott helyett). Lehetővé teszi a mutatók konténerben weak módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott hivatkozásszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus megfelelője. Lehetővé teszi egyedi objektumok karakterláncba konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Meghívja az objektum destruktorát. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)