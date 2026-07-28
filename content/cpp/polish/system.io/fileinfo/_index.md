---
title: FileInfo
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Reprezentuje ścieżkę do pliku oraz plik wskazywany przez tę ścieżkę i udostępnia metody do manipulacji nim. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to powodować błędy czasu wykonywania i/lub awarie asercji. Zawsze opakowuj tę klasę we wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu funkcjom."
type: docs
weight: 274
url: /pl/system.io/fileinfo/
---
## FileInfo klasa

Reprezentuje ścieżkę do pliku oraz plik wskazywany przez tę ścieżkę i udostępnia metody do manipulacji nim. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to skutkować błędami czasu wykonywania i/lub ustąpieniami asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej funkcjom jako argument.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Metody

| Metoda | Opis |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Otwiera plik reprezentowany przez bieżący obiekt do zapisu tekstu przy użyciu kodowania UTF-8, w trybie 'Append' bez współdzielenia. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Kopiuje plik reprezentowany przez bieżący obiekt do określonej lokalizacji. Jeśli plik docelowy już istnieje, kopiowanie kończy się niepowodzeniem. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Kopiuje plik reprezentowany przez bieżący obiekt do określonej lokalizacji. Parametr określa, czy istniejący plik docelowy powinien zostać nadpisany. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Tworzy plik w lokalizacji określonej przez ścieżkę reprezentowaną przez bieżący obiekt i otwiera go do odczytu i zapisu, w trybie przycięcia (truncate) i bez współdzielenia. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Tworzy plik w lokalizacji określonej przez ścieżkę reprezentowaną przez bieżący obiekt i otwiera go do zapisu tekstu przy użyciu kodowania UTF-8 bez współdzielenia. |
| void [Decrypt](./decrypt/)() | NIE ZAIMPLEMENTOWANO. |
| void [Delete](./delete/)() override | Usuwa plik reprezentowany przez bieżący obiekt. |
| void [Encrypt](./encrypt/)() | NIE ZAIMPLEMENTOWANO. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że według IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że według IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Wyłącznie do użytku wewnętrznego. |
| [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | Tworzy nową instancję klasy [FileInfo](./) reprezentującej określony plik. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Nic nie robi. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Zwraca atrybuty encji reprezentowanej przez bieżący obiekt. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Zwraca czas utworzenia encji reprezentowanej przez bieżący obiekt jako czas lokalny. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Zwraca czas utworzenia encji reprezentowanej przez bieżący obiekt jako czas UTC. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | Zwraca obiekt [DirectoryInfo](../directoryinfo/) reprezentujący katalog, w którym znajduje się plik reprezentowany przez bieżący obiekt. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Zwraca pełną nazwę katalogu, w którym znajduje się plik reprezentowany przez bieżący obiekt. |
| **bool** [get_Exists](./get_exists/)() override | Zwraca wartość wskazującą, czy plik istnieje. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Zwraca rozszerzenie pliku reprezentowanego przez bieżący obiekt. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Zwraca pełną nazwę (włącznie ze ścieżką) encji reprezentowanej przez bieżący obiekt. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Zwraca wartość wskazującą, czy ustawiony jest atrybut ReadOnly. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Zwraca ostatni czas dostępu do encji reprezentowanej przez bieżący obiekt jako czas lokalny. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Zwraca ostatni czas dostępu do encji reprezentowanej przez bieżący obiekt jako czas UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Zwraca ostatni czas zapisu encji reprezentowanej przez bieżący obiekt jako czas lokalny. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Zwraca ostatni czas zapisu encji reprezentowanej przez bieżący obiekt jako czas UTC. |
| **int64_t** [get_Length](./get_length/)() | Zwraca rozmiar pliku w bajtach. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Zwraca nazwę pliku. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda do C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczny do wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny do operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie w instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda do C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Przenosi plik reprezentowany przez bieżący obiekt do określonej lokalizacji. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Otwiera plik reprezentowany przez bieżący obiekt w określonym trybie do odczytu i zapisu, bez współdzielenia. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Otwiera plik reprezentowany przez bieżący obiekt w określonym trybie, z określonym typem dostępu i bez współdzielenia. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Otwiera plik reprezentowany przez bieżący obiekt w określonym trybie, z określonym typem dostępu i opcją współdzielenia. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Otwiera plik reprezentowany przez bieżący obiekt wyłącznie do odczytu, w trybie 'Open' z współdzielonym dostępem do odczytu. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Otwiera istniejący plik w lokalizacji określonej przez ścieżkę reprezentowaną przez bieżący obiekt do odczytu tekstu przy użyciu kodowania UTF-8, bez współdzielenia. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Otwiera plik reprezentowany przez bieżący obiekt wyłącznie do zapisu, w trybie 'OpenOrCreate' bez współdzielenia. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty referencyjnie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty referencyjnie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| void [Refresh](../filesysteminfo/refresh/)() | Odświeża stan bieżącego obiektu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zastępuje zawartość określonego pliku docelowego plikiem reprezentowanym przez bieżący obiekt [FileInfo](./) i tworzy kopię zapasową zastąpionego pliku. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Zastępuje zawartość określonego pliku docelowego plikiem reprezentowanym przez bieżący obiekt [FileInfo](./) i tworzy kopię zapasową zastąpionego pliku. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Ustawia podane atrybuty na encji reprezentowanej przez bieżący obiekt. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Ustawia czas utworzenia encji reprezentowanej przez bieżący obiekt jako czas lokalny. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Ustawia czas utworzenia encji reprezentowanej przez bieżący obiekt jako czas UTC. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Ustawia lub usuwa atrybut ReadOnly na pliku. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Ustawia ostatni czas dostępu encji reprezentowanej przez bieżący obiekt jako czas lokalny. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Ustawia ostatni czas dostępu encji reprezentowanej przez bieżący obiekt jako czas UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Ustawia ostatni czas zapisu encji reprezentowanej przez bieżący obiekt jako czas lokalny. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Ustawia ostatni czas zapisu encji reprezentowanej przez bieżący obiekt jako czas UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Zwraca ścieżkę reprezentowaną przez bieżący obiekt. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zniszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [FileSystemInfo](../filesysteminfo/)
* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)