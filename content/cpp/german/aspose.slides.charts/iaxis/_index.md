---
title: IAxis
second_title: Aspose.Slides für C++ API-Referenz
description: Kapselt das Objekt, das die Achse eines Diagramms darstellt.
type: docs
weight: 534
url: /de/aspose.slides.charts/iaxis/
---
## IAxis Klasse

Kapselt das Objekt, das die Achse eines Diagramms darstellt.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand von C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-ähnlichen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN mit keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-ähnlichen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN mit keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | Gibt die tatsächliche Hauptskalaeinheit der Achse an. Rufen Sie zuvor die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um den tatsächlichen Wert zu erhalten. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | Gibt den tatsächlichen Hauptskalenfaktor der Achse an. Rufen Sie zuvor die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um den tatsächlichen Wert zu erhalten. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | Gibt den tatsächlichen Maximalwert auf der Achse an. Rufen Sie zuvor die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um den tatsächlichen Wert zu erhalten. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | Gibt die tatsächliche Nebenheitseinheit der Achse an. Rufen Sie zuvor die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um den tatsächlichen Wert zu erhalten. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | Gibt den tatsächlichen Nebenheitenfaktor der Achse an. Rufen Sie zuvor die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um den tatsächlichen Wert zu erhalten. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | Gibt den tatsächlichen Minimalwert auf der Achse an. Rufen Sie zuvor die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um den tatsächlichen Wert zu erhalten. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | Gibt den Aggregationstyp der Kategorienachse (Binning) an. Auf Kategorien angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | Gibt an, ob die Wertachse die Kategorienachse zwischen den Kategorien kreuzt. Diese Eigenschaft gilt nur für Kategorienachsen und nicht für 3-D-Diagramme. Lesen **bool**. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lesen [TimeUnitType](../timeunittype/). |
| virtual **double** [get_BinWidth](./get_binwidth/)() | Gibt die Bin-Breite an, wenn die Eigenschaft AggregationType auf [AxisAggregationType::ByBinWidth](../axisaggregationtype/) gesetzt ist. Auf Kategorienachsen angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | Gibt den Typ der Kategorienachse an. Lesen [CategoryAxisType](../categoryaxistype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Gibt das Diagramm zurück. Nur-Lese-[IChart](../ichart/). |
| virtual **float** [get_CrossAt](./get_crossat/)() | Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie kreuzt. Lesen **float**. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | Gibt den CrossType auf der angegebenen Achse an, an dem die andere Achse kreuzt. Lesen [CrossesType](../crossestype/). |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | Gibt den Skalierungswert der Anzeigeeinheiten für die Wertachse an. Lesen [DisplayUnitType](../displayunittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | Gibt das Achsenformat an. Nur-Lese-[IAxisFormat](../iaxisformat/). |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | Bestimmt, ob die Achse einen sichtbaren Titel hat. Lesen **bool**. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. Lesen **bool**. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | Gibt an, ob der Maximalwert automatisch zugewiesen wird. Lesen **bool**. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | Gibt an, ob die Nebenheitseinheit der Achse automatisch zugewiesen wird. Lesen **bool**. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | Gibt an, ob der Minimalwert automatisch zugewiesen wird. Lesen **bool**. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | Gibt den automatischen Überlauf-Bin-Wert an. Wenn **false**: verwenden Sie die Eigenschaft OverflowBin. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | Gibt den automatischen Abstand der Tick-Beschriftungen an. Wenn **false**: verwenden Sie die Eigenschaft TickLabelSpacing. Lesen **bool**. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | Gibt den automatischen Abstand der Tick-Markierungen an. Wenn **false**: verwenden Sie die Eigenschaft TickMarksSpacing. Lesen **bool**. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | Gibt den automatischen Unterlauf-Bin-Wert an. Wenn **false**: verwenden Sie die Eigenschaft UnderflowBin. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | Gibt an, ob der Skalierungstyp der Wertachse logarithmisch ist. Lesen **bool**. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Gibt an, ob das Format mit Quelldaten verknüpft ist. Lesen **bool**. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | Gibt an, ob ein Überlauf-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Überlauf-Bin-Wert anzupassen. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | Gibt an, ob MS PowerPoint Datenpunkte von letzter zu erster zeichnet. Lesen **bool**. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | Gibt an, ob ein Unterlauf-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Unterlauf-Bin-Wert anzupassen. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Gibt an, ob die Achse sichtbar ist. Lesen **bool**. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | Gibt den Abstand der Beschriftungen von der Achse an. Auf Kategorien- oder Datumsachse angewendet. Der Wert muss zwischen 0 % und 1000 % liegen. Lesen **uint16_t**. |
| virtual **double** [get_LogBase](./get_logbase/)() | Gibt die logarithmische Basis an. Der Standardwert ist 10. Lesen **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | Gibt das Format der Hauptgitternetzlinien einer Diagrammachse an. Nur-Lese-[IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | Gibt den Typ der Haupt-Tick-Markierung für die angegebene Achse an. Lesen [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | Gibt die Haupteinheiten für die Datums- oder Wertachse an. Lesen **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | Gibt den Skalierungsfaktor der Haupteinheit für die Datumsachse an. Lesen [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | Gibt den Maximalwert auf der Wertachse an. Lesen **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | Gibt das Format der Nebengitternetzlinien einer Diagrammachse an. Nur-Lese-[IChartLinesFormat](../ichartlinesformat/). |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | Gibt den Typ der Neben-Tick-Markierung für die angegebene Achse an. Lesen [TickMarkType](../tickmarktype/). |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | Gibt die Neben-Einheiten für die Datums- oder Wertachse an. Lesen **double**. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | Gibt den Skalierungsfaktor der Haupteinheit für die Datumsachse an. Lesen [TimeUnitType](../timeunittype/). |
| virtual **double** [get_MinValue](./get_minvalue/)() | Gibt den Minimalwert auf der Wertachse an. Lesen **double**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Gibt den Formatstring für die [Axis](../axis/)-Beschriftungen an. Lesen [System::String](../../system/string/). |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | Gibt die Anzahl der Bins an, wenn die Eigenschaft AggregationType auf [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) gesetzt ist. Auf Kategorienachsen angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | Gibt den benutzerdefinierten Wert des Überlauf-Bins an. Wird angewendet, wenn die Eigenschaft IsAutomaticOverflowBin auf **false** gesetzt ist und IsOverflowBin **true** ist. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | Gibt die Position der Achse an. Lesen [AxisPositionType](../axispositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Gibt die Präsentation zurück. Nur-Lese-[IPresentation](../../aspose.slides/ipresentation/). |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | Gibt an, ob die Haupt-Gitternetzlinien angezeigt werden. Nur-Lese-**bool**. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | Gibt an, ob die Neben-Gitternetzlinien angezeigt werden. Nur-Lese-**bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Gibt die Basisslide zurück. Nur-Lese-[IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Gibt das Diagramm-Textformat zurück. Nur-Lese-[IChartTextFormat](../icharttextformat/). |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | Gibt die Position der Tick-Markierungs-Beschriftungen auf der angegebenen Achse an. Lesen [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | Gibt den Rotationswinkel der Tick-Beschriftungen an. Lesen **float**. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | Gibt an, wie viele Tick-Beschriftungen zwischen zwei dargestellten Beschriftungen übersprungen werden sollen. Lesen **uint32_t**. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | Gibt an, wie viele Tick-Markierungen übersprungen werden sollen, bevor die nächste gezeichnet wird. Auf Kategorien- oder Serienachse angewendet. Lesen **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | Gibt den Titel der Achse zurück. Nur-Lese-[IChartTitle](../icharttitle/). |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | Gibt den benutzerdefinierten Wert des Unterlauf-Bins an. Wird angewendet, wenn die Eigenschaft IsAutomaticUnderflowBin auf **false** gesetzt ist und IsUnderflowBin **true** ist. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analogie zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs ist. Analogie zum C#-„is“-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert die C#-lock()-Anweisung. Rufen Sie sie direkt auf oder verwenden Sie das [LockContext](../../system/lockcontext/)-Wächterobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von abgeleiteten Klassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von abgeleiteten Klassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz einen Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | Gibt den Aggregationstyp der Kategorienachse (Binning) an. Auf Kategorien angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | Gibt an, ob die Wertachse die Kategorienachse zwischen den Kategorien kreuzt. Diese Eigenschaft gilt nur für Kategorienachsen und nicht für 3-D-Diagramme. Schreiben **bool**. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Schreiben [TimeUnitType](../timeunittype/). |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | Gibt die Bin-Breite an, wenn die Eigenschaft AggregationType auf [AxisAggregationType::ByBinWidth](../axisaggregationtype/) gesetzt ist. Auf Kategorienachsen angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | Gibt den Typ der Kategorienachse an. Schreiben [CategoryAxisType](../categoryaxistype/). |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie kreuzt. Schreiben **float**. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | Gibt den CrossType auf der angegebenen Achse an, an dem die andere Achse kreuzt. Schreiben [CrossesType](../crossestype/). |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | Gibt den Skalierungswert der Anzeigeeinheiten für die Wertachse an. Schreiben [DisplayUnitType](../displayunittype/). |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | Bestimmt, ob die Achse einen sichtbaren Titel hat. Schreiben **bool**. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. Schreiben **bool**. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | Gibt an, ob der Maximalwert automatisch zugewiesen wird. Schreiben **bool**. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | Gibt an, ob die Nebenheitseinheit der Achse automatisch zugewiesen wird. Schreiben **bool**. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | Gibt an, ob der Minimalwert automatisch zugewiesen wird. Schreiben **bool**. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | Gibt den automatischen Überlauf-Bin-Wert an. Wenn **false**: verwenden Sie die Eigenschaft OverflowBin. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | Gibt den automatischen Abstand der Tick-Beschriftungen an. Wenn **false**: verwenden Sie die Eigenschaft TickLabelSpacing. Schreiben **bool**. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | Gibt den automatischen Abstand der Tick-Markierungen an. Wenn **false**: verwenden Sie die Eigenschaft TickMarksSpacing. Schreiben **bool**. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | Gibt den automatischen Unterlauf-Bin-Wert an. Wenn **false**: verwenden Sie die Eigenschaft UnderflowBin. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | Gibt an, ob der Skalierungstyp der Wertachse logarithmisch ist. Schreiben **bool**. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Gibt an, ob das Format mit Quelldaten verknüpft ist. Schreiben **bool**. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | Gibt an, ob ein Überlauf-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Überlauf-Bin-Wert anzupassen. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | Gibt an, ob MS PowerPoint Datenpunkte von letzter zu erster zeichnet. Schreiben **bool**. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | Gibt an, ob ein Unterlauf-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Unterlauf-Bin-Wert anzupassen. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Gibt an, ob die Achse sichtbar ist. Schreiben **bool**. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | Gibt den Abstand der Beschriftungen von der Achse an. Auf Kategorien- oder Datumsachse angewendet. Der Wert muss zwischen 0 % und 1000 % liegen. Schreiben **uint16_t**. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | Gibt die logarithmische Basis an. Der Standardwert ist 10. Schreiben **double**. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | Gibt den Typ der Haupt-Tick-Markierung für die angegebene Achse an. Schreiben [TickMarkType](../tickmarktype/). |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | Gibt die Haupteinheiten für die Datums- oder Wertachse an. Schreiben **double**. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | Gibt den Skalierungsfaktor der Haupteinheit für die Datumsachse an. Schreiben [TimeUnitType](../timeunittype/). |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | Gibt den Maximalwert auf der Wertachse an. Schreiben **double**. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | Gibt den Typ der Neben-Tick-Markierung für die angegebene Achse an. Schreiben [TickMarkType](../tickmarktype/). |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | Gibt die Neben-Einheiten für die Datums- oder Wertachse an. Schreiben **double**. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | Gibt den Skalierungsfaktor der Haupteinheit für die Datumsachse an. Schreiben [TimeUnitType](../timeunittype/). |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | Gibt den Minimalwert auf der Wertachse an. Schreiben **double**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Gibt den Formatstring für die [Axis](../axis/)-Beschriftungen an. Schreiben [System::String](../../system/string/). |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | Gibt die Anzahl der Bins an, wenn die Eigenschaft AggregationType auf [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) gesetzt ist. Auf Kategorienachsen angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | Gibt den benutzerdefinierten Überlauf-Bin-Wert an. Wird angewendet, wenn IsAutomaticOverflowBin **false** ist und IsOverflowBin **true** ist. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | Gibt die Position der Achse an. Schreiben [AxisPositionType](../axispositiontype/). |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | Gibt die Position der Tick-Markierungs-Beschriftungen auf der angegebenen Achse an. Schreiben [TickLabelPositionType](../ticklabelpositiontype/). |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | Gibt den Rotationswinkel der Tick-Beschriftungen an. Schreiben **float**. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | Gibt an, wie viele Tick-Beschriftungen zwischen zwei dargestellten Beschriftungen übersprungen werden sollen. Schreiben **uint32_t**. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | Gibt an, wie viele Tick-Markierungen übersprungen werden sollen, bevor die nächste gezeichnet wird. Auf Kategorien- oder Serienachse angewendet. Schreiben **uint16_t**. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | Gibt den benutzerdefinierten Unterlauf-Bin-Wert an. Wird angewendet, wenn IsAutomaticUnderflowBin **false** ist und IsUnderflowBin **true** ist. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | Setzt die Eigenschaft IAxis::get(set)_CategoryAxisType mit einem Wert, der automatisch anhand der Achsendaten ermittelt wird. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines shared). Ermöglicht das Umschalten von Zeigern in Containern auf schwarten Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert die C# lock()-Anweisung zum Entsperren. Rufen Sie sie direkt auf oder verwenden Sie das [LockContext](../../system/lockcontext/)-Wächterobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IFormattedTextContainer](../iformattedtextcontainer/)
* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)