---
title: BlobManagementOptions
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt Optionen dar, die zur Verwaltung von BLOB-Verarbeitungsregeln und anderen BLOB-Einstellungen verwendet werden können.
type: docs
weight: 196
url: /de/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions Klasse

Stellt Optionen dar, die zur Verwaltung von BLOB-Verarbeitungsregeln und anderen BLOB-Einstellungen verwendet werden können.

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | Erstellt neue Standard-Blob-Verwaltungsoptionen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mithilfe der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert C#-ähnlichen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert C#-ähnlichen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | Diese Eigenschaft definiert, ob temporäre Dateien während der Arbeit mit BLOBs erstellt werden können, was den Speicherverbrauch stark reduziert, aber Berechtigungen zum Erstellen von Dateien erfordert. |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | Definiert die maximale Gesamtspeicherkapazität (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn diese Grenze erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) eingesetzt. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen. |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | Diese Eigenschaft definiert, ob eine Instanz der [Presentation](../presentation/) Klasse Eigentümer der Quelle – Datei oder Stream – während ihrer Lebensdauer sein kann. Wenn die Instanz Eigentümer ist, sperrt sie die Quelle. Das hilft, den Speicherverbrauch und die Leistung bei der Arbeit mit BLOBs zu verbessern, aber die Quelle (Stream oder Datei) kann während der Lebensdauer von [Presentation](../presentation/) nicht geändert werden. |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | Der Stamm-Pfad, in dem temporäre Dateien erstellt werden. Standardmäßig wird das [System](../../system/)-temporäre Verzeichnis verwendet. Der hostende Prozess sollte Berechtigungen zum Erstellen von Dateien und Ordnern dort besitzen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Referenzzähler-Datenstruktur ab, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Entspricht der C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Aktiviert das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ruft den tatsächlichen Typ des Objekts ab. Entspricht dem C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Entspricht dem C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Entspricht der C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | Diese Eigenschaft definiert, ob temporäre Dateien während der Arbeit mit BLOBs erstellt werden können, was den Speicherverbrauch stark reduziert, aber Berechtigungen zum Erstellen von Dateien erfordert. |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | Definiert die maximale Gesamtspeicherkapazität (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn diese Grenze erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) eingesetzt. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen. |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | Diese Eigenschaft definiert, ob eine Instanz der [Presentation](../presentation/) Klasse Eigentümer der Quelle – Datei oder Stream – während ihrer Lebensdauer sein kann. Wenn die Instanz Eigentümer ist, sperrt sie die Quelle. Das hilft, den Speicherverbrauch und die Leistung bei der Arbeit mit BLOBs zu verbessern, aber die Quelle (Stream oder Datei) kann während der Lebensdauer von [Presentation](../presentation/) nicht geändert werden. |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | Der Stamm-Pfad, in dem temporäre Dateien erstellt werden. Standardmäßig wird das [System](../../system/)-temporäre Verzeichnis verwendet. Der hostende Prozess sollte Berechtigungen zum Erstellen von Dateien und Ordnern dort besitzen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ruft den aktuellen Wert des geteilten Referenzzählers ab. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den geteilten Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Entspricht der C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IBlobManagementOptions](../iblobmanagementoptions/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)