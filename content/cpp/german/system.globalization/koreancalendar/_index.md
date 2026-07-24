---
title: KoreanCalendar
second_title: Aspose.Slides für C++ API-Referenz
description: "Koreanischer Kalender. Objekte dieser Klasse sollten nur mit der System::MakeObject() Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 222
url: /de/system.globalization/koreancalendar/
---
## KoreanCalendar Klasse

Koreanischer Kalender. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/) Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs im Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class KoreanCalendar : public System::Globalization::Calendar
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
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit den Semantiken von C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C# Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C# Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaN-Werte als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaN-Werte als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Liefert den Algorithmustyp. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Liefert den Index der aktuellen Ära. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Liefert den Wert der aktuellen Ära. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Liefert eine Liste der im Kalender existierenden Ären. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Prüft, ob der Kalender schreibgeschützt ist. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximaler Zeitpunkt, der vom Kalender unterstützt wird. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimaler Zeitpunkt, der vom Kalender unterstützt wird. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Liefert das letzte Jahr, das mit einer zweistelligen Darstellung dargestellt werden kann. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Liefert den Tag des Monats für den angegebenen Zeitpunkt. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Liefert den Wochentag für den angegebenen Zeitpunkt. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Liefert den Tag des Jahres für den angegebenen Zeitpunkt. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Liefert die Anzahl der Tage in einem bestimmten Monat. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Liefert die Anzahl der Tage in einem bestimmten Monat. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Liefert die Anzahl der Tage in einem bestimmten Monat. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Liefert die Anzahl der Tage in einem bestimmten Jahr. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Liefert die Anzahl der Tage in einem bestimmten Jahr. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Liefert die Anzahl der Tage in einem bestimmten Jahr. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Liefert die Ära für den angegebenen Zeitpunkt. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/) Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Liefert die Stunden für den angegebenen Zeitpunkt. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Liefert den Schaltmonat für das angegebene Jahr. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Liefert den Schaltmonat für das angegebene Jahr. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Liefert den Schaltmonat für das angegebene Jahr. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Liefert Millisekunden für den angegebenen Zeitpunkt. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Liefert Minuten für den angegebenen Zeitpunkt. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Liefert den Monat für den angegebenen Zeitpunkt. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Liefert die Anzahl der Monate im angegebenen Jahr. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI-Informationen. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI-Informationen. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Liefert Sekunden für den angegebenen Zeitpunkt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/) Aufruf. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Liefert die Kalenderwoche für den angegebenen Zeitpunkt. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | Liefert das Jahr für den angegebenen Zeitpunkt. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C# 'is' Operator. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Prüft, ob der Tag ein Schalttag ist. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Prüft, ob der Tag ein Schalttag ist. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Prüft, ob der Tag ein Schalttag ist. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Prüft, ob der Monat ein Schaltmonat ist. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Prüft, ob der Monat ein Schaltmonat ist. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Prüft, ob der Monat ein Schaltmonat ist. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Prüft, ob das Jahr ein Schaltjahr ist. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Prüft, ob das Jahr ein Schaltjahr ist. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Prüft, ob das Jahr ein Schaltjahr ist. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Prüft die Werte von Jahr, Monat, Tag und Ära. |
|  [KoreanCalendar](./koreancalendar/)() | Konstruktor. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock() Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/) Sentry-Objekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Subklassen. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Subklassen. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Liefert die schreibgeschützte Version des Kalenders. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenzvergleicht ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den Shared-Referenzzähler um den angegebenen Wert. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Setzt das letzte Jahr, das mit einer zweistelligen Darstellung dargestellt werden kann. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des Shared-Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den Shared-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den Shared-Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Konstruiert ein [DateTime](../../system/datetime/)-Objekt aus Komponenten. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Konstruiert ein [DateTime](../../system/datetime/)-Objekt aus Komponenten. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Konstruiert ein [DateTime](../../system/datetime/)-Objekt aus Komponenten. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Konvertiert das Jahr in ein vierstelliges Jahr unter Verwendung der TwoDigitYearMax-Eigenschaft. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/) Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/)) Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock() Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/) Sentry-Objekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [KoreanEra](./koreanera/) | Aktuelle koreanische Ära. |

## Siehe Auch

* Klasse [Calendar](../calendar/)
* Namensraum [System::Globalization](../)
* Bibliothek [Aspose.Slides](../../)