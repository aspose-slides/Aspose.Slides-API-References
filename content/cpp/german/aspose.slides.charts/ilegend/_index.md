---
title: ILegend
second_title: Aspose.Slides für C++ API Referenz
description: Stellt die Legenden-Eigenschaften des Diagramms dar.
type: docs
weight: 1080
url: /de/aspose.slides.charts/ilegend/
---
## ILegend Klasse

Stellt die Legenden-Eigenschaften des Diagramms dar.

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) vorher auf, um die tatsächlichen Werte zu erhalten. Lese **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) vorher auf, um die tatsächlichen Werte zu erhalten. Lese **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) vorher auf, um die tatsächlichen Werte zu erhalten. Lese **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) vorher auf, um die tatsächlichen Werte zu erhalten. Lese **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Ermittelt die obere Position des Diagrammelements als Bruchteil der Diagrammhöhe. Nur lesbar **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Liefert das Diagramm zurück. Nur lesbar [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | Ermittelt die Legendeinträge. Nur lesbar [ILegendEntryCollection](../ilegendentrycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | Ermittelt die Eigenschaften des Legendeeintrags, der dem Datenpunkt im Diagramm am angegebenen Index entspricht. Bei Diagrammtypen: bar-of-pie, exploded pie, exploded pie 3D, pie, pie 3D, pie-of-pie, wird der Datenpunkt aus der ersten Serie genommen. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Liefert das Format einer Legende zurück. Nur lesbar [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Gibt die Höhe des Diagrammelements als Bruchteil der Diagrammhöhe an. Lese **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Ermittelt, ob andere Diagrammelemente das Überlappen der Legende zulassen sollen. Lese **bool**. |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | Gibt die Position der Legende in einem Diagramm an. Nicht-NaN-Werte der Eigenschaften X, Y, Width, Height überschreiben die Wirkung dieser Eigenschaft. Lese [LegendPositionType](../legendpositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Liefert die Präsentation zurück. Nur lesbar [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Ermittelt die rechte Position des Diagrammelements als Bruchteil der Diagrammbreite. Nur lesbar **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Liefert die Basisseite zurück. Nur lesbar [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Liefert das Diagramm-Textformat zurück. Nur lesbar [IChartTextFormat](../icharttextformat/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Gibt die Breite des Diagrammelements als Bruchteil der Diagrammbreite an. Lese **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Gibt die x-Position (links) des Diagrammelements als Bruchteil der Diagrammbreite an. Lese **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Gibt die obere Position des Diagrammelements als Bruchteil der Diagrammhöhe an. Lese **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die mit dem Objekt verbundene Referenzzähler-Datenstruktur. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das C# lock()-Statement für das Sperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, tatsächlich, nur ein neues Objekt initialisiert und das Kopieren von Unterklassen ermöglicht. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, tatsächlich, nur ein neues Objekt initialisiert und das Kopieren von Unterklassen ermöglicht. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenzvergleicht Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsam genutzten Referenzzähler um den angegebenen Wert. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Gibt die Höhe des Diagrammelements als Bruchteil der Diagrammhöhe an. Schreibe **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Ermittelt, ob andere Diagrammelemente das Überlappen der Legende zulassen sollen. Schreibe **bool**. |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | Gibt die Position der Legende in einem Diagramm an. Nicht-NaN-Werte der Eigenschaften X, Y, Width, Height überschreiben die Wirkung dieser Eigenschaft. Schreibe [LegendPositionType](../legendpositiontype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Gibt die Breite des Diagrammelements als Bruchteil der Diagrammbreite an. Schreibe **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Gibt die x-Position (links) des Diagrammelements als Bruchteil der Diagrammbreite an. Schreibe **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Gibt die obere Position des Diagrammelements als Bruchteil der Diagrammhöhe an. Schreibe **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen weak pointer (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das C# lock()-Statement zum Entsperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [ILayoutable](../ilayoutable/)
* Klasse [IFormattedTextContainer](../iformattedtextcontainer/)
* Klasse [IActualLayout](../iactuallayout/)
* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)