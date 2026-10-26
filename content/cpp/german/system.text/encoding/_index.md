---
title: Encoding
second_title: Aspose.Slides für C++ API-Referenz
description: Kodierungsdienste.
type: docs
weight: 222
url: /de/system.text/encoding/
---
## Encoding-Klasse

[Encoding](./) Dienste.

```cpp
class Encoding : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() | Klont das Encoding-Objekt. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Konvertiert Bytes zwischen zwei Kodierungen. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](./convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Konvertiert Bytes zwischen zwei Kodierungen. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergleicht Kodierungen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](./get_ascii/)() | Liefert das ASCII-Encoding. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](./get_bigendianunicode/)() | Liefert das Standard-Big-Endian-Unicode-Encoding-Objekt. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](./get_bigendianutf32/)() | Liefert das Standard-Big-Endian-UTF-32-Encoding-Objekt. |
| virtual [String](../../system/string/) [get_BodyName](./get_bodyname/)() | Liefert den für den Mail-Agent-Body kompatiblen Encoding-Namen. |
| virtual int [get_CodePage](./get_codepage/)() | Liefert die [Windows](../../system.windows/)-Codepage-ID. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](./get_decoderfallback/)() const | Liefert den Decoder-Fallback. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](./get_default/)() | Liefert das Standard-Encoding. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](./get_encoderfallback/)() const | Liefert den Encoder-Fallback. |
| virtual [String](../../system/string/) [get_EncodingName](./get_encodingname/)() | Liefert den menschenlesbaren Encoding-Namen. |
| virtual [String](../../system/string/) [get_HeaderName](./get_headername/)() | Liefert den für Mail-Agent-Header kompatiblen Encoding-Namen. |
| virtual **bool** [get_IsBrowserDisplay](./get_isbrowserdisplay/)() | Prüft, ob das Encoding im Browser zur Anzeige von Inhalten verwendet werden kann. |
| virtual **bool** [get_IsBrowserSave](./get_isbrowsersave/)() | Prüft, ob das Encoding im Browser zum Speichern von Inhalten verwendet werden kann. |
| virtual **bool** [get_IsMailNewsDisplay](./get_ismailnewsdisplay/)() | Prüft, ob das Encoding im Mail-Client zur Anzeige von Inhalten verwendet werden kann. |
| virtual **bool** [get_IsMailNewsSave](./get_ismailnewssave/)() | Prüft, ob das Encoding im Mail-Client zum Speichern von Inhalten verwendet werden kann. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Prüft, ob das Encoding schreibgeschützt ist. |
| virtual **bool** [get_IsSingleByte](./get_issinglebyte/)() | Prüft, ob das Encoding ein Einzelbyte-Encoding ist. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](./get_latin1/)() | Liefert das Latin-1-Encoding. NUR FÜR INTERNEN GEBRAUCH. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](./get_unicode/)() | Liefert das Standard-Unicode-Encoding-Objekt. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](./get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](./get_utf7/)() | Liefert das Standard-UTF-7-Encoding-Objekt. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](./get_utf8/)() | Liefert das Standard-UTF-8-Encoding-Objekt. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](./get_utf8unmarked/)() | Nur intern, zur Verwendung durch die Klassenbibliotheken: Unmarkiert und nicht eingabevalidierend. |
| virtual [String](../../system/string/) [get_WebName](./get_webname/)() | Liefert einen IANA-kompatiblen Encoding-Namen. |
| virtual int [get_WindowsCodePage](./get_windowscodepage/)() | Liefert die [Windows](../../system.windows/)-Codepage-ID. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Ermittelt die Anzahl der Zeichen, die zum Kodieren eines Zeichenpuffers benötigt werden. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Ermittelt die Anzahl der Zeichen, die zum Kodieren eines Zeichenpuffers benötigt werden. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Ermittelt die Anzahl der Zeichen, die zum Kodieren eines Zeichenpuffers benötigt werden. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Ermittelt die Anzahl der Zeichen, die zum Kodieren einer Zeichenkette benötigt werden. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Ermittelt die Anzahl der Zeichen, die zum Kodieren eines Zeichenpuffers benötigt werden. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Ermittelt die Anzahl der Zeichen, die zum Kodieren eines Zeichenpuffers benötigt werden. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Ermittelt die Bytes, die durch das Kodieren eines Zeichenpuffers entstehen. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Ermittelt die Zeichen, die durch das Dekodieren eines Byte-Puffers entstehen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Ermittelt die Zeichen, die durch das Dekodieren eines Byte-Puffers entstehen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ermittelt die Zeichen, die durch das Dekodieren eines Byte-Puffers entstehen. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Ermittelt die Zeichen, die durch das Dekodieren eines Byte-Puffers entstehen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() | Erhält einen Decoder, der Anfragen an dieses Objekt weiterleitet. |
| virtual [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() | Erhält einen Encoder, der Anfragen an dieses Objekt weiterleitet. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&) | Liefert das Encoding anhand des Namens. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int) | Liefert das Encoding anhand der Codepage. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Liefert das Encoding anhand der Codepage. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](./getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Liefert das Encoding anhand des Namens. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](./getencodings/)() | Liefert eine Liste bekannter Encodings. |
| int [GetHashCode](./gethashcode/)() const override | Erzeugt einen Hashwert des Encodings. |
| virtual int [GetMaxByteCount](./getmaxbytecount/)(int) | Ermittelt die maximale Anzahl von Bytes, die zum Kodieren einer angegebenen Zeichenanzahl benötigt werden. |
| virtual int [GetMaxCharCount](./getmaxcharcount/)(int) | Ermittelt die maximale Anzahl von Zeichen, die zum Dekodieren einer angegebenen Byte-Anzahl benötigt werden. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() | Gibt eine Byte-Sequenz zurück, die das Encoding bezeichnet (z. B. BOM). |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Dekodiert einen Byte-Puffer in eine Zeichenkette. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Dekodiert einen Byte-Puffer in eine Zeichenkette. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Dekodiert einen Byte-Puffer in eine Zeichenkette. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Dekodiert einen Byte-Puffer in eine Zeichenkette. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Dekodiert einen Byte-Puffer in eine Zeichenkette. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Dekodiert einen Byte-Puffer in eine Zeichenkette. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Dekodiert einen Byte-Puffer in eine Zeichenkette. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Dekodiert einen Byte-Puffer in eine Zeichenkette. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analogie zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analogie zum C#-‘is‘-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt referenziell mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_DecoderFallback](./set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Setzt den Decoder-Fallback. |
| void [set_EncoderFallback](./set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Setzt den Encoder-Fallback. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in eine Zeichenkette. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](./default_code_page/) | Standard-Codepage-Wert. |

## Typdefinitionen

| Typedef | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | RTTI. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Text](../)
* Bibliothek [Aspose.Slides](../../)