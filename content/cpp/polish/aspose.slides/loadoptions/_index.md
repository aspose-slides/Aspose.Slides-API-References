---
title: LoadOptions
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Umożliwia określenie dodatkowych opcji (takich jak format lub domyślna czcionka) podczas ładowania prezentacji.
type: docs
weight: 4395
url: /pl/aspose.slides/loadoptions/
---
## LoadOptions klasa

Umożliwia określenie dodatkowych opcji (takich jak format lub domyślna czcionka) podczas ładowania prezentacji.

```cpp
class LoadOptions : public Aspose::Slides::ILoadOptions
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() override | Reprezentuje opcje, które mogą być użyte do zarządzania zachowaniem obsługi Binary Large Objects (BLOBs), takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOBs w pamięci. Opcje te mają na celu ustalenie najlepszego stosunku wydajności do zużycia pamięci dla konkretnego środowiska lub wymagań. |
| [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() override | Zwraca czcionkę azjatycką używaną, gdy nie znaleziono czcionki źródłowej. Czytaj [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() override | Zwraca czcionkę regularną używaną, gdy nie znaleziono czcionki źródłowej. Czytaj [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() override | Zwraca czcionkę Symbol używaną, gdy nie znaleziono czcionki źródłowej. Czytaj [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() override | Zwraca domyślny język tekstu prezentacji. Czytaj [System::String](../../system/string/). |
| **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() override | Określa, czy [Aspose.Slides](../) usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() override | Określa źródła zewnętrznych czcionek używanych przez prezentację. Czcionki te są dostępne dla prezentacji przez cały jej okres życia i nie są współdzielone z innymi prezentacjami |
| [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() override | Token służący do monitorowania żądań przerwania. |
| [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() override | Zwraca format prezentacji do załadowania. Czytaj [Slides::LoadFormat](../loadformat/). |
| **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() override | Ta właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem. Wartość true oznacza, że tylko właściwości dokumentu muszą zostać załadowane z zaszyfrowanego pliku prezentacji i hasło ma być zignorowane. Wartość false oznacza, że cała zaszyfrowana prezentacja musi zostać załadowana przy użyciu prawidłowego hasła. Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze ignorowana. Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne i wartość właściwości jest true, właściwości dokumentu nie mogą zostać załadowane i zostanie rzucony wyjątek. Czytaj **bool**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Pobiera hasło. Czytaj [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() override | Zwraca interfejs zwrotny, który zarządza ładowaniem zasobów zewnętrznych. Czytaj [IResourceLoadingCallback](../iresourceloadingcallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() override | Pobiera opcje dla arkuszy kalkulacyjnych. Na przykład, opcje te wpływają na obliczanie formuł dla wykresów. |
| [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() override | Zwraca obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Czytaj [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
|  [LoadOptions](./loadoptions/)() | Tworzy nowe domyślne opcje ładowania. |
|  [LoadOptions](./loadoptions/)([Aspose::Slides::LoadFormat](../loadformat/)) | Tworzy nowe opcje ładowania. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) override | Reprezentuje opcje, które mogą być użyte do zarządzania zachowaniem obsługi Binary Large Objects (BLOBs), takich jak użycie plików tymczasowych lub maksymalna liczba bajtów BLOBs w pamięci. Opcje te mają na celu ustalenie najlepszego stosunku wydajności do zużycia pamięci dla konkretnego środowiska lub wymagań. |
| void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) override | Ustawia czcionkę azjatycką używaną, gdy nie znaleziono czcionki źródłowej. Zapisz [System::String](../../system/string/). |
| void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) override | Ustawia czcionkę regularną używaną, gdy nie znaleziono czcionki źródłowej. Zapisz [System::String](../../system/string/). |
| void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) override | Ustawia czcionkę Symbol używaną, gdy nie znaleziono czcionki źródłowej. Zapisz [System::String](../../system/string/). |
| void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) override | Ustawia domyślny język tekstu prezentacji. Zapisz [System::String](../../system/string/). |
| void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) override | Określa, czy [Aspose.Slides](../) usunie wszystkie osadzone obiekty binarne podczas ładowania prezentacji. |
| void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) override | Określa źródła zewnętrznych czcionek używanych przez prezentację. Czcionki te są dostępne dla prezentacji przez cały jej okres życia i nie są współdzielone z innymi prezentacjami |
| void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) override | Token służący do monitorowania żądań przerwania. |
| void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) override | Ustawia format prezentacji do załadowania. Zapisz [Slides::LoadFormat](../loadformat/). |
| void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) override | Ta właściwość ma sens, jeśli plik prezentacji jest zabezpieczony hasłem. Wartość true oznacza, że tylko właściwości dokumentu muszą zostać załadowane z zaszyfrowanego pliku prezentacji i hasło ma być zignorowane. Wartość false oznacza, że cała zaszyfrowana prezentacja musi zostać załadowana przy użyciu prawidłowego hasła. Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze ignorowana. Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne i wartość właściwości jest true, właściwości dokumentu nie mogą zostać załadowane i zostanie rzucony wyjątek. Zapisz **bool**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Ustawia hasło. Zapisz [System::String](../../system/string/). |
| void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) override | Ustawia interfejs zwrotny, który zarządza ładowaniem zasobów zewnętrznych. Zapisz [IResourceLoadingCallback](../iresourceloadingcallback/). |
| void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) override | Pobiera opcje dla arkuszy kalkulacyjnych. Na przykład, opcje te wpływają na obliczanie formuł dla wykresów. |
| void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Zapisz [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [ILoadOptions](../iloadoptions/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)