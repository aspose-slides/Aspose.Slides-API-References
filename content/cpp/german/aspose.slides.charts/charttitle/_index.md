---
title: ChartTitle
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die Eigenschaften des Diagrammtitels dar.
type: docs
weight: 326
url: /de/aspose.slides.charts/charttitle/
---
## ChartTitle Klasse

Stellt die Eigenschaften des Diagrammtitels dar.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Initialisiert TextFrameForOverriding mit dem Text im Parameter \"text\". Wenn TextFrameForOverriding bereits initialisiert ist, ändert es einfach dessen Text. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztypobjekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttypobjekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Gleitkommavergleich, bei dem zwei NaN-Werte als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Gleitkommavergleich, bei dem zwei NaN-Werte als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) vorher auf, um die tatsächlichen Werte zu erhalten. Lesen **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) vorher auf, um die tatsächlichen Werte zu erhalten. Lesen **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) vorher auf, um die tatsächlichen Werte zu erhalten. Lesen **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) vorher auf, um die tatsächlichen Werte zu erhalten. Lesen **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Unten. Nur lesbar **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Gibt das übergeordnete Diagramm zurück. Nur lesbar [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Gibt die Füll-, Linien- und Effektstile eines Titels zurück. Nur lesbar [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Gibt die Höhe eines Titels als Bruchteil der Diagrammhöhe zurück. Lesen **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Bestimmt, ob andere Diagrammelemente den Titel überlappen dürfen. Lesen **bool**. |
| **float** [get_Right](./get_right/)() override | Rechts. Nur lesbar **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Gibt das Textformat zurück. Nur lesbar [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht null ist, überschreibt dieser formatierte Textwert den automatisch generierten Text. Der automatisch generierte Text ist eine implizite Eigenschaft des Datenbeschriftung, der Anzeigeeinheitenbeschriftung der Werte-Achse, des Achsentitels, des Diagrammtitels, der Beschriftung der Trendlinie. Der automatisch generierte Text wird mit der [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/)-Eigenschaft formatiert. Nur lesbar [ITextFrame](../../aspose.slides/itextframe/). |
| **float** [get_Width](./get_width/)() override | Gibt die Breite eines Titels als Bruchteil der Diagrammbreite zurück. Lesen **float**. |
| **float** [get_X](./get_x/)() override | Gibt die x-Koordinate eines Titels als Bruchteil der Diagrammbreite zurück. Lesen **float**. |
| **float** [get_Y](./get_y/)() override | Gibt die y-Koordinate eines Titels als Bruchteil der Diagrammhöhe zurück. Lesen **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-Konstruktor. Kopiert nichts wirklich, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopier-Konstruieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts wirklich, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopier-Konstruieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_Height](./set_height/)(**float**) override | Setzt die Höhe eines Titels als Bruchteil der Diagrammhöhe. Schreiben **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Bestimmt, ob andere Diagrammelemente den Titel überlappen dürfen. Schreiben **bool**. |
| void [set_Width](./set_width/)(**float**) override | Setzt die Breite eines Titels als Bruchteil der Diagrammbreite. Schreiben **float**. |
| void [set_X](./set_x/)(**float**) override | Setzt die x-Koordinate eines Titels als Bruchteil der Diagrammbreite. Schreiben **float**. |
| void [set_Y](./set_y/)(**float**) override | Setzt die y-Koordinate eines Titels als Bruchteil der Diagrammhöhe. Schreiben **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n'th Template-Argument auf einen schwachen Zeiger (statt eines gemeinsamen). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IChartTitle](../icharttitle/)
* Klasse [IDOMObject](../../aspose.slides/idomobject/)
* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)