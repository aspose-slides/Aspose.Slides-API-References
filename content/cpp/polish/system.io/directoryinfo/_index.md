---
title: DirectoryInfo
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Reprezentuje ścieżkę systemu plików, katalog wskazywany przez tę ścieżkę oraz udostępnia metody instancyjne do manipulacji katalogami. Obiekty tej klasy powinny być tworzone wyłącznie za pomocą funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze owiń tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji."
type: docs
weight: 248
url: /pl/system.io/directoryinfo/
---
## DirectoryInfo klasa


Represents a file system path, a directory referred to by this path and provides instance methods for manipulating directories. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [Create](./create/)() | Tworzy katalog pod ścieżką reprezentowaną przez bieżący obiekt. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | Tworzy podkatalogi w podanej ścieżce. |
| void [Delete](./delete/)() override | Usuwa katalog wskazywany przez ścieżkę reprezentowaną przez bieżący obiekt, jeśli katalog jest pusty. |
| void [Delete](./delete/)(**bool**) | Usuwa katalog wskazywany przez ścieżkę reprezentowaną przez bieżący obiekt. Parametr określa, czy zawartość katalogu powinna być usunięta rekurencyjnie, jeśli katalog nie jest pusty. |
|  [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | Tworzy instancję klasy [DirectoryInfo](./) w podanej ścieżce. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | Zwraca kolekcję enumerowalną zawierającą wszystkie katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | Wyszukuje katalogi spełniające określone kryteria wyszukiwania w katalogu reprezentowanym przez bieżący obiekt. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Wyszukuje katalogi spełniające określone kryteria wyszukiwania albo w katalogu reprezentowanym przez bieżący obiekt, albo w całym drzewie katalogów, którego korzeniem jest katalog reprezentowany przez bieżący obiekt. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | Zwraca kolekcję enumerowalną zawierającą wszystkie pliki znajdujące się w katalogu reprezentowanym przez bieżący obiekt. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | Wyszukuje pliki spełniające określone kryteria wyszukiwania w katalogu reprezentowanym przez bieżący obiekt. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Wyszukuje pliki spełniające określone kryteria wyszukiwania albo w katalogu reprezentowanym przez bieżący obiekt, albo w całym drzewie katalogów, którego korzeniem jest katalog reprezentowany przez bieżący obiekt. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Zwraca kolekcję enumerowalną zawierającą wszystkie pliki i katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | Wyszukuje pliki i katalogi spełniające określone kryteria wyszukiwania w katalogu reprezentowanym przez bieżący obiekt. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Wyszukuje pliki i katalogi spełniające określone kryteria wyszukiwania albo w katalogu reprezentowanym przez bieżący obiekt, albo w całym drzewie katalogów, którego korzeniem jest katalog reprezentowany przez bieżący obiekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Nic nie robi. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Zwraca atrybuty jednostki reprezentowanej przez bieżący obiekt. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Zwraca czas utworzenia jednostki reprezentowanej przez bieżący obiekt jako czas lokalny. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Zwraca czas utworzenia jednostki reprezentowanej przez bieżący obiekt jako czas UTC. |
| **bool** [get_Exists](./get_exists/)() override | Określa, czy ścieżka reprezentowana przez bieżący obiekt odnosi się do istniejącego katalogu. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Zwraca rozszerzenie pliku reprezentowanego przez bieżący obiekt. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Zwraca pełną nazwę (łącznie ze ścieżką) jednostki reprezentowanej przez bieżący obiekt. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Zwraca czas ostatniego dostępu jednostki reprezentowanej przez bieżący obiekt jako czas lokalny. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Zwraca czas ostatniego dostępu jednostki reprezentowanej przez bieżący obiekt jako czas UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Zwraca czas ostatniego zapisu jednostki reprezentowanej przez bieżący obiekt jako czas lokalny. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Zwraca czas ostatniego zapisu jednostki reprezentowanej przez bieżący obiekt jako czas UTC. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Zwraca nazwę jednostki wskazywanej przez ścieżkę reprezentowaną przez bieżący obiekt. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | Zwraca współdzielony wskaźnik do obiektu [DirectoryInfo](./), który reprezentuje ścieżkę wskazującą katalog nadrzędny katalogu reprezentowanego przez bieżący obiekt. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | Zwraca współdzielony wskaźnik do obiektu [DirectoryInfo](./), który reprezentuje ścieżkę wskazującą katalog główny katalogu reprezentowanego przez bieżący obiekt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | Zwraca tablicę zawierającą współdzielone wskaźniki do obiektów [DirectoryInfo](./) reprezentujących wszystkie katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | Wyszukuje katalogi spełniające określone kryteria wyszukiwania w katalogu reprezentowanym przez bieżący obiekt. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Wyszukuje katalogi spełniające określone kryteria wyszukiwania albo w katalogu reprezentowanym przez bieżący obiekt, albo w całym drzewie katalogów, którego korzeniem jest katalog reprezentowany przez bieżący obiekt. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | Zwraca tablicę zawierającą współdzielone wskaźniki do obiektów [FileInfo](../fileinfo/) reprezentujących wszystkie katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | Wyszukuje pliki spełniające określone kryteria wyszukiwania w katalogu reprezentowanym przez bieżący obiekt. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Wyszukuje pliki spełniające określone kryteria wyszukiwania albo w katalogu reprezentowanym przez bieżący obiekt, albo w całym drzewie katalogów, którego korzeniem jest katalog reprezentowany przez bieżący obiekt. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | Zwraca tablicę zawierającą współdzielone wskaźniki do obiektów [FileSystemInfo](../filesysteminfo/) reprezentujących wszystkie pliki i katalogi znajdujące się w katalogu reprezentowanym przez bieżący obiekt. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | Wyszukuje pliki i katalogi spełniające określone kryteria wyszukiwania w katalogu reprezentowanym przez bieżący obiekt. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Wyszukuje pliki i katalogi spełniające określone kryteria wyszukiwania albo w katalogu reprezentowanym przez bieżący obiekt, albo w całym drzewie katalogów, którego korzeniem jest katalog reprezentowany przez bieżący obiekt. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczne wywołanie C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Przenosi katalog reprezentowany przez bieżący obiekt oraz całą jego zawartość do określonej lokalizacji. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, naprawdę, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, naprawdę, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje obiekt typu wartościowego z nullptr poprzez referencję. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| void [Refresh](../filesysteminfo/refresh/)() | Odświeża stan bieżącego obiektu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Ustawia określone atrybuty jednostki reprezentowanej przez bieżący obiekt. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Ustawia czas utworzenia jednostki reprezentowanej przez bieżący obiekt jako czas lokalny. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Ustawia czas utworzenia jednostki reprezentowanej przez bieżący obiekt jako czas UTC. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Ustawia czas ostatniego dostępu jednostki reprezentowanej przez bieżący obiekt jako czas lokalny. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Ustawia czas ostatniego dostępu jednostki reprezentowanej przez bieżący obiekt jako czas UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Ustawia czas ostatniego zapisu jednostki reprezentowanej przez bieżący obiekt jako czas lokalny. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Ustawia czas ostatniego zapisu jednostki reprezentowanej przez bieżący obiekt jako czas UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Zwraca łańcuch znaków zawierający ścieżkę reprezentowaną przez bieżący obiekt. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [FileSystemInfo](../filesysteminfo/)
* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)