---
title: DataLabel
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt Serienbeschriftungen dar.
type: docs
weight: 365
url: /de/aspose.slides.charts/datalabel/
---
## DataLabel Klasse

Stellt Serienbeschriftungen dar.

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Initialisiert TextFrameForOverriding mit dem Text im Parameter "text". Wenn TextFrameForOverriding bereits initialisiert ist, ändert es einfach dessen Text. |
|  [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | Erstellt eine neue Instanz der Klasse [DataLabel](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-ähnlichen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-ähnlichen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um die tatsächlichen Werte zu erhalten. Lese **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um die tatsächlichen Werte zu erhalten. Lese **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um die tatsächlichen Werte zu erhalten. Lese **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Gibt den tatsächlichen oberen Rand des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um die tatsächlichen Werte zu erhalten. Lese **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Unten. Nur lesbar **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Gibt das übergeordnete Diagramm zurück. Nur lesbar [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | Gibt das Datenbeschriftungsformat zurück. Nur lesbar [IDataLabelFormat](../idatalabelformat/). |
| **float** [get_Height](./get_height/)() override | Gibt die Höhe eines Titels als Bruchteil der Diagrammhöhe zurück. Lese **float**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | False bedeutet, dass die Datenbeschriftung nicht sichtbar ist (und daher alle Show*-Flags (ShowValue, ...) false sind). Nur lesbar **bool**. |
| **float** [get_Right](./get_right/)() override | Rechts. Nur lesbar **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Gibt das Textformat zurück. Nur lesbar [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Kann einen reich formatierten Text enthalten. Ist diese Eigenschaft nicht null, überschreibt dieser formatierte Textwert den automatisch generierten Text der Datenbeschriftung. Automatisch generierter Text der Datenbeschriftung bedeutet Text, der von den Eigenschaften ShowSeriesName, ShowValue, ... verwaltet wird und mit der Eigenschaft TextFormatManager.TextFormat formatiert ist. Nur lesbar [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | Liefert die Arbeitsmappendatenzelle. Wird angewendet, wenn die Eigenschaft IDataLabelFormat::get(set)_ShowLabelValueFromCell true ist. |
| **float** [get_Width](./get_width/)() override | Gibt die Breite eines Titels als Bruchteil der Diagrammbreite zurück. Lese **float**. |
| **float** [get_X](./get_x/)() override | Gibt die x-Koordinate eines Titels als Bruchteil der Diagrammbreite zurück. Lese **float**. |
| **float** [get_Y](./get_y/)() override | Gibt die y-Koordinate eines Titels als Bruchteil der Diagrammhöhe zurück. Lese **float**. |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | Gibt den tatsächlichen Beschriftungstext basierend auf den [DataLabelFormat](../datalabelformat/)-Einstellungen oder dem Wert [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text() zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| void [Hide](./hide/)() override | Versteckt die Datenbeschriftung, indem alle Show*-Flags (ShowValue, ...) auf den falschen Zustand gesetzt werden. IsVisible wird danach false sein. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des von targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Rufen Sie direkt auf oder verwenden Sie das [LockContext](../../system/lockcontext/)-Sentry-Objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzählung um den angegebenen Wert. |
| void [set_Height](./set_height/)(**float**) override | Setzt die Höhe eines Titels als Bruchteil der Diagrammhöhe. Schreiben **float**. |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | Setzt die Arbeitsmappendatenzelle. Wird angewendet, wenn die Eigenschaft IDataLabelFormat::get(set)_ShowLabelValueFromCell true ist. |
| void [set_Width](./set_width/)(**float**) override | Setzt die Breite eines Titels als Bruchteil der Diagrammbreite. Schreiben **float**. |
| void [set_X](./set_x/)(**float**) override | Setzt die x-Koordinate eines Titels als Bruchteil der Diagrammbreite. Schreiben **float**. |
| void [set_Y](./set_y/)(**float**) override | Setzt die y-Koordinate eines Titels als Bruchteil der Diagrammhöhe. Schreiben **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt gemeinsam). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert der gemeinsamen Referenzzählung. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart Pointers oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die gemeinsame Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart Pointers oder ThisProtector verwendet werden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Rufen Sie direkt auf oder verwenden Sie das [LockContext](../../system/lockcontext/)-Sentry-Objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart Pointers oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart Pointers oder ThisProtector verwendet werden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
## Siehe auch

* Klasse [IDataLabel](../idatalabel/)
* Klasse [IDOMObject](../../aspose.slides/idomobject/)
* Namensraum [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)