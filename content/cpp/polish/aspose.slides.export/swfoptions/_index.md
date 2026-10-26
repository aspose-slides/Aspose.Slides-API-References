---
title: SwfOptions
second_title: Aspose.Slides dla C++ Referencja API
description: Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie Swf.
type: docs
weight: 742
url: /pl/aspose.slides.export/swfoptions/
---
## SwfOptions klasa


Provides options that control how a presentation is saved in Swf format.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **bool** [get_Compressed](./get_compressed/)() override | Określa, czy wygenerowany dokument SWF ma być kompresowany, czy nie. Domyślnie **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Zwraca czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa. Odczytuje [System::String](../../system/string/). |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | Włącza/wyłącza menu kontekstowe. Domyślnie true. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Zwraca styl wizualny gradientu. Odczytuje [GradientStyle](../../aspose.slides/gradientstyle/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Określa jakość obrazów JPEG. Domyślnie 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | Obraz, który będzie wyświetlany jako logo w prawym górnym rogu przeglądarki. Obraz powinien być 32x64 pikseli PNG, w przeciwnym razie logo może być wyświetlane niepoprawnie. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | Pobiera pełny adres hiperłącza dla logo. Ma efekt tylko jeżeli określono [set_LogoImageBytes()](./set_logoimagebytes/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Reprezentuje obiekt wywołania zwrotnego do zapisywania postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | Pokaż/ukryj dolny panel. Może być nadpisane w flashvars. Domyślnie true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | Pokaż/ukryj przycisk pełnego ekranu. Może być nadpisane w flashvars. Domyślnie true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | Pokaż/ukryj lewy panel. Może być nadpisane w flashvars. Domyślnie true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | Określa, czy ma być wyświetlana ramka wokół stron. Domyślnie true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | Pokaż/ukryj przełącznik stron. Może być nadpisane w flashvars. Domyślnie true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | Pokaż/ukryj sekcję wyszukiwania. Może być nadpisane w flashvars. Domyślnie true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | Pokaż/ukryj cały górny panel. Może być nadpisane w flashvars. Domyślnie true. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Określa, czy pomijać hiperłącza z wywołaniami JavaScript przy zapisywaniu prezentacji. Odczytuje **bool**. Domyślna wartość to **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Pobiera tryb, w którym slajdy są rozmieszczane na stronie przy eksportowaniu prezentacji [ISlidesLayoutOptions](../islideslayoutoptions/). Ta własność nie obsługuje przypisywania obiektów typu [HandoutLayoutingOptions](../handoutlayoutingoptions/) |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | Rozpoczyna z otwartym lewym panelem. Może być nadpisane w flashvars. Domyślnie false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | Określa, czy wygenerowany dokument SWF ma zawierać zintegrowany podgląd dokumentu. Domyślnie **true**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy przerwany. Odczytuje [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o określoną wartość. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | Określa, czy wygenerowany dokument SWF ma być kompresowany, czy nie. Domyślnie **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ustawia czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa. Zapisuje [System::String](../../system/string/). |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | Włącza/wyłącza menu kontekstowe. Domyślnie true. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ustawia styl wizualny gradientu. Zapisuje [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Określa jakość obrazów JPEG. Domyślnie 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Obraz, który będzie wyświetlany jako logo w prawym górnym rogu przeglądarki. Obraz powinien być 32x64 pikseli PNG, w przeciwnym razie logo może być wyświetlane niepoprawnie. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | Ustawia pełny adres hiperłącza dla logo. Ma efekt tylko jeśli określono [set_LogoImageBytes()](./set_logoimagebytes/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Reprezentuje obiekt wywołania zwrotnego do zapisywania postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | Pokaż/ukryj dolny panel. Może być nadpisane w flashvars. Domyślnie true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | Pokaż/ukryj przycisk pełnego ekranu. Może być nadpisane w flashvars. Domyślnie true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | Pokaż/ukryj lewy panel. Może być nadpisane w flashvars. Domyślnie true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | Określa, czy ma być wyświetlana ramka wokół stron. Domyślnie true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | Pokaż/ukryj przełącznik stron. Może być nadpisane w flashvars. Domyślnie true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | Pokaż/ukryj sekcję wyszukiwania. Może być nadpisane w flashvars. Domyślnie true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | Pokaż/ukryj cały górny panel. Może być nadpisane w flashvars. Domyślnie true. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Określa, czy pomijać hiperłącza z wywołaniami JavaScript przy zapisywaniu prezentacji. Zapisuje **bool**. Domyślna wartość to **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Ustawia tryb, w którym slajdy są rozmieszczane na stronie przy eksportowaniu prezentacji [ISlidesLayoutOptions](../islideslayoutoptions/). Ta własność nie obsługuje przypisywania obiektów typu [HandoutLayoutingOptions](../handoutlayoutingoptions/) |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | Rozpoczyna z otwartym lewym panelem. Może być nadpisane w flashvars. Domyślnie false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | Określa, czy wygenerowany dokument SWF ma zawierać zintegrowany podgląd dokumentu. Domyślnie **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy przerwany. Zapisuje [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustaw n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [SwfOptions](./swfoptions/)() | Konstruktor domyślny. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Uwagi


The following example shows how to convert PowerPoint to SWF Flash. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## Zobacz także

* Klasa [SaveOptions](../saveoptions/)
* Klasa [ISwfOptions](../iswfoptions/)
* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)