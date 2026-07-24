---
title: Legend
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Eigenschaften der Diagrammlegende dar.
type: docs
weight: 1262
url: /de/aspose.slides.charts/legend/
---
## Legend Klasse

Represents chart's legend properties.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztypobjekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttypobjekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaN-Werte als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaN-Werte als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um die tatsächlichen Werte zu erhalten. Lesen **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um die tatsächlichen Werte zu erhalten. Lesen **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um die tatsächlichen Werte zu erhalten. Lesen **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Gibt den tatsächlichen oberen Rand des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um die tatsächlichen Werte zu erhalten. Lesen **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Unten. Nur lesbar **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Gibt das Diagramm zurück. Nur lesbar [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | Erhält Legendeinträge. Nur lesbar [ILegendEntryCollection](../ilegendentrycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | Liefert die Eigenschaften des Legendeintrags, der dem Datenpunkt im Diagramm am angegebenen Index entspricht. Bei Diagrammtypen: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie wird der Datenpunkt aus der ersten Serie genommen. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Gibt das Format einer Legende zurück. Nur lesbar [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Gibt die Höhe einer Legende als Bruchteil der Diagrammhöhe zurück. Lesen **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Bestimmt, ob andere Diagrammelemente die Legende überlappen dürfen. Lesen **bool**. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | Gibt die Position der Legende in einem Diagramm an. Nicht-NaN-Werte der Eigenschaften X, Y, Width, Heigt überschreiben die Wirkung dieser Eigenschaft. Lesen [LegendPositionType](../legendpositiontype/). |
| **float** [get_Right](./get_right/)() override | Rechts. Nur lesbar **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Textformat. Nur lesbar [IChartTextFormat](../icharttextformat/). |
| **float** [get_Width](./get_width/)() override | Gibt die Breite einer Legende als Bruchteil der Diagrammbreite zurück. Lesen **float**. |
| **float** [get_X](./get_x/)() override | Gibt die x-Koordinate einer Legende als Bruchteil der Diagrammbreite zurück. Lesen **float**. |
| **float** [get_Y](./get_y/)() override | Gibt die y-Koordinate einer Legende als Bruchteil der Diagrammhöhe zurück. Lesen **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht Referenzweise ein Werttypobjekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_Height](./set_height/)(**float**) override | Setzt die Höhe einer Legende als Bruchteil der Diagrammhöhe. Schreiben **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Bestimmt, ob andere Diagrammelemente die Legende überlappen dürfen. Schreiben **bool**. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | Gibt die Position der Legende in einem Diagramm an. Nicht-NaN-Werte der Eigenschaften X, Y, Width, Heigt überschreiben die Wirkung dieser Eigenschaft. Schreiben [LegendPositionType](../legendpositiontype/). |
| void [set_Width](./set_width/)(**float**) override | Setzt die Breite einer Legende als Bruchteil der Diagrammbreite. Schreiben **float**. |
| void [set_X](./set_x/)(**float**) override | Setzt die x-Koordinate einer Legende als Bruchteil der Diagrammbreite. Schreiben **float**. |
| void [set_Y](./set_y/)(**float**) override | Setzt die y-Koordinate einer Legende als Bruchteil der Diagrammhöhe. Schreiben **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe Auch

* Klasse [DomObject](../../aspose.slides/domobject/)
* Klasse [ILegend](../ilegend/)
* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)