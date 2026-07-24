---
title: MasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides für C++ API Referenz
description: Stellt einen Manager dar, der das Verhalten des Fußzeilen-Platzhalters der Master-Notizfolie, des Datums-Uhrzeit-Platzhalters, des Seitenzahlen-Platzhalters und aller untergeordneten Platzhalter verwaltet. Untergeordnete Platzhalter bedeuten, dass die Platzhalter in abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab.
type: docs
weight: 4460
url: /de/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager Klasse


Represents manager which holds behavior of the master notes slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending notes slides. Depending notes slides use and depend on master notes slide.

```cpp
class MasterNotesSlideHeaderFooterManager : public Aspose::Slides::BaseHandoutNotesSlideHeaderFooterManager,
                                            public Aspose::Slides::IMasterNotesSlideHeaderFooterManager
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | Gibt den Wert zurück, der anzeigt, dass ein Datum-Uhrzeit-Platzhalter vorhanden ist. Lesen **bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | Gibt den Wert zurück, der anzeigt, dass ein Fußzeilen-Platzhalter vorhanden ist. Lesen **bool**. |
| **bool** [get_IsHeaderVisible](../basehandoutnotesslideheaderfootermanager/get_isheadervisible/)() override | Gibt den Wert zurück, der anzeigt, dass ein Kopfzeilen-Platzhalter vorhanden ist. Lesen **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | Gibt den Wert zurück, der anzeigt, dass ein Seitenzahlen-Platzhalter vorhanden ist. Lesen**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das C# lock()-Statement für das Sperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts wirklich, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts wirklich, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | Setzt den Text für den Datum-Uhrzeit-Platzhalter der Master-Folie und alle Kind-Datum-Uhrzeit-Platzhalter. Kind-Platzhalter bedeuten, dass die Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters der Master-Folie und aller Kind-Datum-Uhrzeit-Platzhalter. Kind-Platzhalter bedeuten, dass die Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | Setzt den Text für den Datum-Uhrzeit-Platzhalter der Folie. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | Ändert die Sichtbarkeit des Datum-Uhrzeit-Platzhalters der Folie. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | Setzt den Text für den Fußzeilen-Platzhalter der Master-Folie und alle Kind-Fußzeilen-Platzhalter. Kind-Platzhalter bedeuten, dass die Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | Ändert die Sichtbarkeit des Fußzeilen-Platzhalters der Master-Folie und aller Kind-Fußzeilen-Platzhalter. Kind-Platzhalter bedeuten, dass die Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | Setzt den Text für den Fußzeilen-Platzhalter der Folie. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | Ändert die Sichtbarkeit des Fußzeilen-Platzhalters der Folie. |
| void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) override | Setzt den Text für den Kopfzeilen-Platzhalter der Master-Notizfolie und alle Kind-Kopfzeilen-Platzhalter. Kind-Platzhalter bedeuten, dass die Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab. |
| void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) override | Ändert die Sichtbarkeit des Kopfzeilen-Platzhalters der Master-Notizfolie und aller Kind-Kopfzeilen-Platzhalter. Kind-Platzhalter bedeuten, dass die Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab. |
| void [SetHeaderText](../basehandoutnotesslideheaderfootermanager/setheadertext/)([System::String](../../system/string/)) override | Setzt den Text für den Kopfzeilen-Platzhalter der Folie. |
| void [SetHeaderVisibility](../basehandoutnotesslideheaderfootermanager/setheadervisibility/)(**bool**) override | Ändert die Sichtbarkeit des Kopfzeilen-Platzhalters der Folie. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | Ändert die Sichtbarkeit des Seitenzahl-Platzhalters der Master-Folie und aller Kind-Seitenzahl-Platzhalter. Kind-Platzhalter bedeuten, dass die Platzhalter auf abhängigen Notizfolien enthalten sind. Abhängige Notizfolien verwenden und hängen von der Master-Notizfolie ab. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | Ändert die Sichtbarkeit des Seitenzahl-Platzhalters der Folie. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n'th Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Erlaubt das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des geteilten Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den geteilten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager/)
* Klasse [IMasterNotesSlideHeaderFooterManager](../imasternotesslideheaderfootermanager/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)