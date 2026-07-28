---
title: Start()
second_title: Aspose.Slides dla C++ Referencja API
description: Uruchamia proces z wcześniej określonymi parametrami.
type: docs
weight: 14
url: /pl/system.diagnostics/process/start/
---
## Process::Start() metoda

Uruchamia proces z wcześniej zdefiniowanymi parametrami.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) metoda

Uruchamia proces z określoną ścieżką i argumentami.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) ścieżka. |
| arguments | const [String](../../../system/string/)\& | [Process](../) parametry. |

### Wartość zwracana

[Object](../../../system/object/) przyłączony do nowo uruchomionego procesu.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) metoda

Uruchamia proces z określoną ścieżką i argumentami.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Information on process to start. |

### Wartość zwracana

[Object](../../../system/object/) przyłączony do nowo uruchomionego procesu.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Process](../)
* Klasa [String](../../../system/string/)
* Klasa [ProcessStartInfo](../../processstartinfo/)
* Przestrzeń nazw [System::Diagnostics](../../)
* Biblioteka [Aspose.Slides](../../../)