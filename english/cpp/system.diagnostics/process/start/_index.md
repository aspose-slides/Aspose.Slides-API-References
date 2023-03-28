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

## See Also

* Class [Process](../)
* Namespace [System::Diagnostics](../../)
* Library [Aspose.Slides](../../../)
## Process::Start(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&) method


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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Process](../)
* Class [String](../../../system/string/)
* Class [Process](../)
* Namespace [System::Diagnostics](../../)
* Library [Aspose.Slides](../../../)
## Process::Start(const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\&) method


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
* Class [ProcessStartInfo](../../processstartinfo/)
* Class [Process](../)
* Namespace [System::Diagnostics](../../)
* Library [Aspose.Slides](../../../)
