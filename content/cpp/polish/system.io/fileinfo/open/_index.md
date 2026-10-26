---
title: Open()
second_title: Aspose.Slides for C++ - Referencja API
description: Otwiera plik reprezentowany przez bieżący obiekt w określonym trybie do odczytu i zapisu oraz bez udostępniania.
type: docs
weight: 183
url: /pl/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) metoda

Otwiera plik reprezentowany przez bieżący obiekt w określonym trybie do odczytu i zapisu oraz bez udostępniania.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Określa tryb, w którym należy otworzyć plik |

### Wartość zwracana

Obiekt [FileStream](../../filestream/) powiązany z plikiem reprezentowanym przez bieżący obiekt

## FileInfo::Open(FileMode, FileAccess) metoda

Otwiera plik reprezentowany przez bieżący obiekt w określonym trybie, z określonym typem dostępu i bez udostępniania.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Określa tryb, w którym należy otworzyć plik |
| access | [FileAccess](../../fileaccess/) | Żądany typ dostępu |

### Wartość zwracana

Obiekt [FileStream](../../filestream/) powiązany z plikiem reprezentowanym przez bieżący obiekt

## FileInfo::Open(FileMode, FileAccess, FileShare) metoda

Otwiera plik reprezentowany przez bieżący obiekt w określonym trybie, z określonym typem dostępu i opcją udostępniania.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Określa tryb, w którym należy otworzyć plik |
| access | [FileAccess](../../fileaccess/) | Żądany typ dostępu |
| share | [FileShare](../../fileshare/) | Typ dostępu, jaki inne obiekty [FileStream](../../filestream/) mają do otwartego pliku |

### Wartość zwracana

Obiekt [FileStream](../../filestream/) powiązany z plikiem reprezentowanym przez bieżący obiekt

## Zobacz także

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Klasa [FileInfo](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)