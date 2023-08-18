---
title: Debug
second_title: Aspose.Slides for C++ API Reference
description: Collection of debug methods allowing it sending debug information to registered listeners. All output functions work in Debug only. This is a static type with no instance services. You should never create instances of it by any means.
type: docs
weight: 105
url: /system.diagnostics/debug/
---
## Debug struct


Collection of debug methods allowing it sending debug information to registered listeners. All output functions work in [Debug](./) only. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Debug
```

## Methods

| Method | Description |
| --- | --- |
| static void [Assert](./assert/)(**bool**) | Assert condition and send information on failure. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&) | Assert condition and send information on failure. |
| static void [Assert](./assert/)(**bool**, const char *) | Assert condition and send information on failure. |
| static void [Assert](./assert/)(**bool**, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Assert condition and send information on failure. |
| static void [Fail](./fail/)(const [String](../../system/string/)\&) | Send fail message. |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<[TraceListener](../tracelistener/)\>\>\> [get_Listeners](./get_listeners/)() | Accesses static list of listeners. |
| static void [Print](./print/)(const [String](../../system/string/)\&) | Print message to debug interface. |
| static void [Print](./print/)(const [String](../../system/string/)\&, const [System::ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Print message to debug interface. |
| static void [Write](./write/)(const [String](../../system/string/)\&) | Writes string to debug interface. |
| static void [Write](./write/)(const char_t *) | Writes string to debug interface. |
| static void [WriteIf](./writeif/)(**bool**, const [System::String](../../system/string/)\&) | Writes string to debug interface if a condition is true. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Writes line to debug interface. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Writes line to debug interface. |
| static void [WriteLine](./writeline/)(const char_t *) | Writes line to debug interface. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Writes line to debug interface. |
| static void [WriteLineIf](./writelineif/)(**bool**, const [System::String](../../system/string/)\&) | Writes line to debug interface if a condition is true. |
## See Also

* Namespace [System::Diagnostics](../)
* Library [Aspose.Slides](../../)