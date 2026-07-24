---
title: ResultTask
second_title: Aspose.Slides für C++ API-Referenz
description: Eine Task-Spezialisierung, die bei Abschluss einen Ergebniswert zurückgibt.
type: docs
weight: 40
url: /de/system.threading.tasks/resulttask/
---
## ResultTask Klasse

Eine [Task](../task/) Spezialisierung, die bei Abschluss einen Ergebniswert zurückgibt.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ des von der Aufgabe zurückgegebenen Ergebniswerts |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [Activate](../task/activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Aktiviert die Aufgabe zur Ausführung auf einem Scheduler. |
| void [AddCompletionAction](../task/addcompletionaction/)(const [Action](../../system/action/)<>\&) | Fügt eine Fortsetzungsaktion hinzu, die nach Abschluss ausgeführt wird. |
| void [Cancel](../task/cancel/)() | Markiert die Aufgabe als abgebrochen und beendet sie. |
| void [Complete](./complete/)(const T\&) | Setzt den Ergebniswert für die Aufgabe und schließt sie ab. |
| void [Complete](../task/complete/)() | Markiert die Aufgabe als abgeschlossen und beendet sie. |
| [Runtime::CompilerServices::ConfiguredResultTaskAwaitable](../../system.runtime.compilerservices/configuredresulttaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Konfiguriert, wie Await-Aufrufe für diese Ergebnisaufgabe hinsichtlich Kontextaufnahme verhalten sollen. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>\>\&) | Erstellt eine Fortsetzung, die ausgeführt wird, wenn die Ergebnisaufgabe abgeschlossen ist. |
| [RTaskPtr](../../system/rtaskptr/)\<TNewResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>, TNewResult\>\&) | Erstellt eine Fortsetzung, die ausgeführt wird, wenn die Ergebnisaufgabe abgeschlossen ist. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Erstellt eine Fortsetzung, die ausgeführt wird, wenn die Aufgabe abgeschlossen ist. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | Erstellt eine Fortsetzung, die ausgeführt wird, wenn die Aufgabe abgeschlossen ist. |
| void [Deactivate](../task/deactivate/)() | Deaktiviert die Aufgabe für die Ausführung auf ihrem aktuellen Scheduler, falls vorhanden. |
| void [Dispose](../task/dispose/)() override | Gibt Ressourcen frei, die mit der Aufgabe verbunden sind. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach den C# [Object.Equals](../../system/object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl sie nach IEC 60559:1989 mit keinem Wert, einschließlich NaN, gleich sind. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl sie nach IEC 60559:1989 mit keinem Wert, einschließlich NaN, gleich sind. |
| void [Execute](../task/execute/)() | Führt die Funktion der Aufgabe aus. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](../task/get_asyncstate/)() const | Ruft das benutzerdefinierte Zustandsobjekt ab, das mit der Aufgabe verknüpft ist. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](../task/get_completedtask/)() | Ruft eine abgeschlossene Aufgabe (Singleton) ab. |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](../task/get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](../task/get_exception/)() const | Ruft die ID der Aufgabe ab. |
| **int32_t** [get_Id](../task/get_id/)() const |  |
| **bool** [get_IsCanceled](../task/get_iscanceled/)() const | Ermittelt, ob die Aufgabe aufgrund einer Abbruchanforderung beendet wurde. |
| **bool** [get_IsCompleted](../task/get_iscompleted/)() const | Ermittelt, ob die Aufgabe abgeschlossen ist. |
| **bool** [get_IsFaulted](../task/get_isfaulted/)() const | Ermittelt, ob die Aufgabe wegen einer nicht behandelten Ausnahme beendet wurde. |
| T [get_Result](./get_result/)() | Ruft das Ergebnis der asynchronen Operation ab. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](../task/get_scheduler/)() const | Ruft den Scheduler ab, der mit dieser Aufgabe verknüpft ist. |
| [TaskStatus](../taskstatus/) [get_Status](../task/get_status/)() const | Ruft den aktuellen Status der Aufgabe ab. |
| [Runtime::CompilerServices::ResultTaskAwaiter](../../system.runtime.compilerservices/resulttaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Ruft einen Awaiter für diese Ergebnisaufgabe zurück, der mit Await verwendet werden kann. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Referenzzähler-Datenstruktur ab, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Entspricht der C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ruft den tatsächlichen Typ des Objekts ab. Entspricht dem C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Entspricht dem C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Entspricht der C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt referenziell mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
|  [ResultTask](./resulttask/)(const [Func](../../system/func/)\<T\>\&) | Konstruiert ein [ResultTask](./) mit einer Funktion, die einen Wert zurückgibt. |
|  [ResultTask](./resulttask/)() | Interne Implementierung. Nicht für Benutzercode. |
|  [ResultTask](./resulttask/)(const T\&) | Interner Konstruktor zum Erzeugen von Ergebnisaufgaben mit angegebenem Ergebnis. |
| void [RunSynchronously](../task/runsynchronously/)() | Führt die Aufgabe synchron im aktuellen Thread aus. |
| void [RunSynchronously](../task/runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Führt die Aufgabe synchron mit dem angegebenen Scheduler aus. |
| void [set_Function](../task/set_function/)(const [FunctionT](../task/functiont/)\&) | Setzt die auszuführende interne Funktion. |
| void [set_Result](./set_result/)(const T\&) | Setzt den Ergebniswert für die Aufgabe. |
| void [set_Scheduler](../task/set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Setzt den Scheduler, der mit dieser Aufgabe verknüpft ist. |
| void [set_Status](../task/set_status/)([TaskStatus](../taskstatus/)) | Setzt den Aufgabenstatus. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Erlaubt das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ruft den aktuellen Wert des gemeinsamen Referenzzählers ab. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [Start](../task/start/)() | Startet die Aufgabenausführung mit dem Standardscheduler. |
| void [Start](../task/start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Startet die Aufgabenausführung mit dem angegebenen Scheduler. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&) | Konstruiert ein [Task](../task/) mit einer auszuführenden Aktion. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Konstruiert ein [Task](../task/) mit einer Aktion und einem Abbruch-Token. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Konstruiert ein [Task](../task/) mit einer zustandsbehafteten Aktion und Zustandsobjekt. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Konstruiert ein [Task](../task/) mit einer zustandsbehafteten Aktion, Zustand und Abbruch-Token. |
|  [Task](../task/task/)() | Interner Konstruktor zum Erzeugen nicht initialisierter Aufgaben. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Entspricht der C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| void [Wait](../task/wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Wartet auf den Abschluss der Aufgabe mit Unterstützung für Abbruch. |
| void [Wait](../task/wait/)() | Wartet auf den Abschluss der Aufgabe. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
|  [~Task](../task/~task/)() | Destruktor. |

## Anmerkungen

Stellt eine asynchrone Operation dar, die ein Ergebnis erzeugt, ähnlich wie System.Threading.Tasks.Task<TResult> in .NET

## Siehe auch

* Klasse [Task](../task/)
* Namensraum [System::Threading::Tasks](../)
* Bibliothek [Aspose.Slides](../../)