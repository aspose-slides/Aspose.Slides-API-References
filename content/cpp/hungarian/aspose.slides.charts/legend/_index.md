---
title: Legend
second_title: Aspose.Slides for C++ API referencia
description: A diagram legendájának tulajdonságait reprezentálja.
type: docs
weight: 1262
url: /hu/aspose.slides.charts/legend/
---
## Legend osztály

A diagram legendájának tulajdonságait reprezentálja.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## Módszerek

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika alapján. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Hivatkozástípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Meghatározza a diagram elem tényleges magasságát. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvassa **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Meghatározza a diagram elem tényleges szélességét. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvassa **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Meghatározza a diagram elem tényleges x helyzetét (bal), a diagram bal felső sarkához képest. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvassa **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Meghatározza a diagram elem tényleges felső pozícióját a diagram bal felső sarkához képest. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvassa **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Alsó. Csak olvasható **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Visszaadja a diagramot. Csak olvasható [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | Lekérdezi a legendabejegyzéseket. Csak olvasható [ILegendEntryCollection](../ilegendentrycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | Lekéri a megadott indexnél lévő diagram adatpontnak megfelelő legendabejegyzés tulajdonságait. A diagramtípusok esetén: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, az adatpont az első sorozatból kerül. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Visszaadja a legenda formátumát. Csak olvasható [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Visszaadja a legenda magasságát a diagram magasságának arányában. Olvassa **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Megállapítja, hogy a diagram más elemei átfedhetik-e a legendát. Olvassa **bool**. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | Meghatározza a legend pozícióját egy diagramon. A X, Y, Width, Heigt tulajdonságok NaN-nek nem megfelelő értékei felülbírálják ennek a tulajdonságnak a hatását. Olvassa [LegendPositionType](../legendpositiontype/). |
| **float** [get_Right](./get_right/)() override | Jobb. Csak olvasható **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Szövegformátum. Csak olvasható [IChartTextFormat](../icharttextformat/). |
| **float** [get_Width](./get_width/)() override | Visszaadja a legenda szélességét a diagram szélességének arányában. Olvassa **float**. |
| **float** [get_X](./get_x/)() override | Visszaadja a legenda x koordinátáját a diagram szélességének arányában. Olvassa **float**. |
| **float** [get_Y](./get_y/)() override | Visszaadja a legenda y koordinátáját a diagram magasságának arányában. Olvassa **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekérdezi az objektummal kapcsolatos referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyéni objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekérdezi az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak újat inicializál, és lehetővé teszi a származtatott osztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak újat inicializál, és lehetővé teszi a származtatott osztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot hivatkozásként hasonlít össze nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_Height](./set_height/)(**float**) override | Beállítja a legenda magasságát a diagram magasságának arányában. Írja **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Megállapítja, hogy a diagram más elemei átfedhetik-e a legendát. Írja **bool**. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | Meghatározza a legenda pozícióját egy diagramon. A X, Y, Width, Heigt tulajdonságok NaN-nek nem megfelelő értékei felülbírálják ennek a tulajdonságnak a hatását. Írja [LegendPositionType](../legendpositiontype/). |
| void [set_Width](./set_width/)(**float**) override | Beállítja a legenda szélességét a diagram szélességének arányában. Írja **float**. |
| void [set_X](./set_x/)(**float**) override | Beállítja a legenda x koordinátáját a diagram szélességének arányában. Írja **float**. |
| void [set_Y](./set_y/)(**float**) override | Beállítja a legenda y koordinátáját a diagram magasságának arányában. Írja **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | A n-edik sablonargumentumot gyenge mutatóként állítja be (a megosztott helyett). Lehetővé teszi a mutatók konténerben való weak módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekérdezi a megosztott referencia számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtectort. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtectort. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyéni objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtectort. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtectort. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [DomObject](../../aspose.slides/domobject/)
* Osztály [ILegend](../ilegend/)
* Névterület [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)