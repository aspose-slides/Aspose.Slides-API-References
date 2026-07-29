---
title: Start()
second_title: Aspose.Slides för C++ API-referens
description: Startar processen med fördefinierade parametrar.
type: docs
weight: 14
url: /sv/system.diagnostics/process/start/
---
## Process::Start() metod


Startar processen med fördefinierade parametrar.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) metod


Startar processen med angiven sökväg och argument.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) sökväg. |
| arguments | const [String](../../../system/string/)\& | [Process](../) parametrar. |

### Returvärde

[Object](../../../system/object/) knuten till nystartad process.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) metod


Startar processen med angiven sökväg och argument.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Information om processen att starta. |

### Returvärde

[Object](../../../system/object/) knuten till nystartad process.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Process](../)
* Klass [String](../../../system/string/)
* Klass [ProcessStartInfo](../../processstartinfo/)
* Namnrymd [System::Diagnostics](../../)
* Bibliotek [Aspose.Slides](../../../)