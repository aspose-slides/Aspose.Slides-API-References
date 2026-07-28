---
title: Replace()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zastępuje zawartość określonego pliku docelowego plikiem reprezentowanym przez bieżący obiekt FileInfo i tworzy kopię zapasową zastąpionego pliku.
type: docs
weight: 131
url: /pl/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) metoda


Zastępuje zawartość określonego pliku docelowego plikiem reprezentowanym przez bieżący obiekt [FileInfo](../) oraz tworzy kopię zapasową zastąpionego pliku.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Nazwa pliku do zastąpienia |
| destinationBackupFileName | const [String](../../../system/string/)\& | Nazwa pliku kopii zapasowej |

### Wartość zwracana

Obiekt FileInfor, który reprezentuje plik wskazywany przez **destinationFileName**

## FileInfo::Replace(const String\&, const String\&, bool) metoda


Zastępuje zawartość określonego pliku docelowego plikiem reprezentowanym przez bieżący obiekt [FileInfo](../) oraz tworzy kopię zapasową zastąpionego pliku.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Nazwa pliku do zastąpienia |
| destinationBackupFileName | const [String](../../../system/string/)\& | Nazwa pliku kopii zapasowej |
| ignoreMetadataErrors | **bool** | Określa, czy błędy scalania z zastąpionego pliku do pliku zastępującego powinny być ignorowane (true) czy nie (false) |

### Wartość zwracana

Obiekt FileInfor, który reprezentuje plik wskazywany przez **destinationFileName**

## Zobacz także

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Klasa [String](../../../system/string/)
* Klasa [FileInfo](../)
* Przestrzeń nazw [System::IO](../../)
* Library [Aspose.Slides](../../../)