---
title: operator>>()
second_title: Aspose.Slides C++ API referencia
description: Karakterláncot kér le a bemeneti adatfolyamból UTF-8 kódolással.
type: docs
weight: 3004
url: /hu/system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String\&) function

Lekér egy karakterláncot a bemeneti adatfolyamból UTF-8 kódolással.

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| in | std::istream\& | Egy bemeneti adatfolyam objektum (**basic_ostream**-t **char**-ral példányosítva). |
| str | [String](../string/)\& | Egy karakterlánc, amelyből a bemeneti adatfolyamból olvas. |

### Visszatérési érték

Egy bemeneti adatfolyam, amelyből a karakterlánc ki lett nyerve.

## System::operator>>(std::wistream\&, String\&) function

Lekér egy karakterláncot a bemeneti adatfolyamból.

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| in | std::wistream\& | Egy bemeneti adatfolyam objektum (**basic_ostream**-t ****wchar_t****-ral példányosítva). |
| str | [String](../string/)\& | Egy karakterlánc, amelyből a bemeneti adatfolyamból olvas. |

### Visszatérési érték

Egy bemeneti adatfolyam, amelyből a karakterlánc ki lett nyerve.

## Lásd még

* Osztály [String](../string/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)