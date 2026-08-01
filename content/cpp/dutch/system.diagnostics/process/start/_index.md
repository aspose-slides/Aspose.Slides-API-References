---
title: Start()
second_title: Aspose.Slides voor C++ API-referentie
description: Start proces met vooraf gedefinieerde parameters.
type: docs
weight: 14
url: /nl/system.diagnostics/process/start/
---
## Process::Start() methode


Start proces met vooraf gedefinieerde parameters.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) methode


Start proces met opgegeven pad en argumenten.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) pad. |
| arguments | const [String](../../../system/string/)\& | [Process](../) parameters. |

### Retourwaarde

[Object](../../../system/object/) gekoppeld aan het nieuw gestart proces.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) methode


Start proces met opgegeven pad en argumenten.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Informatie over het proces om te starten. |

### Retourwaarde

[Object](../../../system/object/) gekoppeld aan het nieuw gestart proces.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Process](../)
* Klasse [String](../../../system/string/)
* Klasse [ProcessStartInfo](../../processstartinfo/)
* Naamruimte [System::Diagnostics](../../)
* Library [Aspose.Slides](../../../)