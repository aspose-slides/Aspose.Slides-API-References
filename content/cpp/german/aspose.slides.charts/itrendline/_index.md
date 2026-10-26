---
title: ITrendline
second_title: Aspose.Slides für C++ API-Referenz
description: Klasse stellt die Trendlinie einer Diagrammreihe dar
type: docs
weight: 1223
url: /de/aspose.slides.charts/itrendline/
---
## ITrendline Klasse

Klasse stellt die Trendlinie einer Diagrammreihe dar

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## Methoden

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Initialisiert TextFrameForOverriding mit dem Text im Parameter \"text\". Wenn TextFrameForOverriding bereits initialisiert ist, wird einfach dessen Text geändert. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN laut IEC 60559:1989 keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN laut IEC 60559:1989 keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **double** [get_Backward](./get_backward/)() | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie vor den Daten der zu trendenden Serie erweitert. Bei Streu- und Nicht-Streudiagrammen darf der Wert beliebiger nicht-negativer Wert sein. Lese **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Gibt das Diagramm zurück. Nur-Lesen [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquared-Wert). Lese **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). Lese **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Stellt das Format der Trendlinie dar. Lese [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie nach den Daten der zu trendenden Serie erweitert. Bei Streu- und Nicht-Streudiagrammen darf der Wert beliebiger nicht-negativer Wert sein. Lese **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. Diese Eigenschaft wird nur unterstützt, wenn der Trendlinientyp exp, linear oder poly ist. Lese **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Gibt die Ordnung der polynomialen Trendlinie an. Für andere Trendlinientypen wird dieser Wert ignoriert. Der Wert muss zwischen 2 und 6 liegen. Lese **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Gibt den Zeitraum der Trendlinie für eine gleitende Durchschnitte-Trendlinie an. Für andere Trendlinienvarianten wird dieser Wert ignoriert. Der Wert muss zwischen 2 und 255 liegen. Lese **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Gibt die Präsentation zurück. Nur-Lesen [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Stellt den Legendeneintrag dar, der mit dieser Trendlinie verbunden ist. Nur-Lesen [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Gibt die Basisseite zurück. Nur-Lesen [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Gibt das Diagramm-Textformat zurück. Nur-Lesen [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Kann einen reichhaltig formatierten Text enthalten. Wenn diese Eigenschaft nicht null ist, überschreibt dieser formatierte Textwert automatisch generierten Text. Automatisch generierter Text ist eine implizite Eigenschaft des Datenlabels, des Anzeigeeinheiten-Labels der Wertachse, des Achsentitels, des Diagrammtitels, des Labels der Trendlinie. Automatisch generierter Text wird mit der [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/)-Eigenschaft formatiert. Nur-Lesen [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Ermittelt den Namen der Trendlinie. Lese [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Ermittelt den Typ der Trendlinie. Lese [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-„is“-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|   [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruktieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruktieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [set_Backward](./set_backward/)(**double**) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie vor den Daten der zu trendenden Serie erweitert. Bei Streu- und Nicht-Streudiagrammen darf der Wert beliebiger nicht-negativer Wert sein. Schreibe **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Gibt an, dass die Gleichung der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie der Rsquared-Wert). Schreibe **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Gibt an, dass der R-Quadrat-Wert der Trendlinie im Diagramm angezeigt wird (im selben Beschriftungsfeld wie die Gleichung). Schreibe **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Stellt das Format der Trendlinie dar. Schreibe [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Gibt die Anzahl der Kategorien (oder Einheiten in einem Streudiagramm) an, die die Trendlinie nach den Daten der zu trendenden Serie erweitert. Bei Streu- und Nicht-Streudiagrammen darf der Wert beliebiger nicht-negativer Wert sein. Schreibe **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Gibt den Wert an, an dem die Trendlinie die y-Achse schneidet. Diese Eigenschaft wird nur unterstützt, wenn der Trendlinientyp exp, linear oder poly ist. Schreibe **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Gibt die Ordnung der polynomialen Trendlinie an. Für andere Trendlinientypen wird dieser Wert ignoriert. Der Wert muss zwischen 2 und 6 liegen. Schreibe **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Gibt den Zeitraum der Trendlinie für eine gleitende Durchschnitte-Trendlinie an. Für andere Trendlinienvarianten wird dieser Wert ignoriert. Der Wert muss zwischen 2 und 255 liegen. Schreibe **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Setzt den Namen der Trendlinie. Schreibe [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Setzt den Typ der Trendlinie. Schreibe [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Vorlagenargument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IOverridableText](../ioverridabletext/)
* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)