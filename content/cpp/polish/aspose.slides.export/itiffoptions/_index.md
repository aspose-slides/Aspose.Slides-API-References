---
title: ITiffOptions
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie TIFF.
type: docs
weight: 495
url: /pl/aspose.slides.export/itiffoptions/
---
## ITiffOptions klasa

Zapewnia opcje kontrolujące sposób zapisywania prezentacji w formacie TIFF.

```cpp
class ITiffOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, pomimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, pomimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() | Określa algorytm konwertowania obrazu kolorowego na czarno-biały. Ta opcja zostanie zastosowana tylko jeśli [ITiffOptions::get_CompressionType()](./get_compressiontype/) jest ustawione na [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) lub [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) Odczyt [BlackWhiteConversionMode](../blackwhiteconversionmode/). Domyślna wartość to [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| virtual [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() | Określa typ kompresji. Odczyt [TiffCompressionTypes](../tiffcompressiontypes/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Zwraca czcionkę używaną, gdy nie znaleziono czcionki źródłowej. Odczyt [System::String](../../system/string/). |
| virtual **uint32_t** [get_DpiX](./get_dpix/)() | Określa poziomą rozdzielczość w punktach na cal. Odczyt **uint32_t**. |
| virtual **uint32_t** [get_DpiY](./get_dpiy/)() | Określa pionową rozdzielczość w punktach na cal. Odczyt **uint32_t**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Zwraca styl wizualny gradientu. Odczyt [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() | Określa rozmiar generowanego obrazu TIFF. Wartość domyślna to 0x0, co oznacza, że rozmiary wygenerowanych obrazów będą obliczane na podstawie rozmiaru slajdu prezentacji. Odczyt [System::Drawing::Size](../../system.drawing/size/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Umożliwia opcje kontrolujące wygląd obiektów [Ink](../../aspose.slides.ink/) w wyeksportowanym dokumencie. Tylko do odczytu [IInkOptions](../iinkoptions/) |
| virtual [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() | Określa format pikseli dla wygenerowanych obrazów. Odczyt [ImagePixelFormat](../imagepixelformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Reprezentuje obiekt wywołania zwrotnego służący do zapisywania postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie **false**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Określa, czy pomijać hiperłącza z wywołaniami JavaScript przy zapisywaniu prezentacji. Odczyt **bool**. Domyślna wartość to **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Pobiera tryb, w którym slajdy są układane na stronie przy eksportowaniu prezentacji [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Zwraca obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy przerwany. Odczyt [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę w instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) | Określa algorytm konwertowania obrazu kolorowego na czarno-biały. Ta opcja zostanie zastosowana tylko jeśli [ITiffOptions::get_CompressionType()](./get_compressiontype/) jest ustawione na [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) lub [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) Zapis [BlackWhiteConversionMode](../blackwhiteconversionmode/). Domyślna wartość to [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| virtual void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) | Określa typ kompresji. Zapis [TiffCompressionTypes](../tiffcompressiontypes/). |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Ustawia czcionkę używaną, gdy nie znaleziono czcionki źródłowej. Zapis [System::String](../../system/string/). |
| virtual void [set_DpiX](./set_dpix/)(**uint32_t**) | Określa poziomą rozdzielczość w punktach na cal. Zapis **uint32_t**. |
| virtual void [set_DpiY](./set_dpiy/)(**uint32_t**) | Określa pionową rozdzielczość w punktach na cal. Zapis **uint32_t**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Ustawia styl wizualny gradientu. Zapis [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) | Określa rozmiar generowanego obrazu TIFF. Wartość domyślna to 0x0, co oznacza, że rozmiary wygenerowanych obrazów będą obliczane na podstawie rozmiaru slajdu prezentacji. Zapis [System::Drawing::Size](../../system.drawing/size/). |
| virtual void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) | Określa format pikseli dla generowanych obrazów. Zapis [ImagePixelFormat](../imagepixelformat/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Reprezentuje obiekt wywołania zwrotnego służący do zapisywania postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie **false**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Określa, czy pomijać hiperłącza z wywołaniami JavaScript przy zapisywaniu prezentacji. Zapis **bool**. Domyślna wartość to **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Ustawia tryb, w którym slajdy są układane na stronie przy eksportowaniu prezentacji [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy przerwany. Zapis [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie w instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [ISaveOptions](../isaveoptions/)
* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)