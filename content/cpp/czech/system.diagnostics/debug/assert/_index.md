---
title: Assert()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Ověří podmínku a při selhání odešle informace.
type: docs
weight: 14
url: /cs/system.diagnostics/debug/assert/
---
## Debug::Assert(bool) metoda

Assert condition and send information on failure.

```cpp
static void System::Diagnostics::Debug::Assert(bool condition)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| condition | **bool** | Condition value. |

## Debug::Assert(bool, const String\&) metoda

Assert condition and send information on failure.

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const String &message)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| condition | **bool** | Condition value. |
| message | const [String](../../../system/string/)\& | Message to populate on assertion failure. |

## Debug::Assert(bool, const char *) metoda

Assert condition and send information on failure.

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const char *message)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| condition | **bool** | Condition value. |
| message | const char * | Message to populate on assertion failure. |

## Debug::Assert(bool, const String\&, const String\&) metoda

Assert condition and send information on failure.

```cpp
static void System::Diagnostics::Debug::Assert(bool condition, const String &message, const String &detailMessage)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| condition | **bool** | Condition value. |
| message | const [String](../../../system/string/)\& | Message to populate on assertion failure. |
| detailMessage | const [String](../../../system/string/)\& | Detailed message to populate on assertion failure. |

## Viz také

* Třída [String](../../../system/string/)
* Struktura [Debug](../)
* Jmenný prostor [System::Diagnostics](../../)
* Knihovna [Aspose.Slides](../../../)