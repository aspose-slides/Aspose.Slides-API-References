---
title: Create()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nowy plik (lub nadpisuje istniejący) i otwiera go do odczytu i zapisu, używając określonego rozmiaru bufora i opcji.
type: docs
weight: 53
url: /pl/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) metoda

Tworzy nowy plik (lub nadpisuje istniejący) i otwiera go do odczytu i zapisu, używając określonego rozmiaru bufora i opcji.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Ścieżka pliku do utworzenia lub nadpisania |
| bufferSize | **int32_t** | Liczba bajtów buforowanych podczas odczytu i zapisu pliku |
| options | [FileOptions](../../fileoptions/) | Określa sposób tworzenia lub nadpisywania pliku |

### Wartość zwracana

Wskaźnik współdzielony do obiektu [FileStream](../../filestream/) powiązanego z określonym plikiem

## Zobacz także

* Wyliczenie [FileOptions](../../fileoptions/)
* Definicja typu [FileStreamPtr](../../../system/filestreamptr/)
* Klasa [String](../../../system/string/)
* Klasa [File](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)