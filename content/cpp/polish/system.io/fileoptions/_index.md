---
title: FileOptions
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Reprezentuje zaawansowane opcje tworzenia obiektu FileStream.
type: docs
weight: 521
url: /pl/system.io/fileoptions/
---
## FileOptions enum

Reprezentuje zaawansowane opcje tworzenia obiektu [FileStream](../filestream/).

```cpp
enum class FileOptions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Brak dodatkowych opcji. |
| Encrypted | 16384 | Plik jest zaszyfrowany. NIE ZAIMPLEMENTOWANO. |
| DeleteOnClose | 67108864 | Plik powinien być automatycznie usunięty, gdy nie jest już używany. |
| SequentialScan | 134217728 | Plik powinien być odczytywany sekwencyjnie. |
| RandomAccess | 268435456 | Plik jest dostępny losowo. |
| Asynchronous | 1073741824 | Plik może być używany do asynchronicznych operacji we/wy. |
| WriteThrough | n/a | Wszystkie zapisy powinny trafiać bezpośrednio na dysk, pomijając jakąkolwiek pośrednią pamięć podręczną. |

## See Also

* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)