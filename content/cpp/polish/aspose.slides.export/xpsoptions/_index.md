---
title: XpsOptions
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Udostępnia opcje kontrolujące sposób zapisywania prezentacji w formacie XPS.
type: docs
weight: 807
url: /pl/aspose.slides.export/xpsoptions/
---
## XpsOptions klasa

Provides options that control how a presentation is saved in XPS format.

```cpp
class XpsOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IXpsOptions
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Zwraca czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa. Odczytuje [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | Prawda, aby narysować czarną ramkę wokół każdego slajdu. Odczytuje **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Zwraca styl wizualny gradientu. Odczytuje [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Reprezentuje obiekt zwrotny do zapisywania aktualizacji postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | Prawda, aby konwertować wszystkie pliki metafile używane w prezentacji na obrazy PNG. Odczytuje **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Odczytuje **bool**. Domyślna wartość to **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Zwraca lub ustawia obiekt, który otrzymuje ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Odczytuje [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczny wywołanie C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ustawia czcionkę używaną, gdy nie zostanie znaleziona czcionka źródłowa. Zapisuje [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | Prawda, aby narysować czarną ramkę wokół każdego slajdu. Zapisuje **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ustawia styl wizualny gradientu. Zapisuje [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Reprezentuje obiekt zwrotny do zapisywania aktualizacji postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | Prawda, aby konwertować wszystkie pliki metafile używane w prezentacji na obrazy PNG. Zapisuje **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Zapisuje **bool**. Domyślna wartość to **false**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Zwraca lub ustawia obiekt, który otrzymuje ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Zapisuje [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [XpsOptions](./xpsoptions/)() | Konstruktor domyślny. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Uwagi

The following example shows how to converting presentations to XPS using default settings. 
```cpp
// Utwórz obiekt Presentation, który reprezentuje plik prezentacji
auto pres = System::MakeObject<Presentation>(u"Convert_XPS.pptx");

// Zapisywanie prezentacji do dokumentu XPS
pres->Save(u"XPS_Output_Without_XPSOption_out.xps", SaveFormat::Xps);
```
 The following example shows how to converting presentations to XPS using custom settings. 
```cpp
// Utwórz obiekt Presentation, który reprezentuje plik prezentacji
auto pres = System::MakeObject<Presentation>(u"Convert_XPS_Options.pptx");

// Utwórz obiekt klasy TiffOptions
System::SharedPtr<XpsOptions> options = System::MakeObject<XpsOptions>();
// Zapisz MetaFiles jako PNG
options->set_SaveMetafilesAsPng(true);
// Zapisz prezentację do dokumentu XPS
pres->Save(u"XPS_With_Options_out.xps", SaveFormat::Xps, options);
```

## Zobacz także

* Klasa [SaveOptions](../saveoptions/)
* Klasa [IXpsOptions](../ixpsoptions/)
* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)