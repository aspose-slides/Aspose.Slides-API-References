---
title: CommonSlideViewProperties
second_title: Aspose.Slides C++ API-referencia
description: Képviseli a közös dia nézet tulajdonságait.
type: docs
weight: 469
url: /hu/aspose.slides/commonslideviewproperties/
---
## CommonSlideViewProperties osztály

Képviseli a közös dia nézet tulajdonságait.

```cpp
class CommonSlideViewProperties : public Aspose::Slides::ICommonSlideViewProperties
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semelyik értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semelyik értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuide](../idrawingguide/)\> [get_DrawingGuide](./get_drawingguide/)(**int32_t**) override | Visszaadja a megadott indexű rajzsegédet. Csak olvasható [Aspose::Slides::IDrawingGuide](../idrawingguide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() override | Visszaadja a rajzsegédek gyűjteményét. Csak olvasható [IDrawingGuidesCollection](../idrawingguidescollection/) |
| **int32_t** [get_Scale](./get_scale/)() override | Megadja a nézet nagyítási arányát százalékban. Olvas **int32_t**. |
| **bool** [get_VariableScale](./get_variablescale/)() override | Megadja, hogy a nézet tartalma automatikusan skálázódjon a jelenlegi ablakmérethez legjobban illeszkedő módon. Olvas **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciacs számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyéni objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Referencia szerint hasonlítja össze az objektumokat. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Referencia szerint hasonlítja össze az objektumokat. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Az értéktípusú objektumot hasonlít össze referenciaként a nullptr-pel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata karakterláncok esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciacs számlálót a megadott értékkel. |
| void [set_Scale](./set_scale/)(**int32_t**) override | Megadja a nézet nagyítási arányát százalékban. Írás **int32_t**. |
| void [set_VariableScale](./set_variablescale/)(**bool**) override | Megadja, hogy a nézet tartalma automatikusan skálázódjon a jelenlegi ablakmérethez legjobban illeszkedő módon. Írás **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n'th sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását **konténerek**-ben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a **megosztott** referenciacs számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciacs számlálót. Nem szabad közvetlenül hívni; helyette használjon **okos** mutatókat vagy a ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciacs számlálót. Nem szabad közvetlenül hívni; helyette használjon **okos** mutatókat vagy a ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyéni objektumok átalakítását karakterlánccá. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciacs számlálót. Nem szabad közvetlenül hívni; helyette használjon **okos** mutatókat vagy a ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciacs számlálót. Nem szabad közvetlenül hívni; helyette használjon **okos** mutatókat vagy a ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések

Az alábbi példa bemutatja, hogyan állítható be a nagyítási érték a PowerPoint [Presentation](../presentation/) dián. 
```cpp
// Egy Presentation objektum példányosítása, amely egy bemutató fájlt képvisel
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// A bemutató nézet tulajdonságainak beállítása
presentation->get_ViewProperties()->get_SlideViewProperties()->set_Scale(100);
// Nagyítási érték százalékban a dia nézethez
presentation->get_ViewProperties()->get_NotesViewProperties()->set_Scale(100);
// Nagyítási érték százalékban a jegyzet nézethez
presentation->Save(u"Zoom_out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [ICommonSlideViewProperties](../icommonslideviewproperties/)
* Névterület [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)