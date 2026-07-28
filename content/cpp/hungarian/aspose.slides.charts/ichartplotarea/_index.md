---
title: IChartPlotArea
second_title: Aspose.Slides for C++ API referencia
description: A diagram cím tulajdonságait reprezentálja.
type: docs
weight: 794
url: /hu/aspose.slides.charts/ichartplotarea/
---
## IChartPlotArea osztály


A diagram cím tulajdonságait reprezentálja.

```cpp
class IChartPlotArea : public Aspose::Slides::Charts::ILayoutable,
                       public Aspose::Slides::Charts::IActualLayout
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Megadja a diagram elem tényleges magasságát. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Megadja a diagram elem tényleges szélességét. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Megadja a diagram elem tényleges x helyzetét (bal), a diagram bal felső sarkához viszonyítva. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Megadja a diagram elem tényleges felső pozícióját a diagram bal felső sarkához viszonyítva. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | A diagram elem felső részét a diagram magasságának tört részeként adja vissza. Csak olvasható **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Visszaadja a diagramot. Csak olvasható [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Visszaadja a diagramterület formátumát. Csak olvasható [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | A diagram elem magasságát a diagram magasságának tört részeként adja meg. Olvasható **float**. |
| virtual [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() | Ha a diagramterület elrendezése manuálisan van definiálva, ez a tulajdonság meghatározza, hogy a diagramterületet a belseje (nem tartalmazva a tengelyeket és tengelycímkéket) vagy a külseje (tengelyeket és tengelycímkéket is tartalmazva) szerint rendezze. Olvas [LayoutTargetType](../layouttargettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Visszaadja a bemutatót. Csak olvasható [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | A diagram elem jobb oldalát a diagram szélességének tört részeként adja vissza. Csak olvasható **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Visszaadja az alapdiát. Csak olvasható [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | A diagram elem szélességét a diagram szélességének tört részeként adja meg. Olvasható **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | A diagram elem x helyzetét (bal) a diagram szélességének tört részeként adja meg. Olvasható **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | A diagram elem felső részét a diagram magasságának tört részeként adja meg. Olvasható **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz társított referenciacsökkentő adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi a saját objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy példány-e a targetType által leírt típusról. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi a saját típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstruálását. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstruálását. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | A diagram elem magasságát a diagram magasságának tört részeként adja meg. Ír **float**. |
| virtual void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) | Ha a diagramterület elrendezése manuálisan van definiálva, ez a tulajdonság meghatározza, hogy a diagramterületet a belseje (nem tartalmazva a tengelyeket és tengelycímkéket) vagy a külseje (tengelyeket és tengelycímkéket is tartalmazva) szerint rendezze. Ír [LayoutTargetType](../layouttargettype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | A diagram elem szélességét a diagram szélességének tört részeként adja meg. Ír **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | A diagram elem x helyzetét (bal) a diagram szélességének tört részeként adja meg. Ír **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | A diagram elem felső részét a diagram magasságának tört részeként adja meg. Ír **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-dik sablonargumentumot gyenge mutatóvá állítja (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a tárolókban gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi a saját objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem kell közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Lásd még

* Osztály [ILayoutable](../ilayoutable/)
* Osztály [IActualLayout](../iactuallayout/)
* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)