---
title: FileSystemInfo
second_title: "Aspose.Slides dla C++ – Dokumentacja API"
description: "Klasa bazowa dla FileInfo i DirectoryInfo. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy czasu wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 300
url: /pl/system.io/filesysteminfo/
---
## FileSystemInfo klasa


Klasa bazowa dla [FileInfo](../fileinfo/) i [DirectoryInfo](../directoryinfo/). Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy w czasie wykonania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji.

```cpp
class FileSystemInfo : public System::Object
```

## Metody

| Method | Description |
| --- | --- |
| virtual void [Delete](./delete/)() | Usuwa podmiot reprezentowany przez bieżący obiekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual void [Finalize](./finalize/)() | Nie wykonuje żadnej operacji. |
| [FileAttributes](../fileattributes/) [get_Attributes](./get_attributes/)() | Zwraca atrybuty podmiotu reprezentowanego przez bieżący obiekt. |
| [DateTime](../../system/datetime/) [get_CreationTime](./get_creationtime/)() | Zwraca czas utworzenia podmiotu reprezentowanego przez bieżący obiekt w czasie lokalnym. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](./get_creationtimeutc/)() | Zwraca czas utworzenia podmiotu reprezentowanego przez bieżący obiekt w czasie UTC. |
| virtual **bool** [get_Exists](./get_exists/)() | Określa, czy podmiot wskazywany przez ścieżkę reprezentowaną przez bieżący obiekt istnieje. |
| [String](../../system/string/) [get_Extension](./get_extension/)() | Zwraca rozszerzenie pliku reprezentowanego przez bieżący obiekt. |
| virtual [String](../../system/string/) [get_FullName](./get_fullname/)() | Zwraca pełną nazwę (wraz ze ścieżką) podmiotu reprezentowanego przez bieżący obiekt. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](./get_lastaccesstime/)() | Zwraca czas ostatniego dostępu do podmiotu reprezentowanego przez bieżący obiekt w czasie lokalnym. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | Zwraca czas ostatniego dostępu do podmiotu reprezentowanego przez bieżący obiekt w czasie UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](./get_lastwritetime/)() | Zwraca czas ostatniego zapisu podmiotu reprezentowanego przez bieżący obiekt w czasie lokalnym. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | Zwraca czas ostatniego zapisu podmiotu reprezentowanego przez bieżący obiekt w czasie UTC. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Zwraca nazwę podmiotu reprezentowanego przez bieżący obiekt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia hashowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| void [Refresh](./refresh/)() | Odświeża stan bieżącego obiektu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [set_Attributes](./set_attributes/)([FileAttributes](../fileattributes/)) | Ustawia określone atrybuty podmiotu reprezentowanego przez bieżący obiekt. |
| void [set_CreationTime](./set_creationtime/)([DateTime](../../system/datetime/)) | Ustawia czas utworzenia podmiotu reprezentowanego przez bieżący obiekt w czasie lokalnym. |
| void [set_CreationTimeUtc](./set_creationtimeutc/)([DateTime](../../system/datetime/)) | Ustawia czas utworzenia podmiotu reprezentowanego przez bieżący obiekt w czasie UTC. |
| void [set_LastAccessTime](./set_lastaccesstime/)([DateTime](../../system/datetime/)) | Ustawia czas ostatniego dostępu do podmiotu reprezentowanego przez bieżący obiekt w czasie lokalnym. |
| void [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Ustawia czas ostatniego dostępu do podmiotu reprezentowanego przez bieżący obiekt w czasie UTC. |
| void [set_LastWriteTime](./set_lastwritetime/)([DateTime](../../system/datetime/)) | Ustawia czas ostatniego zapisu podmiotu reprezentowanego przez bieżący obiekt w czasie lokalnym. |
| void [set_LastWriteTimeUtc](./set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Ustawia czas ostatniego zapisu podmiotu reprezentowanego przez bieżący obiekt w czasie UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączyć wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() |  Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)