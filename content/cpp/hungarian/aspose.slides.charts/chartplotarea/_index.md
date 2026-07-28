---
title: ChartPlotArea
second_title: Aspose.Slides for C++ API referenciája
description: A téglalap, amelyben a diagramot kell ábrázolni.
type: docs
weight: 248
url: /hu/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea osztály

A téglalap, amelyben a diagramot meg kell jeleníteni.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Meghatározza a diagram elem tényleges magasságát. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvasható **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Meghatározza a diagram elem tényleges szélességét. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvasható **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Meghatározza a diagram elem tényleges x koordinátáját (bal) a diagram bal felső sarkához képest. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvasható **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Meghatározza a diagram elem tényleges felső pozícióját a diagram bal felső sarkához képest. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvasható **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Alsó. Csak olvasható **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). Csak olvasható [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Visszaadja a rajzterület formátumát. Csak olvasható [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Visszaadja a rajzterület körülhatároló doboz magasságát a diagram magasságának hányadaként (0 és 1 között). Olvasható **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | Meghatározza, hogy a helyzet hogyan számítandó: true \\u2013 automatikusan számítva; az X, Y, Width, Height tulajdonságok által definiált. Csak olvasható **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | Ha a rajzterület elrendezése kézzel van megadva, ez a tulajdonság meghatározza, hogy a rajzterületet a belseje (a tengely és tengelycímkék nélkül) vagy a külsője (tengely és tengelycímkék beleértve) szerint rendezzük. Olvasható [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | Jobb. Csak olvasható **float**. |
| **float** [get_Width](./get_width/)() override | Visszaadja a rajzterület körülhatároló doboz szélességét a diagram szélességének hányadaként (0 és 1 között). Olvasható **float**. |
| **float** [get_X](./get_x/)() override | Visszaadja a rajzterület körülhatároló doboz bal felső sarkának x koordinátáját a diagram szélességének hányadaként (0 és 1 között). Olvasható **float**. |
| **float** [get_Y](./get_y/)() override | Visszaadja a rajzterület körülhatároló doboz bal felső sarkának y koordinátáját a diagram magasságának hányadaként (0 és 1 között). Olvasható **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus egy példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Nem másol semmit, csak új objektumot inicializál, és lehetővé teszi alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Nem másol semmit, csak új objektumot inicializál, és lehetővé teszi alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referencia szerint hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referencia szerint hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_Height](./set_height/)(**float**) override | Beállítja a rajzterület körülhatároló doboz magasságát a diagram magasságának hányadaként (0 és 1 között). Írja **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | Ha a rajzterület elrendezése kézzel van megadva, ez a tulajdonság meghatározza, hogy a rajzterületet a belseje (a tengely és tengelycímkék nélkül) vagy a külsője (tengely és tengelycímkék beleértve) szerint rendezzük. Írja [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | Beállítja a rajzterület körülhatároló doboz szélességét a diagram szélességének hányadaként (0 és 1 között). Írja **float**. |
| void [set_X](./set_x/)(**float**) override | Beállítja a rajzterület körülhatároló doboz bal felső sarkának x koordinátáját a diagram szélességének hányadaként (0 és 1 között). Írja **float**. |
| void [set_Y](./set_y/)(**float**) override | Beállítja a rajzterület körülhatároló doboz bal felső sarkának y koordinátáját a diagram magasságának hányadaként (0 és 1 között). Írja **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem megosztott). Lehetővé teszi a tárolókban lévő mutatók gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [DomObject](../../aspose.slides/domobject/)
* Osztály [IChartPlotArea](../ichartplotarea/)
* Névtér [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)