---
title: ILegend
second_title: Aspose.Slides C++ API Referencia
description: A diagram legenda tulajdonságait képviseli.
type: docs
weight: 1080
url: /hu/aspose.slides.charts/ilegend/
---
## ILegend osztály

A diagram legenda tulajdonságait képviseli.

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást utánoz, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN egyetlen értékhez sem egyenlő, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást utánoz a double típusra, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN egyetlen értékhez sem egyenlő, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Megadja a diagram elem tényleges magasságát. Hívja meg a(z) [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Megadja a diagram elem tényleges szélességét. Hívja meg a(z) [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Megadja a diagram elem tényleges x helyzetét (bal) a diagram bal felső sarkához képest. Hívja meg a(z) [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Megadja a diagram elem tényleges felső pozícióját a diagram bal felső sarkához képest. Hívja meg a(z) [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Lekéri a diagram elem felső részét a diagram magasságának törtként. Csak olvasható **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Visszaadja a diagramot. Csak olvasható [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | Lekéri a legenda bejegyzéseit. Csak olvasható [ILegendEntryCollection](../ilegendentrycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | Lekéri a legendakelemhez tartozó adatponthoz a megadott indexű diagrambejegyzés tulajdonságait. A következő diagramtípusok esetén: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, az adatpont az első sorozatból kerül kiválasztásra. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Visszaadja egy legenda formátumát. Csak olvasható [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Megadja a diagram elem magasságát a diagram magasságának törtként. Olvasható **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Meghatározza, hogy más diagramelemek átfedhetik-e a legendát. Olvasható **bool**. |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | Megadja a legenda pozícióját egy diagramon. A X, Y, Width, Heigt tulajdonságok nem-NaN értékei felülírják ennek a tulajdonságnak a hatását. Olvasható [LegendPositionType](../legendpositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Visszaadja a prezentációt. Csak olvasható [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Lekéri a diagram elem jobb oldalát a diagram szélességének törtként. Csak olvasható **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Visszaadja az alap dia. Csak olvasható [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Visszaadja a diagram szövegformátumát. Csak olvasható [IChartTextFormat](../icharttextformat/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Megadja a diagram elem szélességét a diagram szélességének törtként. Olvasható **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Megadja a diagram elem x helyzetét (bal) a diagram szélességének törtként. Olvasható **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Megadja a diagram elem felső részét a diagram magasságának törtként. Olvasható **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri a objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a(z) [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot referenciával hasonlít össze a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Megadja a diagram elem magasságát a diagram magasságának törtként. Írható **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Meghatározza, hogy más diagramelemek átfedhetik-e a legendát. Írható **bool**. |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | Megadja a legenda pozícióját egy diagramon. A X, Y, Width, Heigt tulajdonságok nem-NaN értékei felülírják ennek a tulajdonságnak a hatását. Írható [LegendPositionType](../legendpositiontype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Megadja a diagram elem szélességét a diagram szélességének törtként. Írható **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Megadja a diagram elem x helyzetét (bal) a diagram szélességének törtként. Írható **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Megadja a diagram elem felső részét a diagram magasságának törtként. Írható **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a gyenge módra a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a(z) [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisitja az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* osztály [ILayoutable](../ilayoutable/)
* osztály [IFormattedTextContainer](../iformattedtextcontainer/)
* osztály [IActualLayout](../iactuallayout/)
* névtér [Aspose::Slides::Charts](../)
* könyvtár [Aspose.Slides](../../)