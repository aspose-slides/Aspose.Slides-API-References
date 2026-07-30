---
title: Replace()
second_title: Referenční příručka API Aspose.Slides pro C++
description: Nahradí obsah zadaného cílového souboru souborem reprezentovaným aktuálním objektem FileInfo a vytvoří zálohu nahrazeného souboru.
type: docs
weight: 131
url: /cs/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) metoda

Nahradí obsah určeného cílového souboru souborem reprezentovaným aktuálním objektem [FileInfo](../) a vytvoří zálohu nahrazeného souboru.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Název souboru, který má být nahrazen |
| destinationBackupFileName | const [String](../../../system/string/)\& | Název záložního souboru |

### Návratová hodnota

Objekt FileInfor, který představuje soubor, na který ukazuje **destinationFileName**

## FileInfo::Replace(const String\&, const String\&, bool) metoda

Nahradí obsah určeného cílového souboru souborem reprezentovaným aktuálním objektem [FileInfo](../) a vytvoří zálohu nahrazeného souboru.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Název souboru, který má být nahrazen |
| destinationBackupFileName | const [String](../../../system/string/)\& | Název záložního souboru |
| ignoreMetadataErrors | **bool** | Určuje, zda mají být chyby sloučení z nahrazeného souboru do souboru náhrady ignorovány (true) nebo ne (false) |

### Návratová hodnota

Objekt FileInfor, který představuje soubor, na který ukazuje **destinationFileName**

## Viz také

* Definice typu [FileInfoPtr](../../../system/fileinfoptr/)
* Třída [String](../../../system/string/)
* Třída [FileInfo](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)