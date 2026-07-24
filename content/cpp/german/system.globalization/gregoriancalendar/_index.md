---
title: GregorianCalendar
second_title: Aspose.Slides für C++ API-Referenz
description: "Gregorianischer Kalender. Objekte dieser Klasse sollten nur über die System::MakeObject()-Funktion alloziert werden. Nie eine Instanz dieses Typs auf dem Stack oder mit dem new-Operator erzeugen, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Immer diese Klasse in einen System::SmartPtr-Pointer einwickeln und diesen Zeiger verwenden, um sie als Argument an Funktionen zu übergeben."
type: docs
weight: 131
url: /de/system.globalization/gregoriancalendar/
---
## GregorianCalendar Klasse


Gregorian calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class GregorianCalendar : public System::Globalization::Calendar
```

## Methoden

| Method | Beschreibung |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Fügt dem Zeitpunkt Tage hinzu. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Fügt dem Zeitpunkt Stunden hinzu. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Fügt dem Zeitpunkt Millisekunden hinzu. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Fügt dem Zeitpunkt Minuten hinzu. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Fügt dem Zeitpunkt Monate hinzu. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Fügt dem Zeitpunkt Sekunden hinzu. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Fügt dem Zeitpunkt Wochen hinzu. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Fügt dem Zeitpunkt Jahre hinzu. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | RTTI-Information. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Erstellt eine Kopie des aktuellen Objekts und gibt einen Shared-Pointer darauf zurück. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach den C# [Object.Equals](../../system/object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert C#-ähnlichen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert C#-ähnlichen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Gibt den Algorithmustyp zurück. |
| virtual [GregorianCalendarTypes](../gregoriancalendartypes/) [get_CalendarType](./get_calendartype/)() const | Gibt den GregorianCalendar-Typ zurück. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Gibt den Index der aktuellen Ära zurück. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Gibt den Wert der aktuellen Ära zurück. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Gibt die Liste der im Kalender vorhandenen Äras zurück. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Prüft, ob der Kalender schreibgeschützt ist. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximaler Zeitpunkt, der vom Kalender unterstützt wird. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimaler Zeitpunkt, der vom Kalender unterstützt wird. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Gibt das letzte Jahr zurück, das mit zweistelliger Darstellung dargestellt werden kann. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Gibt den Tag des Monats für den angegebenen Zeitpunkt zurück. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Gibt den Wochentag für den angegebenen Zeitpunkt zurück. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Gibt den Tag des Jahres für den angegebenen Zeitpunkt zurück. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Gibt die Anzahl der Tage im angegebenen Monat zurück. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Gibt die Anzahl der Tage im angegebenen Monat zurück. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Gibt die Anzahl der Tage im angegebenen Monat zurück. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Gibt die Anzahl der Tage im angegebenen Jahr zurück. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Gibt die Anzahl der Tage im angegebenen Jahr zurück. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Gibt die Anzahl der Tage im angegebenen Jahr zurück. |
| static [CalendarPtr](../calendarptr/) [GetDefaultInstance](./getdefaultinstance/)() | Gibt die Standardinstanz des GregorianCalendar zurück. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Gibt die Ära für den angegebenen Zeitpunkt zurück. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Gibt die Stunden für den angegebenen Zeitpunkt zurück. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Gibt den Schaltmonat für das angegebene Jahr zurück. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Gibt den Schaltmonat für das angegebene Jahr zurück. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Gibt den Schaltmonat für das angegebene Jahr zurück. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Gibt die Millisekunden für den angegebenen Zeitpunkt zurück. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Gibt die Minuten für den angegebenen Zeitpunkt zurück. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Gibt den Monat für den angegebenen Zeitpunkt zurück. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Gibt die Anzahl der Monate im angegebenen Jahr zurück. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI-Information. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI-Information. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Gibt die Sekunden für den angegebenen Zeitpunkt zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Gibt die Kalenderwoche für den angegebenen Zeitpunkt zurück. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | Gibt das Jahr für den angegebenen Zeitpunkt zurück. |
|  [GregorianCalendar](./gregoriancalendar/)([GregorianCalendarTypes](../gregoriancalendartypes/)) | Konstruiert einen spezifischen GregorianCalendar. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des von targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Prüft, ob der Tag ein Schalttag ist. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Prüft, ob der Tag ein Schalttag ist. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Prüft, ob der Tag ein Schalttag ist. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Prüft, ob der Monat ein Schaltmonat ist. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Prüft, ob der Monat ein Schaltmonat ist. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Prüft, ob der Monat ein Schaltmonat ist. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Prüft, ob das Jahr ein Schaltjahr ist. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Prüft, ob das Jahr ein Schaltjahr ist. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Prüft, ob das Jahr ein Schaltjahr ist. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Prüft die Werte für Jahr, Monat, Tag und Ära. |
| void [Lock](../../system/object/lock/)() | Implementiert das C#-lock()-Statement zum Sperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopier-Konstruktion von Unterklassen. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopier-Konstruktion von Unterklassen. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Gibt die schreibgeschützte Version des Kalenders zurück. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz einen Werttyp mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den Shared-Referenzzähler um den angegebenen Wert. |
| virtual void [set_CalendarType](./set_calendartype/)([GregorianCalendarTypes](../gregoriancalendartypes/)) | Setzt den GregorianCalendar-Typ. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Setzt das letzte Jahr, das mit zweistelliger Darstellung dargestellt werden kann. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern auf Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des Shared-Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den Shared-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den Shared-Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Konstruiert ein [DateTime](../../system/datetime/)-Objekt aus Komponenten. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Konstruiert ein [DateTime](../../system/datetime/)-Objekt aus Komponenten. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Konstruiert ein [DateTime](../../system/datetime/)-Objekt aus Komponenten. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Wandelt das Jahr mithilfe der TwoDigitYearMax-Eigenschaft in ein vierstelliges Jahr um. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das C#-lock()-Statement zum Entsperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [ADEra](./adera/) | Aktuelle Ära. |

## Siehe auch

* Klasse [Calendar](../calendar/)
* Namensraum [System::Globalization](../)
* Bibliothek [Aspose.Slides](../../)