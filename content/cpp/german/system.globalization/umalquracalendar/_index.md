---
title: UmAlQuraCalendar
second_title: Aspose.Slides für C++ API-Referenz
description: "Um Al Qura-Kalender. Nicht implementiert. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 391
url: /de/system.globalization/umalquracalendar/
---
## UmAlQuraCalendar Klasse

Um Al Qura-Kalender. Nicht implementiert. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class UmAlQuraCalendar : public System::Globalization::Calendar
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Fügt dem Zeitpunkt Tage hinzu. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Fügt dem Zeitpunkt Stunden hinzu. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Fügt dem Zeitpunkt Millisekunden hinzu. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Fügt dem Zeitpunkt Minuten hinzu. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Fügt dem Zeitpunkt Monate hinzu. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Fügt dem Zeitpunkt Sekunden hinzu. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Fügt dem Zeitpunkt Wochen hinzu. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Fügt dem Zeitpunkt Jahre hinzu. |
| [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI-Information. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Erstellt eine Kopie des aktuellen Objekts und gibt einen Shared-Pointer darauf zurück. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Ermittelt den Algorithmustyp. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Ermittelt den Index der aktuellen Ära. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Ermittelt den Wert der aktuellen Ära. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Ermittelt die Liste der im Kalender vorhandenen Ären. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Prüft, ob der Kalender schreibgeschützt ist. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximaler Zeitpunkt, der vom Kalender unterstützt wird. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimaler Zeitpunkt, der vom Kalender unterstützt wird. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Ermittelt das letzte Jahr, das mit einer zweistelligen Darstellung dargestellt werden kann. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Ermittelt den Tag des Monats für den angegebenen Zeitpunkt. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Ermittelt den Wochentag für den angegebenen Zeitpunkt. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Ermittelt den Tag des Jahres für den angegebenen Zeitpunkt. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Ermittelt die Anzahl der Tage im angegebenen Monat. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Ermittelt die Anzahl der Tage im angegebenen Monat. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Ermittelt die Anzahl der Tage im angegebenen Jahr. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Ermittelt die Anzahl der Tage im angegebenen Jahr. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Ermittelt die Ära für den angegebenen Zeitpunkt. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-[Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Ermittelt die Stunden für den angegebenen Zeitpunkt. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Ermittelt den Schaltmonat für das angegebene Jahr. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | RTTI-Information. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | RTTI-Information. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Ermittelt die Millisekunden für den angegebenen Zeitpunkt. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Ermittelt die Minuten für den angegebenen Zeitpunkt. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Ermittelt den Monat für den angegebenen Zeitpunkt. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Ermittelt die Anzahl der Monate im angegebenen Jahr. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Ermittelt die Anzahl der Monate im angegebenen Jahr. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Ermittelt die Sekunden für den angegebenen Zeitpunkt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-[System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Ermittelt die Kalenderwoche für den angegebenen Zeitpunkt. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Ermittelt das Jahr für den angegebenen Zeitpunkt. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs ist. Analog zum C#-„is“-Operator. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Prüft, ob der Tag ein Schaltjahr-Tag ist. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Prüft, ob der Tag ein Schaltjahr-Tag ist. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Prüft, ob der Tag ein Schaltjahr-Tag ist. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Prüft, ob der Monat ein Schaltmonat ist. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Prüft, ob der Monat ein Schaltmonat ist. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Prüft, ob der Monat ein Schaltmonat ist. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Prüft, ob das Jahr ein Schaltjahr ist. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Prüft, ob das Jahr ein Schaltjahr ist. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Prüft, ob das Jahr ein Schaltjahr ist. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Prüft die Werte von Jahr, Monat, Tag und Ära. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-[Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Ermittelt die schreibgeschützte Version des Kalenders. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenzvergleicht Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) override | Setzt das letzte Jahr, das mit einer zweistelligen Darstellung dargestellt werden kann. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Konstruiert ein [DateTime](../../system/datetime/)-Objekt aus Komponenten. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Konstruiert ein [DateTime](../../system/datetime/)-Objekt aus Komponenten. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Konvertiert das Jahr mittels TwoDigitYearMax-Eigenschaft in ein vierstelliges Jahr. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-[Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstruktor. |
| [UmAlQuraCalendar](./umalquracalendar/)() | Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [UmAlQuraEra](./umalquraera/) | Aktuelle UmAlQura-Ära. |

## Siehe Auch

* Klasse [Calendar](../calendar/)
* Namensraum [System::Globalization](../)
* Bibliothek [Aspose.Slides](../../)