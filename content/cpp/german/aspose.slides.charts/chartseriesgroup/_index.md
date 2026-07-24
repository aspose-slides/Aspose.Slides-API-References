---
title: ChartSeriesGroup
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Gruppe von Serien dar.
type: docs
weight: 300
url: /de/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup Klasse


Represents group of series.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Gibt an, wie die Bubble-Größenwerte im Bubble-Diagramm dargestellt werden. Lese [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Gibt den Skalierungsfaktor für das Bubble-Diagramm an (kann zwischen 0 % und 300 % der Standardgröße liegen). Lese **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Gibt das übergeordnete Diagramm zurück. Nur-Lese [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Gibt die Diagramm-Series in der Gruppe am angegebenen Index zurück. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 0 % und 90 % der Größe des Zeichenbereichs liegen). Lese **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Liest den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lese **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | Gibt den Abstand als Prozentsatz der Markerbreite zwischen den Daten-Series in einem 3D-Diagramm zurück. Lese **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Gibt den Abstand zwischen Balken- oder Spalten-Clustern als Prozentsatz der Balken- bzw. Spaltenbreite an. Lese **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | Wahr, wenn das Diagramm Serienlinien enthält. Gilt für gestapelte Balken- und OfPie-Diagramme. Lese **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | Gibt das Format der HiLowLines an. HiLowLines werden bei den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose angewendet. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Gibt an, dass jeder Datenmarker in der Series eine andere Farbe hat. Lese **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. Lese [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | Die benutzerdefinierten Aufteilung-Informationen für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit benutzerdefinierter Aufteilung. Gibt den Datenpunkt zurück, der nach Index im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms gezeichnet werden soll. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | Die benutzerdefinierten Aufteilung-Informationen für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit benutzerdefinierter Aufteilung. Enthält Datenpunkte, die im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms gezeichnet werden sollen. Nur-Lese [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. Wird zusammen mit der PieSplitBy-Eigenschaft verwendet. Lese **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Gibt an, ob die Series dieser Gruppe auf einer sekundären Achse geplottet werden. Nur-Lese **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 % und 200 % liegen). Lese **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Gibt eine Sammlung von Series zurück. Nur-Lese [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Gibt den Typ dieser Seriengruppe zurück. Nur-Lese [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Stellt Zugriff auf Auf-/Ab-Balken von Linien- oder Aktien-Diagrammen bereit. Nur-Lese [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liest die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liest den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Liest das Element am angegebenen Index. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Subklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Subklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Gibt an, wie die Bubble-Größenwerte im Bubble-Diagramm dargestellt werden. Schreibe [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Gibt den Skalierungsfaktor für das Bubble-Diagramm an (kann zwischen 0 % und 300 % der Standardgröße liegen). Schreibe **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 0 % und 90 % der Größe des Zeichenbereichs liegen). Schreibe **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | Setzt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Schreibe **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | Setzt den Abstand als Prozentsatz der Markerbreite zwischen den Daten-Series in einem 3D-Diagramm. Schreibe **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Gibt den Abstand zwischen Balken- oder Spalten-Clustern als Prozentsatz der Balken- bzw. Spaltenbreite an. Schreibe **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | Wahr, wenn das Diagramm Serienlinien enthält. Gilt für gestapelte Balken- und OfPie-Diagramme. Schreibe **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Gibt an, dass jeder Datenmarker in der Series eine andere Farbe hat. Schreibe **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. Schreibe [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. Wird zusammen mit der PieSplitBy-Eigenschaft verwendet. Schreibe **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 % und 200 % liegen). Schreibe **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liest den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den geteilten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht das Konvertieren benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Anmerkungen

1) Siehe Zusammenfassung und Anmerkungen zur ChartSeriesGroupCollection-Klasse und zum CombinableSeriesTypesGroup-Enum. 2) Die Gruppe von Serien enthält einige Serien-Eigenschaften, die für jede Serie in der Gruppe gemeinsam sind („Serien-Gruppen-Eigenschaften“). „Serien-Gruppen-Eigenschaften“ in der Klasse [ChartSeriesGroup](./) sind Lese/Schreib. Jede der „Serien-Gruppen-Eigenschaften“ kann eine schreibgeschützte Projektion in der Klasse [ChartSeries](../chartseries/) haben. 

## Siehe auch

* Klasse [IChartSeriesGroup](../ichartseriesgroup/)
* Klasse [IDOMObject](../../aspose.slides/idomobject/)
* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)