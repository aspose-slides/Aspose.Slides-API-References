---
title: Copy()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Kopiuje określony plik do wskazanej lokalizacji. Jeśli plik docelowy już istnieje, parametr określa, czy powinien zostać nadpisany.
type: docs
weight: 40
url: /pl/system.io/file/copy/
---
## File::Copy(const String&, const String&, bool) metoda

Kopiuje wskazany plik do określonej lokalizacji. Jeśli plik docelowy już istnieje, parametr określa, czy ma zostać nadpisany.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | Ścieżka pliku do skopiowania |
| destFileName | const [String](../../../system/string/)\& | Ścieżka nowej lokalizacji pliku do skopiowania |
| overwrite | **bool** | True, jeśli istniejący plik docelowy powinien zostać nadpisany; false, jeśli kopiowanie powinno się nie powieść, gdy plik docelowy już istnieje |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [File](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)