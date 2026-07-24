---
title: HttpUtility
second_title: Aspose.Slides für C++ API-Referenz
description: Dienstklasse, die URL-Teile in Hex-Escape-Fragmenten kodiert und dekodiert.
type: docs
weight: 40
url: /de/system.web/httputility/
---
## HttpUtility Klasse

Dienstklasse, die URL-Teile in Hex-Escape-Fragmenten kodiert und dekodiert.

```cpp
class HttpUtility : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| static [String](../../system/string/) [HtmlDecode](./htmldecode/)(const [String](../../system/string/)\&) | Dekodiert ein HTML-Fragment. |
| static void [HtmlDecode](./htmldecode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Dekodiert ein HTML-Fragment. |
| static [String](../../system/string/) [HtmlEncode](./htmlencode/)(const [String](../../system/string/)\&) | Kodiert ein HTML-Fragment. |
| static [String](../../system/string/) [HtmlEncode](./htmlencode/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Kodiert ein HTML-Fragment. |
| static void [HtmlEncode](./htmlencode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Kodiert ein HTML-Fragment. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert die Sperrung des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren beim Erstellen von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren beim Erstellen von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die geteilte Referenzzählung um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem Weak-Pointer (statt eines Shared-Pointers). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die geteilte Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die geteilte Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert die Entsperrung des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| static [String](../../system/string/) [UrlDecode](./urldecode/)([String](../../system/string/)) | Dekodiert ein URI-Fragment aus einem String. |
| static [String](../../system/string/) [UrlDecode](./urldecode/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | Dekodiert ein URI-Fragment aus einem String. |
| static [String](../../system/string/) [UrlDecode](./urldecode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Dekodiert ein URI-Fragment aus einem Byte-Array. |
| static [String](../../system/string/) [UrlDecode](./urldecode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Dekodiert ein URI-Fragment aus einem Byte-Array. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Dekodiert ein URI-Fragment aus einem Byte-Array. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [String](../../system/string/)\&) | Dekodiert ein URI-Fragment aus einer Byte-Zeichenkette. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [String](../../system/string/)\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Dekodiert ein URI-Fragment aus einem String. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlDecodeToBytes](./urldecodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Dekodiert ein URI-Fragment aus einem Byte-Array. |
| static [String](../../system/string/) [UrlEncode](./urlencode/)([String](../../system/string/)) | Kodiert ein URI-Fragment. |
| static [String](../../system/string/) [UrlEncode](./urlencode/)([String](../../system/string/), const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Kodiert ein URI-Fragment. |
| static [String](../../system/string/) [UrlEncode](./urlencode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Kodiert ein URI-Fragment. |
| static [String](../../system/string/) [UrlEncode](./urlencode/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Kodiert ein URI-Fragment. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [String](../../system/string/)\&) | Kodiert ein URI-Fragment. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [String](../../system/string/)\&, const [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Kodiert ein URI-Fragment. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Kodiert ein URI-Fragment. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeToBytes](./urlencodetobytes/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Kodiert ein URI-Fragment. |
| static [String](../../system/string/) [UrlEncodeUnicode](./urlencodeunicode/)(const [String](../../system/string/)\&) | Kodiert ein URI-Fragment unter Verwendung von Unicode. |
| static [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [UrlEncodeUnicodeToBytes](./urlencodeunicodetobytes/)(const [String](../../system/string/)\&) | Kodiert ein URI-Fragment unter Verwendung von Unicode. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Web](../)
* Bibliothek [Aspose.Slides](../../)