---
title: XmlReaderSettings
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt einen Satz von Funktionen an, die im XmlReader-Objekt unterstützt werden, das durch die XmlReader::Create-Methode erstellt wurde."
type: docs
weight: 443
url: /de/system.xml/xmlreadersettings/
---
## XmlReaderSettings Klasse

Gibt einen Satz von Funktionalitäten an, die im [XmlReader](../xmlreader/)-Objekt unterstützt werden, das durch die [XmlReader::Create](../xmlreader/create/)-Methode erstellt wird.

```cpp
class XmlReaderSettings : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | Erstellt eine Kopie der [XmlReaderSettings](./)-Instanz. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Gibt einen Wert zurück, der angibt, ob eine Zeichenprüfung durchgeführt werden soll. |
| **bool** [get_CloseInput](./get_closeinput/)() | Gibt einen Wert zurück, der angibt, ob der zugrunde liegende Stream oder TextReader geschlossen werden soll, wenn der Reader geschlossen wird. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Gibt das Konformitätsniveau zurück, dem [XmlReader](../xmlreader/) entsprechen wird. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | Gibt einen Wert zurück, der die Verarbeitung von DTDs bestimmt. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Gibt einen Wert zurück, der angibt, ob Kommentare ignoriert werden sollen. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | Gibt einen Wert zurück, der angibt, ob Verarbeitungsanweisungen ignoriert werden sollen. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Gibt einen Wert zurück, der angibt, ob unwesentliche Leerzeichen ignoriert werden sollen. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | Gibt den Zeilennummer-Versatz des [XmlReader](../xmlreader/)-Objekts zurück. |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | Gibt den Zeilenpositions-Versatz des [XmlReader](../xmlreader/)-Objekts zurück. |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Gibt einen Wert zurück, der die maximal zulässige Anzahl von Zeichen in einem Dokument angibt, die durch Auflösen von Entitäten entstehen. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Gibt einen Wert zurück, der die maximal zulässige Anzahl von Zeichen in einem XML-Dokument angibt. Ein Wert von Null (0) bedeutet keine Begrenzung der Dokumentgröße. Ein von Null verschiedener Wert gibt die maximale Größe in Zeichen an. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Gibt das [XmlNameTable](../xmlnametable/) zurück, das für atomisierte Zeichenkettenvergleiche verwendet wird. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Gibt einen Wert zurück, der angibt, ob die Verarbeitung von Document Type Definition (DTD) verboten werden soll. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Gibt das XmlSchemaSet zurück, das bei der Schemagültigkeitsprüfung verwendet werden soll. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Gibt einen Wert zurück, der die Einstellungen zur Schemagültigkeitsprüfung angibt. Diese Einstellung gilt für [XmlReader](../xmlreader/)-Objekte, die Schemen validieren ([XmlReaderSettings::get_ValidationType](./get_validationtype/)-Wert ist [ValidationType::Schema](../validationtype/)). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Gibt einen Wert zurück, der angibt, ob [XmlReader](../xmlreader/) bei der Lektüre Validierung oder Typzuweisung durchführen wird. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-Anweisung lock(). Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [Reset](./reset/)() | Setzt die Mitglieder der Einstellungsklasse auf ihre Standardwerte zurück. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Setzt einen Wert, der angibt, ob eine Zeichenprüfung durchgeführt werden soll. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Setzt einen Wert, der angibt, ob der zugrunde liegende Stream oder TextReader geschlossen werden soll, wenn der Reader geschlossen wird. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Setzt das Konformitätsniveau, dem [XmlReader](../xmlreader/) entsprechen wird. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Setzt einen Wert, der die Verarbeitung von DTDs bestimmt. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Setzt einen Wert, der angibt, ob Kommentare ignoriert werden sollen. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | Setzt einen Wert, der angibt, ob Verarbeitungsanweisungen ignoriert werden sollen. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Setzt einen Wert, der angibt, ob unwesentliche Leerzeichen ignoriert werden sollen. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | Setzt den Zeilennummer-Versatz des [XmlReader](../xmlreader/)-Objekts. |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | Setzt den Zeilenpositions-Versatz des [XmlReader](../xmlreader/)-Objekts. |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Setzt einen Wert, der die maximal zulässige Zeichenanzahl in einem Dokument angibt, die durch Auflösen von Entitäten entsteht. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | Setzt einen Wert, der die maximal zulässige Zeichenanzahl in einem XML-Dokument angibt. Ein Nullwert (0) bedeutet keine Begrenzung der Dokumentgröße. Ein von Null verschiedener Wert gibt die maximale Größe in Zeichen an. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Setzt das [XmlNameTable](../xmlnametable/) für atomisierte Zeichenkettenvergleiche. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Setzt einen Wert, der angibt, ob die Verarbeitung von Document Type Definition (DTD) verboten werden soll. |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Setzt das XmlSchemaSet, das bei der Schemagültigkeitsprüfung verwendet werden soll. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Setzt einen Wert, der die Einstellungen zur Schemagültigkeitsprüfung angibt. Diese Einstellung gilt für [XmlReader](../xmlreader/)-Objekte, die Schemen validieren ([XmlReaderSettings::get_ValidationType](./get_validationtype/)-Wert ist [ValidationType::Schema](../validationtype/)). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Setzt einen Wert, der angibt, ob [XmlReader](../xmlreader/) bei der Lektüre Validierung oder Typzuweisung durchführen wird. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Setzt das [XmlResolver](../xmlresolver/) zum Zugriff auf externe Dokumente. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den geteilten Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in eine Zeichenkette. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-Anweisung lock(). Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Fügt einen Ereignishandler hinzu, der ausgelöst wird, wenn der Reader Validierungsfehler erkennt. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Entfernt einen Ereignishandler, der ausgelöst wird, wenn der Reader Validierungsfehler erkennt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
|  [XmlReaderSettings](./xmlreadersettings/)() | Initialisiert eine neue Instanz der [XmlReaderSettings](./)-Klasse. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [Ptr](./ptr/) | Ein Alias für einen Shared-Pointer auf eine Instanz dieser Klasse. |

## Bemerkungen

Objekte dieser Klasse sollten ausschließlich mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Instanzen dieses Typs niemals auf dem Stack oder mit dem Operator new erzeugen, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Pointer ein und verwenden Sie diesen Pointer, um ihn als Argument an Funktionen zu übergeben.

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Xml](../)
* Bibliothek [Aspose.Slides](../../)