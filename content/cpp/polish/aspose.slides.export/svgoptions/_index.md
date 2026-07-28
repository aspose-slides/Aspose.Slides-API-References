---
title: SVGOptions
second_title: Aspose.Slides dla C++ - odniesienie API
description: Reprezentuje opcje SVG.
type: docs
weight: 703
url: /pl/aspose.slides.export/svgoptions/
---
## SVGOptions klasa

Reprezentuje opcje SVG.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | Zwraca domyślne ustawienia. Tylko do odczytu [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Zwraca czcionkę używaną w przypadku, gdy nie odnaleziono czcionki źródłowej. Odczytuje [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | Flaga logiczna wskazuje, czy przycięte części pozostają częścią dokumentu. Jeśli true, przycięte części zostaną usunięte, jeśli false, zostaną zapisane w dokumencie (co może prowadzić do większego pliku). |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | Określa, czy tekst 3D jest wyłączony w SVG. Tylko do odczytu **bool**. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | Pobiera wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na **true**, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie ta właściwość jest ustawiona na **false**. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | Wyłącza podział gradientów FromCornerX i FromCenter. Tylko do odczytu **bool**. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1 nie posiada możliwości definiowania wcięć dla znaczników. [Aspose.Slides](../../aspose.slides/) silnik zapisu SVG ma obejście tego problemu: przycina koniec linii z strzałką, tak aby linia nie nachodziła na znaczniki. Ta opcja wyłącza takie zachowanie. Tylko do odczytu **bool**. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | Określa sposób obsługi zewnętrznie ładowanych czcionek. Odczytuje [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Zwraca styl wizualny gradientu. Odczytuje [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Udostępnia opcje kontrolujące wygląd obiektów [Ink](../../aspose.slides.ink/) w wyeksportowanym dokumencie. Tylko do odczytu [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Określa jakość kodowania JPEG. Tylko do odczytu **int32_t**. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | Zwraca dolny limit rozdzielczości dla rasteryzacji metafili. Tylko do odczytu **int32_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | Reprezentuje poziom kompresji obrazów |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Reprezentuje obiekt zwrotny do zapisywania postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | Zwraca i ustawia interfejs zwrotny, który umożliwia użytkownikowi kontrolowanie konwersji kształtu. Odczytuje [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | Zwraca ustawienia najprostszego i najmniejszego generowania pliku SVG. Tylko do odczytu [SVGOptions](./). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Określa, czy pomijać hiperłącza z wywołaniami JavaScript przy zapisywaniu prezentacji. Tylko do odczytu **bool**. Domyślna wartość to **false**. |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | Określa, czy wykonać określony obrót kształtu podczas renderowania. Tylko do odczytu **bool**. Domyślna wartość to true. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | Określa, czy ramka tekstu będzie uwzględniona w obszarze renderowania. Tylko do odczytu **bool**. Domyślna wartość to false. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | Określa, czy tekst na slajdzie zostanie zapisany jako grafika. Tylko do odczytu **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Zwraca lub ustawia obiekt, który otrzymuje ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany czy przerwany. Odczytuje [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | Zwraca ustawienia najdokładniejszego generowania pliku SVG. Tylko do odczytu [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ustawia czcionkę używaną gdy nie odnaleziono czcionki źródłowej. Zapisuje [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | Flaga logiczna wskazuje, czy przycięte części pozostają częścią dokumentu. Jeśli true, przycięte części zostaną usunięte, jeśli false, zostaną zapisane w dokumencie (co może prowadzić do większego pliku). |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | Określa, czy tekst 3D jest wyłączony w SVG. Zapisz **bool**. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | Ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na **true**, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie ta właściwość jest ustawiona na **false**. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | Wyłącza podział gradientów FromCornerX i FromCenter. Zapisz **bool**. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1 nie posiada możliwości definiowania wcięć dla znaczników. [Aspose.Slides](../../aspose.slides/) silnik zapisu SVG ma obejście tego problemu: przycina koniec linii z strzałką, tak aby linia nie nachodziła na znaczniki. Ta opcja wyłącza takie zachowanie. Zapisz **bool**. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | Określa sposób obsługi zewnętrznie ładowanych czcionek. Zapisz [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ustawia styl wizualny gradientu. Zapisz [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Określa jakość kodowania JPEG. Zapisz **int32_t**. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | Ustawia dolny limit rozdzielczości dla rasteryzacji metafili. Zapisz **int32_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | Reprezentuje poziom kompresji obrazów |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Reprezentuje obiekt zwrotny do zapisywania postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | Zwraca i ustawia interfejs zwrotny, który umożliwia użytkownikowi kontrolowanie konwersji kształtu. Zapisz [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Określa, czy pomijać hiperłącza z wywołaniami JavaScript przy zapisywaniu prezentacji. Zapisz **bool**. Domyślna wartość to **false**. |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | Określa, czy wykonać określony obrót kształtu podczas renderowania. Zapisz **bool**. Domyślna wartość to true. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | Określa, czy ramka tekstu będzie uwzględniona w obszarze renderowania. Zapisz **bool**. Domyślna wartość to false. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | Określa, czy tekst na slajdzie zostanie zapisany jako grafika. Zapisz **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Zwraca lub ustawia obiekt, który otrzymuje ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany czy przerwany. Zapisz [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [SVGOptions](./svgoptions/)() | Inicjalizuje nową instancję klasy [SVGOptions](./). |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | Inicjalizuje nową instancję klasy [SVGOptions](./) określając obiekt kontrolera osadzania linków. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zniszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [SaveOptions](../saveoptions/)
* Klasa [ISVGOptions](../isvgoptions/)
* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)