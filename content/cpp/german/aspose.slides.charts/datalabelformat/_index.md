---
title: DataLabelFormat
second_title: Aspose.Slides für C++ API Referenz
description: Stellt Formatierungsoptionen für DataLabel bereit.
type: docs
weight: 391
url: /de/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat Klasse

Stellt Formatierungsoptionen für [DataLabel](../datalabel/) bereit.

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergleicht mit dem angegebenen Objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mithilfe der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Gibt das Diagramm zurück. Schreibgeschützt [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Stellt das Format des Datenlabels dar. Schreibgeschützt [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Lese **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Lesen [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Gibt das Parent_Immediate-Objekt zurück. Schreibgeschützt [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Gibt das übergeordnete [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) zurück. Schreibgeschützt [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | Stellt die Position des Datenlabels dar. Lesen [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | Setzt oder gibt eine Variant zurück, die das Trennzeichen für die Datenlabels in einem Diagramm darstellt. Lesen [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | Stellt das Anzeigeverhalten des Bubble-Größenwerts eines Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Bubble-Größenwert an. Falsch verbirgt ihn. Lesbar **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | Stellt das Anzeigeverhalten des Kategorienamens eines Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Kategorienamen an. Falsch verbirgt ihn. Lesbar **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | Bestimmt, ob das Datenlabel eines angegebenen Diagramms als Datenaufruf oder als Datenlabel angezeigt wird. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | Stellt das Anzeigeverhalten des Zellenwerts eines Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Zellenwert an. Falsch verbirgt ihn. Lesbar **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | Stellt das Anzeigeverhalten der Führungs-Linien eines Datenlabels eines angegebenen Diagramms dar. Wahr zeigt die Führungs-Linien an. Falsch verbirgt sie. Lesbar **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | Stellt das Anzeigeverhalten des Legenden-Schlüssels eines Datenlabels eines angegebenen Diagramms dar. Wahr wenn der Legenden-Schlüssel sichtbar ist. Lesbar **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | Stellt das Anzeigeverhalten des Prozentwerts eines Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Prozentwert an. Falsch verbirgt ihn. Lesbar **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | Gibt einen Bool-Wert zurück, der das Anzeigeverhalten des Seriennamens für die Datenlabels in einem Diagramm angibt. Wahr zeigt den Seriennamen. Falsch verbirgt ihn. Lesbar **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | Stellt das Anzeigeverhalten des Prozentwerts eines Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Prozentwert an. Falsch verbirgt ihn. Lesbar **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Gibt das Textformat des Diagramms zurück. Schreibgeschützt [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Referenzzähler-Datenstruktur ab, die mit dem Objekt verknüpft ist. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | Gibt den Hash-Code zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-„is“-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das C#-`lock()`-Statement. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopierkonstruktieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopierkonstruktieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleich eines Werttyps mit `nullptr` per Referenz. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und `nullptr`. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Schreibe **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Stellt die Formatzeichenfolge für das DataLabels-Objekt dar. Schreiben [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | Stellt die Position des Datenlabels dar. Schreiben [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | Setzt oder gibt eine Variant zurück, die das Trennzeichen für die Datenlabels in einem Diagramm darstellt. Schreiben [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | Stellt das Anzeigeverhalten des Bubble-Größenwerts eines Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Bubble-Größenwert an. Falsch verbirgt ihn. Schreiben **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | Stellt das Anzeigeverhalten des Kategorienamens eines Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Kategorienamen an. Falsch verbirgt ihn. Schreiben **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | Bestimmt, ob das Datenlabel eines angegebenen Diagramms als Datenaufruf oder als Datenlabel angezeigt wird. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | Stellt das Anzeigeverhalten des Zellenwerts eines Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Zellenwert an. Falsch verbirgt ihn. Schreiben **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | Stellt das Anzeigeverhalten der Führungs-Linien eines Datenlabels eines angegebenen Diagramms dar. Wahr zeigt die Führungs-Linien an. Falsch verbirgt sie. Schreiben **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | Stellt das Anzeigeverhalten des Legenden-Schlüssels eines Datenlabels eines angegebenen Diagramms dar. Wahr wenn der Legenden-Schlüssel sichtbar ist. Schreiben **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | Stellt das Anzeigeverhalten des Prozentwerts eines Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Prozentwert an. Falsch verbirgt ihn. Schreiben **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | Setzt einen Bool-Wert, der das Anzeigeverhalten des Seriennamens für die Datenlabels in einem Diagramm angibt. Wahr zeigt den Seriennamen. Falsch verbirgt ihn. Schreiben **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | Stellt das Anzeigeverhalten des Prozentwerts eines Datenlabels eines angegebenen Diagramms dar. Wahr zeigt den Prozentwert an. Falsch verbirgt ihn. Schreiben **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt zu einem geteilten). Ermöglicht das Wechseln von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ruft den aktuellen Wert des geteilten Referenzzählers ab. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den geteilten Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-`typeof([System.Object](../../system/object/))`-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das C#-`lock()`-Statement zum Entsperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe Auch

* Klasse [PVIObject](../../aspose.slides/pviobject/)
* Klasse [IDataLabelFormat](../idatalabelformat/)
* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)