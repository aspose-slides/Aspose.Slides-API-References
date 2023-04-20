---
title: Start()
second_title: Aspose.Slides for C++ API Reference
description: Starts process with pre-defined parameters.
type: docs
weight: 14
url: /cpp/system.diagnostics/process/start/
---
## Process::Start() method


Starts process with pre-defined parameters.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) method


Starts process with specified path and arguments.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) path. |
| arguments | const [String](../../../system/string/)\& | [Process](../) parameters. |

### Return Value

[Object](../../../system/object/) attached to newly started process.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) method


Starts process with specified path and arguments.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Information on process to start. |

### Return Value

[Object](../../../system/object/) attached to newly started process.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Process](../)
* Class [String](../../../system/string/)
* Class [ProcessStartInfo](../../processstartinfo/)
* Namespace [System::Diagnostics](../../)
* Library [Aspose.Slides](../../../)