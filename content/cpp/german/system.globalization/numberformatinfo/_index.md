---
title: NumberFormatInfo
second_title: Aspose.Slides für C++ API-Referenz
description: "Enthält Informationen darüber, wie Zahlen formatiert werden. Setz-Operationen sind nur bei nicht schreibgeschützten Objekten aktiviert. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 248
url: /de/system.globalization/numberformatinfo/
---
## NumberFormatInfo Klasse

Enthält Informationen darüber, wie Zahlen formatiert werden. Setz-Operationen sind nur bei nicht schreibgeschützten Objekten aktiviert. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/) Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Klont Formatinformationen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Liefert die Anzahl der Dezimalstellen der Währung. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Liefert das Dezimaltrennzeichen der Währung. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Liefert das Gruppentrennzeichen der Währung. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Liefert die Anzahl der Dezimalstellen der Währung pro Gruppe. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Liefert das negative Währungsmuster. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Liefert das positive Währungsmuster. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Liefert das Währungssymbol. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Liefert die vom aktuellen Thread festgelegten kulturabhängigen Zahlenformatinformationen. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | Liefert einen Wert, der angibt, wie die Form einer Ziffer dargestellt wird. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Liefert die kulturunabhängigen Zahlenformatinformationen. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Prüft, ob das Format schreibgeschützt ist. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Liefert das Not-a-Number-Symbol. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | Liefert die Ziffernsymbole (0 bis 9). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Liefert das Symbol für negative Unendlichkeit. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | Liefert das Vorzeichen für negative Zahlen. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Liefert die Anzahl der Dezimalstellen. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Liefert das Dezimaltrennzeichen. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Liefert das Gruppentrennzeichen für Zahlen. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Liefert die Anzahl der Ziffern pro Gruppe. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Liefert das negative Zahlenmuster. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Liefert die Anzahl der Dezimalstellen in Prozentwerten. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Liefert das Dezimaltrennzeichen in Prozentwerten. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Liefert das Gruppentrennzeichen in Prozentwerten. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Liefert die Anzahl der Ziffern pro Prozentwertgruppe. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Liefert das negative Prozentmuster. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Liefert das positive Prozentmuster. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | Liefert das Prozentzeichen. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | Liefert das Promillezeichen. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Liefert das Symbol für positive Unendlichkeit. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | Liefert das Vorzeichen für positive Zahlen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Liefert den Formatter eines bestimmten Typs. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zu C# [Object.GetHashCode()](../../system/object/gethashcode/) Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Liefert den Formatter, der dem Formatprovider zugeordnet ist. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/) Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C# 'is'-Operator. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zu C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [NumberFormatInfo](./numberformatinfo/)() | Standardkonstruktor (invariante [NumberFormatInfo](./)). |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Liefert die schreibgeschützte Version des Formatters. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzählung um den angegebenen Wert. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Setzt die Anzahl der Dezimalstellen der Währung. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | Setzt das Dezimaltrennzeichen der Währung. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | Setzt das Gruppentrennzeichen der Währung. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Setzt die Anzahl der Dezimalstellen der Währung pro Gruppe. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Setzt das negative Währungsmuster. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Setzt das positive Währungsmuster. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | Setzt das Währungssymbol. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | Setzt einen Wert, der festlegt, wie die Form einer Ziffer dargestellt wird. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Setzt das Not-a-Number-Symbol. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Setzt die Ziffernsymbole (0 bis 9). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | Setzt das Symbol für negative Unendlichkeit. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | Setzt das negative Vorzeichen. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Setzt die Anzahl der Dezimalstellen. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | Setzt das Dezimaltrennzeichen. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | Setzt das Gruppentrennzeichen für Zahlen. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Setzt die Anzahl der Ziffern pro Gruppe. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Setzt das negative Zahlenmuster. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Setzt die Anzahl der Dezimalstellen in Prozentwerten. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | Setzt das Dezimaltrennzeichen in Prozentwerten. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | Setzt das Gruppentrennzeichen in Prozentwerten. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Setzt die Anzahl der Ziffern pro Prozentwertgruppe. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Setzt das negative Prozentmuster. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Setzt das positive Prozentmuster. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | Setzt das Prozentzeichen. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | Setzt das Promillezeichen. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | Setzt das Symbol für positive Unendlichkeit. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | Setzt das positive Vorzeichen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf den Schwachmodus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert die gemeinsame Referenzzählung und gibt sie zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zu C# [Object.ToString()](../../system/object/tostring/) Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Klasse [IFormatProvider](../../system/iformatprovider/)
* Klasse [ICloneable](../../system/icloneable/)
* Namensraum [System::Globalization](../)
* Bibliothek [Aspose.Slides](../../)