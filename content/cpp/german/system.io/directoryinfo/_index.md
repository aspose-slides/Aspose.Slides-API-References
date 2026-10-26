---
title: DirectoryInfo
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen Dateisystempfad dar, ein Verzeichnis, das durch diesen Pfad referenziert wird, und bietet Instanzmethoden zum Manipulieren von Verzeichnissen. Objekte dieser Klasse sollten nur über die Funktion System::MakeObject() alloziert werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 248
url: /de/system.io/directoryinfo/
---
## DirectoryInfo Klasse

Stellt einen Dateisystempfad dar, ein Verzeichnis, das durch diesen Pfad referenziert wird, und bietet Instanzmethoden zum Manipulieren von Verzeichnissen. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Umwickeln Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/) Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [Create](./create/)() | Erstellt ein Verzeichnis am Pfad, der vom aktuellen Objekt repräsentiert wird. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | Erstellt Unterverzeichnisse am angegebenen Pfad. |
| void [Delete](./delete/)() override | Entfernt das Verzeichnis, auf das der vom aktuellen Objekt repräsentierte Pfad verweist, falls das Verzeichnis leer ist. |
| void [Delete](./delete/)(**bool**) | Entfernt das Verzeichnis, auf das der vom aktuellen Objekt repräsentierte Pfad verweist. Ein Parameter gibt an, ob der Inhalt des Verzeichnisses rekursiv entfernt werden soll, falls das Verzeichnis nicht leer ist. |
| [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | Konstruiert eine Instanz der Klasse [DirectoryInfo](./) am angegebenen Pfad. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | Gibt eine aufzählbare Sammlung zurück, die alle im vom aktuellen Objekt repräsentierten Verzeichnis befindlichen Unterverzeichnisse enthält. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis bzw. den gesamten Verzeichnisbaum, der in diesem Verzeichnis verwurzelt ist, nach Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | Gibt eine aufzählbare Sammlung zurück, die alle im vom aktuellen Objekt repräsentierten Verzeichnis befindlichen Dateien enthält. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Dateien, die die angegebenen Suchkriterien erfüllen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis bzw. den gesamten Verzeichnisbaum, der in diesem Verzeichnis verwurzelt ist, nach Dateien, die die angegebenen Suchkriterien erfüllen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Gibt eine aufzählbare Sammlung zurück, die alle im vom aktuellen Objekt repräsentierten Verzeichnis befindlichen Dateien und Unterverzeichnisse enthält. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Dateien und Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis bzw. den gesamten Verzeichnisbaum, der in diesem Verzeichnis verwurzelt ist, nach Dateien und Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Tut nichts. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Gibt die Attribute der vom aktuellen Objekt repräsentierten Entität zurück. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Gibt die Erstellungszeit der vom aktuellen Objekt repräsentierten Entität als lokale Zeit zurück. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Gibt die Erstellungszeit der vom aktuellen Objekt repräsentierten Entität als UTC-Zeit zurück. |
| **bool** [get_Exists](./get_exists/)() override | Bestimmt, ob der vom aktuellen Objekt repräsentierte Pfad auf ein existierendes Verzeichnis verweist. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Gibt die Erweiterung der vom aktuellen Objekt repräsentierten Datei zurück. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Gibt den vollständigen Namen (einschließlich Pfad) der vom aktuellen Objekt repräsentierten Entität zurück. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Gibt die letzte Zugriffszeit der vom aktuellen Objekt repräsentierten Entität als lokale Zeit zurück. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Gibt die letzte Zugriffszeit der vom aktuellen Objekt repräsentierten Entität als UTC-Zeit zurück. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Gibt die letzte Schreibzeit der vom aktuellen Objekt repräsentierten Entität als lokale Zeit zurück. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Gibt die letzte Schreibzeit der vom aktuellen Objekt repräsentierten Entität als UTC-Zeit zurück. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Gibt den Namen der Entität zurück, auf die der vom aktuellen Objekt repräsentierte Pfad verweist. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | Gibt einen Shared-Pointer auf ein [DirectoryInfo](./)-Objekt zurück, das einen Pfad darstellt, der auf das übergeordnete Verzeichnis des vom aktuellen Objekt repräsentierten Verzeichnisses verweist. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | Gibt einen Shared-Pointer auf ein [DirectoryInfo](./)-Objekt zurück, das einen Pfad darstellt, der auf das Stammverzeichnis des vom aktuellen Objekt repräsentierten Verzeichnisses verweist. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die mit dem Objekt verbunden ist. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | Gibt ein Array zurück, das Shared-Pointer auf [DirectoryInfo](./)-Objekte enthält, die alle im vom aktuellen Objekt repräsentierten Verzeichnis befindlichen Unterverzeichnisse darstellen. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis bzw. den gesamten Verzeichnisbaum, der in diesem Verzeichnis verwurzelt ist, nach Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | Gibt ein Array zurück, das Shared-Pointer auf [FileInfo](../fileinfo/)-Objekte enthält, die alle im vom aktuellen Objekt repräsentierten Verzeichnis befindlichen Unterverzeichnisse darstellen. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Dateien, die die angegebenen Suchkriterien erfüllen. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis bzw. den gesamten Verzeichnisbaum, der in diesem Verzeichnis verwurzelt ist, nach Dateien, die die angegebenen Suchkriterien erfüllen. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | Gibt ein Array zurück, das Shared-Pointer auf [FileSystemInfo](../filesysteminfo/)-Objekte enthält, die alle im vom aktuellen Objekt repräsentierten Verzeichnis befindlichen Dateien und Unterverzeichnisse darstellen. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis nach Dateien und Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Durchsucht das vom aktuellen Objekt repräsentierte Verzeichnis bzw. den gesamten Verzeichnisbaum, der in diesem Verzeichnis verwurzelt ist, nach Dateien und Verzeichnissen, die die angegebenen Suchkriterien erfüllen. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Verschiebt das vom aktuellen Objekt repräsentierte Verzeichnis und dessen gesamten Inhalt an den angegebenen Ort. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert eigentlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert eigentlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialiserung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialiserung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| void [Refresh](../filesysteminfo/refresh/)() | Aktualisiert den Zustand des aktuellen Objekts. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Setzt die angegebenen Attribute auf die vom aktuellen Objekt repräsentierte Entität. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Setzt die Erstellungszeit der vom aktuellen Objekt repräsentierten Entität als lokale Zeit. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Setzt die Erstellungszeit der vom aktuellen Objekt repräsentierten Entität als UTC-Zeit. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Setzt die letzte Zugriffszeit der vom aktuellen Objekt repräsentierten Entität als lokale Zeit. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Setzt die letzte Zugriffszeit der vom aktuellen Objekt repräsentierten Entität als UTC-Zeit. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Setzt die letzte Schreibzeit der vom aktuellen Objekt repräsentierten Entität als lokale Zeit. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Setzt die letzte Schreibzeit der vom aktuellen Objekt repräsentierten Entität als UTC-Zeit. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen weak pointer (statt shared). Erlaubt das Umschalten von Zeigern in Containern in den weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Gibt einen String zurück, der den vom aktuellen Objekt repräsentierten Pfad enthält. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten Smart-Pointer oder ThisProtector verwendet werden. |
| virtual [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [FileSystemInfo](../filesysteminfo/)
* Namensraum [System::IO](../)
* Bibliothek [Aspose.Slides](../../)