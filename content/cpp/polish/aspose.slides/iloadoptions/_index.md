---
title: ILoadOptions
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Umożliwia określenie dodatkowych opcji (takich jak format lub domyślna czcionka) podczas ładowania prezentacji.
type: docs
weight: 2796
url: /pl/aspose.slides/iloadoptions/
---
## ILoadOptions klasa


Umożliwia określenie dodatkowych opcji (takich jak format lub domyślna czcionka) podczas ładowania prezentacji.

```cpp
class ILoadOptions : public virtual System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do celów wewnętrznych. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() | Reprezentuje opcje, które mogą być użyte do zarządzania zachowaniem obsługi dużych obiektów binarnych (BLOB), takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. Opcje te mają na celu ustalenie najlepszego stosunku wydajności do zużycia pamięci dla konkretnego środowiska lub wymagań. |
| virtual [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() | Zwraca czcionkę azjatycką używaną, gdy nie zostanie znaleziona czcionka źródłowa. Czyta [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() | Zwraca standardową czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa. Czyta [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() | Zwraca czcionkę Symbol używaną, gdy nie zostanie znaleziona czcionka źródłowa. Czyta [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() | Zwraca domyślny język tekstu prezentacji. Czyta [System::String](../../system/string/). |
| virtual **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() | Określa, czy [Aspose.Slides](../) usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() | Określa źródła zewnętrznych czcionek używanych przez prezentację. Czcionki te są dostępne dla prezentacji przez cały jej czas życia i nie są współdzielone z innymi prezentacjami |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() | Token monitorujący żądania przerwania. |
| virtual [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() | Zwraca format prezentacji do załadowania. Czyta [Slides::LoadFormat](../loadformat/). |
| virtual **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() | Ta właściwość ma sens, jeśli plik prezentacji jest chroniony hasłem. Wartość true oznacza, że z zaszyfrowanego pliku prezentacji muszą być załadowane tylko właściwości dokumentu i hasło ma być ignorowane. Wartość false oznacza, że cała zaszyfrowana prezentacja musi być załadowana z użyciem prawidłowego hasła. Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze ignorowana. Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne i wartość właściwości jest true, właściwości dokumentu nie mogą być załadowane i zostanie zgłoszony wyjątek. Czyta **bool**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | Pobiera hasło. Czyta [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() | Zwraca interfejs zwrotny, który zarządza ładowaniem zasobów zewnętrznych. Czyta [IResourceLoadingCallback](../iresourceloadingcallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() | Reprezentuje opcje, które mogą być użyte do określenia dodatkowego zachowania arkuszy kalkulacyjnych. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() | Zwraca obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Czyta [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia tworzenie podklas przez kopiowanie. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia tworzenie podklas przez kopiowanie. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) | Reprezentuje opcje, które mogą być użyte do zarządzania zachowaniem obsługi dużych obiektów binarnych (BLOB), takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOB w pamięci. Opcje te mają na celu ustalenie najlepszego stosunku wydajności do zużycia pamięci dla konkretnego środowiska lub wymagań. |
| virtual void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) | Ustawia czcionkę azjatycką używaną, gdy nie zostanie znaleziona czcionka źródłowa. Zapisuje [System::String](../../system/string/). |
| virtual void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) | Ustawia standardową czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa. Zapisuje [System::String](../../system/string/). |
| virtual void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) | Ustawia czcionkę Symbol używaną, gdy nie zostanie znaleziona czcionka źródłowa. Zapisuje [System::String](../../system/string/). |
| virtual void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) | Ustawia domyślny język tekstu prezentacji. Zapisuje [System::String](../../system/string/). |
| virtual void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) | Określa, czy [Aspose.Slides](../) usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji. |
| virtual void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) | Określa źródła zewnętrznych czcionek używanych przez prezentację. Czcionki te są dostępne dla prezentacji przez cały jej czas życia i nie są współdzielone z innymi prezentacjami |
| virtual void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) | Token monitorujący żądania przerwania. |
| virtual void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) | Ustawia format prezentacji do załadowania. Zapisuje [Slides::LoadFormat](../loadformat/). |
| virtual void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) | Ta właściwość ma sens, jeśli plik prezentacji jest chroniony hasłem. Wartość true oznacza, że z zaszyfrowanego pliku prezentacji muszą być załadowane tylko właściwości dokumentu i hasło ma być ignorowane. Wartość false oznacza, że cała zaszyfrowana prezentacja musi być załadowana z użyciem prawidłowego hasła. Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze ignorowana. Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne i wartość właściwości jest true, właściwości dokumentu nie mogą być załadowane i zostanie zgłoszony wyjątek. Zapisuje **bool**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | Ustawia hasło. Zapisuje [System::String](../../system/string/). |
| virtual void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) | Ustawia interfejs zwrotny, który zarządza ładowaniem zasobów zewnętrznych. Zapisuje [IResourceLoadingCallback](../iresourceloadingcallback/). |
| virtual void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) | Reprezentuje opcje, które mogą być użyte do określenia dodatkowego zachowania arkuszy kalkulacyjnych. |
| virtual void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Zapisuje [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję niestandardowych obiektów na łańcuch znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)