---
title: Axis
second_title: Aspose.Slides C++ API referencia
description: Becsomagolja azt az objektumot, amely egy diagram tengelyét reprezentálja.
type: docs
weight: 14
url: /hu/aspose.slides.charts/axis/
---
## Axis osztály


Becsomagolja azt az objektumot, amely egy diagram tengelyét reprezentálja.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Megadja a tengely tényleges főegységét. Előtte hívd meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a tényleges érték lekéréséhez. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Megadja a tengely tényleges főegység skáláját. Előtte hívd meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a tényleges érték lekéréséhez. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Megadja a tengely tényleges legnagyobb értékét. Előtte hívd meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a tényleges érték lekéréséhez. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Megadja a tengely tényleges alsegységét. Előtte hívd meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a tényleges érték lekéréséhez. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Megadja a tengely tényleges alegység skáláját. Előtte hívd meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a tényleges érték lekéréséhez. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Megadja a tengely tényleges legkisebb értékét. Előtte hívd meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a tényleges érték lekéréséhez. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Képviseli a kategória tengely aggregációs típusát (binning). Kategóriára alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Jelzi, hogy az értéktengely áthalad-e a kategória tengelyen a kategóriák között. Ez a tulajdonság csak kategória tengelyekre vonatkozik, és nem érvényes 3D diagramokra. Olvasható **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Megadja a legkisebb időegységet, amely a dátum tengelyen megjelenik. Olvasható [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | Megadja a bin szélességét, amikor az AggregationType tulajdonság értéke [AxisAggregationType::ByBinWidth](../axisaggregationtype/)-ra van állítva. Kategória tengelyeken alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Megadja a kategória tengely típusát. Olvasható [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Visszaadja a szülő diagramot. Csak olvasható [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Képviseli azt a pontot a tengelyen, ahol a merőleges tengely kereszteződik vele. Olvasható **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Képviseli a CrossType-ot a megadott tengelyen, ahol a másik tengely kereszteződik. Olvasható [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Megadja az értéktengely megjelenítési egységeinek skálázási értékét. Olvasható [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Képviseli a tengely formátumát. Csak olvasható [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Meghatározza, hogy a tengelynek van-e látható címe. Olvasható **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Jelzi, hogy a tengely főegysége automatikusan van-e hozzárendelve. Olvasható **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Jelzi, hogy a legnagyobb érték automatikusan van-e hozzárendelve. Olvasható **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Jelzi, hogy a tengely alegysége automatikusan van-e hozzárendelve. Olvasható **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Jelzi, hogy a legkisebb érték automatikusan van-e hozzárendelve. Olvasható **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Megadja az automatikus overflow bin értékét. Ha hamis, használd az OverflowBin tulajdonságot. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Megadja az automatikus jelölőcímke távolságértéket. Ha hamis, használd a TickLabelSpacing tulajdonságot. Olvasható **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Megadja az automatikus jelölővonalak távolságértékét. Ha hamis, használd a TickMarksSpacing tulajdonságot. Olvasható **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Megadja az automatikus underflow bin értékét. Ha hamis, használd az UnderflowBin tulajdonságot. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Képviseli, hogy az értéktengely skálatípusa logaritmikus-e vagy sem. Olvasható **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Jelzi, hogy a formátum összekapcsolt forrásadat-e. Olvasható **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Megadja, hogy az overflow bin alkalmazva van-e. Használd az IsAutomaticOverflowBin és az OverflowBin értékeket az overflow bin módosításához. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | Képviseli, hogy a MS PowerPoint az adatpontokat utolsótól az elsőig ábrázolja-e. Olvasható **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Megadja, hogy az underflow bin alkalmazva van-e. Használd az IsAutomaticUnderflowBin és az UnderflowBin értékeket az underflow bin módosításához. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Képviseli, hogy a tengely látható-e. Olvasható **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Megadja a címkék távolságát a tengelytől. Kategória vagy dátum tengelyen alkalmazott. Az értéknek 0% és 1000% között kell lennie. Olvasható **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Képviseli a logaritmikus alapot. Alapértelmezett érték 10. Olvasható **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Képviseli a fő rácsvonalak formátumát egy diagram tengelyén. Csak olvasható [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Képviseli a megadott tengely fő jelölővonalának típusát. Olvasható [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Képviseli a fő egységeket a dátum vagy értéktengelyen. Olvasható **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Képviseli a fő egység skáláját a dátum tengelyen. Olvasható [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Képviseli a legnagyobb értéket az értéktengelyen. Olvasható **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Képviseli a kisebb rácsvonalak formátumát egy diagram tengelyén. Csak olvasható [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Képviseli a megadott tengely kisebb jelölővonalának típusát. Olvasható [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Képviseli a kisebb egységeket a dátum vagy értéktengelyen. Olvasható **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Képviseli a fő egység skáláját a dátum tengelyen. Olvasható [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Képviseli a legkisebb értéket az értéktengelyen. Olvasható **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Képviseli a formátum stringet a [Axis](./) címkékhez. Olvasható [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | Megadja a bin-ek számát, amikor az AggregationType tulajdonság értéke [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/)-ra van állítva. Kategória tengelyeken alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Megadja az overflow bin egyéni értékét. Alkalmazott, amikor az IsAutomaticOverflowBin hamisra van állítva és az IsOverflowBin igaz. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Képviseli a tengely pozícióját. Olvasható [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | A fő rácsvonal elrejtéséhez állítsd a [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() értékét [FillType::NoFill](../../aspose.slides/filltype/)-ra. Csak olvasható **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | A kisebb rácsvonal elrejtéséhez állítsd a [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() értékét [FillType::NoFill](../../aspose.slides/filltype/)-ra. Csak olvasható **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Képviseli a szöveg formátumát. Csak olvasható [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Képviseli a jelölőcímke pozícióját a megadott tengelyen. Olvasható [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Képviseli a jelölőcímkék forgatási szögét. Olvasható **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Megadja, hány jelölőcímkét kell kihagyni a megjelenített címke között. Kategória vagy sorozat tengelyen alkalmazott. Olvasható **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Megadja, hány jelölővonalat kell kihagyni a következő megjelenítése előtt. Kategória vagy sorozat tengelyen alkalmazott. Olvasható **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Lekéri a tengely címét. Csak olvasható [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Megadja az underflow bin egyéni értékét. Alkalmazott, amikor az IsAutomaticUnderflowBin hamisra van állítva és az IsUnderflowBin igaz. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektummal kapcsolódó referenciacs számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típusú példány-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Implementálja a C# lock() utasítást zároláshoz. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciák számát a megadott értékkel. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Képviseli a kategória tengely aggregációs típusát (binning). Kategóriára alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Képviseli, hogy az értéktengely áthalad-e a kategória tengelyen a kategóriák között. Ez a tulajdonság csak kategória tengelyekre vonatkozik, és nem alkalmazható 3D diagramokra. Írd **bool**-ként. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Megadja a legkisebb időegységet, amely a dátum tengelyen megjelenik. Írd [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | Megadja a bin szélességét, amikor az AggregationType tulajdonság értéke [AxisAggregationType::ByBinWidth](../axisaggregationtype/)-ra van állítva. Kategória tengelyeken alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Megadja a kategória tengely típusát. Írd [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Képviseli azt a pontot a tengelyen, ahol a merőleges tengely kereszteződik. Írd **float**-ként. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Képviseli a CrossType-ot a megadott tengelyen, ahol a másik tengely kereszteződik. Írd [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Megadja az értéktengely megjelenítési egységeinek skálázási értékét. Írd [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Meghatározza, hogy a tengelynek van-e látható címe. Írd **bool**-ként. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Jelzi, hogy a tengely főegysége automatikusan van-e hozzárendelve. Írd **bool**-ként. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Jelzi, hogy a legnagyobb érték automatikusan van-e hozzárendelve. Írd **bool**-ként. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Jelzi, hogy a tengely alegysége automatikusan van-e hozzárendelve. Írd **bool**-ként. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Jelzi, hogy a legkisebb érték automatikusan van-e hozzárendelve. Írd **bool**-ként. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Megadja az automatikus overflow bin értékét. Ha hamis, használd az OverflowBin tulajdonságot. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Megadja az automatikus jelölőcímke távolságértékét. Ha hamis, használd a TickLabelSpacing tulajdonságot. Írd **bool**-ként. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Megadja az automatikus jelölővonalak távolságértékét. Ha hamis, használd a TickMarksSpacing tulajdonságot. Írd **bool**-ként. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Megadja az automatikus underflow bin értékét. Ha hamis, használd az UnderflowBin tulajdonságot. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Képviseli, hogy az értéktengely skálatípusa logaritmikus-e vagy sem. Írd **bool**-ként. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Jelzi, hogy a formátum összekapcsolt forrásadat-e. Írd **bool**-ként. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Megadja, hogy az overflow bin alkalmazva van-e. Használd az IsAutomaticOverflowBin és az OverflowBin értékét az overflow bin módosításához. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | Képviseli, hogy a MS PowerPoint az adatpontokat utolsótól az elsőig ábrázolja-e. Írd **bool**-ként. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Megadja, hogy az underflow bin alkalmazva van-e. Használd az IsAutomaticUnderflowBin és az UnderflowBin értékét az underflow bin módosításához. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Képviseli, hogy a tengely látható-e. Írd **bool**-ként. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Megadja a címkék távolságát a tengelytől. Kategória vagy dátum tengelyen alkalmazott. Az érték 0% és 1000% között kell legyen. Írd **uint16_t**-ként. |
| void [set_LogBase](./set_logbase/)(**double**) override | Képviseli a logaritmikus alapot. Alapértelmezett érték 10. Írd **double**-ként. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Képviseli a megadott tengely fő jelölővonalának típusát. Írd [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Képviseli a fő egységeket a dátum vagy értéktengelyen. Írd **double**-ként. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Képviseli a fő egység skáláját a dátum tengelyen. Írd [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Képviseli a legnagyobb értéket az értéktengelyen. Írd **double**-ként. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Képviseli a megadott tengely kisebb jelölővonalának típusát. Írd [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Képviseli a kisebb egységeket a dátum vagy értéktengelyen. Írd **double**-ként. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Képviseli a fő egység skáláját a dátum tengelyen. Írd [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Képviseli a legkisebb értéket az értéktengelyen. Írd **double**-ként. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Képviseli a formátum stringet a [Axis](./) címkékhez. Írd [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | Megadja a bin-ek számát, amikor az AggregationType tulajdonság értéke [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/)-ra van állítva. Kategória tengelyeken alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Megadja az overflow bin egyéni értékét. Alkalmazott, amikor az IsAutomaticOverflowBin hamisra van állítva és az IsOverflowBin igaz. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Képviseli a tengely pozícióját. Írd [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Képviseli a jelölőcímke pozícióját a megadott tengelyen. Írd [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Képviseli a jelölőcímkék forgatási szögét. Írd **float**-ként. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Megadja, hány jelölőcímkét kell kihagyni a megjelenített címke között. Kategória vagy sorozat tengelyen alkalmazott. Írd **uint32_t**-ként. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Megadja, hány jelölővonalat kell kihagyni a következő megjelenítése előtt. Kategória vagy sorozat tengelyen alkalmazott. Írd **uint16_t**-ként. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Megadja az underflow bin egyéni értékét. Alkalmazott, amikor az IsAutomaticUnderflowBin hamisra van állítva és az IsUnderflowBin igaz. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | Beállítja az IAxis::get(set)_CategoryAxisType tulajdonságot egy értékkel, amely automatikusan a tengely adatai alapján kerül meghatározásra. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Beállítja a n-edik sablon argumentumot gyenge pointerként (nem megosztottként). Lehetővé teszi a pointerek átkapcsolását a gyenge módra a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciacs számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciacs számlálót. Nem szabad közvetlenül hívni; helyette használj okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciacs számlálót. Nem szabad közvetlenül hívni; helyette használj okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementálja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Implementálja a C# lock() utasítás feloldását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciacs számlálót. Nem szabad közvetlenül hívni; helyette használj okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciacs számlálót. Nem szabad közvetlenül hívni; helyette használj okos pointereket vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [DomObject](../../aspose.slides/domobject/)
* Osztály [IAxis](../iaxis/)
* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)