---
title: TaiwanLunisolarCalendar
second_title: Aspose.Slides für C++ API Referenz
description: "Taiwan lunisolar Kalender. Nicht implementiert. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Packen Sie diese Klasse stets in einen System::SmartPtr-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 339
url: /de/system.globalization/taiwanlunisolarcalendar/
---
## TaiwanLunisolarCalendar Klasse


Taiwan lunisolarkalender. Nicht implementiert. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class TaiwanLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
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
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI-Informationen. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Erstellt eine Kopie des aktuellen Objekts und gibt einen Shared-Pointer darauf zurück. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach C#-[Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Fließkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl sie gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich sind. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Fließkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl sie gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich sind. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | RTTI-Informationen. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Gibt den Index der aktuellen Ära zurück. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Gibt den Wert der aktuellen Ära zurück. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Gibt die Liste der im Kalender vorhandenen Äras zurück. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Prüft, ob der Kalender schreibgeschützt ist. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximaler Zeitpunkt, der vom Kalender unterstützt wird. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimaler Zeitpunkt, der vom Kalender unterstützt wird. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Gibt das letzte Jahr zurück, das mit einer 2-stelligen Darstellung darstellbar ist. |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | Ermittelt den Himmelsstamm. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur des Objekts zurück. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Gibt den Tag des Monats für den angegebenen Zeitpunkt zurück. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Gibt den Wochentag für den angegebenen Zeitpunkt zurück. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Gibt den Tag des Jahres für den angegebenen Zeitpunkt zurück. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Gibt die Anzahl der Tage im angegebenen Monat zurück. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Gibt die Anzahl der Tage im angegebenen Monat zurück. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Gibt die Anzahl der Tage im angegebenen Monat zurück. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Gibt die Anzahl der Tage im angegebenen Jahr zurück. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Gibt die Anzahl der Tage im angegebenen Jahr zurück. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Gibt die Ära für den angegebenen Zeitpunkt zurück. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-[Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Gibt die Stunden für den angegebenen Zeitpunkt zurück. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Gibt den Schaltmonat für das angegebene Jahr zurück. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Gibt den Schaltmonat für das angegebene Jahr zurück. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Gibt den Schaltmonat für das angegebene Jahr zurück. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Gibt die Millisekunden für den angegebenen Zeitpunkt zurück. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Gibt die Minuten für den angegebenen Zeitpunkt zurück. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Gibt den Monat für den angegebenen Zeitpunkt zurück. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Gibt die Anzahl der Monate im angegebenen Jahr zurück. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI-Informationen. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI-Informationen. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Gibt die Sekunden für den angegebenen Zeitpunkt zurück. |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | Gibt das Jahr im Sexagenärzyklus zurück. |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | Gibt den Erdzweig zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C#-[System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Gibt die Kalenderwoche für den angegebenen Zeitpunkt zurück. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Gibt das Jahr für den angegebenen Zeitpunkt zurück. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs ist. Analog zum C#-„is“-Operator. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Prüft, ob der Tag ein Schalttag ist. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Prüft, ob der Tag ein Schalttag ist. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Prüft, ob der Tag ein Schalttag ist. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int) const | Prüft, ob der Monat ein Schaltmonat ist. |
| virtual **bool** [IsLeapMonth](../calendar/isleapmonth/)(int, int, int) const | Prüft, ob der Monat ein Schaltmonat ist. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Prüft, ob das Jahr ein Schaltjahr ist. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Prüft, ob das Jahr ein Schaltjahr ist. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Prüft, ob das Jahr ein Schaltjahr ist. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Prüft Jahr-, Monats-, Tages- und Ära-Werte. |
| void [Lock](../../system/object/lock/)() | Implementiert die C#-lock()-Anweisung. Direkt aufrufen oder das Sentry-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-[Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopier-Konstrukt von abgeleiteten Klassen. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopier-Konstrukt von abgeleiteten Klassen. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Gibt eine schreibgeschützte Version des Kalenders zurück. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleich eines Werttyps mit nullptr nach Referenz. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Setzt das letzte Jahr, das mit einer 2-stelligen Darstellung dargestellt werden kann. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt shared). Ermöglicht das Wechseln von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des gemeinsamen Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
|  [TaiwanLunisolarCalendar](./taiwanlunisolarcalendar/)() | Konstruktor. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Erstellt ein [DateTime](../../system/datetime/)-Objekt aus Komponenten. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Erstellt ein [DateTime](../../system/datetime/)-Objekt aus Komponenten. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Konvertiert das Jahr mithilfe der Eigenschaft TwoDigitYearMax in ein 4-stelliges Jahr. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-[Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Ent-locken der C#-lock()-Anweisung. Direkt aufrufen oder das Sentry-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* Namespace [System::Globalization](../)
* Bibliothek [Aspose.Slides](../../)