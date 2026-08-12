---
title: Start()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: परिभाषित पैरामीटर के साथ प्रोसेस शुरू करता है।
type: docs
weight: 14
url: /hi/system.diagnostics/process/start/
---
## Process::Start() विधि


परिभाषित पैरामीटर के साथ प्रोसेस शुरू करता है।

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) विधि


निर्दिष्ट पाथ और आर्ग्युमेंट्स के साथ प्रोसेस शुरू करता है।

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) पाथ। |
| arguments | const [String](../../../system/string/)\& | [Process](../) पैरामीटर। |

### रिटर्न मान

[Object](../../../system/object/) नया शुरू किया गया प्रोसेस से जुड़ा हुआ।

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) विधि


निर्दिष्ट पाथ और आर्ज्युमेंट्स के साथ प्रोसेस शुरू करता है।

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | प्रोसेस को शुरू करने की जानकारी। |

### रिटर्न मान

[Object](../../../system/object/) नया शुरू किया गया प्रोसेस से जुड़ा हुआ।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Process](../)
* Class [String](../../../system/string/)
* Class [ProcessStartInfo](../../processstartinfo/)
* Namespace [System::Diagnostics](../../)
* Library [Aspose.Slides](../../../)