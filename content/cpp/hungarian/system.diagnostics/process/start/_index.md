---
title: Start()
second_title: Aspose.Slides C++ API referencia
description: Elindítja a folyamatot előre meghatározott paraméterekkel.
type: docs
weight: 14
url: /hu/system.diagnostics/process/start/
---
## Process::Start() metódus

Elindítja a folyamatot előre meghatározott paraméterekkel.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) metódus

Elindítja a folyamatot a megadott úttal és argumentumokkal.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) útvonal. |
| arguments | const [String](../../../system/string/)\& | [Process](../) paraméterek. |

### Visszatérési érték

[Object](../../../system/object/) csatolva az újonnan elindított folyamathoz.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) metódus

Elindítja a folyamatot a megadott úttal és argumentumokkal.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Információ a elindítandó folyamatról. |

### Visszatérési érték

[Object](../../../system/object/) csatolva az újonnan elindított folyamathoz.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Process](../)
* Osztály [String](../../../system/string/)
* Osztály [ProcessStartInfo](../../processstartinfo/)
* Névtér [System::Diagnostics](../../)
* Könyvtár [Aspose.Slides](../../../)