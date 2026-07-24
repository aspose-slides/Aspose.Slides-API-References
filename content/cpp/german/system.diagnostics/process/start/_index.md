---
title: Start()
second_title: Aspose.Slides für C++ API Referenz
description: Startet den Prozess mit vordefinierten Parametern.
type: docs
weight: 14
url: /de/system.diagnostics/process/start/
---
## Process::Start() Methode


Startet den Prozess mit vordefinierten Parametern.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) Methode


Startet den Prozess mit angegebenem Pfad und Argumenten.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) Pfad. |
| arguments | const [String](../../../system/string/)\& | [Process](../) Parameter. |

### Rückgabewert

[Object](../../../system/object/) angehängt an den neu gestarteten Prozess.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) Methode


Startet den Prozess mit angegebenem Pfad und Argumenten.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Informationen zum Starten des Prozesses. |

### Rückgabewert

[Object](../../../system/object/) angehängt an den neu gestarteten Prozess.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Process](../)
* Klasse [String](../../../system/string/)
* Klasse [ProcessStartInfo](../../processstartinfo/)
* Namensraum [System::Diagnostics](../../)
* Bibliothek [Aspose.Slides](../../../)