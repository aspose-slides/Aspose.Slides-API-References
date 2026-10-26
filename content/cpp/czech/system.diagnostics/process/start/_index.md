---
title: Start()
second_title: Aspose.Slides pro C++ API Reference
description: Spouští proces s předdefinovanými parametry.
type: docs
weight: 14
url: /cs/system.diagnostics/process/start/
---
## Process::Start() metoda


Spustí proces s předdefinovanými parametry.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) metoda


Spustí proces s určenou cestou a argumenty.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) cesta. |
| arguments | const [String](../../../system/string/)\& | [Process](../) parametry. |

### Návratová hodnota

[Object](../../../system/object/) připojený k nově spuštěnému procesu.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) metoda


Spustí proces s určenou cestou a argumenty.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Informace o procesu, který se má spustit. |

### Návratová hodnota

[Object](../../../system/object/) připojený k nově spuštěnému procesu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [Process](../)
* třída [String](../../../system/string/)
* třída [ProcessStartInfo](../../processstartinfo/)
* jmenný prostor [System::Diagnostics](../../)
* knihovna [Aspose.Slides](../../../)