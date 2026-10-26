---
title: Convert
second_title: Aspose.Slides für C++ API-Referenz
description: "Die Struktur, die Methoden enthält, die die Konvertierung von Werten eines Typs zu den Werten eines anderen Typs durchführen. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse System::SmartPtr, um Objekte dieses Typs zu verwalten."
type: docs
weight: 1561
url: /de/system/convert/
---
## Konvertierungsstruktur

Die Struktur, die Methoden zur Konvertierung von Werten eines Typs in Werte eines anderen Typs enthält. Dieser Typ sollte auf dem Stack zugewiesen und Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die Klasse [System::SmartPtr](../smartptr/) zur Verwaltung von Objekten dieses Typs.

```cpp
class Convert
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&) | NICHT IMPLEMENTIERT. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ChangeType](./changetype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64CharArray](./frombase64chararray/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Dekodiert Base-64-kodierte Daten, die als Bereich im Array von Unicode-Zeichen dargestellt werden. |
| static [ArrayPtr](../arrayptr/)\<**uint8_t**\> [FromBase64String](./frombase64string/)(const [String](../string/)\&) | Dekodiert Base-64-kodierte Daten, die als Zeichenkette dargestellt werden. |
| static [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Gibt einen TypeCode-Wert zurück, der den Typ des angegebenen gekapselten Werts darstellt. |
| static std::enable_if_t<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\> [IsDBNull](./isdbnull/)(const T\&) | NICHT IMPLEMENTIERT. |
| static **bool** [IsDBNull](./isdbnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | NICHT IMPLEMENTIERT Fake-Implementierung, prüft, ob der Wert nullptr ist. |
| static Target [To](./to/)(const Source\&) |  |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, **bool**) | Base-64 kodiert einen Bereich von Elementen im angegebenen Byte-Array und speichert die kodierten Daten als Array von Unicode-Zeichen. |
| static int [ToBase64CharArray](./tobase64chararray/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, [Base64FormattingOptions](../base64formattingoptions/)) | Base-64 kodiert einen Bereich von Elementen im angegebenen Byte-Array und speichert die kodierten Daten als Array von Unicode-Zeichen. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**) | Base-64 kodiert Elemente im angegebenen Byte-Array und gibt die kodierten Daten als Zeichenkette zurück. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, **bool**) | Base-64 kodiert einen Bereich von Elementen im angegebenen Byte-Array und gibt die kodierten Daten als Zeichenkette zurück. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, [Base64FormattingOptions](../base64formattingoptions/)) | Base-64 kodiert Elemente im angegebenen Byte-Array und gibt die kodierten Daten als Zeichenkette zurück. |
| static [String](../string/) [ToBase64String](./tobase64string/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int, [Base64FormattingOptions](../base64formattingoptions/)) | Base-64 kodiert einen Bereich von Elementen im angegebenen Byte-Array und gibt die kodierten Daten als Zeichenkette zurück. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**bool**) | Gibt den angegebenen booleschen Wert zurück. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint8_t**) | Konvertiert die angegebene 8-Bit-Unsigned-Integer in einen äquivalenten booleschen Wert. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int8_t**) | Konvertiert die angegebene 8-Bit-Signed-Integer in einen äquivalenten booleschen Wert. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint16_t**) | Konvertiert die angegebene 16-Bit-Unsigned-Integer in einen äquivalenten booleschen Wert. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int16_t**) | Konvertiert die angegebene 16-Bit-Signed-Integer in einen äquivalenten booleschen Wert. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint32_t**) | Konvertiert die angegebene 32-Bit-Unsigned-Integer in einen äquivalenten booleschen Wert. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int32_t**) | Konvertiert die angegebene 32-Bit-Signed-Integer in einen äquivalenten booleschen Wert. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**uint64_t**) | Konvertiert die angegebene 64-Bit-Unsigned-Integer in einen äquivalenten booleschen Wert. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**int64_t**) | Konvertiert die angegebene 64-Bit-Signed-Integer in einen äquivalenten booleschen Wert. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**float**) | Konvertiert die angegebene Fließkommazahl in einen äquivalenten booleschen Wert. |
| static constexpr **bool** [ToBoolean](./toboolean/)(**double**) | Konvertiert die angegebene Double-Zahl in einen äquivalenten booleschen Wert. |
| static **bool** [ToBoolean](./toboolean/)(const [Decimal](../decimal/)\&) | Konvertiert die angegebene Dezimalzahl in einen äquivalenten booleschen Wert. |
| static **bool** [ToBoolean](./toboolean/)(char_t) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static **bool** [ToBoolean](./toboolean/)([DateTime](../datetime/)) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static constexpr **bool** [ToBoolean](./toboolean/)(std::nullptr_t) | Konvertiert die angegebene Null-Zeichenkette in den entsprechenden booleschen Wert. |
| static **bool** [ToBoolean](./toboolean/)(const char_t *) | Konvertiert die angegebene C-Zeichenkette in den bool-Wert. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette in den bool-Wert. |
| static **bool** [ToBoolean](./toboolean/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette in den bool-Wert. |
| static **bool** [ToBoolean](./toboolean/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen gekapselten Wert in einen äquivalenten booleschen Wert. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**bool**) | Konvertiert den angegebenen booleschen Wert in ein äquivalentes 8-Bit-Unsigned-Integer. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(**uint8_t**) | Gibt das angegebene 8-Bit-Unsigned-Integer zurück. |
| static **uint8_t** [ToByte](./tobyte/)(**int8_t**) | Konvertiert die angegebene 8-Bit-Signed-Integer in ein äquivalentes 8-Bit-Unsigned-Integer. |
| static **uint8_t** [ToByte](./tobyte/)(**uint16_t**) | Konvertiert die angegebene 16-Bit-Unsigned-Integer in ein äquivalentes 8-Bit-Unsigned-Integer. |
| static **uint8_t** [ToByte](./tobyte/)(**int16_t**) | Konvertiert die angegebene 16-Bit-Signed-Integer in ein äquivalentes 8-Bit-Unsigned-Integer. |
| static **uint8_t** [ToByte](./tobyte/)(**uint32_t**) | Konvertiert die angegebene 32-Bit-Unsigned-Integer in ein äquivalentes 8-Bit-Unsigned-Integer. |
| static **uint8_t** [ToByte](./tobyte/)(**int32_t**) | Konvertiert die angegebene 32-Bit-Signed-Integer in ein äquivalentes 8-Bit-Unsigned-Integer. |
| static **uint8_t** [ToByte](./tobyte/)(**uint64_t**) | Konvertiert die angegebene 64-Bit-Unsigned-Integer in ein äquivalentes 8-Bit-Unsigned-Integer. |
| static **uint8_t** [ToByte](./tobyte/)(**int64_t**) | Konvertiert die angegebene 64-Bit-Signed-Integer in ein äquivalentes 8-Bit-Unsigned-Integer. |
| static **uint8_t** [ToByte](./tobyte/)(**float**) | Konvertiert die angegebene Fließkommazahl in ein äquivalentes 8-Bit-Unsigned-Integer. |
| static **uint8_t** [ToByte](./tobyte/)(**double**) | Konvertiert die angegebene Double-Zahl in ein äquivalentes 8-Bit-Unsigned-Integer. |
| static **uint8_t** [ToByte](./tobyte/)(const [Decimal](../decimal/)\&) | Konvertiert die angegebene Dezimalzahl in ein äquivalentes 8-Bit-Unsigned-Integer. |
| static **uint8_t** [ToByte](./tobyte/)(char_t) | Konvertiert das angegebene Unicode-Zeichen in ein äquivalentes 8-Bit-Unsigned-Integer. |
| static **uint8_t** [ToByte](./tobyte/)([DateTime](../datetime/)) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static constexpr **uint8_t** [ToByte](./tobyte/)(std::nullptr_t) | Konvertiert die angegebene Null-Zeichenkette in den entsprechenden unsigned 8-Bit-Integer-Wert. |
| static **uint8_t** [ToByte](./tobyte/)(const char_t *) | Konvertiert die angegebene C-Zeichenkette, die die Zahlendarstellung enthält, in den entsprechenden unsigned 8-Bit-Integer-Wert. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die Zahlendarstellung enthält, in den entsprechenden unsigned 8-Bit-Integer-Wert. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, int) | Konvertiert die angegebene Zeichenkette, die die Zahlendarstellung in der angegebenen Basis enthält, in den entsprechenden unsigned 8-Bit-Integer-Wert. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zahlendarstellung enthält, mittels der bereitgestellten Formatierungsinformationen in den entsprechenden unsigned 8-Bit-Integer-Wert. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zahlendarstellung enthält, mittels der bereitgestellten Formatierungsinformationen und des Zahlen-Stils in den entsprechenden unsigned 8-Bit-Integer-Wert. |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint8_t** [ToByte](./tobyte/)([Enum](../enum/)) |  |
| static **uint8_t** [ToByte](./tobyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen gekapselten Wert in einen äquivalenten unsigned 8-Bit-Integer-Wert. |
| static char_t [ToChar](./tochar/)(**bool**) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(**uint8_t**) | Konvertiert das angegebene 8-Bit-Unsigned-Integer in ein äquivalentes Unicode-Zeichen. |
| static char_t [ToChar](./tochar/)(**int8_t**) | Konvertiert das angegebene 8-Bit-Signed-Integer in ein äquivalentes Unicode-Zeichen. |
| static constexpr char_t [ToChar](./tochar/)(**uint16_t**) | Konvertiert das angegebene 16-Bit-Unsigned-Integer in ein äquivalentes Unicode-Zeichen. |
| static char_t [ToChar](./tochar/)(**int16_t**) | Konvertiert das angegebene 16-Bit-Signed-Integer in ein äquivalentes Unicode-Zeichen. |
| static char_t [ToChar](./tochar/)(**uint32_t**) | Konvertiert das angegebene 32-Bit-Unsigned-Integer in ein äquivalentes Unicode-Zeichen. |
| static char_t [ToChar](./tochar/)(**int32_t**) | Konvertiert das angegebene 32-Bit-Signed-Integer in ein äquivalentes Unicode-Zeichen. |
| static char_t [ToChar](./tochar/)(**uint64_t**) | Konvertiert das angegebene 64-Bit-Unsigned-Integer in ein äquivalentes Unicode-Zeichen. |
| static char_t [ToChar](./tochar/)(**int64_t**) | Konvertiert das angegebene 64-Bit-Signed-Integer in ein äquivalentes Unicode-Zeichen. |
| static char_t [ToChar](./tochar/)(**float**) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static char_t [ToChar](./tochar/)(**double**) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static char_t [ToChar](./tochar/)(const [Decimal](../decimal/)\&) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static constexpr char_t [ToChar](./tochar/)(char_t) | Gibt das angegebene Unicode-Zeichen zurück. |
| static char_t [ToChar](./tochar/)([DateTime](../datetime/)) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static char_t [ToChar](./tochar/)(const char_t *) | Konvertiert das erste und einzige Zeichen der angegebenen C-Zeichenkette in einen char_t-Wert. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&) | Konvertiert das erste und einzige Zeichen der angegebenen Zeichenkette in einen char_t-Wert. |
| static char_t [ToChar](./tochar/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert das erste und einzige Zeichen der angegebenen Zeichenkette in einen char_t-Wert. |
| static char_t [ToChar](./tochar/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen gekapselten Wert in ein äquivalentes Unicode-Zeichen. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**bool**) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint8_t**) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int8_t**) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint16_t**) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int16_t**) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint32_t**) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int32_t**) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**uint64_t**) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**int64_t**) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**float**) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(**double**) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [Decimal](../decimal/)\&) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(char_t) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static constexpr [DateTime](../datetime/) [ToDateTime](./todatetime/)([DateTime](../datetime/)) | Gibt das angegebene Datum und die Uhrzeit zurück. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette in eine Instanz der Klasse [DateTime](../datetime/). |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette in eine Instanz der Klasse [DateTime](../datetime/) unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [DateTime](../datetime/) [ToDateTime](./todatetime/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen geboxten Wert in den entsprechenden [DateTime](../datetime/)-Wert. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**bool**) | Konvertiert den angegebenen booleschen Wert in eine äquivalente Dezimalzahl. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint8_t**) | Konvertiert die angegebene 8-Bit-vorzeichenlose Ganzzahl in eine äquivalente Dezimalzahl. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int8_t**) | Konvertiert die angegebene 8-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente Dezimalzahl. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint16_t**) | Konvertiert die angegebene 16-Bit-vorzeichenlose Ganzzahl in eine äquivalente Dezimalzahl. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int16_t**) | Konvertiert die angegebene 16-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente Dezimalzahl. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint32_t**) | Konvertiert die angegebene 32-Bit-vorzeichenlose Ganzzahl in eine äquivalente Dezimalzahl. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int32_t**) | Konvertiert die angegebene 32-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente Dezimalzahl. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**uint64_t**) | Konvertiert die angegebene 64-Bit-vorzeichenlose Ganzzahl in eine äquivalente Dezimalzahl. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**int64_t**) | Konvertiert die angegebene 64-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente Dezimalzahl. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**float**) | Konvertiert die angegebene Float-Zahl in eine äquivalente Dezimalzahl. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(**double**) | Konvertiert die angegebene Double-Zahl in eine äquivalente Dezimalzahl. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [Decimal](../decimal/)\&) | Gibt die angegebene Dezimalzahl zurück. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(char_t) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)([DateTime](../datetime/)) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(std::nullptr_t) | Konvertiert die angegebene Nullzeichenkette in den entsprechenden [Decimal](../decimal/)-Wert. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const char_t *) | Konvertiert die angegebene C-Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden [Decimal](../decimal/)-Wert. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden [Decimal](../decimal/)-Wert. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden [Decimal](../decimal/)-Wert unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden [Decimal](../decimal/)-Wert unter Verwendung der angegebenen Zahlenformate und Formatierungsinformationen. |
| static [Decimal](../decimal/) [ToDecimal](./todecimal/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen geboxten Wert in den entsprechenden [Decimal](../decimal/)-Wert. |
| static constexpr **double** [ToDouble](./todouble/)(**bool**) | Konvertiert den angegebenen booleschen Wert in eine äquivalente double-Genau-Gleitkommazahl. |
| static constexpr **double** [ToDouble](./todouble/)(**uint8_t**) | Konvertiert die angegebene 8-Bit-vorzeichenlose Ganzzahl in eine äquivalente double-Genau-Gleitkommazahl. |
| static constexpr **double** [ToDouble](./todouble/)(**int8_t**) | Konvertiert die angegebene 8-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente double-Genau-Gleitkommazahl. |
| static constexpr **double** [ToDouble](./todouble/)(**uint16_t**) | Konvertiert die angegebene 16-Bit-vorzeichenlose Ganzzahl in eine äquivalente double-Genau-Gleitkommazahl. |
| static constexpr **double** [ToDouble](./todouble/)(**int16_t**) | Konvertiert die angegebene 16-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente double-Genau-Gleitkommazahl. |
| static constexpr **double** [ToDouble](./todouble/)(**uint32_t**) | Konvertiert die angegebene 32-Bit-vorzeichenlose Ganzzahl in eine äquivalente double-Genau-Gleitkommazahl. |
| static constexpr **double** [ToDouble](./todouble/)(**int32_t**) | Konvertiert die angegebene 32-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente double-Genau-Gleitkommazahl. |
| static constexpr **double** [ToDouble](./todouble/)(**uint64_t**) | Konvertiert die angegebene 64-Bit-vorzeichenlose Ganzzahl in eine äquivalente double-Genau-Gleitkommazahl. |
| static constexpr **double** [ToDouble](./todouble/)(**int64_t**) | Konvertiert die angegebene 64-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente double-Genau-Gleitkommazahl. |
| static constexpr **double** [ToDouble](./todouble/)(**float**) | Konvertiert die angegebene Float-Zahl in eine äquivalente double-Genau-Gleitkommazahl. |
| static constexpr **double** [ToDouble](./todouble/)(**double**) | Gibt die angegebene Double-Zahl zurück. |
| static **double** [ToDouble](./todouble/)(const [Decimal](../decimal/)\&) | Konvertiert die angegebene Dezimalzahl in eine äquivalente double-Genau-Gleitkommazahl. |
| static **double** [ToDouble](./todouble/)(char_t) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static **double** [ToDouble](./todouble/)([DateTime](../datetime/)) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static constexpr **double** [ToDouble](./todouble/)(std::nullptr_t) | Konvertiert die angegebene Nullzeichenkette in den entsprechenden double-Genau-Gleitkommawert. |
| static **double** [ToDouble](./todouble/)(const char_t *) | Konvertiert die angegebene C-Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden double-Genau-Gleitkommawert. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden double-Genau-Gleitkommawert. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden double-Genau-Gleitkommawert unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden double-Genau-Gleitkommawert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenformats. |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [ToDouble](./todouble/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **double** [ToDouble](./todouble/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen geboxten Wert in einen double-Genau-Gleitkommawert. Falls der Typ des geboxten Werts [String](../string/) ist, wird das angegebene Zeichenkettenformat während der Konvertierung verwendet. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**bool**) | Konvertiert den angegebenen booleschen Wert in eine äquivalente 16-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**uint8_t**) | Konvertiert die angegebene 8-Bit-vorzeichenlose Ganzzahl in eine äquivalente 16-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int8_t**) | Konvertiert die angegebene 8-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente 16-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int16_t** [ToInt16](./toint16/)(**uint16_t**) | Konvertiert die angegebene 16-Bit-vorzeichenlose Ganzzahl in eine äquivalente 16-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr **int16_t** [ToInt16](./toint16/)(**int16_t**) | Gibt die angegebene 16-Bit-vorzeichenbehaftete Ganzzahl zurück. |
| static **int16_t** [ToInt16](./toint16/)(**uint32_t**) | Konvertiert die angegebene 32-Bit-vorzeichenlose Ganzzahl in eine äquivalente 16-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int16_t** [ToInt16](./toint16/)(**int32_t**) | Konvertiert die angegebene 32-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente 16-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int16_t** [ToInt16](./toint16/)(**uint64_t**) | Konvertiert die angegebene 64-Bit-vorzeichenlose Ganzzahl in eine äquivalente 16-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int16_t** [ToInt16](./toint16/)(**int64_t**) | Konvertiert die angegebene 64-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente 16-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int16_t** [ToInt16](./toint16/)(**float**) | Konvertiert die angegebene Float-Zahl in eine äquivalente 16-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int16_t** [ToInt16](./toint16/)(**double**) | Konvertiert die angegebene Double-Zahl in eine äquivalente 16-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int16_t** [ToInt16](./toint16/)(const [Decimal](../decimal/)\&) | Konvertiert die angegebene Dezimalzahl in eine äquivalente 16-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int16_t** [ToInt16](./toint16/)(char_t) | Konvertiert das angegebene Unicode-Zeichen in eine äquivalente 16-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int16_t** [ToInt16](./toint16/)([DateTime](../datetime/)) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static constexpr **int16_t** [ToInt16](./toint16/)(std::nullptr_t) | Konvertiert die angegebene Nullzeichenkette in den entsprechenden 16-Bit-Ganzzahlwert. |
| static **int16_t** [ToInt16](./toint16/)(const char_t *) | Konvertiert die angegebene C-Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden 16-Bit-Ganzzahlwert. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden 16-Bit-Ganzzahlwert. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, int) | Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl in der angegebenen Basis enthält, in den entsprechenden 16-Bit-Ganzzahlwert. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden 16-Bit-Ganzzahlwert unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenfolgendarstellung einer Zahl enthält, in den entsprechenden 16-Bit-Ganzzahlwert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenformats. |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int16_t** [ToInt16](./toint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int16_t** [ToInt16](./toint16/)([Enum](../enum/)) |  |
| static **int16_t** [ToInt16](./toint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen geboxten Wert in einen äquivalenten 16-Bit-Ganzzahlwert. |
| static constexpr int [ToInt32](./toint32/)(**bool**) | Konvertiert den angegebenen booleschen Wert in eine äquivalente 32-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr int [ToInt32](./toint32/)(**uint8_t**) | Konvertiert die angegebene 8-Bit-vorzeichenlose Ganzzahl in eine äquivalente 32-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr int [ToInt32](./toint32/)(**int8_t**) | Konvertiert die angegebene 8-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente 32-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr int [ToInt32](./toint32/)(**uint16_t**) | Konvertiert die angegebene 16-Bit-vorzeichenlose Ganzzahl in eine äquivalente 32-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr int [ToInt32](./toint32/)(**int16_t**) | Konvertiert die angegebene 16-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente 32-Bit-vorzeichenbehaftete Ganzzahl. |
| static int [ToInt32](./toint32/)(**uint32_t**) | Konvertiert die angegebene 32-Bit-vorzeichenlose Ganzzahl in eine äquivalente 32-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr int [ToInt32](./toint32/)(**int32_t**) | Gibt die angegebene 32-Bit-vorzeichenbehaftete Ganzzahl zurück. |
| static int [ToInt32](./toint32/)(**uint64_t**) | Konvertiert die angegebene 64-Bit-vorzeichenlose Ganzzahl in eine äquivalente 32-Bit-vorzeichenbehaftete Ganzzahl. |
| static int [ToInt32](./toint32/)(**int64_t**) | Konvertiert die angegebene 64-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente 32-Bit-vorzeichenbehaftete Ganzzahl. |
| static int [ToInt32](./toint32/)(**float**) | Konvertiert die angegebene float-Zahl in eine äquivalente 32-Bit-vorzeichenbehaftete Ganzzahl. |
| static int [ToInt32](./toint32/)(**double**) | Konvertiert die angegebene double-Zahl in eine äquivalente 32-Bit-vorzeichenbehaftete Ganzzahl. |
| static int [ToInt32](./toint32/)(const [Decimal](../decimal/)\&) | Konvertiert die angegebene Dezimalzahl in eine äquivalente 32-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr int [ToInt32](./toint32/)(char_t) | Konvertiert das angegebene Unicode-Zeichen in eine äquivalente 32-Bit-vorzeichenbehaftete Ganzzahl. |
| static int [ToInt32](./toint32/)([DateTime](../datetime/)) | Konvertierung wird nicht unterstützt. Wirft stets InvalidCastException. |
| static constexpr int [ToInt32](./toint32/)(std::nullptr_t) | Konvertiert die angegebene Null-Zeichenfolge in den entsprechenden 32-Bit-Ganzzahlwert. |
| static int [ToInt32](./toint32/)(const char_t *) | Konvertiert die angegebene C-Zeichenkette, die die Zeichendarstellung einer Zahl enthält, in den entsprechenden 32-Bit-Ganzzahlwert. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die Zeichendarstellung einer Zahl enthält, in den entsprechenden 32-Bit-Ganzzahlwert. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, int) | Konvertiert die angegebene Zeichenkette, die die Zeichendarstellung einer Zahl in der angegebenen Basis enthält, in den entsprechenden 32-Bit-Ganzzahlwert. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichendarstellung einer Zahl enthält, in den entsprechenden 32-Bit-Ganzzahlwert unter Verwendung der angegebenen Formatierungsinformationen. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichendarstellung einer Zahl enthält, in den entsprechenden 32-Bit-Ganzzahlwert unter Verwendung der angegebenen Formatierungsinformationen und des Zahlenstils. |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static int [ToInt32](./toint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [ToInt32](./toint32/)([Enum](../enum/)) |  |
| static int [ToInt32](./toint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen gepackten Wert in einen entsprechenden 32-Bit-Ganzzahlwert. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**bool**) | Konvertiert den angegebenen booleschen Wert in eine äquivalente 64-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint8_t**) | Konvertiert die angegebene 8-Bit-vorzeichenlose Ganzzahl in eine äquivalente 64-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int8_t**) | Konvertiert die angegebene 8-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente 64-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint16_t**) | Konvertiert die angegebene 16-Bit-vorzeichenlose Ganzzahl in eine äquivalente 64-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int16_t**) | Konvertiert die angegebene 16-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente 64-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**uint32_t**) | Konvertiert die angegebene 32-Bit-vorzeichenlose Ganzzahl in eine äquivalente 64-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int32_t**) | Konvertiert die angegebene 32-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente 64-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int64_t** [ToInt64](./toint64/)(**uint64_t**) | Konvertiert die angegebene 64-Bit-vorzeichenlose Ganzzahl in eine äquivalente 64-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr **int64_t** [ToInt64](./toint64/)(**int64_t**) | Gibt die angegebene 64-Bit-vorzeichenbehaftete Ganzzahl zurück. |
| static **int64_t** [ToInt64](./toint64/)(**float**) | Konvertiert die angegebene float-Zahl in eine äquivalente 64-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int64_t** [ToInt64](./toint64/)(**double**) | Konvertiert die angegebene double-Zahl in eine äquivalente 64-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int64_t** [ToInt64](./toint64/)(const [Decimal](../decimal/)\&) | Konvertiert die angegebene Dezimalzahl in eine äquivalente 64-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr **int64_t** [ToInt64](./toint64/)(char_t) | Konvertiert das angegebene Unicode-Zeichen in eine äquivalente 64-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int64_t** [ToInt64](./toint64/)([DateTime](../datetime/)) | Konvertierung wird nicht unterstützt. Wirft stets InvalidCastException. |
| static constexpr **int64_t** [ToInt64](./toint64/)(std::nullptr_t) | Konvertiert die angegebene Null-Zeichenfolge in den entsprechenden 64-Bit-Ganzzahlwert. |
| static **int64_t** [ToInt64](./toint64/)(const char_t *) | Konvertiert die angegebene C-Zeichenkette, die die Zeichendarstellung einer Zahl enthält, in den entsprechenden 64-Bit-Ganzzahlwert. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die Zeichendarstellung einer Zahl enthält, in den entsprechenden 64-Bit-Ganzzahlwert. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, int) | Konvertiert die angegebene Zeichenkette, die die Zeichendarstellung einer Zahl in der angegebenen Basis enthält, in den entsprechenden 64-Bit-Ganzzahlwert. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichendarstellung einer Zahl enthält, in den entsprechenden 64-Bit-Ganzzahlwert unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichendarstellung einer Zahl enthält, in den entsprechenden 64-Bit-Ganzzahlwert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int64_t** [ToInt64](./toint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int64_t** [ToInt64](./toint64/)([Enum](../enum/)) |  |
| static **int64_t** [ToInt64](./toint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen gepackten Wert in einen entsprechenden 64-Bit-Ganzzahlwert. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**bool**) | Konvertiert den angegebenen booleschen Wert in eine äquivalente 8-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint8_t**) | Konvertiert die angegebene 8-Bit-vorzeichenlose Ganzzahl in eine äquivalente 8-Bit-vorzeichenbehaftete Ganzzahl. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(**int8_t**) | Gibt die angegebene 8-Bit-vorzeichenbehaftete Ganzzahl zurück. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint16_t**) | Konvertiert die angegebene 16-Bit-vorzeichenlose Ganzzahl in eine äquivalente 8-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int8_t** [ToSByte](./tosbyte/)(**int16_t**) | Konvertiert die angegebene 16-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente 8-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint32_t**) | Konvertiert die angegebene 32-Bit-vorzeichenlose Ganzzahl in eine äquivalente 8-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int8_t** [ToSByte](./tosbyte/)(**int32_t**) | Konvertiert die angegebene 32-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente 8-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int8_t** [ToSByte](./tosbyte/)(**uint64_t**) | Konvertiert die angegebene 64-Bit-vorzeichenlose Ganzzahl in eine äquivalente 8-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int8_t** [ToSByte](./tosbyte/)(**int64_t**) | Konvertiert die angegebene 64-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente 8-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int8_t** [ToSByte](./tosbyte/)(**float**) | Konvertiert die angegebene float-Zahl in eine äquivalente 8-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int8_t** [ToSByte](./tosbyte/)(**double**) | Konvertiert die angegebene double-Zahl in eine äquivalente 8-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int8_t** [ToSByte](./tosbyte/)(const [Decimal](../decimal/)\&) | Konvertiert die angegebene Dezimalzahl in eine äquivalente 8-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int8_t** [ToSByte](./tosbyte/)(char_t) | Konvertiert das angegebene Unicode-Zeichen in eine äquivalente 8-Bit-vorzeichenbehaftete Ganzzahl. |
| static **int8_t** [ToSByte](./tosbyte/)([DateTime](../datetime/)) | Konvertierung wird nicht unterstützt. Wirft stets InvalidCastException. |
| static constexpr **int8_t** [ToSByte](./tosbyte/)(std::nullptr_t) | Konvertiert die angegebene Null-Zeichenfolge in den entsprechenden 8-Bit-Ganzzahlwert. |
| static **int8_t** [ToSByte](./tosbyte/)(const char_t *) | Konvertiert die angegebene C-Zeichenkette, die die Zeichendarstellung einer Zahl enthält, in den entsprechenden 8-Bit-Ganzzahlwert. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die Zeichendarstellung einer Zahl enthält, in den entsprechenden 8-Bit-Ganzzahlwert. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, int) | Konvertiert die angegebene Zeichenkette, die die Zeichendarstellung einer Zahl in der angegebenen Basis enthält, in den entsprechenden 8-Bit-Ganzzahlwert. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichendarstellung einer Zahl enthält, in den entsprechenden vorzeichenlosen 8-Bit-Ganzzahlwert unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichendarstellung einer Zahl enthält, in den entsprechenden 8-Bit-Ganzzahlwert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int8_t** [ToSByte](./tosbyte/)([Enum](../enum/)) |  |
| static **int8_t** [ToSByte](./tosbyte/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen gepackten Wert in einen entsprechenden 8-Bit-Ganzzahlwert. |
| static constexpr **float** [ToSingle](./tosingle/)(**bool**) | Konvertiert den angegebenen booleschen Wert in eine äquivalente float-Gleitkommazahl mit einfacher Genauigkeit. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint8_t**) | Konvertiert die angegebene 8-Bit-vorzeichenlose Ganzzahl in eine äquivalente float-Gleitkommazahl mit einfacher Genauigkeit. |
| static constexpr **float** [ToSingle](./tosingle/)(**int8_t**) | Konvertiert die angegebene 8-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente float-Gleitkommazahl mit einfacher Genauigkeit. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint16_t**) | Konvertiert die angegebene 16-Bit-vorzeichenlose Ganzzahl in eine äquivalente float-Gleitkommazahl mit einfacher Genauigkeit. |
| static constexpr **float** [ToSingle](./tosingle/)(**int16_t**) | Konvertiert die angegebene 16-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente float-Gleitkommazahl mit einfacher Genauigkeit. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint32_t**) | Konvertiert die angegebene 32-Bit-vorzeichenlose Ganzzahl in eine äquivalente float-Gleitkommazahl mit einfacher Genauigkeit. |
| static constexpr **float** [ToSingle](./tosingle/)(**int32_t**) | Konvertiert die angegebene 32-Bit-vorzeichenbehaftete Ganzzahl in eine äquivalente float-Gleitkommazahl mit einfacher Genauigkeit. |
| static constexpr **float** [ToSingle](./tosingle/)(**uint64_t**) | Konvertiert die angegebene 64-bit vorzeichenlose Ganzzahl in eine entsprechende Gleitkommazahl einfacher Genauigkeit. |
| static constexpr **float** [ToSingle](./tosingle/)(**int64_t**) | Konvertiert die angegebene 64-bit vorzeichenbehaftete Ganzzahl in eine entsprechende Gleitkommazahl einfacher Genauigkeit. |
| static constexpr **float** [ToSingle](./tosingle/)(**float**) | Gibt die angegebene float-Zahl zurück. |
| static constexpr **float** [ToSingle](./tosingle/)(**double**) | Konvertiert die angegebene double-Genauigkeitszahl in eine entsprechende Gleitkommazahl einfacher Genauigkeit. |
| static **float** [ToSingle](./tosingle/)(const [Decimal](../decimal/)\&) | Konvertiert die angegebene Dezimalzahl in eine entsprechende Gleitkommazahl einfacher Genauigkeit. |
| static **float** [ToSingle](./tosingle/)(char_t) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static **float** [ToSingle](./tosingle/)([DateTime](../datetime/)) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static constexpr **float** [ToSingle](./tosingle/)(std::nullptr_t) | Konvertiert die angegebene null-string in den entsprechenden Gleitkommawert einfacher Genauigkeit. |
| static **float** [ToSingle](./tosingle/)(const char_t *) | Konvertiert die angegebene c-string, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden Gleitkommawert einfacher Genauigkeit. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden Gleitkommawert einfacher Genauigkeit. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden Gleitkommawert einfacher Genauigkeit unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden Gleitkommawert einfacher Genauigkeit unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [ToSingle](./tosingle/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **float** [ToSingle](./tosingle/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen verpackten Wert in einen Gleitkommawert einfacher Genauigkeit. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation. |
| static [String](../string/) [ToString](./tostring/)(**float**) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation. |
| static [String](../string/) [ToString](./tostring/)(**double**) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/)) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in eine Zeichenkette unter Verwendung der kulturspezifischen Formatierungsinformationen. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in eine Zeichenkette unter Verwendung der kulturspezifischen Formatierungsinformationen. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in eine Zeichenkette unter Verwendung der kulturspezifischen Formatierungsinformationen. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in eine Zeichenkette unter Verwendung der kulturspezifischen Formatierungsinformationen. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in eine Zeichenkette unter Verwendung der kulturspezifischen Formatierungsinformationen. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in eine Zeichenkette unter Verwendung der kulturspezifischen Formatierungsinformationen. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in eine Zeichenkette unter Verwendung der kulturspezifischen Formatierungsinformationen. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in eine Zeichenkette unter Verwendung der kulturspezifischen Formatierungsinformationen. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in eine Zeichenkette unter Verwendung der kulturspezifischen Formatierungsinformationen. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in eine Zeichenkette unter Verwendung der kulturspezifischen Formatierungsinformationen. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in eine Zeichenkette unter Verwendung der kulturspezifischen Formatierungsinformationen. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in eine Zeichenkette unter Verwendung der kulturspezifischen Formatierungsinformationen. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation unter Verwendung des angegebenen Stringformats und der kulturspezifischen Formatierungsinformationen, die vom angegebenen [IFormatProvider](../iformatprovider/)-Objekt bereitgestellt werden. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation unter Verwendung des angegebenen Stringformats und der kulturspezifischen Formatierungsinformationen, die vom angegebenen [IFormatProvider](../iformatprovider/)-Objekt bereitgestellt werden. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation unter Verwendung des angegebenen Stringformats und der kulturspezifischen Formatierungsinformationen, die vom angegebenen [IFormatProvider](../iformatprovider/)-Objekt bereitgestellt werden. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation unter Verwendung des angegebenen Stringformats und der kulturspezifischen Formatierungsinformationen, die vom angegebenen [IFormatProvider](../iformatprovider/)-Objekt bereitgestellt werden. |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation unter Verwendung des angegebenen Stringformats und der kulturspezifischen Formatierungsinformationen, die vom angegebenen [IFormatProvider](../iformatprovider/)-Objekt bereitgestellt werden. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in seine Zeichenkettenrepräsentation unter Verwendung des angegebenen Stringformats und der kulturspezifischen Formatierungsinformationen, die vom angegebenen [IFormatProvider](../iformatprovider/)-Objekt bereitgestellt werden. |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in seine Stringdarstellung unter Verwendung des angegebenen Zeichenkettenformats und der kulturspezifischen Formatinformationen, die vom angegebenen [IFormatProvider](../iformatprovider/)-Objekt bereitgestellt werden. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in seine Stringdarstellung unter Verwendung des angegebenen Zeichenkettenformats und der kulturspezifischen Formatinformationen, die vom angegebenen [IFormatProvider](../iformatprovider/)-Objekt bereitgestellt werden. |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**uint64_t**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in seine Stringdarstellung unter Verwendung des angegebenen Zeichenkettenformats und der kulturspezifischen Formatinformationen, die vom angegebenen [IFormatProvider](../iformatprovider/)-Objekt bereitgestellt werden. |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**float**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in seine Stringdarstellung unter Verwendung des angegebenen Zeichenkettenformats und der kulturspezifischen Formatinformationen, die vom angegebenen [IFormatProvider](../iformatprovider/)-Objekt bereitgestellt werden. |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(**double**, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in seine Stringdarstellung unter Verwendung des angegebenen Zeichenkettenformats und der kulturspezifischen Formatinformationen, die vom angegebenen [IFormatProvider](../iformatprovider/)-Objekt bereitgestellt werden. |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [Decimal](../decimal/)\&, const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in seine Stringdarstellung unter Verwendung des angegebenen Zeichenkettenformats und der kulturspezifischen Formatinformationen, die vom angegebenen [IFormatProvider](../iformatprovider/)-Objekt bereitgestellt werden. |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)([DateTime](../datetime/), const [String](../string/)\&, std::nullptr_t) |  |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&) | Konvertiert den angegebenen Wert in einen String. |
| static [String](../string/) [ToString](./tostring/)(const [Guid](../guid/)\&, const [String](../string/)\&) | Konvertiert den angegebenen Wert in einen String unter Verwendung des angegebenen Zeichenkettenformats. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), std::nullptr_t) | Konvertiert das angegebene Array von Unicode-Zeichen in einen String. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert das angegebene Array von Unicode-Zeichen in einen String unter Verwendung der angegebenen kulturspezifischen Formatinformationen, die vom angegebenen [IFormatProvider](../iformatprovider/)-Objekt bereitgestellt werden. |
| static [String](../string/) [ToString](./tostring/)(const char_t(&), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) | Gibt den angegebenen Wert zurück; es wird keine Konvertierung durchgeführt. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Gibt den angegebenen Wert zurück; es wird keine Konvertierung durchgeführt. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Gibt den angegebenen Wert zurück; es wird keine Konvertierung durchgeführt. |
| static [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Gibt den angegebenen Wert zurück; es wird keine Konvertierung durchgeführt. |
| static [String](../string/) [ToString](./tostring/)(char_t, std::nullptr_t) | Gibt den angegebenen Wert zurück; es wird keine Konvertierung durchgeführt. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Gibt den angegebenen Wert zurück; es wird keine Konvertierung durchgeführt. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Gibt den angegebenen Wert zurück; es wird keine Konvertierung durchgeführt. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Gibt den angegebenen Wert zurück; es wird keine Konvertierung durchgeführt. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Gibt den angegebenen Wert zurück; es wird keine Konvertierung durchgeführt. |
| static [String](../string/) [ToString](./tostring/)(char_t, const [String](../string/)\&, std::nullptr_t) | Gibt den angegebenen Wert zurück; es wird keine Konvertierung durchgeführt. |
| static [String](../string/) [ToString](./tostring/)(**bool**, std::nullptr_t) | Konvertiert den angegebenen Wert in seine Stringdarstellung. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in seine Stringdarstellung. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Konvertiert den angegebenen Wert in seine Stringdarstellung. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) | Konvertiert den angegebenen Wert in seine Stringdarstellung. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen Wert in seine Stringdarstellung. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Konvertiert den angegebenen Wert in seine Stringdarstellung. |
| static [String](../string/) [ToString](./tostring/)(**bool**, const [String](../string/)\&, std::nullptr_t) | Konvertiert den angegebenen Wert in seine Stringdarstellung. |
| static [String](../string/) [ToString](./tostring/)(**int8_t**, int) | Konvertiert den angegebenen Ganzzahlwert in seine Stringdarstellung in der angegebenen Basis. |
| static [String](../string/) [ToString](./tostring/)(**int16_t**, int) | Konvertiert den angegebenen Ganzzahlwert in seine Stringdarstellung in der angegebenen Basis. |
| static [String](../string/) [ToString](./tostring/)(**int32_t**, int) | Konvertiert den angegebenen Ganzzahlwert in seine Stringdarstellung in der angegebenen Basis. |
| static [String](../string/) [ToString](./tostring/)(**int64_t**, int) | Konvertiert den angegebenen Ganzzahlwert in seine Stringdarstellung in der angegebenen Basis. |
| static [String](../string/) [ToString](./tostring/)(**uint8_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint16_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(**uint32_t**, int) |  |
| static [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen verpackten Wert in seine Stringdarstellung. Wenn der Typ des verpackten Werts [String](../string/) ist, wird das angegebene Zeichenkettenformat bei der Konvertierung verwendet. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**bool**) | Konvertiert den angegebenen booleschen Wert in einen entsprechenden 16-Bit-unsigned-Integer. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint8_t**) | Konvertiert den angegebenen 8-Bit-unsigned-Integer in einen entsprechenden 16-Bit-unsigned-Integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**int8_t**) | Konvertiert den angegebenen 8-Bit-signed-Integer in einen entsprechenden 16-Bit-unsigned-Integer. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(**uint16_t**) | Gibt den angegebenen 16-Bit-unsigned-Integer zurück. |
| static **uint16_t** [ToUInt16](./touint16/)(**int16_t**) | Konvertiert den angegebenen 16-Bit-signed-Integer in einen entsprechenden 16-Bit-unsigned-Integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint32_t**) | Konvertiert den angegebenen 32-Bit-unsigned-Integer in einen entsprechenden 16-Bit-unsigned-Integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**int32_t**) | Konvertiert den angegebenen 32-Bit-signed-Integer in einen entsprechenden 16-Bit-unsigned-Integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**uint64_t**) | Konvertiert den angegebenen 64-Bit-unsigned-Integer in einen entsprechenden 16-Bit-unsigned-Integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**int64_t**) | Konvertiert den angegebenen 64-Bit-signed-Integer in einen entsprechenden 16-Bit-unsigned-Integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**float**) | Konvertiert die angegebene Float-Zahl in einen entsprechenden 16-Bit-unsigned-Integer. |
| static **uint16_t** [ToUInt16](./touint16/)(**double**) | Konvertiert die angegebene Double-Zahl in einen entsprechenden 16-Bit-unsigned-Integer. |
| static **uint16_t** [ToUInt16](./touint16/)(const [Decimal](../decimal/)\&) | Konvertiert die angegebene Dezimalzahl in einen entsprechenden 16-Bit-unsigned-Integer. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(char_t) | Konvertiert das angegebene Unicode-Zeichen in einen entsprechenden 16-Bit-unsigned-Integer. |
| static **uint16_t** [ToUInt16](./touint16/)([DateTime](../datetime/)) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static constexpr **uint16_t** [ToUInt16](./touint16/)(std::nullptr_t) | Konvertiert die angegebene Null-Zeichenkette in den entsprechenden 16-Bit-unsigned-Integer-Wert. |
| static **uint16_t** [ToUInt16](./touint16/)(const char_t *) | Konvertiert die angegebene C-Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden 16-Bit-unsigned-Integer-Wert. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden 16-Bit-unsigned-Integer-Wert. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, int) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl in der angegebenen Basis enthält, in den entsprechenden 16-Bit-unsigned-Integer-Wert. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden 16-Bit-unsigned-Integer-Wert unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden 16-Bit-unsigned-Integer-Wert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint16_t** [ToUInt16](./touint16/)([Enum](../enum/)) |  |
| static **uint16_t** [ToUInt16](./touint16/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen verpackten Wert in den entsprechenden 16-Bit-unsigned-Integer-Wert. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**bool**) | Konvertiert den angegebenen booleschen Wert in einen entsprechenden 32-Bit-unsigned-Integer. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint8_t**) | Konvertiert den angegebenen 8-Bit-unsigned-Integer in einen entsprechenden 32-Bit-unsigned-Integer. |
| static **uint32_t** [ToUInt32](./touint32/)(**int8_t**) | Konvertiert den angegebenen 8-Bit-signed-Integer in einen entsprechenden 32-Bit-unsigned-Integer. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint16_t**) | Konvertiert den angegebenen 16-Bit-unsigned-Integer in einen entsprechenden 32-Bit-unsigned-Integer. |
| static **uint32_t** [ToUInt32](./touint32/)(**int16_t**) | Konvertiert den angegebenen 16-Bit-signed-Integer in einen entsprechenden 32-Bit-unsigned-Integer. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(**uint32_t**) | Gibt den angegebenen 32-Bit-unsigned-Integer zurück. |
| static **uint32_t** [ToUInt32](./touint32/)(**int32_t**) | Konvertiert die angegebene 32-bit-Ganzzahl mit Vorzeichen in einen äquivalenten 32-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint32_t** [ToUInt32](./touint32/)(**uint64_t**) | Konvertiert die angegebene 64-bit-Ganzzahl ohne Vorzeichen in einen äquivalenten 32-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint32_t** [ToUInt32](./touint32/)(**int64_t**) | Konvertiert die angegebene 64-bit-Ganzzahl mit Vorzeichen in einen äquivalenten 32-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint32_t** [ToUInt32](./touint32/)(**float**) | Konvertiert die angegebene Fließkommazahl in einen äquivalenten 32-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint32_t** [ToUInt32](./touint32/)(**double**) | Konvertiert die angegebene Double-Zahl in einen äquivalenten 32-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint32_t** [ToUInt32](./touint32/)(const [Decimal](../decimal/)\&) | Konvertiert die angegebene Dezimalzahl in einen äquivalenten 32-bit-Ganzzahlwert ohne Vorzeichen. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(char_t) | Konvertiert das angegebene Unicode-Zeichen in einen äquivalenten 32-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint32_t** [ToUInt32](./touint32/)([DateTime](../datetime/)) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static constexpr **uint32_t** [ToUInt32](./touint32/)(std::nullptr_t) | Konvertiert die angegebene Nullzeichenfolge in den entsprechenden 32-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint32_t** [ToUInt32](./touint32/)(const char_t *) | Konvertiert die angegebene C-Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden 32-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden 32-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, int) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl in der angegebenen Basis enthält, in den entsprechenden 32-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden 32-bit-Ganzzahlwert ohne Vorzeichen unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden 32-bit-Ganzzahlwert ohne Vorzeichen unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint32_t** [ToUInt32](./touint32/)([Enum](../enum/)) |  |
| static **uint32_t** [ToUInt32](./touint32/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen boxed-Wert in einen äquivalenten 32-bit-Ganzzahlwert ohne Vorzeichen. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**bool**) | Konvertiert den angegebenen booleschen Wert in einen äquivalenten 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint8_t**) | Konvertiert die angegebene 8-bit-Ganzzahl ohne Vorzeichen in einen äquivalenten 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint64_t** [ToUInt64](./touint64/)(**int8_t**) | Konvertiert die angegebene 8-bit-Ganzzahl mit Vorzeichen in einen äquivalenten 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint16_t**) | Konvertiert die angegebene 16-bit-Ganzzahl ohne Vorzeichen in einen äquivalenten 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint64_t** [ToUInt64](./touint64/)(**int16_t**) | Konvertiert die angegebene 16-bit-Ganzzahl mit Vorzeichen in einen äquivalenten 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint32_t**) | Konvertiert die angegebene 32-bit-Ganzzahl ohne Vorzeichen in einen äquivalenten 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint64_t** [ToUInt64](./touint64/)(**int32_t**) | Konvertiert die angegebene 32-bit-Ganzzahl mit Vorzeichen in einen äquivalenten 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(**uint64_t**) | Gibt die angegebene 64-bit-Ganzzahl ohne Vorzeichen zurück. |
| static **uint64_t** [ToUInt64](./touint64/)(**int64_t**) | Konvertiert die angegebene 64-bit-Ganzzahl mit Vorzeichen in einen äquivalenten 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint64_t** [ToUInt64](./touint64/)(**float**) | Konvertiert die angegebene Fließkommazahl in einen äquivalenten 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint64_t** [ToUInt64](./touint64/)(**double**) | Konvertiert die angegebene Double-Zahl in einen äquivalenten 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint64_t** [ToUInt64](./touint64/)(const [Decimal](../decimal/)\&) | Konvertiert die angegebene Dezimalzahl in einen äquivalenten 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(char_t) | Konvertiert das angegebene Unicode-Zeichen in einen äquivalenten 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint64_t** [ToUInt64](./touint64/)([DateTime](../datetime/)) | Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException. |
| static constexpr **uint64_t** [ToUInt64](./touint64/)(std::nullptr_t) | Konvertiert die angegebene Nullzeichenfolge in den entsprechenden 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint64_t** [ToUInt64](./touint64/)(const char_t *) | Konvertiert die angegebene C-Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, int) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl in der angegebenen Basis enthält, in den entsprechenden 64-bit-Ganzzahlwert ohne Vorzeichen. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden 64-bit-Ganzzahlwert ohne Vorzeichen unter Verwendung der bereitgestellten Formatierungsinformationen. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die angegebene Zeichenkette, die die Stringdarstellung einer Zahl enthält, in den entsprechenden 64-bit-Ganzzahlwert ohne Vorzeichen unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **uint64_t** [ToUInt64](./touint64/)([Enum](../enum/)) |  |
| static **uint64_t** [ToUInt64](./touint64/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert den angegebenen boxed-Wert in einen äquivalenten 64-bit-Ganzzahlwert ohne Vorzeichen. |
## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)