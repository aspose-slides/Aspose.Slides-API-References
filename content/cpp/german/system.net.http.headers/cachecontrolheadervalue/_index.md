---
title: CacheControlHeaderValue
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen Wert des 'Cache-Control'-Headers dar. Objekte dieser Klasse sollten ausschließlich über die Funktion System::MakeObject() alloziert werden. Instanzen dieses Typs dürfen niemals auf dem Stack oder mit dem Operator new erstellt werden, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Pointer ein und verwenden Sie diesen Pointer, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 14
url: /de/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue Klasse


Stellt einen Wert des 'Cache-Control'-Headers dar. Objekte dieser Klasse sollten ausschließlich über die Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Instanzen dieses Typs dürfen niemals auf dem Stack oder mit dem Operator new erstellt werden, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Pointer ein und verwenden Sie diesen Pointer, um ihn als Argument an Funktionen zu übergeben.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Methoden

| Method | Description |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Erzeugt eine neue Instanz. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergleicht Objekte mit den C# [Object.Equals](../../system/object/equals/) Semantiken. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit den C# [Object.Equals](../../system/object/equals/) Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Gibt die Sammlung der Cache-Erweiterungs-Token zurück. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | Ruft den maximalen Alterswert in Sekunden ab, der die Zeit bestimmt, während der der Client eine Antwort akzeptiert. |
| **bool** [get_MaxStale](./get_maxstale/)() | Ruft den Wert ab, der bestimmt, ob der Client abgelaufene Antworten akzeptiert. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | Ruft den Wert in Sekunden ab, der die Zeit bestimmt, während der der Client abgelaufene Antworten akzeptiert. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Ruft den Wert ab, der die Frischelebensdauer bestimmt. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Ruft den Wert ab, der bestimmt, ob der Server eine Neuvalidierung eines Cache-Eintrags erfordert, wenn er veraltet wird. |
| **bool** [get_NoCache](./get_nocache/)() | Ruft den Wert ab, der bestimmt, ob der Client eine zwischengespeicherte Antwort akzeptiert. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | Ruft die Sammlung von Feldnamen in der 'no-cache'-Direktive im 'Cache-Control'-Header ab. |
| **bool** [get_NoStore](./get_nostore/)() | Ruft den Wert ab, der bestimmt, ob ein Cache keinen Teil einer HTTP-Anfrage oder -Antwort speichern darf. |
| **bool** [get_NoTransform](./get_notransform/)() | Ruft den Wert ab, der bestimmt, ob ein Cache oder Proxy keinen Teil des Entity-Body ändern darf. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | Ruft den Wert ab, der bestimmt, ob der Client nur zwischengespeicherte Einträge verwenden muss. |
| **bool** [get_Private](./get_private/)() | Ruft den Wert ab, der bestimmt, ob die HTTP-Antwortnachricht oder ihr Teil für einen einzelnen Benutzer bestimmt ist und nicht von einem gemeinsam genutzten Cache zwischengespeichert werden darf. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | Ruft die Sammlung von Feldnamen in der 'private'-Direktive im 'Cache-Control'-Header ab. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Ruft den Wert ab, der bestimmt, ob der Server eine Neuvalidierung eines Cache-Eintrags erfordert, wenn er für gemeinsam genutzte User-Agent-Caches veraltet wird. |
| **bool** [get_Public](./get_public/)() | Ruft den Wert ab, der bestimmt, ob eine HTTP-Antwort von irgendeinem Cache zwischengespeichert werden kann. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Ruft den gemeinsamen maximalen Alterswert in Sekunden ab, der die 'max-age'-Direktive im 'Cache-Control'-Header oder den 'Expires'-Header für einen gemeinsamen Cache überschreibt. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Konvertiert einen übergebenen String ab dem angegebenen Index in eine Instanz der [CacheControlHeaderValue](./) Klasse. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Referenzzähler-Datenstruktur ab, die mit dem Objekt verknüpft ist. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ruft den tatsächlichen Typ des Objekts ab. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Konvertiert einen übergebenen String in eine Instanz der [CacheControlHeaderValue](./) Klasse. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht Referenzwerttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Setzt den maximalen Alterswert in Sekunden, der die Zeit bestimmt, während der der Client eine Antwort akzeptiert. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | Setzt den Wert, der bestimmt, ob der Client abgelaufene Antworten akzeptiert. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Setzt den Wert in Sekunden, der die Zeit bestimmt, während der der Client abgelaufene Antworten akzeptiert. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Setzt den Wert, der die Frischelebensdauer bestimmt. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Setzt den Wert, der bestimmt, ob der Server eine Neuvalidierung eines Cache-Eintrags erfordert, wenn er veraltet wird. |
| void [set_NoCache](./set_nocache/)(**bool**) | Setzt den Wert, der bestimmt, ob der Client eine zwischengespeicherte Antwort akzeptiert. |
| void [set_NoStore](./set_nostore/)(**bool**) | Setzt den Wert, der bestimmt, ob ein Cache keinen Teil einer HTTP-Anfrage oder -Antwort speichern darf. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Setzt den Wert, der bestimmt, ob ein Cache oder Proxy keinen Teil des Entity-Body ändern darf. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | Setzt den Wert, der bestimmt, ob der Client nur zwischengespeicherte Einträge verwenden muss. |
| void [set_Private](./set_private/)(**bool**) | Setzt den Wert, der bestimmt, ob die HTTP-Antwortnachricht oder ihr Teil für einen einzelnen Benutzer bestimmt ist und nicht von einem gemeinsam genutzten Cache zwischengespeichert werden darf. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Setzt den Wert, der bestimmt, ob der Server eine Neuvalidierung eines Cache-Eintrags erfordert, wenn er für gemeinsam genutzte User-Agent-Caches veraltet wird. |
| void [set_Public](./set_public/)(**bool**) | Setzt den Wert, der bestimmt, ob eine HTTP-Antwort von irgendeinem Cache zwischengespeichert werden kann. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Setzt den gemeinsamen maximalen Alterswert in Sekunden, der die 'max-age'-Direktive im 'Cache-Control'-Header oder den 'Expires'-Header für einen gemeinsamen Cache überschreibt. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ruft den aktuellen Wert des gemeinsamen Referenzzählers ab. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht das Konvertieren benutzerdefinierter Objekte zu einem String. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Versucht, einen übergebenen String in eine Instanz der [CacheControlHeaderValue](./) Klasse zu konvertieren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert die C# typeof([System.Object](../../system/object/))-Konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [ICloneable](../../system/icloneable/)
* Namensraum [System::Net::Http::Headers](../)
* Bibliothek [Aspose.Slides](../../)