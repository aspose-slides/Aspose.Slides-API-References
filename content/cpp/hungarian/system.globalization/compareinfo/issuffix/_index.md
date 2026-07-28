---
title: IsSuffix()
second_title: Aspose.Slides C++ API referencia
description: Ellenőrzi, hogy a megadott karakterlánc a megadott utótaggal végződik-e a megadott összehasonlítási beállítások használatával.
type: docs
weight: 118
url: /hu/system.globalization/compareinfo/issuffix/
---
## CompareInfo::IsSuffix(const String\&, const String\&, CompareOptions) const metódus

Ellenőrzi, hogy a megadott karakterlánc a megadott utótaggal végződik-e a megadott összehasonlítási opciók segítségével.

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix, CompareOptions options) const
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | Forrás karakterlánc. |
| suffix | const [String](../../../system/string/)\& | Utótag karakterlánc. |
| options | [CompareOptions](../../compareoptions/) | Összehasonlítási beállítások. |

### Return Value

Igaz, ha a karakterlánc utótaggal végződik; egyébként hamis.

## CompareInfo::IsSuffix(const String\&, const String\&) const metódus

Ellenőrzi, hogy a megadott karakterlánc a megadott utótaggal végződik-e.

```cpp
virtual bool System::Globalization::CompareInfo::IsSuffix(const String &source, const String &suffix) const
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | const [String](../../../system/string/)\& | Forrás karakterlánc. |
| suffix | const [String](../../../system/string/)\& | Utótag karakterlánc. |

### Return Value

Igaz, ha a karakterlánc utótaggal végződik; egyébként hamis.

## See Also

* Enum [CompareOptions](../../compareoptions/)
* Osztály [String](../../../system/string/)
* Osztály [CompareInfo](../)
* Névtér [System::Globalization](../../)
* Könyvtár [Aspose.Slides](../../../)