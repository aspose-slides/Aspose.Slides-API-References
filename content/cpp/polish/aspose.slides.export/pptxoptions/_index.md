---
title: PptxOptions
second_title: Aspose.Slides dla C++ - Referencja API
description: Reprezentuje opcje zapisywania prezentacji OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
type: docs
weight: 599
url: /pl/aspose.slides.export/pptxoptions/
---
## Klasa PptxOptions

Represents options for saving OpenXml presentations (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

```cpp
class PptxOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::IPptxOptions
```

## Metody

| Method | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [Aspose::Slides::Export::CompressionLevel](../compressionlevel/) [get_CompressionLevel](./get_compressionlevel/)() override | Określa poziom kompresji używany przy zapisywaniu dokumentu prezentacji. Domyślna wartość to [CompressionLevel::Level6](../compressionlevel/). |
| [Aspose::Slides::Export::Conformance](../conformance/) [get_Conformance](./get_conformance/)() override | Określa klasę zgodności, do której dokument [Presentation](../../aspose.slides/presentation/) jest zgodny. Domyślna wartość to [Aspose::Slides::Export::Conformance::Ecma376_2006](../conformance/) |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Zwraca czcionkę używaną w przypadku, gdy nie znaleziono czcionki źródłowej. Odczytuje [System::String](../../system/string/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Zwraca styl wizualny gradientu. Odczytuje [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Reprezentuje obiekt zwrotny (callback) do zapisywania postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RefreshThumbnail](./get_refreshthumbnail/)() override | Określa, czy miniatura prezentacji zostanie odświeżona. Odczyt **bool**. Domyślna wartość to **true**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Określa, czy pomijać hiperłącza z wywołaniami JavaScript przy zapisywaniu prezentacji. Odczyt **bool**. Domyślna wartość to **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Zwraca lub ustawia obiekt, który otrzymuje ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Odczyt [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| [Aspose::Slides::Export::Zip64Mode](../zip64mode/) [get_Zip64Mode](./get_zip64mode/)() override | Określa, czy format ZIP64 jest używany dla dokumentu [Presentation](../../aspose.slides/presentation/). Domyślna wartość to [Zip64Mode::IfNecessary](../zip64mode/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczny wywołanie C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuję niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuję niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
|  [PptxOptions](./pptxoptions/)() | Tworzy nową instancję [PptxOptions](./) |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_CompressionLevel](./set_compressionlevel/)([Aspose::Slides::Export::CompressionLevel](../compressionlevel/)) override | Określa poziom kompresji używany przy zapisywaniu dokumentu prezentacji. Domyślna wartość to [CompressionLevel::Level6](../compressionlevel/). |
| void [set_Conformance](./set_conformance/)([Aspose::Slides::Export::Conformance](../conformance/)) override | Określa klasę zgodności, do której dokument [Presentation](../../aspose.slides/presentation/) jest zgodny. Domyślna wartość to [Aspose::Slides::Export::Conformance::Ecma376_2006](../conformance/) |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ustawia czcionkę używaną, gdy nie znaleziono czcionki źródłowej. Zapisuje [System::String](../../system/string/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ustawia styl wizualny gradientu. Zapisuje [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Reprezentuje obiekt zwrotny (callback) do zapisywania postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RefreshThumbnail](./set_refreshthumbnail/)(**bool**) override | Określa, czy miniatura prezentacji ma być odświeżona. Zapis **bool**. Domyślna wartość to **true**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Określa, czy pomijać hiperłącza z wywołaniami JavaScript przy zapisywaniu prezentacji. Zapis **bool**. Domyślna wartość to **false**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Zwraca lub ustawia obiekt, który otrzymuje ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Zapis [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| void [set_Zip64Mode](./set_zip64mode/)([Aspose::Slides::Export::Zip64Mode](../zip64mode/)) override | Określa, czy format ZIP64 jest używany dla dokumentu [Presentation](../../aspose.slides/presentation/). Domyślna wartość to [Zip64Mode::IfNecessary](../zip64mode/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję niestandardowych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [SaveOptions](../saveoptions/)
* Klasa [IPptxOptions](../ipptxoptions/)
* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)