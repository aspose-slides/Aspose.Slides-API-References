---
title: IChartTitle
second_title: Aspose.Slides für C++ API Referenz
description: Stellt die Eigenschaften des Diagrammtitels dar.
type: docs
weight: 911
url: /de/aspose.slides.charts/icharttitle/
---
## IChartTitle Klasse

Stellt die Eigenschaften des Diagrammtitels dar.

```cpp
class IChartTitle : public Aspose::Slides::Charts::ILayoutable,
                    public Aspose::Slides::Charts::IOverridableText,
                    public Aspose::Slides::Charts::IActualLayout
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Initialisiert TextFrameForOverriding mit dem Text im Parameter \"text\". Wenn TextFrameForOverriding bereits initialisiert ist, ändert es einfach dessen Text. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert C#-ähnlichen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich gelten, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert C#-ähnlichen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich gelten, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um aktuelle Werte zu erhalten. Lese **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um aktuelle Werte zu erhalten. Lese **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um aktuelle Werte zu erhalten. Lese **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um aktuelle Werte zu erhalten. Lese **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Gibt die obere Position des Diagrammelements als Bruchteil der Diagrammhöhe zurück. Nur lesender **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Gibt das Diagramm zurück. Nur lesend [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Gibt die Füll-, Linien- und Effektstile eines Titels zurück. Nur lesend [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Gibt die Höhe des Diagrammelements als Bruchteil der Diagrammhöhe an. Lese **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Bestimmt, ob andere Diagrammelemente den Titel überlappen dürfen. Lese **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Gibt die Präsentation zurück. Nur lesend [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Gibt das rechte Ende des Diagrammelements als Bruchteil der Diagrammbreite zurück. Nur lesender **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Gibt die Basis-Folien zurück. Nur lesend [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Gibt das Textformat des Diagramms zurück. Nur lesend [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht null ist, überschreibt dieser formatierte Text den automatisch generierten Text. Der automatisch generierte Text ist eine implizite Eigenschaft des Datenlabels, der Anzeigeeinheitsbeschriftung der Wertachse, des Achsentitels, des Diagrammtitels, der Beschriftung der Trendlinie. Der automatisch generierte Text wird mit der [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/)-Eigenschaft formatiert. Nur lesend [ITextFrame](../../aspose.slides/itextframe/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Gibt die Breite des Diagrammelements als Bruchteil der Diagrammbreite an. Lese **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Gibt die x-Position (links) des Diagrammelements als Bruchteil der Diagrammbreite an. Lese **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Gibt die obere Position des Diagrammelements als Bruchteil der Diagrammhöhe an. Lese **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Objekttyp zurück. Analogie zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs ist. Analogie zum C#-Operator \"is\". |
| void [Lock](../../system/object/lock/)() | Implementiert das C#-lock()-Statement. Rufen Sie die Methode direkt auf oder verwenden Sie das [LockContext](../../system/lockcontext/)-Wächterobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von abgeleiteten Klassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von abgeleiteten Klassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleich von Werttyp-Objekten mit nullptr per Referenz. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Gibt die Höhe des Diagrammelements als Bruchteil der Diagrammhöhe an. Schreibe **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Bestimmt, ob andere Diagrammelemente den Titel überlappen dürfen. Schreibe **bool**. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Gibt die Breite des Diagrammelements als Bruchteil der Diagrammbreite an. Schreibe **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Gibt die x-Position (links) des Diagrammelements als Bruchteil der Diagrammbreite an. Schreibe **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Gibt die obere Position des Diagrammelements als Bruchteil der Diagrammhöhe an. Schreibe **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern auf den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das C#-lock()-Statement zum Entsperren. Rufen Sie die Methode direkt auf oder verwenden Sie das [LockContext](../../system/lockcontext/)-Wächterobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; verwenden Sie stattdessen Smart-Pointer oder ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [ILayoutable](../ilayoutable/)
* Klasse [IOverridableText](../ioverridabletext/)
* Klasse [IActualLayout](../iactuallayout/)
* Namensraum [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)