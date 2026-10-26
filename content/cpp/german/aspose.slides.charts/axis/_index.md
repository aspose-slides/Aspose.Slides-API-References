---
title: Axis
second_title: Aspose.Slides für C++ API-Referenz
description: Kapselt das Objekt, das die Achse eines Diagramms darstellt.
type: docs
weight: 14
url: /de/aspose.slides.charts/axis/
---
## Axis Klasse

Encapsulates the object that represents a chart's axis.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaN-Werte als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaN-Werte als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | Gibt die tatsächliche Haupteinheit der Achse an. Rufen Sie zuvor die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um den tatsächlichen Wert zu erhalten. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | Gibt die tatsächliche Skalierung der Haupteinheit der Achse an. Rufen Sie zuvor die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um den tatsächlichen Wert zu erhalten. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | Gibt den tatsächlichen Maximalwert der Achse an. Rufen Sie zuvor die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um den tatsächlichen Wert zu erhalten. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | Gibt die tatsächliche Nebeneinheit der Achse an. Rufen Sie zuvor die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um den tatsächlichen Wert zu erhalten. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | Gibt die tatsächliche Skalierung der Nebeneinheit der Achse an. Rufen Sie zuvor die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um den tatsächlichen Wert zu erhalten. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | Gibt den tatsächlichen Minimalwert der Achse an. Rufen Sie zuvor die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um den tatsächlichen Wert zu erhalten. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | Stellt den Aggregationstyp der Kategorienachse (Binning) dar. Auf Kategorien angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | Gibt an, ob die Werteachse die Kategorienachse zwischen den Kategorien kreuzt. Diese Eigenschaft gilt nur für Kategorienachsen und nicht für 3-D-Diagramme. Lesen **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lesen [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | Gibt die Bin-Breite an, wenn der Eigenschaftswert AggregationType auf [AxisAggregationType::ByBinWidth](../axisaggregationtype/) gesetzt ist. Auf Kategorienachsen angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | Gibt den Typ der Kategorienachse an. Lesen [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Gibt das übergeordnete Diagramm zurück. Nur lesbar [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie kreuzt. Lesen **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | Gibt den CrossType auf der angegebenen Achse an, an dem die andere Achse kreuzt. Lesen [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. Lesen [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | Stellt das Format der Achse dar. Nur lesbar [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lesen **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. Lesen **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | Gibt an, ob der Maximalwert automatisch zugewiesen wird. Lesen **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. Lesen **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | Gibt an, ob der Minimalwert automatisch zugewiesen wird. Lesen **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | Gibt den automatischen Overflow-Bin-Wert an. Wenn false: verwenden Sie die Eigenschaft OverflowBin. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | Gibt den automatischen Abstand der Tick-Label an. Wenn false: verwenden Sie die Eigenschaft TickLabelSpacing. Lesen **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | Gibt den automatischen Abstand der Tick-Markierungen an. Wenn false: verwenden Sie die Eigenschaft TickMarksSpacing. Lesen **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | Gibt den automatischen Underflow-Bin-Wert an. Wenn false: verwenden Sie die Eigenschaft UnderflowBin. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | Gibt an, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. Lesen **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Gibt an, ob das Format mit Quelldaten verknüpft ist. Lesen **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | Gibt an, ob ein Overflow-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Overflow-Bin-Wert anzupassen. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | Gibt an, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst darstellt. Lesen **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | Gibt an, ob ein Underflow-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Underflow-Bin-Wert anzupassen. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Gibt an, ob die Achse sichtbar ist. Lesen **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | Gibt den Abstand der Beschriftungen von der Achse an. Auf Kategorien- oder Datumsachsen angewendet. Der Wert muss zwischen 0 % und 1000 % liegen. Lesen **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | Gibt die logarithmische Basis an. Standardwert ist 10. Lesen **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | Stellt das Format der Hauptgitterlinien auf einer Diagrammachse dar. Nur lesbar [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | Gibt den Typ der Haupt-Tick-Markierung für die angegebene Achse an. Lesen [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | Gibt die Haupteinheiten für die Datums- oder Werteachse an. Lesen **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | Gibt die Skalierung der Haupteinheit für die Datumsachse an. Lesen [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | Gibt den Maximalwert auf der Werteachse an. Lesen **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | Stellt das Format der Nebengitterlinien auf einer Diagrammachse dar. Nur lesbar [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | Gibt den Typ der Neben-Tick-Markierung für die angegebene Achse an. Lesen [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | Gibt die Nebeneinheiten für die Datums- oder Werteachse an. Lesen **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | Gibt die Skalierung der Haupteinheit für die Datumsachse an. Lesen [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | Gibt den Minimalwert auf der Werteachse an. Lesen **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Gibt die Formatzeichenfolge für die [Axis](./)-Beschriftungen an. Lesen [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | Gibt die Anzahl der Bins an, wenn der Eigenschaftswert AggregationType auf [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) gesetzt ist. Auf Kategorienachsen angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | Gibt den benutzerdefinierten Wert des Overflow-Bins an. Wird angewendet, wenn die Eigenschaft IsAutomaticOverflowBin auf false gesetzt ist und IsOverflowBin true ist. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | Gibt die Position der Achse an. Lesen [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | Um die Hauptgitterlinie auszublenden, setzen Sie [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() auf [FillType::NoFill](../../aspose.slides/filltype/). Nur lesbar **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | Um die Nebengitterlinie auszublenden, setzen Sie [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() auf [FillType::NoFill](../../aspose.slides/filltype/). Nur lesbar **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Stellt das Textformat dar. Nur lesbar [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | Gibt die Position der Tick-Label auf der angegebenen Achse an. Lesen [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | Gibt den Rotationswinkel der Tick-Label an. Lesen **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | Gibt an, wie viele Tick-Labels zwischen den zu zeichnenden Labels übersprungen werden sollen. Auf Kategorien- oder Serienachsen angewendet. Lesen **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | Gibt an, wie viele Tick-Markierungen übersprungen werden sollen, bevor die nächste gezeichnet wird. Auf Kategorien- oder Serienachsen angewendet. Lesen **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | Liefert den Titel der Achse. Nur lesbar [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | Gibt den benutzerdefinierten Wert des Underflow-Bins an. Wird angewendet, wenn die Eigenschaft IsAutomaticUnderflowBin auf false gesetzt ist und IsUnderflowBin true ist. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die mit dem Objekt verbundene Referenzzähler-Datenstruktur. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts wirklich, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopier-Konstruktion von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts wirklich, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopier-Konstruktion von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsam genutzte Referenzzählung um den angegebenen Wert. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | Stellt den Aggregationstyp der Kategorienachse (Binning) dar. Auf Kategorien angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | Gibt an, ob die Werteachse die Kategorienachse zwischen den Kategorien kreuzt. Diese Eigenschaft gilt nur für Kategorienachsen und nicht für 3-D-Diagramme. Schreiben **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Schreiben [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | Gibt die Bin-Breite an, wenn der Eigenschaftswert AggregationType auf [AxisAggregationType::ByBinWidth](../axisaggregationtype/) gesetzt ist. Auf Kategorienachsen angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | Gibt den Typ der Kategorienachse an. Schreiben [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie kreuzt. Schreiben **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | Gibt den CrossType auf der angegebenen Achse an, an dem die andere Achse kreuzt. Schreiben [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. Schreiben [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | Bestimmt, ob eine Achse einen sichtbaren Titel hat. Schreiben **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. Schreiben **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | Gibt an, ob der Maximalwert automatisch zugewiesen wird. Schreiben **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. Schreiben **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | Gibt an, ob der Minimalwert automatisch zugewiesen wird. Schreiben **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | Gibt den automatischen Overflow-Bin-Wert an. Wenn false: verwenden Sie die Eigenschaft OverflowBin. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | Gibt den automatischen Abstand der Tick-Label an. Wenn false: verwenden Sie die Eigenschaft TickLabelSpacing. Schreiben **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | Gibt den automatischen Abstand der Tick-Markierungen an. Wenn false: verwenden Sie die Eigenschaft TickMarksSpacing. Schreiben **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | Gibt den automatischen Underflow-Bin-Wert an. Wenn false: verwenden Sie die Eigenschaft UnderflowBin. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | Gibt an, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. Schreiben **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Gibt an, ob das Format mit Quelldaten verknüpft ist. Schreiben **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | Gibt an, ob ein Overflow-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Overflow-Bin-Wert anzupassen. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | Gibt an, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst darstellt. Schreiben **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | Gibt an, ob ein Underflow-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Underflow-Bin-Wert anzupassen. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Gibt an, ob die Achse sichtbar ist. Schreiben **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | Gibt den Abstand der Beschriftungen von der Achse an. Auf Kategorien- oder Datumsachsen angewendet. Der Wert muss zwischen 0 % und 1000 % liegen. Schreiben **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | Gibt die logarithmische Basis an. Standardwert ist 10. Schreiben **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | Gibt den Typ der Haupt-Tick-Markierung für die angegebene Achse an. Schreiben [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | Gibt die Haupteinheiten für die Datums- oder Werteachse an. Schreiben **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | Gibt die Skalierung der Haupteinheit für die Datumsachse an. Schreiben [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | Gibt den Maximalwert auf der Werteachse an. Schreiben **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | Gibt den Typ der Neben-Tick-Markierung für die angegebene Achse an. Schreiben [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | Gibt die Nebeneinheiten für die Datums- oder Werteachse an. Schreiben **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | Gibt die Skalierung der Haupteinheit für die Datumsachse an. Schreiben [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | Gibt den Minimalwert auf der Werteachse an. Schreiben **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Gibt die Formatzeichenfolge für die [Axis](./)-Beschriftungen an. Schreiben [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | Gibt die Anzahl der Bins an, wenn der Eigenschaftswert AggregationType auf [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) gesetzt ist. Auf Kategorienachsen angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | Gibt den benutzerdefinierten Wert des Overflow-Bins an. Wird angewendet, wenn die Eigenschaft IsAutomaticOverflowBin auf false gesetzt ist und IsOverflowBin true ist. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | Gibt die Position der Achse an. Schreiben [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | Gibt die Position der Tick-Label auf der angegebenen Achse an. Schreiben [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | Gibt den Rotationswinkel der Tick-Label an. Schreiben **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | Gibt an, wie viele Tick-Labels zwischen den zu zeichnenden Labels übersprungen werden sollen. Auf Kategorien- oder Serienachsen angewendet. Schreiben **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | Gibt an, wie viele Tick-Markierungen übersprungen werden sollen, bevor die nächste gezeichnet wird. Auf Kategorien- oder Serienachsen angewendet. Schreiben **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | Gibt den benutzerdefinierten Wert des Underflow-Bins an. Wird angewendet, wenn die Eigenschaft IsAutomaticUnderflowBin auf false gesetzt ist und IsUnderflowBin true ist. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | Setzt die Eigenschaft IAxis::get(set)_CategoryAxisType auf einen Wert, der automatisch anhand der Achsendaten bestimmt wird. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Setzt das n-te Template-Argument auf einen weak-Pointer (statt shared). Erlaubt das Umschalten von Zeigern in Containern in den weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert der gemeinsam genutzten Referenzzählung. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsam genutzte Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert die gemeinsam genutzte Referenzzählung und gibt sie zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [DomObject](../../aspose.slides/domobject/)
* Klasse [IAxis](../iaxis/)
* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)