---
title: IDataLabelFormat
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt Formatoptionen für DataLabel dar.
type: docs
weight: 963
url: /de/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat Klasse

Stellt Formatoptionen für [DataLabel](../datalabel/) dar.

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Gibt das Diagramm zurück. Schreibgeschützt [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Stellt das Format der Datenbeschriftung dar. Schreibgeschützt [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Lese **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Nur lesbar [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | Stellt die Position der Datenbeschriftung dar. Nur lesbar [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Gibt die Präsentation zurück. Schreibgeschützt [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | Setzt oder gibt einen Variant zurück, der das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. Nur lesbar [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | Stellt das Anzeigeverhalten des Blasengrößenwerts einer bestimmten Diagrammdatenbeschriftung dar. Wahr zeigt den Blasengrößenwert an. Falsch versteckt ihn. Lese **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | Stellt das Anzeigeverhalten des Kategorienamens einer bestimmten Diagrammdatenbeschriftung dar. Wahr zeigt den Kategorienamen an. Falsch versteckt ihn. Lese **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | Bestimmt, ob die Datenbeschriftung eines bestimmten Diagramms als Datencallout oder als Datenbeschriftung angezeigt wird. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | Stellt das Anzeigeverhalten des Zellenwerts einer bestimmten Diagrammdatenbeschriftung dar. Wahr zeigt den Zellenwert an. Falsch versteckt ihn. Lese **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | Stellt das Anzeigeverhalten der Führungsleitungen einer bestimmten Diagrammdatenbeschriftung dar. Wahr zeigt die Führungsleitungen an. Falsch versteckt sie. Lese **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | Stellt das Anzeigeverhalten des Legenden-Schlüssels einer bestimmten Diagrammdatenbeschriftung dar. Wahr wenn der Legenden-Schlüssel sichtbar ist. Lese **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | Stellt das Anzeigeverhalten des Prozentwerts einer bestimmten Diagrammdatenbeschriftung dar. Wahr zeigt den Prozentwert an. Falsch versteckt ihn. Lese **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | Gibt ein boolesches Ergebnis zurück, das das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm angibt. Wahr zeigt den Seriennamen an. Falsch versteckt ihn. Lese **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | Stellt das Anzeigeverhalten des Prozentwerts einer bestimmten Diagrammdatenbeschriftung dar. Wahr zeigt den Prozentwert an. Falsch versteckt ihn. Lese **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Gibt die Basisseite zurück. Schreibgeschützt [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Gibt das Diagramm-Textformat zurück. Schreibgeschützt [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Referenzzähler-Datenstruktur ab, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen von benutzerdefinierten Objekten. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ruft den tatsächlichen Typ des Objekts ab. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Schreibe **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Schreibe [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | Stellt die Position der Datenbeschriftung dar. Schreibe [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | Setzt oder gibt einen Variant zurück, der das Trennzeichen für die Datenbeschriftungen in einem Diagramm darstellt. Schreibe [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | Stellt das Anzeigeverhalten des Blasengrößenwerts einer bestimmten Diagrammdatenbeschriftung dar. Wahr zeigt den Blasengrößenwert an. Falsch versteckt ihn. Schreibe **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | Stellt das Anzeigeverhalten des Kategorienamens einer bestimmten Diagrammdatenbeschriftung dar. Wahr zeigt den Kategorienamen an. Falsch versteckt ihn. Schreibe **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | Bestimmt, ob die Datenbeschriftung eines bestimmten Diagramms als Datencallout oder als Datenbeschriftung angezeigt wird. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | Stellt das Anzeigeverhalten des Zellenwerts einer bestimmten Diagrammdatenbeschriftung dar. Wahr zeigt den Zellenwert an. Falsch versteckt ihn. Schreibe **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | Stellt das Anzeigeverhalten der Führungsleitungen einer bestimmten Diagrammdatenbeschriftung dar. Wahr zeigt die Führungsleitungen an. Falsch versteckt sie. Schreibe **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | Stellt das Anzeigeverhalten des Legenden-Schlüssels einer bestimmten Diagrammdatenbeschriftung dar. Wahr wenn der Legenden-Schlüssel sichtbar ist. Schreibe **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | Stellt das Anzeigeverhalten des Prozentwerts einer bestimmten Diagrammdatenbeschriftung dar. Wahr zeigt den Prozentwert an. Falsch versteckt ihn. Schreibe **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | Setzt ein Boolesches, um das Anzeigeverhalten des Seriennamens für die Datenbeschriftungen in einem Diagramm anzugeben. Wahr zeigt den Seriennamen an. Falsch versteckt ihn. Schreibe **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | Stellt das Anzeigeverhalten des Prozentwerts einer bestimmten Diagrammdatenbeschriftung dar. Wahr zeigt den Prozentwert an. Falsch versteckt ihn. Schreibe **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ruft den aktuellen Wert des geteilten Referenzzählers ab. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den geteilten Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht das Konvertieren benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IFormattedTextContainer](../iformattedtextcontainer/)
* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)