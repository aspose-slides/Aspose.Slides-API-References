---
title: FileStream()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Tworzy nową instancję klasy FileStream i inicjalizuje ją przy użyciu określonych parametrów.
type: docs
weight: 1
url: /pl/system.io/filestream/filestream/
---
## FileStream::FileStream(const String&, FileMode) konstruktor


Tworzy nową instancję klasy [FileStream](../) i inicjalizuje ją przy użyciu określonych parametrów.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Ścieżka do pliku, który ma zostać otwarty. |
| mode | [FileMode](../../filemode/) | Określa tryb otwierania pliku. |

## FileStream::FileStream(const String&, FileMode, FileAccess, FileShare, int32_t, FileOptions) konstruktor


Tworzy nową instancję klasy [FileStream](../) i inicjalizuje ją przy użyciu określonych parametrów.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Ścieżka do pliku, który ma zostać otwarty. |
| mode | [FileMode](../../filemode/) | Określa tryb otwierania pliku. |
| access | [FileAccess](../../fileaccess/) | Żądany typ dostępu. |
| share | [FileShare](../../fileshare/) | Typ dostępu, jaki inne obiekty [FileStream](../) mają do otwartego pliku. |
| buffer_size | **int32_t** | Liczba bajtów buforowanych podczas operacji odczytu i zapisu. |
| options | [FileOptions](../../fileoptions/) | Dodatkowe opcje. |

## FileStream::FileStream(const String&, FileMode, FileAccess, FileShare, int32_t, bool) konstruktor


Tworzy nową instancję klasy [FileStream](../) i inicjalizuje ją przy użyciu określonych parametrów.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | Ścieżka do pliku, który ma zostać otwarty. |
| mode | [FileMode](../../filemode/) | Określa tryb otwierania pliku. |
| access | [FileAccess](../../fileaccess/) | Żądany typ dostępu. |
| share | [FileShare](../../fileshare/) | Typ dostępu, jaki inne obiekty [FileStream](../) mają do otwartego pliku. |
| buffer_size | **int32_t** | Liczba bajtów buforowanych podczas operacji odczytu i zapisu. |
| useAsync | **bool** | Określa, czy używać asynchronicznego I/O czy synchronicznego I/O. |
## Uwagi



Podstawowy system operacyjny może nie obsługiwać asynchronicznego I/O. 

## FileStream::FileStream(const FileStream&) konstruktor




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## Zobacz również

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Klasa [String](../../../system/string/)
* Klasa [FileStream](../)
* Przestrzeń nazw [System::IO](../../)
* Library [Aspose.Slides](../../../)