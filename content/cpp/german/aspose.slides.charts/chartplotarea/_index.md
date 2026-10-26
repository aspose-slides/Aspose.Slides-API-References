---
title: ChartPlotArea
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt das Rechteck dar, in dem das Diagramm gezeichnet werden soll.
type: docs
weight: 248
url: /de/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea Klasse

Stellt das Rechteck dar, in dem das Diagramm gezeichnet werden soll.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) zuvor auf, um die tatsächlichen Werte zu erhalten. Lese **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) zuvor auf, um die tatsächlichen Werte zu erhalten. Lese **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) zuvor auf, um die tatsächlichen Werte zu erhalten. Lese **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) zuvor auf, um die tatsächlichen Werte zu erhalten. Lese **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Unten. Nur-lesbar **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). Nur-lesbar [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Gibt das Format eines Plot-Bereichs zurück. Nur-lesbar [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Gibt die Höhe einer Plot-Bereich-Bounding-Box als Bruchteil der Diagrammhöhe zurück (von 0 bis 1). Lese **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | Definiert, wie die Position berechnet werden soll: true – automatisch berechnet; definiert durch die Eigenschaften X, Y, Width, Height. Nur-lesbar **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | Falls das Layout des Plot-Bereichs manuell definiert ist, gibt diese Eigenschaft an, ob der Plot-Bereich nach seinem Inneren (ohne Achsen und Achsenbeschriftungen) oder nach außen (einschließlich Achsen und Achsenbeschriftungen) angeordnet werden soll. Lese [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | Rechts. Nur-lesbar **float**. |
| **float** [get_Width](./get_width/)() override | Gibt die Breite einer Plot-Bereich-Bounding-Box als Bruchteil der Diagrammbreite zurück (von 0 bis 1). Lese **float**. |
| **float** [get_X](./get_x/)() override | Gibt die x-Koordinate der oberen linken Ecke der Plot-Bereich-Bounding-Box als Bruchteil der Diagrammbreite zurück (von 0 bis 1). Lese **float**. |
| **float** [get_Y](./get_y/)() override | Gibt die y-Koordinate der oberen linken Ecke der Plot-Bereich-Bounding-Box als Bruchteil der Diagrammhöhe zurück (von 0 bis 1). Lese **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Referenzzähler-Datenstruktur ab, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-Anweisung lock(). Rufen Sie es direkt auf oder verwenden Sie das Sentry-Objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_Height](./set_height/)(**float**) override | Setzt die Höhe einer Plot-Bereich-Bounding-Box als Bruchteil der Diagrammhöhe (von 0 bis 1). Schreibe **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | Falls das Layout des Plot-Bereichs manuell definiert ist, gibt diese Eigenschaft an, ob der Plot-Bereich nach seinem Inneren (ohne Achsen und Achsenbeschriftungen) oder nach außen (einschließlich Achsen und Achsenbeschriftungen) angeordnet werden soll. Schreibe [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | Setzt die Breite einer Plot-Bereich-Bounding-Box als Bruchteil der Diagrammbreite (von 0 bis 1). Schreibe **float**. |
| void [set_X](./set_x/)(**float**) override | Setzt die x-Koordinate der oberen linken Ecke der Plot-Bereich-Bounding-Box als Bruchteil der Diagrammbreite (von 0 bis 1). Schreibe **float**. |
| void [set_Y](./set_y/)(**float**) override | Setzt die y-Koordinate der oberen linken Ecke der Plot-Bereich-Bounding-Box als Bruchteil der Diagrammhöhe (von 0 bis 1). Schreibe **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt eines Shared-Pointers). Ermöglicht das Umschalten von Zeigern in Containern auf den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ruft den aktuellen Wert des gemeinsamen Referenzzählers ab. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-Anweisung lock(). Rufen Sie es direkt auf oder verwenden Sie das Sentry-Objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [DomObject](../../aspose.slides/domobject/)
* Klasse [IChartPlotArea](../ichartplotarea/)
* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)