---
title: Regex
second_title: Aspose.Slides für C++ API Referenz
description: "Regulärer Ausdruck, der einer C#-ähnlichen Syntax folgt. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Pointer ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 92
url: /de/system.text.regularexpressions/regex/
---
## Regex-Klasse

Regulärer Ausdruck, der einer C#-ähnlichen Syntax folgt. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Immer diese Klasse in einen [System::SmartPtr](../../system/smartptr/)-Pointer einwickeln und diesen Zeiger verwenden, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Regex : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich gelten, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschliesslich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich gelten, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschliesslich NaN, gleich ist. |
| static [String](../../system/string/) [Escape](./escape/)(const [String](../../system/string/)\&) | Maskiert Sonderzeichen, um die Zeichenkette als Teil des Musters zu verwenden. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [TimeSpan](../../system/timespan/) [get_MatchTimeout](./get_matchtimeout/)() | Ruft das Matching-Zeitlimit ab. |
| [RegexOptions](../regexoptions/) [get_Options](./get_options/)() | Ruft die Regex-Optionen ab. |
| **bool** [get_RightToLeft](./get_righttoleft/)() | Prüft, ob das Matching im Rechts-nach-Links-Modus durchgeführt wird. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Referenzzähler-Datenstruktur ab, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| **bool** [IsMatch](./ismatch/)(const [String](../../system/string/)\&, int) | Prüft das Regex gegen die Zeichenkette. |
| static **bool** [IsMatch](./ismatch/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int) | Prüft, ob die Zeichenkette dem Muster entspricht. |
| void [Lock](../../system/object/lock/)() | Implementiert das C#-lock()-Statement zum Sperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&) | Prüft das Regex gegen die Zeichenkette. |
| [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&, int, int) | Prüft das Regex gegen die Zeichenkette. |
| static [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int, int) | Prüft das Regex gegen die Zeichenkette. |
| [MatchCollectionPtr](../matchcollectionptr/) [Matches](./matches/)(const [String](../../system/string/)\&, int) | Ermittelt alle Übereinstimmungen des Regex in der angegebenen Zeichenkette durch wiederholtes Matching. |
| static [MatchCollectionPtr](../matchcollectionptr/) [Matches](./matches/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int, int) | Ermittelt alle Übereinstimmungen zwischen Zeichenkette und Muster. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
|  [Regex](./regex/)() | Konstruiert ein leeres Regex. |
|  [Regex](./regex/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [Regex](./regex/)(const [String](../../system/string/)\&, [RegexOptions](../regexoptions/)) | Konstruktor. |
|  [Regex](./regex/)(const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | Konstruktor. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ersetzt alle Übereinstimmungen des Regex in der Zeichenkette durch die Ersetzungszeichenkette. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const char_t *) | Ersetzt alle Übereinstimmungen des Regex in der Zeichenkette durch die Ersetzungszeichenkette. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const char_t *, const char_t *) | Ersetzt alle Übereinstimmungen des Regex in der Zeichenkette durch die Ersetzungszeichenkette. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const char_t *) | Ersetzt alle Übereinstimmungen des Regex in der Zeichenkette durch die Ersetzungszeichenkette. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&) | Ersetzt alle Übereinstimmungen in der Zeichenkette durch delegatgenerierte Ersetzungszeichenketten. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, int) | Ersetzt alle Übereinstimmungen in der Zeichenkette durch delegatgenerierte Ersetzungszeichenketten. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, int, int) | Ersetzt alle Übereinstimmungen in der Zeichenkette durch delegatgenerierte Ersetzungszeichenketten. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, [RegexOptions](../regexoptions/)) | Ersetzt alle Übereinstimmungen in der Zeichenkette durch delegatgenerierte Ersetzungszeichenketten (statische Funktion). |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/)) | Ersetzt alle Übereinstimmungen des Regex in der Zeichenkette durch die Ersetzungszeichenkette. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) | Ersetzt Teilzeichenketten in der Zeichenkette. Nicht implementiert. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Ersetzt Teilzeichenketten in der Zeichenkette. Nicht implementiert. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ersetzt Regex-Übereinstimmungen. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&) | Ersetzt Regex-Übereinstimmungen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointer oder ThisProtector verwenden. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&) | Teilt die Zeichenkette anhand von Regex-Übereinstimmungen. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, int) | Teilt die Zeichenkette anhand von Regex-Übereinstimmungen. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, int, int) | Teilt eine Eingabezeichenkette bis zu einer angegebenen maximalen Anzahl von Malen in ein Array von Teilzeichenketten, an den Positionen, die durch einen im [Regex](./)-Konstruktor angegebenen regulären Ausdruck definiert sind. Die Suche nach dem regulären Ausdruck beginnt an einer angegebenen Zeichenposition in der Eingabezeichenkette. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | Teilt die Zeichenkette anhand von Regexp. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | Teilt die Zeichenkette anhand von Regexp. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Konvertiert das Regex in eine Zeichenkette. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| static [String](../../system/string/) [Unescape](./unescape/)(const [String](../../system/string/)\&) | Entmaskiert Sonderzeichen in der als Teil des Musters verwendeten Zeichenkette. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [InfiniteMatchTimeout](./infinitematchtimeout/) | Spezieller Timeout-Wert, um das Unterbrechen des Matching durch Timeout zu deaktivieren. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Text::RegularExpressions](../)
* Bibliothek [Aspose.Slides](../../)