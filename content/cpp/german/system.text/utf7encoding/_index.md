---
title: UTF7Encoding
second_title: Aspose.Slides für C++ API-Referenz
description: "UTF-7-Kodierung. Objekte dieser Klasse sollten ausschließlich über die Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 365
url: /de/system.text/utf7encoding/
---
## UTF7Encoding class

UTF-7-Kodierung. Objekte dieser Klasse sollten nur über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Verpacken Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## Methoden

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Klont das Kodierungsobjekt. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Konvertiert Bytes zwischen zwei Kodierungen. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Konvertiert Bytes zwischen zwei Kodierungen. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergleicht mit dem Objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Gibt die ASCII-Kodierung zurück. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Gibt das standardmäßige Big-Endian-Unicode-Kodierungsobjekt zurück. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Gibt das standardmäßige Big-Endian-UTF-32-Kodierungsobjekt zurück. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Gibt den mit Mail-Agent-Body kompatiblen Kodierungsnamen zurück. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Gibt die [Windows](../../system.windows/)-Codepage-ID zurück. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Gibt die Decoder-Fallback-Strategie zurück. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Gibt die Standardkodierung zurück. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Gibt die Encoder-Fallback-Strategie zurück. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Gibt den menschenlesbaren Kodierungsnamen zurück. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Gibt den mit Mail-Agent-Header kompatiblen Kodierungsnamen zurück. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Prüft, ob die Kodierung im Browser zur Anzeige von Inhalten verwendet werden kann. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Prüft, ob die Kodierung im Browser zum Speichern von Inhalten verwendet werden kann. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Prüft, ob die Kodierung im Mail-Client zur Anzeige von Inhalten verwendet werden kann. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Prüft, ob die Kodierung im Mail-Client zum Speichern von Inhalten verwendet werden kann. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Prüft, ob die Kodierung schreibgeschützt ist. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Prüft, ob die Kodierung einstellig (ein Byte) ist. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Gibt die Latin1-Kodierung zurück. FOR INTERNAL USE. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Gibt das standardmäßige Unicode-Kodierungsobjekt zurück. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Gibt das standardmäßige UTF-7-Kodierungsobjekt zurück. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Gibt das standardmäßige UTF-8-Kodierungsobjekt zurück. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Nur intern, zur Verwendung durch die Klassenbibliotheken: Unmarkiert und nicht eingabevalidierend. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Gibt den IANA-kompatiblen Kodierungsnamen zurück. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Gibt die [Windows](../../system.windows/)-Codepage-ID zurück. |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | Ermittelt die Anzahl der Zeichen, die zum Kodieren eines Zeichenpuffers benötigt werden. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Ermittelt die Anzahl der Zeichen, die zum Kodieren eines Zeichenpuffers benötigt werden. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Ermittelt die Anzahl der Zeichen, die zum Kodieren eines Zeichenpuffers benötigt werden. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Ermittelt die Anzahl der Zeichen, die zum Kodieren eines Zeichenpuffers benötigt werden. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Ermittelt die Anzahl der Zeichen, die zum Kodieren eines Strings benötigt werden. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Ermittelt die Anzahl der Zeichen, die zum Kodieren eines Zeichenpuffers benötigt werden. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Ermittelt die Anzahl der Zeichen, die zum Kodieren eines Zeichenpuffers benötigt werden. |
| int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Ermittelt die Bytes, die beim Kodieren eines Zeichenpuffers entstehen. |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | Ermittelt die Bytes, die beim Kodieren eines Zeichenpuffers entstehen. |
| int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Ermittelt die Bytes, die beim Kodieren eines Zeichenpuffers entstehen. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Ermittelt die Bytes, die beim Kodieren eines Zeichenpuffers entstehen. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Ermittelt die Bytes, die beim Kodieren eines Zeichenpuffers entstehen. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Ermittelt die Bytes, die beim Kodieren eines Zeichenpuffers entstehen. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Ermittelt die Bytes, die beim Kodieren eines Zeichenpuffers entstehen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Ermittelt die Bytes, die beim Kodieren eines Zeichenpuffers entstehen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Ermittelt die Bytes, die beim Kodieren eines Zeichenpuffers entstehen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Ermittelt die Bytes, die beim Kodieren eines Zeichenpuffers entstehen. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Ermittelt die Bytes, die beim Kodieren eines Zeichenpuffers entstehen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Ermittelt die Bytes, die beim Kodieren eines Zeichenpuffers entstehen. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Ermittelt die Bytes, die beim Kodieren eines Zeichenpuffers entstehen. |
| int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden. |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Ermittelt die Anzahl der Zeichen, die zum Dekodieren eines Byte-Puffers benötigt werden. |
| int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) override | Ermittelt die Zeichen, die beim Dekodieren eines Byte-Puffers entstehen. |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | Ermittelt die Zeichen, die beim Dekodieren eines Byte-Puffers entstehen. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Ermittelt die Zeichen, die beim Dekodieren eines Byte-Puffers entstehen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Ermittelt die Zeichen, die beim Dekodieren eines Byte-Puffers entstehen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ermittelt die Zeichen, die beim Dekodieren eines Byte-Puffers entstehen. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Ermittelt die Zeichen, die beim Dekodieren eines Byte-Puffers entstehen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gibt die Referenzzähler-Datenstruktur zurück, die dem Objekt zugeordnet ist. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | Erhält einen Decoder, der Anfragen an dieses Objekt weiterleitet. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | Erhält einen Encoder, der Anfragen an dieses Objekt weiterleitet. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Gibt die Kodierung nach Name zurück. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Gibt die Kodierung nach Codepage zurück. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Gibt die Kodierung nach Codepage zurück. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Gibt die Kodierung nach Name zurück. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Gibt die Liste bekannter Kodierungen zurück. |
| int [GetHashCode](./gethashcode/)() const override | Gibt den Hash-Code der Kodierung zurück. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Ermittelt die maximale Anzahl an Bytes, die zum Kodieren einer angegebenen Anzahl von Zeichen benötigt werden. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Ermittelt die maximale Anzahl an Zeichen, die zum Dekodieren einer angegebenen Anzahl von Bytes benötigt werden. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../encoding/getpreamble/)() | Gibt eine Byte-Sequenz zurück, die die Kodierung bezeichnet (z. B. BOM). |
| [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Dekodiert einen Byte-Puffer in einen String. |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Dekodiert einen Byte-Puffer in einen String. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Dekodiert einen Byte-Puffer in einen String. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Dekodiert einen Byte-Puffer in einen String. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Dekodiert einen Byte-Puffer in einen String. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Dekodiert einen Byte-Puffer in einen String. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Dekodiert einen Byte-Puffer in einen String. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Dekodiert einen Byte-Puffer in einen String. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Dekodiert einen Byte-Puffer in einen String. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gibt den tatsächlichen Typ des Objekts zurück. Analogie zum C#-[System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analogie zum C#-„is“-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie zur C#-[Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF7Encoding](./)\&) const | Vergleicht die Parameter von Kodierungen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt referenziell mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsam genutzte Referenzzählung um den angegebenen Wert. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Setzt die Decoder-Fallback-Strategie. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Setzt die Encoder-Fallback-Strategie. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gibt den aktuellen Wert des geteilten Referenzzählers zurück. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die gemeinsame Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie zur C#-[Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
|  [UTF7Encoding](./utf7encoding/)() | Konstruktor. |
|  [UTF7Encoding](./utf7encoding/)(**bool**) | Konstruktor. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Felder

| Field | Description |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Standard-Codepage-Wert. |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | Magische Zahl, die von [Windows](../../system.windows/) für die UTF-7-Codepage-ID verwendet wird. |

## Siehe auch

* Klasse [Encoding](../encoding/)
* Namensraum [System::Text](../)
* Bibliothek [Aspose.Slides](../../)