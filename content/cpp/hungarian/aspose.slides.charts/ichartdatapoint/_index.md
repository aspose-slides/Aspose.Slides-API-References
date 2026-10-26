---
title: IChartDataPoint
second_title: Aspose.Slides C++ API referencia
description: A sorozat adatpontját képviseli.
type: docs
weight: 677
url: /hu/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint osztály


Represents series data point.

```cpp
class IChartDataPoint : public Aspose::Slides::Charts::IActualLayout
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szintaxisával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semelyik értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semelyik értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Megadja a diagram elem tényleges magasságát. Hívja meg a(z) [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Megadja a diagram elem tényleges szélességét. Hívja meg a(z) [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Megadja a diagram elem tényleges x helyzetét (balra) a diagram bal felső sarkához képest. Hívja meg a(z) [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Megadja a diagram elem tényleges felső pozícióját a diagram bal felső sarkához képest. Hívja meg a(z) [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előbb a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() | Visszaadja a diagram adatpont buborékméretét. Csak olvasható [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() | Visszaadja a diagram adatpont színértékét. Map diagramokhoz használható. Csak olvasható [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) | Visszaad egy adatpont szintet a megadott indexnél. Treeamp és Sunburst sorozatokhoz alkalmazható. Az adatpont szintek indexelése nulláral kezdődik. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() | Visszaadja az adatpont szintek konténerét. Treeamp és Sunburst sorozatokhoz alkalmazható. Az adatpont szintek indexelése nulláral kezdődik. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() | A sorozat hibasáv értékeket képviseli egyedi értéktípus esetén. Csak olvasható [IErrorBarsCustomValues](../ierrorbarscustomvalues/). |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | Megadja, hogy az adatpont mennyivel legyen eltolva a kör diagram középpontjától. Olvasható **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | A formázási tulajdonságokat képviseli. Olvasható [IFormat](../iformat/). |
| virtual **uint32_t** [get_Index](./get_index/)() | Meghatározza, hogy a szülő gyermekgyűjteményének melyik elemére vonatkozik ez az adatpont. Olvasható **uint32_t**. |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | Megadja, hogy az adatpont megfordítja-e a színeit, ha az érték negatív. Olvasható **bool**. |
| virtual **bool** [get_IsBubble3D](./get_isbubble3d/)() | Megadja, hogy a buborékokra 3-D hatás legyen alkalmazva. Olvasható **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() | A diagram adatpont címkéjét képviseli. Csak olvasható [IDataLabel](../idatalabel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | Egy adatjelölőt határoz meg. Csak olvasható [IMarker](../imarker/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | A megfelelő legendabejegyzés tulajdonságait adja vissza, ha a diagram típusa a következő lista valamelyike: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). Csak olvasható [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual **bool** [get_SetAsTotal](./get_setastotal/)() | Az adatpontot összegként állítja be. Csak Waterfall sorozatoknál alkalmazható. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() | Visszaadja a diagram adatpont méretértékét. Treemap és Sunburst diagramokhoz használható. Csak olvasható [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() | Visszaadja a diagram adatpont értékét. Csak olvasható [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() | Visszaadja a diagram adatpont x-értékét. Csak olvasható [IStringOrDoubleChartValue](../istringordoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() | Visszaadja a diagram adatpont y-értékét. Csak olvasható [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() | Visszaad egy automatikus színt az adatponthoz a sorozat indexe, adatpont indexe, ParentSeriesGroup.IsColorVaried tulajdonság és a diagram stílusa alapján. Ez a szín alapértelmezés szerint akkor használatos, ha a FillType értéke NotDefined. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekérdezi az objektummal társított hivatkozásszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi a saját objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekérdezi az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a céltípus által leírt példány-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a(z) [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi a saját típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és engedélyezi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és engedélyezi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja az értéktípusú objektumot a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetére. |
| virtual void [Remove](./remove/)() | Eltávolítja a DataPoint-ot a diagram sorozatból. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámlálót a megadott értékkel. |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | Megadja, hogy az adatpont mennyivel legyen eltolva a kör diagram középpontjától. Írja **int32_t**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | A formázási tulajdonságokat képviseli. Írja [IFormat](../iformat/). |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | Megadja, hogy az adatpont megfordítja-e a színeit, ha az érték negatív. Írja **bool**. |
| virtual void [set_IsBubble3D](./set_isbubble3d/)(**bool**) | Megadja, hogy a buborékokra 3-D hatás legyen alkalmazva. Írja **bool**. |
| virtual void [set_SetAsTotal](./set_setastotal/)(**bool**) | Az adatpontot összegként állítja be. Csak Waterfall sorozatoknál alkalmazható. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóvá (nem megosztottá) állítja. Lehetővé teszi a mutatók átkapcsolását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekérdezi a megosztott hivatkozásszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Közvetlenül nem szabad meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámlálót. Közvetlenül nem szabad meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi a saját objektumok string-gé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | A C# typeof([System.Object](../../system/object/)) konstrukciót valósítja meg. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a(z) [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Közvetlenül nem szabad meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Közvetlenül nem szabad meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Lásd még

* Osztály [IActualLayout](../iactuallayout/)
* Névterület [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)