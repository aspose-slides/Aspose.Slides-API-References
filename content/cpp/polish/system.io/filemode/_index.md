---
title: FileMode
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa, w jaki sposób plik powinien zostać otwarty.
type: docs
weight: 508
url: /pl/system.io/filemode/
---
## FileMode enum

Określa, w jaki sposób plik powinien zostać otwarty.

```cpp
enum class FileMode
```

### Wartości

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| CreateNew | 1 | Utwórz nowy plik. Jeśli plik już istnieje, zostaje zgłoszony wyjątek. |
| Create | 2 | Utwórz nowy plik. Jeśli plik już istnieje, zostaje nadpisany. |
| Open | 3 | Otwórz istniejący plik. Jeśli plik nie istnieje, zostaje zgłoszony wyjątek. |
| OpenOrCreate | 4 | Otwórz istniejący plik lub utwórz nowy, jeśli nie istnieje. |
| Truncate | 5 | Otwórz istniejący plik i przytnij go, aby był pusty. Jeśli plik nie istnieje, zostaje zgłoszony wyjątek. |
| Append | 6 | Otwórz istniejący plik i przejdź do jego końca lub utwórz nowy, jeśli nie istnieje. |

## Zobacz także

* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)