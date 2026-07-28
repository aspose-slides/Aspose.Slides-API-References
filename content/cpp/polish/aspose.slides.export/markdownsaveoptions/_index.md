---
title: MarkdownSaveOptions
second_title: Odwołanie API Aspose.Slides dla C++
description: Reprezentuje opcje kontrolujące sposób zapisywania prezentacji do markdown.
type: docs
weight: 547
url: /pl/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions klasa

Represents options that control how presentation should be saved to markdown.

```cpp
class MarkdownSaveOptions : public Aspose::Slides::Export::SaveOptions
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::String](../../system/string/) [get_BasePath](./get_basepath/)() const | Określa podstawową ścieżkę, w której zostanie zapisana dokumentacja z zasobami. Domyślnie jest to bieżący katalog aplikacji. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Zwraca czcionkę używaną, gdy nie odnaleziono czcionki źródłowej. Odczytuje [System::String](../../system/string/). |
| [MarkdownExportType](../markdownexporttype/) [get_ExportType](./get_exporttype/)() const | Określa specyfikację markdown używaną do konwersji prezentacji. Domyślnie jest **TextOnly**. |
| [Aspose::Slides::Export::Flavor](../flavor/) [get_Flavor](./get_flavor/)() const | Określa specyfikację markdown używaną do konwersji prezentacji. Domyślnie jest **Multi-markdown**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Zwraca styl wizualny gradientu. Odczytaj [GradientStyle](../../aspose.slides/gradientstyle/). |
| [Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/) [get_HandleRepeatedSpaces](./get_handlerepeatedspaces/)() const | Określa, jak powinny być obsługiwane powtarzające się znaki zwykłej spacji podczas eksportu do Markdown. |
| [System::String](../../system/string/) [get_ImagesSaveFolderName](./get_imagessavefoldername/)() const | Określa nazwę folderu, w którym zapisywane są obrazy. Domyślnie jest **[Images](../../aspose.slides/images/)**. |
| [Aspose::Slides::Export::NewLineType](../newlinetype/) [get_NewLineType](./get_newlinetype/)() const | Określa, czy wygenerowany dokument ma używać znaków nowej linii \r (Macintosh), \n (Unix) lub \r\n (Windows). Domyślnie jest **Unix**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Reprezentuje obiekt wywołania zwrotnego służący do zapisywania postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RemoveEmptyLines](./get_removeemptylines/)() const | Jeśli ustawione na **true**, usuwa puste lub zawierające wyłącznie białe znaki wiersze z ostatecznego wyjścia Markdown. Domyślnie jest **false**. |
| **bool** [get_ShowComments](./get_showcomments/)() const | Określa, czy wygenerowany dokument ma wyświetlać komentarze. Domyślnie jest **false**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() const | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie jest **false**. |
| **bool** [get_ShowSlideNumber](./get_showslidenumber/)() const | Określa, czy wygenerowany dokument ma wyświetlać numer każdego slajdu. Domyślnie jest **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Odczytaj **bool**. Domyślna wartość to **false**. |
| [System::String](../../system/string/) [get_SlideNumberFormat](./get_slidenumberformat/)() | Pobiera format ciągu używanego dla nagłówków numerów slajdów w wyjściu Markdown. Format musi zawierać znak zastępczy \"{0}\", który zostanie zastąpiony indeksem slajdu podczas eksportu. Przykład: \"# Slide {0}\" wytworzy \"# Slide 1\", \"# Slide 2\" itd. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Zwraca lub ustawia obiekt, który otrzymuje ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Odczytaj [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie obiektów niestandardowych. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strzegącego [LockContext](../../system/lockcontext/). |
|  [MarkdownSaveOptions](./markdownsaveoptions/)() | Konstruktor. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BasePath](./set_basepath/)([System::String](../../system/string/)) | Określa podstawową ścieżkę, w której zostanie zapisana dokumentacja z zasobami. Domyślnie jest to bieżący katalog aplikacji. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ustawia czcionkę używaną, gdy nie odnaleziono czcionki źródłowej. Zapisuje [System::String](../../system/string/). |
| void [set_ExportType](./set_exporttype/)([MarkdownExportType](../markdownexporttype/)) | Określa specyfikację markdown używaną do konwersji prezentacji. Domyślnie jest **TextOnly**. |
| void [set_Flavor](./set_flavor/)([Aspose::Slides::Export::Flavor](../flavor/)) | Określa specyfikację markdown używaną do konwersji prezentacji. Domyślnie jest **Multi-markdown**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ustawia styl wizualny gradientu. Zapisz [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_HandleRepeatedSpaces](./set_handlerepeatedspaces/)([Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/)) | Określa, jak powinny być obsługiwane powtarzające się znaki zwykłej spacji podczas eksportu do Markdown. |
| void [set_ImagesSaveFolderName](./set_imagessavefoldername/)([System::String](../../system/string/)) | Określa nazwę folderu, w którym zapisywane są obrazy. Domyślnie jest **[Images](../../aspose.slides/images/)**. |
| void [set_NewLineType](./set_newlinetype/)([Aspose::Slides::Export::NewLineType](../newlinetype/)) | Określa, czy wygenerowany dokument ma używać znaków nowej linii \r (Macintosh), \n (Unix) lub \r\n (Windows). Domyślnie jest **Unix**. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Reprezentuje obiekt wywołania zwrotnego służący do zapisywania postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RemoveEmptyLines](./set_removeemptylines/)(**bool**) | Jeśli ustawione na **true**, usuwa puste lub zawierające wyłącznie białe znaki wiersze z ostatecznego wyjścia Markdown. Domyślnie jest **false**. |
| void [set_ShowComments](./set_showcomments/)(**bool**) | Określa, czy wygenerowany dokument ma wyświetlać komentarze. Domyślnie jest **false**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie jest **false**. |
| void [set_ShowSlideNumber](./set_showslidenumber/)(**bool**) | Określa, czy wygenerowany dokument ma wyświetlać numer każdego slajdu. Domyślnie jest **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Zapisz **bool**. Domyślna wartość to **false**. |
| void [set_SlideNumberFormat](./set_slidenumberformat/)([System::String](../../system/string/)) | Ustawia format ciągu używanego dla nagłówków numerów slajdów w wyjściu Markdown. Format musi zawierać znak zastępczy \"{0}\", który zostanie zastąpiony indeksem slajdu podczas eksportu. Przykład: \"# Slide {0}\" wytworzy \"# Slide 1\", \"# Slide 2\" itd. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Zwraca lub ustawia obiekt, który otrzymuje ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Zapisz [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję obiektów niestandardowych na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strzegącego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Typedefy

| Definicja typu | Opis |
| --- | --- |
| [MarkdownImageSavingHandler](./markdownimagesavinghandler/) | Wywoływany dla każdego obrazu nie-SVG (bitmapa lub metafilu) podczas eksportu do Markdown. Zwróć **true**, aby użyć określonego *linku*, lub **false**, aby zastosować domyślną logikę zapisu. |
| [MarkdownSvgImageSavingHandler](./markdownsvgimagesavinghandler/) | Wywoływany dla każdego obrazu SVG podczas eksportu do Markdown. Zwróć **true**, aby użyć określonego *linku*, lub **false**, aby zastosować domyślną logikę zapisu. |

## Uwagi

Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## Zobacz także

* Klasa [SaveOptions](../saveoptions/)
* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)