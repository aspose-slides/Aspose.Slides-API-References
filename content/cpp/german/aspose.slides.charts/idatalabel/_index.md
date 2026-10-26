---
title: IDataLabel
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt Serienbeschriftungen dar.
type: docs
weight: 937
url: /de/aspose.slides.charts/idatalabel/
---
## IDataLabel Klasse


Stellt Serienbeschriftungen dar.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Initialisiert TextFrameForOverriding mit dem Text im Parameter \"text\". Wenn TextFrameForOverriding bereits initialisiert ist, ändert es einfach seinen Text. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um die wirklichen Werte zu erhalten. Lese **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um die wirklichen Werte zu erhalten. Lese **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um die wirklichen Werte zu erhalten. Lese **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Gibt die tatsächliche Oberseite des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie vorher die Methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) auf, um die wirklichen Werte zu erhalten. Lese **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Liefert die Oberseite des Diagrammelements als Bruchteil der Diagrammhöhe. Nur-Lesen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Gibt das Diagramm zurück. Nur-Lesen [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | Gibt das Format des Datenlabels zurück. Nur-Lesen [IDataLabelFormat](../idatalabelformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Gibt die Höhe des Diagrammelements als Bruchteil der Diagrammhöhe an. Lese **float**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | False bedeutet, dass das Datenlabel nicht sichtbar ist (und daher alle Show*-Flags (ShowValue, ...) false sind). Nur-Lesen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Gibt die Präsentation zurück. Nur-Lesen [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Liefert die rechte Seite des Diagrammelements als Bruchteil der Diagrammbreite. Nur-Lesen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Gibt die Basisfolie zurück. Nur-Lesen [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Gibt das Diagramm-Textformat zurück. Nur-Lesen [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Kann einen reich formatierten Text enthalten. Wenn diese Eigenschaft nicht null ist, überschreibt dieser formatierte Textwert den automatisch erzeugten Text. Der automatisch erzeugte Text ist eine implizite Eigenschaft des Datenlabels, des Anzeigeeinheitslabels der Werteachse, des Achsentitels, des Diagrammtitels, des Trendlinien-Labels. Der automatisch erzeugte Text wird mit der [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/)-Eigenschaft formatiert. Nur-Lesen [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | Liefert die Arbeitsmappendatenzelle. Wird angewendet, wenn die Eigenschaft IDataLabelFormat::get(set)_ShowLabelValueFromCell true ist. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Gibt die Breite des Diagrammelements als Bruchteil der Diagrammbreite an. Lese **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Gibt die x-Position (links) des Diagrammelements als Bruchteil der Diagrammbreite an. Lese **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Gibt die Oberseite des Diagrammelements als Bruchteil der Diagrammhöhe an. Lese **float**. |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | Gibt den tatsächlichen Beschriftungstext basierend auf den [DataLabelFormat](../datalabelformat/)-Einstellungen oder dem Wert von TextFrameForOverriding.Text zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [Hide](./hide/)() | Macht das Datenlabel unsichtbar, indem alle Show*-Flags (ShowValue, ...) auf false gesetzt werden. IsVisible wird danach false sein. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, wirklich, initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, wirklich, initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht einen Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die geteilte Referenzzählung um den angegebenen Wert. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Gibt die Höhe des Diagrammelements als Bruchteil der Diagrammhöhe an. Schreibe **float**. |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | Setzt die Arbeitsmappendatenzelle. Wird angewendet, wenn die Eigenschaft IDataLabelFormat::get(set)_ShowLabelValueFromCell true ist. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Gibt die Breite des Diagrammelements als Bruchteil der Diagrammbreite an. Schreibe **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Gibt die x-Position (links) des Diagrammelements als Bruchteil der Diagrammbreite an. Schreibe **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Gibt die Oberseite des Diagrammelements als Bruchteil der Diagrammhöhe an. Schreibe **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die geteilte Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die geteilte Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht das Konvertieren benutzerdefinierter Objekte zu einem String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert die C#-Konstruktion typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [ILayoutable](../ilayoutable/)
* Klasse [IOverridableText](../ioverridabletext/)
* Klasse [IActualLayout](../iactuallayout/)
* Namensraum [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)