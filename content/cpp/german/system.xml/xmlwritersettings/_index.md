---
title: XmlWriterSettings
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt einen Satz von Funktionen an, die im XmlWriter-Objekt unterstützt werden, das durch die XmlWriter::Create-Methode erstellt wird."
type: docs
weight: 586
url: /de/system.xml/xmlwritersettings/
---
## XmlWriterSettings Klasse


Gibt einen Satz von Funktionen an, die im [XmlWriter](../xmlwriter/)-Objekt unterstützt werden, das durch die [XmlWriter::Create](../xmlwriter/create/)-Methode erstellt wird.

```cpp
class XmlWriterSettings : public System::Object
```

## Methoden

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Erstellt eine Kopie der [XmlWriterSettings](./)-Instanz. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Gibt einen Wert zurück, der angibt, ob der XML-Writer überprüfen soll, dass alle Zeichen im Dokument dem Abschnitt „2.2 Characters“ der W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) entsprechen. |
| **bool** [get_CloseOutput](./get_closeoutput/)() | Gibt einen Wert zurück, der angibt, ob [XmlWriter](../xmlwriter/) beim Aufruf der [XmlWriter::Close](../xmlwriter/close/)-Methode auch den zugrunde liegenden Stream oder TextWriter schließen soll. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Gibt das Konformitätsniveau zurück, das der XML-Writer bei der Überprüfung der XML-Ausgabe verwendet. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Gibt einen Wert zurück, der angibt, ob [XmlWriter](../xmlwriter/) URI-Attribute nicht maskiert. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Gibt den zu verwendenden Textkodierungstyp zurück. |
| **bool** [get_Indent](./get_indent/)() | Gibt einen Wert zurück, der angibt, ob Elemente eingerückt werden sollen. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Gibt die Zeichenfolge zurück, die beim Einrücken verwendet wird. Diese Einstellung wird verwendet, wenn der [XmlWriterSettings::set_Indent](./set_indent/)-Wert auf **true** gesetzt ist. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | Gibt einen Wert zurück, der angibt, ob [XmlWriter](../xmlwriter/) beim Schreiben von XML-Inhalten doppelte Namespace-Deklarationen entfernen soll. Das Standardverhalten ist, dass der Writer alle im Namespace-Resolver des Writers vorhandenen Namespace-Deklarationen ausgibt. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Gibt die Zeichenfolge zurück, die für Zeilenumbrüche verwendet wird. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Gibt einen Wert zurück, der angibt, ob Zeilenumbrüche in der Ausgabe normalisiert werden sollen. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Gibt einen Wert zurück, der angibt, ob Attribute in einer neuen Zeile geschrieben werden sollen. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Gibt einen Wert zurück, der angibt, ob eine XML-Deklaration weggelassen werden soll. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | Gibt die Methode zurück, die zum Serialisieren der [XmlWriter](../xmlwriter/)-Ausgabe verwendet wird. |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Gibt einen Wert zurück, der angibt, ob [XmlWriter](../xmlwriter/) beim Aufruf der [XmlWriter::Close](../xmlwriter/close/)-Methode schließende Tags zu allen nicht geschlossenen Element-Tags hinzufügt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-[Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-[System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-[Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Subklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Subklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [Reset](./reset/)() | Setzt die Mitglieder der Einstellungs-Klasse auf ihre Standardwerte zurück. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Setzt einen Wert, der angibt, ob der XML-Writer überprüfen soll, dass alle Zeichen im Dokument dem Abschnitt „2.2 Characters“ der W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) entsprechen. |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | Setzt einen Wert, der angibt, ob [XmlWriter](../xmlwriter/) beim Aufruf der [XmlWriter::Close](../xmlwriter/close/)-Methode ebenfalls den zugrunde liegenden Stream oder TextWriter schließen soll. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Setzt das Konformitätsniveau, das der XML-Writer bei der Überprüfung der XML-Ausgabe verwendet. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | Setzt einen Wert, der angibt, ob [XmlWriter](../xmlwriter/) URI-Attribute nicht maskiert. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Setzt den zu verwendenden Textkodierungstyp. |
| void [set_Indent](./set_indent/)(**bool**) | Setzt einen Wert, der angibt, ob Elemente eingerückt werden sollen. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Setzt die Zeichenfolge, die beim Einrücken verwendet wird. Diese Einstellung wird verwendet, wenn der [XmlWriterSettings::set_Indent](./set_indent/)-Wert auf **true** gesetzt ist. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | Setzt einen Wert, der angibt, ob [XmlWriter](../xmlwriter/) beim Schreiben von XML-Inhalten doppelte Namespace-Deklarationen entfernen soll. Das Standardverhalten ist, dass der Writer alle im Namespace-Resolver des Writers vorhandenen Namespace-Deklarationen ausgibt. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Setzt die Zeichenfolge, die für Zeilenumbrüche verwendet wird. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Setzt einen Wert, der angibt, ob Zeilenumbrüche in der Ausgabe normalisiert werden sollen. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Setzt einen Wert, der angibt, ob Attribute in einer neuen Zeile geschrieben werden sollen. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | Setzt einen Wert, der angibt, ob eine XML-Deklaration weggelassen werden soll. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | Setzt einen Wert, der angibt, ob [XmlWriter](../xmlwriter/) beim Aufruf der [XmlWriter::Close](../xmlwriter/close/)-Methode schließende Tags zu allen nicht geschlossenen Element-Tags hinzufügt. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-[Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointers oder ThisProtector verwenden. |
|  [XmlWriterSettings](./xmlwritersettings/)() | Initialisiert eine neue Instanz der [XmlWriterSettings](./)-Klasse. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared-Pointer auf eine Instanz dieser Klasse. |

## Hinweise

Objekte dieser Klasse sollten ausschließlich über die [System::MakeObject()](../../system/makeobject/)-Funktion alloziert werden. Erstellen Sie niemals Instanzen dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Pointer ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. 

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Xml](../)
* Bibliothek [Aspose.Slides](../../)