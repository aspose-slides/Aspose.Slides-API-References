---
title: ISwfOptions
second_title: Aspose.Slides dla C++ – odniesienie API
description: Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie SWF.
type: docs
weight: 469
url: /pl/aspose.slides.export/iswfoptions/
---
## ISwfOptions klasa

Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie SWF.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual **bool** [get_Compressed](./get_compressed/)() | Określa, czy wygenerowany dokument SWF powinien być skompresowany. Domyślnie **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Zwraca czcionkę używaną, gdy nie odnaleziono czcionki źródłowej. Odczytuje [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | Włącza/wyłącza menu kontekstowe. Domyślnie true. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Zwraca styl wizualny gradientu. Odczytuje [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Określa jakość obrazów JPEG.\n\n Domyślnie 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Obraz wyświetlany jako logo w prawym górnym rogu przeglądarki.\n\n Obraz powinien być PNG o wymiarach 32x64 piksele, w przeciwnym razie logo może być wyświetlane niepoprawnie. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Pobiera pełny adres hiperłącza dla logo. Ma efekt tylko wtedy, gdy określono [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Reprezentuje obiekt wywołania zwrotnego do zapisywania aktualizacji postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Pokaż/ukryj dolny panel. Może być nadpisane w flashvars. Domyślnie true. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Pokaż/ukryj przycisk pełnoekranowy. Może być nadpisane w flashvars. Domyślnie true. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Pokaż/ukryj lewy panel. Może być nadpisane w flashvars. Domyślnie true. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Określa, czy ramka wokół stron ma być wyświetlana. Domyślnie true. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Pokaż/ukryj kontrolkę przełączania stron. Może być nadpisane w flashvars. Domyślnie true. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Pokaż/ukryj sekcję wyszukiwania. Może być nadpisane w flashvars. Domyślnie true. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Pokaż/ukryj cały górny panel. Może być nadpisane w flashvars. Domyślnie true. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Określa, czy pomijać hiperłącza z wywołaniami JavaScript przy zapisywaniu prezentacji. Odczytuje **bool**. Domyślna wartość to **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Pobiera tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [ISlidesLayoutOptions](../islideslayoutoptions/). Właściwość nie obsługuje przypisywania obiektów typu **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Rozpoczyna z otwartym lewym panelem. Może być nadpisane w flashvars. Domyślnie false. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Określa, czy wygenerowany dokument SWF ma zawierać zintegrowany podgląd dokumentu. Domyślnie **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Zwraca obiekt, który otrzymuje ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy przerwany. Odczytuje [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, naprawdę, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstrukcji podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, naprawdę, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstrukcji podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Określa, czy wygenerowany dokument SWF powinien być skompresowany. Domyślnie **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Ustawia czcionkę używaną, gdy nie odnaleziono czcionki źródłowej. Zapisuje [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | Włącza/wyłącza menu kontekstowe. Domyślnie true. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Ustawia styl wizualny gradientu. Zapisuje [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Określa jakość obrazów JPEG.\n\n Domyślnie 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Obraz wyświetlany jako logo w prawym górnym rogu przeglądarki.\n\n Obraz powinien być PNG o wymiarach 32x64 piksele, w przeciwnym razie logo może być wyświetlane niepoprawnie. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Ustawia pełny adres hiperłącza dla logo. Ma efekt tylko wtedy, gdy określono [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Reprezentuje obiekt wywołania zwrotnego do zapisywania aktualizacji postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Pokaż/ukryj dolny panel. Może być nadpisane w flashvars. Domyślnie true. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Pokaż/ukryj przycisk pełnoekranowy. Może być nadpisane w flashvars. Domyślnie true. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Pokaż/ukryj lewy panel. Może być nadpisane w flashvars. Domyślnie true. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Określa, czy ramka wokół stron ma być wyświetlana. Domyślnie true. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Pokaż/ukryj kontrolkę przełączania stron. Może być nadpisane w flashvars. Domyślnie true. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Pokaż/ukryj sekcję wyszukiwania. Może być nadpisane w flashvars. Domyślnie true. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Pokaż/ukryj cały górny panel. Może być nadpisane w flashvars. Domyślnie true. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Określa, czy pomijać hiperłącza z wywołaniami JavaScript przy zapisywaniu prezentacji. Zapisuje **bool**. Domyślna wartość to **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportowania prezentacji [ISlidesLayoutOptions](../islideslayoutoptions/). Właściwość nie obsługuje przypisywania obiektów typu **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Rozpoczyna z otwartym lewym panelem. Może być nadpisane w flashvars. Domyślnie false. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Określa, czy wygenerowany dokument SWF ma zawierać zintegrowany podgląd dokumentu. Domyślnie **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Ustawia obiekt, który otrzymuje ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy przerwany. Zapisuje [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala na przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [ISaveOptions](../isaveoptions/)
* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)