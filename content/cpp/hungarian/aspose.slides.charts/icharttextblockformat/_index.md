---
title: IChartTextBlockFormat
second_title: Aspose.Slides C++ API Referenciája
description: A diagram szövegelemek formázási tulajdonságait reprezentálja.
type: docs
weight: 885
url: /hu/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat osztály


Represents formatting properties for chart text elements.

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## Metódusok

| Method | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célra. |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Visszaadja a függőleges rögzítő szöveget egy [TextFrame](../../aspose.slides/textframe/)-ban. Olvasd [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | Visszaadja a szöveg automatikus illesztési módját. Ennek a tulajdonnak a módosítása csak a következő diagramrészeknél fejthet ki hatást: [DataLabel](../datalabel/) és [DataLabelFormat](../datalabelformat/) (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasd [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | Ha [NullableBool::True](../../aspose.slides/nullablebool/), akkor a szöveget vízszintesen kell középre helyezni a dobozban. Olvasd [NullableBool](../../aspose.slides/nullablebool/). |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Visszaadja az alsó margót (pontban) egy [TextFrame](../../aspose.slides/textframe/)-ben. Ennek a tulajdonnak a módosítása csak a következő diagramrészeknél fejthet ki hatást: [DataLabel](../datalabel/) és [DataLabelFormat](../datalabelformat/) (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasd **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Visszaadja a bal margót (pontban) egy [TextFrame](../../aspose.slides/textframe/)-ben. Ennek a tulajdonnak a módosítása csak a következő diagramrészeknél fejthet ki hatást: [DataLabel](../datalabel/) és [DataLabelFormat](../datalabelformat/) (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasd **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Visszaadja a jobb margót (pontban) egy [TextFrame](../../aspose.slides/textframe/)-ban. Ennek a tulajdonnak a módosítása csak a következő diagramrészeknél fejthet ki hatást: [DataLabel](../datalabel/) és [DataLabelFormat](../datalabelformat/) (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasd **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Visszaadja a felső margót (pontban) egy [TextFrame](../../aspose.slides/textframe/)-ban. Ennek a tulajdonnak a módosítása csak a következő diagramrészeknél fejthet ki hatást: [DataLabel](../datalabel/) és [DataLabelFormat](../datalabelformat/) (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasd **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Meghatározza az egyedi forgatást, amely a szövegre a határolókeret belsejében vonatkozik. Ha nincs megadva, a kísérő alakzat forgása kerül alkalmazásra. Ha meg van adva, akkor ez függetlenül az alakzattól kerül alkalmazásra. Ez azt jelenti, hogy az alakzat rendelkezhet forgatással, miközben a szövegnek is saját forgatása van. A vizuális szövegforgatás értéke ebből a tulajdonságból és a TextVerticalType előre definiált függőleges típusából kerül összegzésre. Olvasd **float**. |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Meghatározza a szöveg orientációját. A vizuális szövegforgatás értéke ebből a tulajdonságból és a RotationAngle egyéni szögéből kerül összegzésre. Olvasd [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | Igaz, ha a szöveg a [TextFrame](../../aspose.slides/textframe/) margóinál van tördelve. Ennek a tulajdonnak a módosítása csak a következő diagramrészeknél fejthet ki hatást: [DataLabel](../datalabel/) és [DataLabelFormat](../datalabelformat/) (teljes támogatás PowerPoint 2007/2013). Olvasd [NullableBool](../../aspose.slides/nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz tartozó hivatkozásszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot hasonlít össze nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | Beállítja a függőleges rögzítő szöveget egy [TextFrame](../../aspose.slides/textframe/)-ban. Írd [TextAnchorType](../../aspose.slides/textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | Beállítja a szöveg automatikus illesztési módját. Ennek a tulajdonnak a módosítása csak a következő diagramrészeknél fejthet ki hatást: [DataLabel](../datalabel/) és [DataLabelFormat](../datalabelformat/) (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre). Írd [TextAutofitType](../../aspose.slides/textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | Ha [NullableBool::True](../../aspose.slides/nullablebool/), akkor a szöveget vízszintesen kell középre helyezni a dobozban. Írd [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Beállítja az alsó margót (pontban) egy [TextFrame](../../aspose.slides/textframe/)-ban. Ennek a tulajdonnak a módosítása csak a következő diagramrészeknél fejthet ki hatást: [DataLabel](../datalabel/) és [DataLabelFormat](../datalabelformat/) (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre). Írd **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Beállítja a bal margót (pontban) egy [TextFrame](../../aspose.slides/textframe/)-ban. Ennek a tulajdonnak a módosítása csak a következő diagramrészeknél fejthet ki hatást: [DataLabel](../datalabel/) és [DataLabelFormat](../datalabelformat/) (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre). Írd **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Beállítja a jobb margót (pontban) egy [TextFrame](../../aspose.slides/textframe/)-ban. Ennek a tulajdonnak a módosítása csak a következő diagramrészeknél fejthet ki hatást: [DataLabel](../datalabel/) és [DataLabelFormat](../datalabelformat/) (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre). Írd **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Beállítja a felső margót (pontban) egy [TextFrame](../../aspose.slides/textframe/)-ban. Ennek a tulajdonnak a módosítása csak a következő diagramrészeknél fejthet ki hatást: [DataLabel](../datalabel/) és [DataLabelFormat](../datalabelformat/) (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre). Írd **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Meghatározza az egyedi forgatást, amely a szövegre a határolókeret belsejében vonatkozik. Ha nincs megadva, a kísérő alakzat forgása kerül alkalmazásra. Ha meg van adva, akkor ez függetlenül az alakzattól kerül alkalmazásra. Ez azt jelenti, hogy az alakzat rendelkezhet forgatással, miközben a szövegnek is saját forgatása van. A vizuális szövegforgatás értéke ebből a tulajdonságból és a TextVerticalType előre definiált függőleges típusából kerül összegzésre. Írd **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | Meghatározza a szöveg orientációját. A vizuális szövegforgatás értéke ebből a tulajdonságból és a RotationAngle egyéni szögéből kerül összegzésre. Írd [Slides::TextVerticalType](../../aspose.slides/textverticaltype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | Igaz, ha a szöveg a [TextFrame](../../aspose.slides/textframe/) margóinál van tördelve. Ennek a tulajdonnak a módosítása csak a következő diagramrészeknél fejthet ki hatást: [DataLabel](../datalabel/) és [DataLabelFormat](../datalabelformat/) (teljes támogatás PowerPoint 2007/2013). Írd [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Állítsa be a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerekben való weak módra való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)