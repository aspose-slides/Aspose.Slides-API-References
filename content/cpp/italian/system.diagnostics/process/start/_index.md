---
title: Start()
second_title: Riferimento API di Aspose.Slides per C++
description: Avvia il processo con parametri predefiniti.
type: docs
weight: 14
url: /it/system.diagnostics/process/start/
---
## Process::Start() metodo

Avvia il processo con parametri predefiniti.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) metodo

Avvia il processo con percorso e argomenti specificati.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```

### Arguments

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) percorso. |
| arguments | const [String](../../../system/string/)\& | [Process](../) parametri. |

### Valore restituito

[Object](../../../system/object/) collegato al processo appena avviato.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) metodo

Avvia il processo con percorso e argomenti specificati.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```

### Arguments

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Informazioni sul processo da avviare. |

### Valore restituito

[Object](../../../system/object/) collegato al processo appena avviato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Process](../)
* Classe [String](../../../system/string/)
* Classe [ProcessStartInfo](../../processstartinfo/)
* Spazio dei nomi [System::Diagnostics](../../)
* Libreria [Aspose.Slides](../../../)