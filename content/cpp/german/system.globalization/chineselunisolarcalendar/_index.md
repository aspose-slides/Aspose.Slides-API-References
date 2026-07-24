---
title: ChineseLunisolarCalendar
second_title: Aspose.Slides für C++ API Referenz
description: "Chinesischer lunisolarer Kalender. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse stets in einen System::SmartPtr-Pointer und verwenden Sie diesen Pointer, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 27
url: /de/system.globalization/chineselunisolarcalendar/
---
## ChineseLunisolarCalendar Klasse

Chinesischer lunisolarer Kalender. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mittels operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Pointer und verwenden Sie diesen Pointer, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ChineseLunisolarCalendar : public System::Globalization::EastAsianLunisolarCalendar
```

## Methoden

| Method | Description |
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
|  [ChineseLunisolarCalendar](./chineselunisolarcalendar/)() | Standardkonstruktor. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Erstellt eine Kopie des aktuellen Objekts und gibt einen Shared-Pointer darauf zurück. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte gemäß C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-ähnlichen Vergleich von Gleitkommazahlen, wobei zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-ähnlichen Vergleich von Gleitkommazahlen, wobei zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](../eastasianlunisolarcalendar/get_algorithmtype/)() const override | RTTI-Information. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Liefert den Index der aktuellen Ära. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Liefert den Wert der aktuellen Ära. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Liefert die Liste der im Kalender existierenden Äras. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Prüft, ob der Kalender schreibgeschützt ist. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Maximaler Zeitpunkt, der vom Kalender unterstützt wird. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Minimaler Zeitpunkt, der vom Kalender unterstützt wird. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Liefert das letzte Jahr, das mit einer zweistelligen Angabe dargestellt werden kann. |
| int [GetCelestialStem](../eastasianlunisolarcalendar/getcelestialstem/)(int) const | Liefert den himmlischen Stamm. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Liefert den Tag des Monats für den angegebenen Zeitpunkt. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](../calendar/getdayofweek/)([DateTime](../../system/datetime/)) const | Liefert den Wochentag für den angegebenen Zeitpunkt. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Liefert den Tag des Jahres für den angegebenen Zeitpunkt. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Liefert die Anzahl der Tage im angegebenen Monat. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Liefert die Anzahl der Tage im angegebenen Monat. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Liefert die Anzahl der Tage im angegebenen Monat. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Liefert die Anzahl der Tage im angegebenen Jahr. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Liefert die Anzahl der Tage im angegebenen Jahr. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Liefert die Ära für den angegebenen Zeitpunkt. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Liefert die Stunden für den angegebenen Zeitpunkt. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Liefert den Schaltmonat für das angegebene Jahr. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Liefert den Schaltmonat für das angegebene Jahr. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Liefert den Schaltmonat für das angegebene Jahr. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Liefert die Millisekunden für den angegebenen Zeitpunkt. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Liefert die Minuten für den angegebenen Zeitpunkt. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Liefert den Monat für den angegebenen Zeitpunkt. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Liefert die Anzahl der Monate im angegebenen Jahr. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | RTTI-Information. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | RTTI-Information. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Liefert die Sekunden für den angegebenen Zeitpunkt. |
| virtual int [GetSexagenaryYear](../eastasianlunisolarcalendar/getsexagenaryyear/)([DateTime](../../system/datetime/)) const | Liefert das Jahr im sexagenären Zyklus. |
| int [GetTerrestrialBranch](../eastasianlunisolarcalendar/getterrestrialbranch/)(int) const | Liefert den irdischen Zweig. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Liefert die Kalenderwoche für den angegebenen Zeitpunkt. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Liefert das Jahr für den angegebenen Zeitpunkt. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-„is“-Operator. |
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
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Liefert die schreibgeschützte Version des Kalenders. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisation von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisation von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den Shared-Referenzzähler um den angegebenen Wert. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Setzt das letzte Jahr, das mit einer zweistelligen Angabe dargestellt werden kann. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines Shared-Zeigers). Ermöglicht das Umschalten von Zeigern in Containern in den Schwach-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des Shared-Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den Shared-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den Shared-Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Konstruiert ein [DateTime](../../system/datetime/)-Objekt aus Komponenten. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Konstruiert ein [DateTime](../../system/datetime/)-Objekt aus Komponenten. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Wandelt das Jahr mittels der TwoDigitYearMax-Eigenschaft in ein vierstelliges Jahr um. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Felder

| Field | Description |
| --- | --- |
| static constexpr [ChineseEra](./chineseera/) | Aktuelle chinesische Ära. |

## Siehe auch

* Klasse [EastAsianLunisolarCalendar](../eastasianlunisolarcalendar/)
* Namespace [System::Globalization](../)
* Bibliothek [Aspose.Slides](../../)