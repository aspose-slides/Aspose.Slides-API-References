---
title: "System::Diagnostics"
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 456
url: /system.diagnostics/
---



## Classes

| Class | Description |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | Provides information on file version. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [PerformanceCounter](./performancecounter/) | Dummy class for PerformanceCounter-using translated code to compile. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Process](./process/) | Encapsulates process information and manipulation. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [ProcessStartInfo](./processstartinfo/) | Describes process start parameters. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [StackFrame](./stackframe/) | Gets information on single stack frame. MSVS only. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [StackTrace](./stacktrace/) | Collection of stack frames. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [Stopwatch](./stopwatch/) | Allows time measurement. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
| [TraceListener](./tracelistener/) | Interface to react to debug and trace infofmation. Objects of this class should only be allocated using [System::MakeObject()](../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../system/smartptr/) pointer and use this pointer to pass it to functions as argument. |
## Structures

| Struct | Description |
| --- | --- |
| [Debug](./debug/) | Collection of debug methods allowing it sending debug information to registered listeners. All output functions work in [Debug](./debug/) only. This is a static type with no instance services. You should never create instances of it by any means. |
| [Debugger](./debugger/) | [Debugger](./debugger/) interface. This is a static type with no instance services. You should never create instances of it by any means. |
| [Trace](./trace/) | Provides interface to access debugger trace (if any). Works in [Debug](./debug/) mode only. This is a static type with no instance services. You should never create instances of it by any means. |
## Enums

| Enum | Description |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | Style of process window. |
| [TraceEventType](./traceeventtype/) | Identifies the type of event that has caused the trace. |
| [TraceLevel](./tracelevel/) | Specifies what messages to output for the [System.Diagnostics.Debug](./debug/), [System.Diagnostics.Trace](./trace/) and System.Diagnostics.TraceSwitch classes. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | Pointer type. |
