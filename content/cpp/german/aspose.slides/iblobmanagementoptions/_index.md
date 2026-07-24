---
title: IBlobManagementOptions
second_title: Aspose.Slides für C++ API Referenz
description: Ein Binary Large Object (BLOB) ist ein binäres Datum, das als einzelne Einheit gespeichert wird - d.h. ein BLOB kann ein Audio, Video oder die Präsentation selbst sein. Es werden verschiedene Techniken eingesetzt, um den Speicherverbrauch beim Arbeiten mit BLOBs zu optimieren - wobei das BLOB bereits in der Präsentation gespeichert ist oder später programmgesteuert hinzugefügt werden kann. Mit IBlobManagementOptions können Sie verschiedene Verhaltensaspekte im Umgang mit BLOBs für die Lebensdauer der IPresentation-Instanz ändern.
type: docs
weight: 1535
url: /de/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions Klasse

Ein Binary Large Object (BLOB) ist ein binäres Datum, das als einzelne Einheit gespeichert wird – d. h. ein BLOB kann ein Audio, Video oder eine Präsentation selbst sein. Es werden verschiedene Techniken eingesetzt, um den Speicherverbrauch beim Arbeiten mit BLOBs zu optimieren – sei es, dass das BLOB bereits in der Präsentation gespeichert ist oder später programmgesteuert hinzugefügt wird. Mit [IBlobManagementOptions](./) können Sie verschiedene Verhaltensaspekte im Umgang mit BLOBs für die Lebensdauer der [IPresentation](../ipresentation/) Instanz ändern.

```cpp
class IBlobManagementOptions : public virtual System::Object
```

## Methoden

| Method | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaN-Werte als gleich angesehen werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaN-Werte als gleich angesehen werden, obwohl gemäß IEC 60559:1989 NaN zu keinem Wert gleich ist, einschließlich NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() | Diese Eigenschaft legt fest, ob temporäre Dateien beim Arbeiten mit BLOBs erstellt werden können, was den Speicherverbrauch erheblich reduziert, aber Berechtigungen zum Erstellen von Dateien erfordert. |
| virtual **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() | Definiert die maximale Gesamtspeichermenge (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn diese Grenze erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) eingesetzt. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen. |
| virtual [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() | Diese Eigenschaft legt fest, ob eine Instanz der [Presentation](../presentation/) Klasse Eigentümer der Quelle – Datei oder Stream – während der Lebensdauer der Instanz sein kann. Ist die Instanz Eigentümer, wird die Quelle gesperrt. Dies verbessert den Speicherverbrauch und die Leistung beim Arbeiten mit BLOBs, aber die Quelle (Stream oder Datei) kann während der Lebensdauer von [Presentation](../presentation/) nicht geändert werden. Dies ist ein Beispiel: |
| virtual [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() | Der Stamm-Pfad, unter dem temporäre Dateien erstellt werden. [System](../../system/) temporäres Verzeichnis wird standardmäßig verwendet. Der Hostprozess sollte über Berechtigungen zum Erstellen von Dateien und Ordnern dort verfügen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Referenzzähler-Datenstruktur ab, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/) Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ruft den tatsächlichen Typ des Objekts ab. Analog zum C# [System.Object.GetType()](../../system/object/gettype/) Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert eigentlich nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert eigentlich nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die geteilte Referenzzähler um den angegebenen Wert. |
| virtual void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) | Diese Eigenschaft legt fest, ob temporäre Dateien beim Arbeiten mit BLOBs erstellt werden können, was den Speicherverbrauch erheblich reduziert, aber Berechtigungen zum Erstellen von Dateien erfordert. |
| virtual void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) | Definiert die maximale Gesamtspeichermenge (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn diese Grenze erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) eingesetzt. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen. |
| virtual void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) | Diese Eigenschaft legt fest, ob eine Instanz der [Presentation](../presentation/) Klasse Eigentümer der Quelle – Datei oder Stream – während der Lebensdauer der Instanz sein kann. Ist die Instanz Eigentümer, wird die Quelle gesperrt. Dies verbessert den Speicherverbrauch und die Leistung beim Arbeiten mit BLOBs, aber die Quelle (Stream oder Datei) kann während der Lebensdauer von [Presentation](../presentation/) nicht geändert werden. Dies ist ein Beispiel: |
| virtual void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) | Der Stamm-Pfad, unter dem temporäre Dateien erstellt werden. [System](../../system/) temporäres Verzeichnis wird standardmäßig verwendet. Der Hostprozess sollte über Berechtigungen zum Erstellen von Dateien und Ordnern dort verfügen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ruft den aktuellen Wert des geteilten Referenzzählers ab. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den geteilten Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/) Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)