---
title: File
second_title: Aspose.Slides dla C++ – odniesienie do API
description: Udostępnia metody do manipulacji plikami. Jest to typ statyczny bez usług instancji. Nie należy nigdy tworzyć jego instancji w żaden sposób.
type: docs
weight: 261
url: /pl/system.io/file/
---
## File klasa

Zapewnia metody do manipulacji plikami. Jest to typ statyczny bez usług instancji. Nigdy nie należy tworzyć jego instancji w żaden sposób.

```cpp
class File
```

## Metody

| Method | Description |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Dodaje ciągi znaków z określonej kolekcji ciągów do określonego pliku przy użyciu określonego kodowania, zapisując każdy ciąg w nowej linii. Jeśli określony plik nie istnieje, zostaje utworzony. Plik jest zamykany po zapisaniu wszystkich ciągów. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Dodaje określony ciąg znaków do określonego pliku przy użyciu określonego kodowania. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Tworzy obiekt [StreamWriter](../streamwriter/), który dodaje tekst do określonego pliku przy użyciu kodowania UTF-8. Jeśli określony plik nie istnieje, zostaje utworzony. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Kopiuje określony plik do określonej lokalizacji. Jeśli plik docelowy już istnieje, parametr określa, czy ma zostać nadpisany. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Tworzy nowy plik (lub nadpisuje istniejący) i otwiera go pod kątem odczytu i zapisu, używając określonego rozmiaru bufora i opcji. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | Tworzy nowy lub otwiera istniejący plik do zapisu tekstu zakodowanego w UTF-8. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | NIE ZREALIZOWANO. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | Usuwa określony plik lub katalog. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | NIE ZREALIZOWANO. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Określa, czy określona ścieżka odnosi się do istniejącego pliku. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Zwraca atrybuty określonego podmiotu. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Zwraca czas utworzenia określonego podmiotu jako czas lokalny. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Zwraca czas utworzenia określonego podmiotu jako czas UTC. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Zwraca czas ostatniego dostępu do określonego podmiotu jako czas lokalny. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Zwraca czas ostatniego dostępu do określonego podmiotu jako czas UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Zwraca czas ostatniego zapisu określonego podmiotu jako czas lokalny. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Zwraca czas ostatniego zapisu określonego podmiotu jako czas UTC. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Przenosi określony plik do nowej lokalizacji. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Otwiera określony plik w określonym trybie do odczytu i zapisu bez udostępniania. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Otwiera określony plik w określonym trybie, z określonym typem dostępu i opcją udostępniania. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Otwiera określony plik tylko do odczytu, w trybie 'Open' z udostępnionym dostępem do odczytu. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Otwiera określony istniejący plik do odczytu tekstu przy użyciu kodowania UTF-8 bez udostępniania. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Otwiera określony plik tylko do zapisu, w trybie 'OpenOrCreate' bez udostępniania. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Odczytuje zawartość określonego pliku binarnego do tablicy bajtów. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Odczytuje zawartość określonego pliku tekstowego wiersz po wierszu do tablicy ciągów przy użyciu określonego kodowania znaków. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Odczytuje zawartość określonego pliku tekstowego do pojedynczego obiektu [String](../../system/string/) przy użyciu określonego kodowania znaków. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Odczytuje zawartość określonego pliku tekstowego wiersz po wierszu przy użyciu określonego kodowania znaków i zwraca kolekcję wyliczalną ciągów, z których każdy reprezentuje pojedynczy wiersz zawartości pliku. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Zamienia zawartość jednego pliku innym i tworzy kopię zapasową zastąpionego pliku. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Ustawia określone atrybuty na określonym pliku. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NIE ZREALIZOWANO. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NIE ZREALIZOWANO. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NIE ZREALIZOWANO. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NIE ZREALIZOWANO. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ustawia czas ostatniego zapisu określonego podmiotu jako czas lokalny. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Ustawia czas ostatniego zapisu określonego podmiotu jako czas UTC. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Nadpisuje określony plik binarny i zapisuje w nim określone bajty. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Tworzy nowy plik tekstowy lub nadpisuje istniejący i zapisuje w nim wszystkie ciągi z określonej wyliczalnej kolekcji ciągów, każdy ciąg w nowej linii, przy użyciu określonego kodowania. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Tworzy nowy plik tekstowy lub nadpisuje istniejący i zapisuje w nim wszystkie ciągi z określonej tablicy ciągów, każdy ciąg w nowej linii, przy użyciu określonego kodowania. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Tworzy nowy plik tekstowy lub nadpisuje istniejący i zapisuje w nim zawartość określonego ciągu przy użyciu określonego kodowania. |

## Pola

| Field | Description |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Domyślna wartość liczby bajtów buforowanych podczas odczytu z pliku i zapisu do pliku. |

## Zobacz także

* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)