---
title: Task
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine asynchrone Operation dar, die abgewartet und mit anderen Tasks kombiniert werden kann.
type: docs
weight: 66
url: /de/system.threading.tasks/task/
---
## Task Klasse

Stellt eine asynchrone Operation dar, die abgewartet und mit anderen Tasks zusammengesetzt werden kann.

```cpp
class Task : public System::IDisposable
```

## Methods

| Methode | Beschreibung |
| --- | --- |
| void [Activate](./activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Aktiviert den Task zur Ausführung auf einem Scheduler. |
| void [AddCompletionAction](./addcompletionaction/)(const [Action](../../system/action/)<>\&) | Fügt eine Fortsetzungsaktion hinzu, die bei Abschluss ausgeführt wird. |
| void [Cancel](./cancel/)() | Markiert den Task als abgebrochen und beendet den Task. |
| void [Complete](./complete/)() | Markiert den Task als abgeschlossen und beendet den Task. |
| [Runtime::CompilerServices::ConfiguredTaskAwaitable](../../system.runtime.compilerservices/configuredtaskawaitable/) [ConfigureAwait](./configureawait/)(**bool**) const | Konfiguriert, wie await-Aufrufe für diesen Task sich in Bezug auf das Kontext-Capturing verhalten sollen. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Erstellt eine Fortsetzung, die ausgeführt wird, wenn der Task abgeschlossen ist. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | Erstellt eine Fortsetzung, die ausgeführt wird, wenn der Task abgeschlossen ist. |
| void [Deactivate](./deactivate/)() | Deaktiviert den Task für die Ausführung auf seinem aktuellen Scheduler, falls vorhanden. |
| void [Dispose](./dispose/)() override | Gibt Ressourcen frei, die mit dem Task verbunden sind. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mittels C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-stilisierten Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-stilisierten Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| void [Execute](./execute/)() | Führt die Funktion des Tasks aus. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](./get_asyncstate/)() const | Liefert das benutzerdefinierte Zustandsobjekt, das mit dem Task verknüpft ist. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](./get_completedtask/)() | Liefert einen abgeschlossenen Task (Singleton). |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](./get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](./get_exception/)() const | Liefert die ID für den Task. |
| **int32_t** [get_Id](./get_id/)() const |  |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | Liefert, ob der Task aufgrund einer Abbruchoperation abgeschlossen wurde. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | Liefert, ob der Task abgeschlossen ist. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | Liefert, ob der Task aufgrund einer nicht abgefangenen Ausnahme abgeschlossen wurde. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](./get_scheduler/)() const | Liefert den Scheduler, der mit diesem Task verknüpft ist. |
| [TaskStatus](../taskstatus/) [get_Status](./get_status/)() const | Liefert den aktuellen Status des Tasks. |
| [Runtime::CompilerServices::TaskAwaiter](../../system.runtime.compilerservices/taskawaiter/) [GetAwaiter](./getawaiter/)() const | Liefert einen Awaiter für diesen Task zur Verwendung mit Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzählungs-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts; initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Subklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts; initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Subklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [RunSynchronously](./runsynchronously/)() | Führt den Task synchron im aktuellen Thread aus. |
| void [RunSynchronously](./runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Führt den Task synchron mit dem angegebenen Scheduler aus. |
| void [set_Function](./set_function/)(const [FunctionT](./functiont/)\&) | Setzt die interne auszuführende Funktion. |
| void [set_Scheduler](./set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Setzt den Scheduler, der mit diesem Task verknüpft ist. |
| void [set_Status](./set_status/)([TaskStatus](../taskstatus/)) | Setzt den Task-Status. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und liefert den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [Start](./start/)() | Startet die Task-Ausführung mit dem Standard-Scheduler. |
| void [Start](./start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Startet die Task-Ausführung mit dem angegebenen Scheduler. |
| [Task](./task/)(const [Action](../../system/action/)<>\&) | Konstruiert ein [Task](./) mit einer auszuführenden Aktion. |
| [Task](./task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Konstruiert ein [Task](./) mit einer Aktion und einem Abbruch-Token. |
| [Task](./task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Konstruiert ein [Task](./) mit einer zustandsbehafteten Aktion und einem Zustandsobjekt. |
| [Task](./task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Konstruiert ein [Task](./) mit einer zustandsbehafteten Aktion, einem Zustand und einem Abbruch-Token. |
| [Task](./task/)() | Interner Konstruktor zum Erzeugen nicht initialisierter Tasks. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte zu einem String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| void [Wait](./wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Wartet darauf, dass der Task mit Unterstützung für Abbruch abgeschlossen wird. |
| void [Wait](./wait/)() | Wartet darauf, dass der Task abgeschlossen wird. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
| [~Task](./~task/)() | Destruktor. |

## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [FunctionT](./functiont/) | Interne Implementierung. Nicht für Benutzercode. |

## Hinweise

Stellt eine C++-Implementierung bereit, die der [System.Threading.Tasks.Task](./) in .NET ähnelt und Abbruch, Fortsetzungen sowie async/await-Muster unterstützt.

## Siehe auch

* Klasse [IDisposable](../../system/idisposable/)
* Namensraum [System::Threading::Tasks](../)
* Bibliothek [Aspose.Slides](../../)