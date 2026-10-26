---
title: CheckPath()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, czy podana ścieżka jest prawidłowa, sprawdzając, czy zawiera nieprawidłowe znaki. Jeśli ścieżka zawiera nieprawidłowe znaki, wyrzucany jest wyjątek.
type: docs
weight: 209
url: /pl/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) metoda

Określa, czy podana ścieżka jest prawidłowa, sprawdzając, czy zawiera nieprawidłowe znaki. Jeśli ścieżka zawiera nieprawidłowe znaki, wyrzucany jest wyjątek.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Ścieżka do sprawdzenia |
| msg | const [String](../../../system/string/)\& | Komunikat przekazywany do konstruktora obiektu wyjątku |
| allow_empty | **bool** | Określa, czy pusty lub nullowy ciąg powinien być uznany za poprawną ścieżkę (true) lub nie (false); jeśli ten parametr ma wartość false i **path** jest pusty, wyrzucany jest ArgumentException; jeśli ten parametr ma wartość false i **path** jest null, wyrzucany jest ArgumentNullException |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [Path](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)