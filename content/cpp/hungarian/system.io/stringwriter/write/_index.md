---
title: Write()
second_title: Aspose.Slides C++ API referencia
description: A megadott karaktert írja a streambe.
type: docs
weight: 40
url: /hu/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) metódus

A megadott karaktert írja a streambe.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char_t | Az írandó érték |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metódus

A megadott karaktertömbből a megadott részkarakter-tartományt írja a streambe.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Az írandó karaktereket tartalmazó tömb |
| index | **int32_t** | A 0-alapú index a **buffer** tömbben, ahol a írandó részkarakter-tartomány kezdődik |
| count | **int32_t** | A részkarakter-tartományban írandó karakterek száma |

## StringWriter::Write(const String\&) metódus

A megadott karakterláncot írja a streambe.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Az írandó karakterlánc |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [StringWriter](../)
* Osztály [String](../../../system/string/)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)