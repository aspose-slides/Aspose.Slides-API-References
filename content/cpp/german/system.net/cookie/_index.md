---
title: Cookie
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt ein HTTP-Cookie dar. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 1
url: /de/system.net/cookie/
---
## Cookie-Klasse

Stellt ein HTTP-Cookie dar. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erzeugen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Cookie : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Erstellt eine Kopie der aktuellen Instanz. |
| [Cookie](./cookie/)() | Konstruiert eine neue Instanz. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Konstruiert eine neue Instanz. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Konstruiert eine neue Instanz. |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Konstruiert eine neue Instanz. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergleicht Objekte nach den C# [Object.Equals](../../system/object/equals/)-Semantiken. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach den C# [Object.Equals](../../system/object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | Liefert den Wert des Attributs 'Comment'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | Liefert den Wert des Attributs 'CommentURL'. |
| **bool** [get_Discard](./get_discard/)() const | Liefert den Wert des Attributs 'Discard'. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | Liefert den Wert des Attributs 'Domain'. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Liefert einen Wert, der angibt, ob die Domain implizit ist. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Gibt den Domänenschlüssel zurück. |
| **bool** [get_Expired](./get_expired/)() | Liefert einen Wert, der angibt, ob das Cookie abgelaufen ist. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | Liefert den Wert des Attributs 'Expires'. |
| **bool** [get_HttpOnly](./get_httponly/)() const | Liefert den Wert des Attributs 'HttpOnly'. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Liefert den Namen des Cookies. |
| [String](../../system/string/) [get_Path](./get_path/)() const | Liefert den Wert des Attributs 'Path'. |
| **bool** [get_Plain](./get_plain/)() const | Gibt einen Wert zurück, der angibt, ob die Cookie-Spezifikation 'Plain' ist. |
| [String](../../system/string/) [get_Port](./get_port/)() const | Liefert den Wert des Attributs 'Port'. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | Gibt die Sammlung der Werte des Attributs 'Port' zurück. |
| **bool** [get_Secure](./get_secure/)() const | Liefert den Wert des Attributs 'Secure'. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Gibt den Zeitpunkt zurück, zu dem das Cookie erstellt wurde. |
| [String](../../system/string/) [get_Value](./get_value/)() const | Liefert den Wert des Cookies. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | Liefert die Spezifikation des Cookies. |
| **int32_t** [get_Version](./get_version/)() const | Liefert den Wert des Attributs '[Version](../../system/version/)'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die mit dem Objekt verbunden ist. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | Diese Methode wird von anderen Methoden aufgerufen, um einen Methodennamen zu setzen. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Sentry-Objekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzähler um den angegebenen Wert. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | Setzt den Wert des Attributs 'Comment'. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Setzt den Wert des Attributs 'CommentURL'. |
| void [set_Discard](./set_discard/)(**bool**) | Setzt den Wert des Attributs 'Discard'. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | Setzt den Wert des Attributs 'Domain'. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Setzt einen Wert, der angibt, ob die Domain implizit ist. |
| void [set_Expired](./set_expired/)(**bool**) | Setzt einen Wert, der angibt, ob das Cookie abgelaufen ist. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | Setzt den Wert des Attributs 'Expires'. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | Setzt den Wert des Attributs 'HttpOnly'. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Setzt den Namen des Cookies. |
| void [set_Path](./set_path/)([String](../../system/string/)) | Setzt den Wert des Attributs 'Path'. |
| void [set_Port](./set_port/)([String](../../system/string/)) | Setzt den Wert des Attributs 'Port'. |
| void [set_Secure](./set_secure/)(**bool**) | Setzt den Wert des Attributs 'Secure'. |
| void [set_Value](./set_value/)([String](../../system/string/)) | Setzt den Wert des Cookies. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | Setzt die Spezifikation des Cookies. |
| void [set_Version](./set_version/)(**int32_t**) | Setzt den Wert des Attributs '[Version](../../system/version/)'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Wechseln von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Serialisiert die aktuelle Instanz in die Zeichenkettenrepräsentation. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Sentry-Objekt verwenden. |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Verifiziert und setzt die Standardattribute-Werte. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | Der Name des Attributs 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | Der Name des Attributs 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | Der Name des Attributs 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | Der Name des Attributs 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | Das Trennzeichen, das verwendet wird, um Namen und Wert eines Attributs zu trennen. |
| static [ExpiresAttributeName](./expiresattributename/) | Der Name des Attributs 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | Der Name des Attributs 'HttpOnly'. |
| static [MaxAgeAttributeName](./maxageattributename/) | Der Name des Attributs 'Max-Age'. |
| static [MaxSupportedVersion](./maxsupportedversion/) | Die maximal unterstützte Version. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | Die Zeichenkettenrepräsentation der maximal unterstützten Version. |
| static [PathAttributeName](./pathattributename/) | Der Name des Attributs 'Path'. |
| static [PortAttributeName](./portattributename/) | Der Name des Attributs 'Port'. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | Das Array, das Trennzeichen für die Werte des Attributs 'Port' enthält. |
| static [QuotesLiteral](./quotesliteral/) | Das Symbol, das verwendet wird, um die Teile des Attributs zu umschließen. |
| static [ReservedToName](./reservedtoname/) | Ein für den Cookie-Namen reservierter Wert. |
| static [ReservedToValue](./reservedtovalue/) | Ein für den Cookie-Wert reservierter Wert. |
| static [SecureAttributeName](./secureattributename/) | Der Name des Attributs 'Secure'. |
| static [SeparatorLiteral](./separatorliteral/) | Das Attributtrennzeichen. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | Das Präfix der Namen spezieller Attribute. |
| static [VersionAttributeName](./versionattributename/) | Der Name des Attributs '[Version](../../system/version/)'. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Net](../)
* Bibliothek [Aspose.Slides](../../)