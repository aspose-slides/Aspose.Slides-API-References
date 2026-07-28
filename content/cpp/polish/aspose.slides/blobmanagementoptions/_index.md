---
title: BlobManagementOptions
second_title: Referencja API Aspose.Slides dla C++
description: Reprezentuje opcje, które mogą być użyte do zarządzania zasadami obsługi BLOB oraz innymi ustawieniami BLOB.
type: docs
weight: 196
url: /pl/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions klasa

Reprezentuje opcje, które mogą być użyte do zarządzania zasadami obsługi BLOB oraz innymi ustawieniami BLOB.

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## Metody

| Method | Description |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | Tworzy nowe domyślne opcje zarządzania BLOB. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do celów wewnętrznych. |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | Ta właściwość określa, czy tymczasowe pliki mogą być tworzone podczas pracy z BLOB, co znacznie zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików. |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | Definiuje maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOBy mogą zajmować w pamięci. Domyślnie wszystkie BLOBy są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOBów w pamięci maksymalizuje wydajność, ale może prowadzić do dużego zużycia pamięci. Użyj tej właściwości, aby dopasować zachowanie do swojego środowiska lub wymagań. |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | Ta właściwość określa, czy instancja klasy [Presentation](../presentation/) może być właścicielem źródła – pliku lub strumienia podczas życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność przy pracy z BLOB, ale źródło (strumień lub plik) nie może być zmienione podczas życia instancji [Presentation](../presentation/). |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | Ścieżka główna, w której będą tworzone pliki tymczasowe. Domyślnie używany będzie katalog [System](../../system/). Proces hostingowy powinien mieć uprawnienia do tworzenia plików i folderów w tym miejscu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje w rzeczywistości nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje w rzeczywistości nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | Ta właściwość określa, czy tymczasowe pliki mogą być tworzone podczas pracy z BLOB, co znacznie zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików. |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | Definiuje maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOBy mogą zajmować w pamięci. Domyślnie wszystkie BLOBy są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (takie jak pliki tymczasowe). Przechowywanie BLOBów w pamięci maksymalizuje wydajność, ale może prowadzić do dużego zużycia pamięci. Użyj tej właściwości, aby dopasować zachowanie do swojego środowiska lub wymagań. |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | Ta właściwość określa, czy instancja klasy [Presentation](../presentation/) może być właścicielem źródła – pliku lub strumienia podczas życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność przy pracy z BLOB, ale źródło (strumień lub plik) nie może być zmienione podczas życia instancji [Presentation](../presentation/). |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | Ścieżka główna, w której będą tworzone pliki tymczasowe. Domyślnie używany będzie katalog [System](../../system/). Proces hostingowy powinien mieć uprawnienia do tworzenia plików i folderów w tym miejscu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Zobacz także

* Klasa [IBlobManagementOptions](../iblobmanagementoptions/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)