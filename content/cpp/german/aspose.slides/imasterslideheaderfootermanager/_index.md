---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides für C++ API Referenz
description: Stellt einen Manager dar, der das Verhalten des Fußzeilen-Platzhalters der Master-Folie, des Datums-Zeit-Platzhalters, des Seitenzahlen-Platzhalters und aller untergeordneten Platzhalter verwaltet. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Master-Folie ab.
type: docs
weight: 2952
url: /de/aspose.slides/imasterslideheaderfootermanager/
---
## IMasterSlideHeaderFooterManager Klasse


Stellt einen Manager dar, der das Verhalten des Fußzeilen-Platzhalters der Master-Folien, des Datums-Zeit-Platzhalters, des Seitenzahlen-Platzhalters und aller untergeordneten Platzhalter verwaltet. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Master-Folie ab.

```cpp
class IMasterSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseSlideHeaderFooterManager
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Fließkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Fließkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | Liefert einen Wert, der anzeigt, dass ein Datums-Zeit-Platzhalter vorhanden ist. Read**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | Liefert einen Wert, der anzeigt, dass ein Fußzeilen-Platzhalter vorhanden ist. Read **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | Liefert einen Wert, der anzeigt, dass ein Seitenzahlen-Platzhalter vorhanden ist. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähl-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsam genutzte Referenzzähler um den angegebenen Wert. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | Setzt den Text des Datums-Zeit-Platzhalters der Master-Folie und aller untergeordneten Datums-Zeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Master-Folie ab. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | Ändert die Sichtbarkeit des Datums-Zeit-Platzhalters der Master-Folie und aller untergeordneten Datums-Zeit-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Master-Folie ab. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | Setzt den Text des Datums-Zeit-Platzhalters der Folie. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | Ändert die Sichtbarkeit des Datums-Zeit-Platzhalters der Folie. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | Setzt den Text des Fußzeilen-Platzhalters der Master-Folie und aller untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Master-Folie ab. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | Ändert die Sichtbarkeit des Fußzeilen-Platzhalters der Master-Folie und aller untergeordneten Fußzeilen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Master-Folie ab. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | Setzt den Text des Fußzeilen-Platzhalters der Folie. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | Ändert die Sichtbarkeit des Fußzeilen-Platzhalters der Folie. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | Ändert die Sichtbarkeit des Seitenzahlen-Platzhalters der Master-Folie und aller untergeordneten Seitenzahlen-Platzhalter. Untergeordnete Platzhalter bedeuten, dass Platzhalter auf abhängigen Layout-Folien und abhängigen Folien enthalten sind. Abhängige Layout-Folien und Folien verwenden und hängen von der Master-Folie ab. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | Ändert die Sichtbarkeit des Seitenzahlen-Platzhalters der Folie. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines gemeinsam genutzten). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des gemeinsam genutzten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsam genutzten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsam genutzten Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert die C#-Konstruktion typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IBaseSlideHeaderFooterManager](../ibaseslideheaderfootermanager/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)