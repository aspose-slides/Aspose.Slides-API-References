---
title: ContentDispositionHeaderValue
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Reprezentuje wartość nagłówka 'Content-Disposition'. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argument do funkcji."
type: docs
weight: 27
url: /pl/system.net.http.headers/contentdispositionheadervalue/
---
## ContentDispositionHeaderValue klasa

Reprezentuje wartość nagłówka 'Content-Disposition'. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy w czasie wykonania i/lub naruszenia asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania go jako argument do funkcji.

```cpp
class ContentDispositionHeaderValue : public System::ICloneable
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [ContentDispositionHeaderValue](./contentdispositionheadervalue/)() | Tworzy nową instancję. |
|  [ContentDispositionHeaderValue](./contentdispositionheadervalue/)([String](../../system/string/)) | Tworzy nową instancję. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_CreationDate](./get_creationdate/)() | Pobiera datę utworzenia pliku. |
| [String](../../system/string/) [get_DispositionType](./get_dispositiontype/)() | Pobiera typ dyspozycji. |
| [String](../../system/string/) [get_FileName](./get_filename/)() | Pobiera wartość określającą, jak utworzyć nazwę pliku do przechowywania ładunku wiadomości. Jest używana, gdy jednostka jest odłączona i przechowywana w osobnym pliku. |
| [String](../../system/string/) [get_FileNameStar](./get_filenamestar/)() | Pobiera wartość określającą, jak tworzyć nazwy plików do przechowywania ładunku wiadomości. Jest używana, gdy jednostki są odłączone i przechowywane w osobnych plikach. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_ModificationDate](./get_modificationdate/)() | Pobiera datę modyfikacji pliku. |
| [String](../../system/string/) [get_Name](./get_name/)() | Pobiera nazwę części treści. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](./get_parameters/)() | Zwraca kolekcję parametrów nagłówka 'Content-Disposition'. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_ReadDate](./get_readdate/)() | Pobiera datę ostatniego odczytu pliku. |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_Size](./get_size/)() | Pobiera przybliżony rozmiar pliku. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| static **int32_t** [GetDispositionTypeLength](./getdispositiontypelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Konwertuje przekazany ciąg znaków od określonego indeksu do instancji klasy [ContentDispositionHeaderValue](./). |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analog metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Konwertuje przekazany ciąg znaków do instancji klasy [ContentDispositionHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o wskazaną wartość. |
| void [set_CreationDate](./set_creationdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | Ustawia datę utworzenia pliku. |
| void [set_DispositionType](./set_dispositiontype/)([String](../../system/string/)) | Ustawia typ dyspozycji. |
| void [set_FileName](./set_filename/)([String](../../system/string/)) | Ustawia wartość określającą, jak utworzyć nazwę pliku do przechowywania ładunku wiadomości. Jest używana, gdy jednostka jest odłączona i przechowywana w osobnym pliku. |
| void [set_FileNameStar](./set_filenamestar/)([String](../../system/string/)) | Ustawia wartość określającą, jak tworzyć nazwy plików do przechowywania ładunku wiadomości. Jest używana, gdy jednostki są odłączone i przechowywane w osobnych plikach. |
| void [set_ModificationDate](./set_modificationdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | Ustawia datę modyfikacji pliku. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Ustawia nazwę części treści. |
| void [set_ReadDate](./set_readdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | Ustawia datę ostatniego odczytu pliku. |
| void [set_Size](./set_size/)([Nullable](../../system/nullable/)\<**int64_t**\>) | Ustawia przybliżony rozmiar pliku. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach do trybu słabego. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do string. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](./)\>\&) | Próbuje skonwertować przekazany string do instancji klasy [ContentDispositionHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [ICloneable](../../system/icloneable/)
* Przestrzeń nazw [System::Net::Http::Headers](../)
* Biblioteka [Aspose.Slides](../../)