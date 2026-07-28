---
title: Open()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Otwiera wskazany plik w określonym trybie do odczytu i zapisu, bez udostępniania.
type: docs
weight: 235
url: /pl/system.io/file/open/
---
## File::Open(const String\&, FileMode) metoda


Otwiera określony plik w określonym trybie do odczytu i zapisu oraz bez udostępniania.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Ścieżka do pliku, który ma zostać otwarty |
| mode | [FileMode](../../filemode/) | Określa tryb, w którym otworzyć plik |

### Wartość zwracana

Obiekt [FileStream](../../filestream/) powiązany z otwartym plikiem

## File::Open(const String\&, FileMode, FileAccess, FileShare) metoda


Otwiera określony plik w określonym trybie, z określonym typem dostępu i opcją udostępniania.

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Ścieżka do pliku, który ma zostać otwarty |
| mode | [FileMode](../../filemode/) | Określa tryb, w którym otworzyć plik |
| access | [FileAccess](../../fileaccess/) | Żądany typ dostępu |
| share | [FileShare](../../fileshare/) | Typ dostępu, jaki inne obiekty [FileStream](../../filestream/) mają do otwartego pliku |

### Wartość zwracana

Obiekt [FileStream](../../filestream/) powiązany z otwartym plikiem

## Zobacz także

* Wyliczenie [FileMode](../../filemode/)
* Wyliczenie [FileAccess](../../fileaccess/)
* Wyliczenie [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Klasa [String](../../../system/string/)
* Klasa [File](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)