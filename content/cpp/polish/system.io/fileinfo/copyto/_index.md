---
title: CopyTo()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Kopiuje plik reprezentowany przez bieżący obiekt do określonej lokalizacji. Jeśli plik docelowy już istnieje, kopiowanie kończy się niepowodzeniem.
type: docs
weight: 105
url: /pl/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) metoda

Kopiuje plik reprezentowany przez bieżący obiekt do określonej lokalizacji. Jeśli plik docelowy już istnieje, kopiowanie kończy się niepowodzeniem.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Nazwa pliku docelowego |

### Wartość zwracana

Obiekt [FileInfo](../) reprezentujący kopię

## FileInfo::CopyTo(const String\&, bool) metoda

Kopiuje plik reprezentowany przez bieżący obiekt do określonej lokalizacji. Parametr określa, czy istniejący plik docelowy ma zostać nadpisany.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | Nazwa pliku docelowego |
| overwrite | **bool** | True, jeśli istniejący plik docelowy ma zostać nadpisany, false, jeśli kopiowanie ma się nie powieść, gdy plik docelowy już istnieje |

### Wartość zwracana

Obiekt [FileInfo](../) reprezentujący kopię

## Zobacz także

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Klasa [String](../../../system/string/)
* Klasa [FileInfo](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)