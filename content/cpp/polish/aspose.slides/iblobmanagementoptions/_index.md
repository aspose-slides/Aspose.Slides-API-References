---
title: IBlobManagementOptions
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Binary Large Object (BLOB) to binarne dane przechowywane jako pojedynczy byt - tzn. BLOB może być plikiem audio, wideo lub samą prezentacją. Stosuje się liczne techniki optymalizacji zużycia pamięci przy pracy z BLOB-ami, które były już zapisane w prezentacji lub mogą być dodane później programowo. Korzystając z IBlobManagementOptions możesz zmienić różne aspekty zachowania związane z obsługą BLOB-ów w czasie życia instancji IPresentation.
type: docs
weight: 1535
url: /pl/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions klasa

Binary Large Object (BLOB) to dane binarne przechowywane jako pojedynczy byt - tzn. BLOB może być samym plikiem audio, wideo lub prezentacją. Do optymalizacji zużycia pamięci podczas pracy z BLOB-ami stosuje się różne techniki - które były już zapisane w prezentacji lub mogą być dodane później programowo. Korzystając z [IBlobManagementOptions](./) możesz zmienić różne aspekty zachowania związane z obsługą BLOB-ów dla czasu życia instancji [IPresentation](../ipresentation/).

```cpp
class IBlobManagementOptions : public virtual System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że według IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że według IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() | Ta właściwość określa, czy podczas pracy z BLOB-ami mogą być tworzone pliki tymczasowe, co znacznie zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików. |
| virtual **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() | Definiuje maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. Domyślnie wszystkie BLOB-y są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (np. pliki tymczasowe). Trzymanie BLOB-ów w pamięci maksymalizuje wydajność, ale może prowadzić do wysokiego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań. |
| virtual [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() | Ta właściwość określa, czy instancja klasy [Presentation](../presentation/) może być właścicielem źródła – pliku lub strumienia – podczas czasu życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność przy pracy z BLOB-ami, ale źródło (strumień lub plik) nie może być zmieniane podczas czasu życia instancji [Presentation](../presentation/). Oto przykład: |
| virtual [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() | Ścieżka główna, w której będą tworzone pliki tymczasowe. Domyślnie używany będzie katalog [System](../../system/) tymczasowy. Proces hostujący powinien mieć uprawnienia do tworzenia tam plików i folderów. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczny do wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny do operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) | Ta właściwość określa, czy podczas pracy z BLOB-ami mogą być tworzone pliki tymczasowe, co znacznie zmniejsza zużycie pamięci, ale wymaga uprawnień do tworzenia plików. |
| virtual void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) | Definiuje maksymalny łączny rozmiar (w bajtach), jaki wszystkie BLOB-y mogą zajmować w pamięci. Domyślnie wszystkie BLOB-y są ładowane do pamięci; dopiero po osiągnięciu tego limitu stosowane są alternatywne mechanizmy (np. pliki tymczasowe). Trzymanie BLOB-ów w pamięci maksymalizuje wydajność, ale może prowadzić do wysokiego zużycia pamięci. Użyj tej właściwości, aby dostosować zachowanie do swojego środowiska lub wymagań. |
| virtual void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) | Ta właściwość określa, czy instancja klasy [Presentation](../presentation/) może być właścicielem źródła – pliku lub strumienia – podczas czasu życia instancji. Jeśli instancja jest właścicielem, blokuje źródło. Pomaga to poprawić zużycie pamięci i wydajność przy pracy z BLOB-ami, ale źródło (strumień lub plik) nie może być zmieniane podczas czasu życia instancji [Presentation](../presentation/). Oto przykład: |
| virtual void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) | Ścieżka główna, w której będą tworzone pliki tymczasowe. Domyślnie używany będzie katalog [System](../../system/) tymczasowy. Proces hostujący powinien mieć uprawnienia do tworzenia tam plików i folderów. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)