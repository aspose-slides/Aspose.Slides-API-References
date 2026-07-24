---
title: FileInfo
second_title: Aspose.Slides für C++ API Referenz
description: "Stellt einen Pfad zu einer Datei und die durch diesen Pfad referenzierte Datei dar und bietet Methoden zu ihrer Manipulation. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 274
url: /de/system.io/fileinfo/
---
## FileInfo Klasse

Stellt einen Pfad zu einer Datei und die durch diesen Pfad referenzierte Datei dar und bietet Methoden zu deren Manipulation. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Öffnet eine Datei, die vom aktuellen Objekt repräsentiert wird, zum Schreiben von Text mit UTF-8-Kodierung im 'Append'-Modus ohne Sharing. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Kopiert die vom aktuellen Objekt repräsentierte Datei an den angegebenen Ort. Existiert die Zieldatei bereits, schlägt das Kopieren fehl. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Kopiert die vom aktuellen Objekt repräsentierte Datei an den angegebenen Ort. Ein Parameter gibt an, ob eine bereits vorhandene Zieldatei überschrieben werden soll. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Erzeugt eine Datei am vom Pfad des aktuellen Objekts angegebenen Ort und öffnet sie zum Lesen und Schreiben im Kürzungsmodus ohne Sharing. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Erzeugt eine Datei am vom Pfad des aktuellen Objekts angegebenen Ort und öffnet sie zum Schreiben von Text mit UTF-8-Kodierung ohne Sharing. |
| void [Decrypt](./decrypt/)() | NICHT IMPLEMENTIERT. |
| void [Delete](./delete/)() override | Entfernt die vom aktuellen Objekt repräsentierte Datei. |
| void [Encrypt](./encrypt/)() | NICHT IMPLEMENTIERT. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | Konstruiert eine neue Instanz der Klasse [FileInfo](./), die die angegebene Datei repräsentiert. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Tut nichts. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Gibt die Attribute der vom aktuellen Objekt dargestellten Entität zurück. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Gibt die Erstellungszeit der vom aktuellen Objekt dargestellten Entität als lokale Zeit zurück. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Gibt die Erstellungszeit der vom aktuellen Objekt dargestellten Entität als UTC-Zeit zurück. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | Gibt ein [DirectoryInfo](../directoryinfo/)-Objekt zurück, das ein Verzeichnis repräsentiert, in dem die vom aktuellen Objekt dargestellte Datei liegt. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Gibt den vollständigen Namen des Verzeichnisses zurück, in dem die vom aktuellen Objekt dargestellte Datei loctaed. |
| **bool** [get_Exists](./get_exists/)() override | Gibt einen Wert zurück, der angibt, ob die Datei existiert. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Gibt die Erweiterung der vom aktuellen Objekt dargestellten Datei zurück. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Gibt den vollständigen Namen (inklusive Pfad) der vom aktuellen Objekt dargestellten Entität zurück. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Gibt einen Wert zurück, der angibt, ob das ReadOnly-Attribut gesetzt ist. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Gibt die letzte Zugriffszeit der vom aktuellen Objekt dargestellten Entität als lokale Zeit zurück. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Gibt die letzte Zugriffszeit der vom aktuellen Objekt dargestellten Entität als UTC-Zeit zurück. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Gibt die letzte Schreibzeit der vom aktuellen Objekt dargestellten Entität als lokale Zeit zurück. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Gibt die letzte Schreibzeit der vom aktuellen Objekt dargestellten Entität als UTC-Zeit zurück. |
| **int64_t** [get_Length](./get_length/)() | Gibt die Größe der Datei in Bytes zurück. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Gibt den Namen der Datei zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die mit dem Objekt verbunden ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das Sentinelformat [LockContext](../../system/lockcontext/) verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Verschiebt die vom aktuellen Objekt repräsentierte Datei an den angegebenen Ort. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopiervorhaben für Unterklassen. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Öffnet die vom aktuellen Objekt repräsentierte Datei im angegebenen Modus zum Lesen und Schreiben ohne Sharing. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Öffnet die vom aktuellen Objekt repräsentierte Datei im angegebenen Modus, mit dem angegebenen Zugriffstyp und ohne Sharing. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Öffnet die vom aktuellen Objekt repräsentierte Datei im angegebenen Modus, mit dem angegebenen Zugriffstyp und der angegebenen Freigabeoption. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Öffnet die vom aktuellen Objekt repräsentierte Datei nur zum Lesen im 'Open'-Modus mit gemeinsamem Lesezugriff. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Öffnet die vorhandene Datei am vom Pfad des aktuellen Objekts angegebenen Ort zum Lesen von Text mit UTF-8-Kodierung ohne Sharing. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Öffnet die vom aktuellen Objekt repräsentierte Datei nur zum Schreiben im 'OpenOrCreate'-Modus ohne Sharing. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| void [Refresh](../filesysteminfo/refresh/)() | Aktualisiert den Zustand des aktuellen Objekts. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Ersetzt den Inhalt einer angegebenen Zieldatei durch die vom aktuellen [FileInfo](./)-Objekt repräsentierte Datei und erstellt ein Backup der ersetzten Datei. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Ersetzt den Inhalt einer angegebenen Zieldatei durch die vom aktuellen [FileInfo](./)-Objekt repräsentierte Datei und erstellt ein Backup der ersetzten Datei. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Setzt die angegebenen Attribute für die vom aktuellen Objekt dargestellte Entität. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Setzt die Erstellungszeit der vom aktuellen Objekt dargestellten Entität als lokale Zeit. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Setzt die Erstellungszeit der vom aktuellen Objekt dargestellten Entität als UTC-Zeit. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Setzt oder hebt das ReadOnly-Attribut der Datei. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Setzt die letzte Zugriffszeit der vom aktuellen Objekt dargestellten Entität als lokale Zeit. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Setzt die letzte Zugriffszeit der vom aktuellen Objekt dargestellten Entität als UTC-Zeit. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Setzt die letzte Schreibzeit der vom aktuellen Objekt dargestellten Entität als lokale Zeit. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Setzt die letzte Schreibzeit der vom aktuellen Objekt dargestellten Entität als UTC-Zeit. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Gibt einen vom aktuellen Objekt dargestellten Pfad zurück. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das Sentinelformat [LockContext](../../system/lockcontext/) verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [FileSystemInfo](../filesysteminfo/)
* Namespace [System::IO](../)
* Bibliothek [Aspose.Slides](../../)