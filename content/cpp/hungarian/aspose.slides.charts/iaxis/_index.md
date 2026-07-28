---
title: IAxis
second_title: Aspose.Slides C++ API referencia
description: Lefoglalja azt az objektumot, amely egy diagram tengelyét ábrázolja.
type: docs
weight: 534
url: /hu/aspose.slides.charts/iaxis/
---
## IAxis osztály

Lekapszolja azt az objektumot, amely egy diagram tengelyét ábrázolja.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Megadja a tengely tényleges fő egységét. Előtte hívd meg a(z) [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a tényleges érték lekéréséhez. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Megadja a tengely tényleges fő egység skáláját. Előtte hívd meg a(z) [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a tényleges érték lekéréséhez. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Megadja a tengely tényleges maximális értékét. Előtte hívd meg a(z) [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a tényleges érték lekéréséhez. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Megadja a tengely tényleges alsegységét. Előtte hívd meg a(z) [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a tényleges érték lekéréséhez. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Megadja a tengely tényleges alsegység skáláját. Előtte hívd meg a(z) [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a tényleges érték lekéréséhez. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Megadja a tengely tényleges minimális értékét. Előtte hívd meg a(z) [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a tényleges érték lekéréséhez. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Jeleníti a kategória tengely összegző típusát (binning). Kategóriára alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Jelzi, hogy az értéktengely áthalad-e a kategória tengelyen a kategóriák között. Ez a tulajdonság csak kategória tengelyekre vonatkozik, és nem érvényes 3-D diagramokra. Olvasható **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Megadja a legkisebb időegységet, amely a dátumtengelyen megjelenik. Olvasd [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | Megadja a bin szélességét, amikor az AggregationType tulajdonság értéke [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Kategória tengelyekre alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Megadja a kategória tengely típusát. Olvasd [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Visszaadja a diagramot. Írásvédett [IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | Jelzi a pontot a tengelyen, ahol a merőleges tengely áthalad rajta. Olvasd **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Jelzi a CrossType-ot a megadott tengelyen, ahol a másik tengely áthalad. Olvasd [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Megadja a megjelenítési egységek skálázási értékét az értéktengelyen. Olvasd [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Jeleníti a tengely formátumát. Írásvédett [IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Meghatározza, hogy a tengelynek van-e látható címe. Olvasd **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Jelzi, hogy a tengely fő egysége automatikusan van-e hozzárendelve. Olvasd **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Jelzi, hogy a maximális érték automatikusan van-e hozzárendelve. Olvasd **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Jelzi, hogy a tengely alsegysége automatikusan van-e hozzárendelve. Olvasd **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Jelzi, hogy a minimális érték automatikusan van-e hozzárendelve. Olvasd **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Megadja az automatikus overflow bin értéket. Ha hamis: használd az OverflowBin tulajdonságot. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Megadja az automatikus jelölőcímke távolság értékét. Ha hamis: használd a TickLabelSpacing tulajdonságot. Olvasd **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Megadja az automatikus jelölővonalak távolság értékét. Ha hamis: használd a TickMarksSpacing tulajdonságot. Olvasd **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Megadja az automatikus underflow bin értéket. Ha hamis: használd az UnderflowBin tulajdonságot. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Jelzi, hogy az értéktengely skála típusa logaritmikus-e vagy sem. Olvasd **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Jelzi, hogy a formátum összekapcsolt forrásadat-e. Olvasd **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Megadja, hogy az overflow bin alkalmazva van-e. Használd az IsAutomaticOverflowBin és az OverflowBin értékeket az overflow bin módosításához. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | Jelzi, hogy a MS PowerPoint a pontokat az utolsótól az elsőig rajzolja-e. Olvasd **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Megadja, hogy az underflow bin alkalmazva van-e. Használd az IsAutomaticUnderflowBin és az UnderflowBin értékeket az underflow bin módosításához. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Jelzi, hogy a tengely látható-e. Olvasd **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Megadja a címkék távolságát a tengelytől. Kategória vagy dátumtengelyre alkalmazott. Az értéknek 0% és 1000% között kell lennie. Olvasd **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | JELZI a logaritmikus alapot. Alapértelmezett érték 10. Olvasd **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | JELZI a fő rácsvonalak formátumát egy diagram tengelyen. Írásvédett [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | JELZI a fő jelölővonal típusát a megadott tengelyen. Olvasd [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | JELZI a fő egységeket a dátum vagy értéktengelyen. Olvasd **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | JELZI a fő egység skáláját a dátumtengelyen. Olvasd [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | JELZI a maximális értéket az értéktengelyen. Olvasd **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | JELZI a kisebb rácsvonalak formátumát egy diagram tengelyen. Írásvédett [IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | JELZI a kisebb jelölővonal típusát a megadott tengelyen. Olvasd [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | JELZI a kisebb egységeket a dátum vagy értéktengelyen. Olvasd **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | JELZI a fő egység skáláját a dátumtengelyen. Olvasd [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | JELZI a minimális értéket az értéktengelyen. Olvasd **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | JELZI a [Axis](../axis/) címkék formátum karakterláncát. Olvasd [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | Megadja a bin-ek számát, amikor az AggregationType tulajdonság értéke [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Kategória tengelyekre alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Megadja az overflow bin egyéni értékét. Akkor alkalmazott, ha az IsAutomaticOverflowBin tulajdonság false és az IsOverflowBin true. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | JELZI a tengely pozícióját. Olvasd [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Visszaadja a prezentációt. Írásvédett [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | JELZI, hogy a fő rácsvonalak megjelennek-e. Írásvédett **bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | JELZI, hogy a kisebb rácsvonalak megjelennek-e. Írásvédett **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Visszaadja az alapdiát. Írásvédett [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Visszaadja a diagram szövegformátumát. Írásvédett [IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | JELZI a jelölőcímkék pozícióját a megadott tengelyen. Olvasd [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | JELZI a jelölőcímkék forgásszögét. Olvasd **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Megadja, hány jelölőcímkét kell kihagyni a megjelenő címke között. Olvasd **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Megadja, hány jelölővonalat kell kihagyni a következő megjelenése előtt. Kategória vagy sorozat tengelyre alkalmazott. Olvasd **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Lekéri a tengely címét. Írásvédett [IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Megadja az underflow bin egyéni értékét. Akkor alkalmazott, ha az IsAutomaticUnderflowBin false és az IsUnderflowBin true. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri a objektummal kapcsolatos referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívd közvetlenül vagy használd a(z) [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolását. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolását. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Érték típusú objektumot hasonlít össze nullptr-tal referenciaként. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Jeleníti a kategória tengely összegző típusát (binning). Kategóriára alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Jelzi, hogy az értéktengely áthalad-e a kategória tengelyen a kategóriák között. Ez a tulajdonság csak kategória tengelyekre vonatkozik, és nem érvényes 3-D diagramokra. Írj **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Megadja a legkisebb időegységet, amely a dátumtengelyen megjelenik. Írj [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | Megadja a bin szélességét, amikor az AggregationType tulajdonság értéke [AxisAggregationType::ByBinWidth](../axisaggregationtype/). Kategória tengelyekre alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Megadja a kategória tengely típusát. Írj [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Jelzi a pontot a tengelyen, ahol a merőleges tengely áthalad rajta. Írj **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Jelzi a CrossType-ot a megadott tengelyen, ahol a másik tengely áthalad. Írj [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Megadja a megjelenítési egységek skálázási értékét az értéktengelyen. Írj [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Meghatározza, hogy a tengelynek van-e látható címe. Írj **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Jelzi, hogy a tengely fő egysége automatikusan van-e hozzárendelve. Írj **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Jelzi, hogy a maximális érték automatikusan van-e hozzárendelve. Írj **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Jelzi, hogy a tengely alsegysége automatikusan van-e hozzárendelve. Írj **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Jelzi, hogy a minimális érték automatikusan van-e hozzárendelve. Írj **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Megadja az automatikus overflow bin értéket. Ha hamis: használd az OverflowBin tulajdonságot. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Megadja az automatikus jelölőcímke távolság értékét. Ha hamis: használd a TickLabelSpacing tulajdonságot. Írj **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Megadja az automatikus jelölővonalak távolság értékét. Ha hamis: használd a TickMarksSpacing tulajdonságot. Írj **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Megadja az automatikus underflow bin értéket. Ha hamis: használd az UnderflowBin tulajdonságot. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Jelzi, hogy az értéktengely skála típusa logaritmikus-e vagy sem. Írj **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Jelzi, hogy a formátum összekapcsolt forrásadat-e. Írj **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Megadja, hogy az overflow bin alkalmazva van-e. Használd az IsAutomaticOverflowBin és az OverflowBin értékeket az overflow bin módosításához. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | Jelzi, hogy a MS PowerPoint a pontokat az utolsótól az elsőig rajzolja-e. Írj **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Megadja, hogy az underflow bin alkalmazva van-e. Használd az IsAutomaticUnderflowBin és az UnderflowBin értékeket az underflow bin módosításához. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Jelzi, hogy a tengely látható-e. Írj **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Megadja a címkék távolságát a tengelytől. Kategória vagy dátumtengelyre alkalmazott. Az értéknek 0% és 1000% között kell lennie. Írj **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Megadja a logaritmikus alapot. Alapértelmezett érték 10. Írj **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Jelzi a fő jelölővonal típusát a megadott tengelyen. Írj [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Jelzi a fő egységeket a dátum vagy értéktengelyen. Írj **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Jelzi a fő egység skáláját a dátumtengelyen. Írj [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Jelzi a maximális értéket az értéktengelyen. Írj **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Jelzi a kisebb jelölővonal típusát a megadott tengelyen. Írj [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Jelzi a kisebb egységeket a dátum vagy értéktengelyen. Írj **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Jelzi a fő egység skáláját a dátumtengelyen. Írj [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Jelzi a minimális értéket az értéktengelyen. Írj **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Jelzi a [Axis](../axis/) címkék formátum karakterláncát. Írj [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | Megadja a bin-ek számát, amikor az AggregationType tulajdonság értéke [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/). Kategória tengelyekre alkalmazott. Csak Histogram vagy HistogramPareto sorozatokkal használható. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Megadja az overflow bin egyéni értékét. Akkor alkalmazott, ha az IsAutomaticOverflowBin tulajdonság false és az IsOverflowBin true. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Jelzi a tengely pozícióját. Írj [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Jelzi a jelölőcímkék pozícióját a megadott tengelyen. Írj [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Jelzi a jelölőcímkék forgásszögét. Írj **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Megadja, hány jelölőcímkét kell kihagyni a megjelenő címke között. Írj **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Megadja, hány jelölővonalat kell kihagyni a következő megjelenése előtt. Kategória vagy sorozat tengelyre alkalmazott. Írj **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Megadja az underflow bin egyéni értékét. Akkor alkalmazott, ha az IsAutomaticUnderflowBin false és az IsUnderflowBin true. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | Beállítja az IAxis::get(set)_CategoryAxisType tulajdonságot egy olyan értékkel, amely a tengely adatok alapján automatikusan kerül meghatározásra. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóként (a shared helyett) állítja be. Lehetővé teszi a mutatók konténerekben weak módra való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívd közvetlenül vagy használd a(z) [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Kapcsolódó

* Osztály [IFormattedTextContainer](../iformattedtextcontainer/)
* Névtere [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)