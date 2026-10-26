---
title: Open()
second_title: Aspose.Slides pro C++ API Reference
description: Otevře soubor reprezentovaný aktuálním objektem ve specifikovaném režimu pro čtení i zápis a bez sdílení.
type: docs
weight: 183
url: /cs/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) metoda


Otevře soubor reprezentovaný aktuálním objektem ve specifikovaném režimu pro čtení i zápis a bez sdílení.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```


### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Určuje režim, ve kterém otevřít soubor |

### Return Value

Objekt [FileStream](../../filestream/) spojený se souborem reprezentovaným aktuálním objektem

## FileInfo::Open(FileMode, FileAccess) metoda


Otevře soubor reprezentovaný aktuálním objektem ve specifikovaném režimu, s určeným typem přístupu a bez sdílení.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```


### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Určuje režim, ve kterém otevřít soubor |
| access | [FileAccess](../../fileaccess/) | Požadovaný typ přístupu |

### Return Value

Objekt [FileStream](../../filestream/) spojený se souborem reprezentovaným aktuálním objektem

## FileInfo::Open(FileMode, FileAccess, FileShare) metoda


Otevře soubor reprezentovaný aktuálním objektem ve specifikovaném režimu, s určeným typem přístupu a možností sdílení.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```


### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Určuje režim, ve kterém otevřít soubor |
| access | [FileAccess](../../fileaccess/) | Požadovaný typ přístupu |
| share | [FileShare](../../fileshare/) | Typ přístupu, který mají ostatní objekty [FileStream](../../filestream/) k otevřenému souboru |

### Return Value

Objekt [FileStream](../../filestream/) spojený se souborem reprezentovaným aktuálním objektem

## Viz také

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)