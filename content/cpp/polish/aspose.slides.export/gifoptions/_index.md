---
title: GifOptions
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Reprezentuje opcje eksportu GIF.
type: docs
weight: 53
url: /pl/aspose.slides.export/gifoptions/
---
## GifOptions klasa


Represents GIF exporting options.

```cpp
class GifOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IGifOptions
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **int32_t** [get_DefaultDelay](./get_defaultdelay/)() override | Pobiera domyślny czas opóźnienia [ms]. Ta wartość zostanie użyta, jeśli metoda [ISlideShowTransition::set_AdvanceAfterTime()](../../aspose.slides/islideshowtransition/set_advanceaftertime/) nie została wywołana. Domyślna wartość to 1000. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Zwraca czcionkę używaną w przypadku, gdy źródłowa czcionka nie zostanie znaleziona. Odczytuje [System::String](../../system/string/). |
| **bool** [get_ExportHiddenSlides](./get_exporthiddenslides/)() override | Określa, czy ukryte slajdy będą eksportowane. Domyślna wartość to false. |
| [System::Drawing::Size](../../system.drawing/size/) [get_FrameSize](./get_framesize/)() override | Pobiera rozmiar ramki. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Zwraca styl wizualny gradientu. Odczytuje [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Reprezentuje obiekt wywołania zwrotnego służący do zapisywania aktualizacji postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Odczyt **bool**. Domyślna wartość to **false**. |
| **int32_t** [get_TransitionFps](./get_transitionfps/)() override | Pobiera FPS przejścia [klatki/sek] Domyślna wartość to 25. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Odczytuje [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
|  [GifOptions](./gifoptions/)() | Inicjalizuje nową instancję klasy [GifOptions](./). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultDelay](./set_defaultdelay/)(**int32_t**) override | Ustawia domyślny czas opóźnienia [ms]. Ta wartość zostanie użyta, jeśli metoda [ISlideShowTransition::set_AdvanceAfterTime()](../../aspose.slides/islideshowtransition/set_advanceaftertime/) nie została wywołana. Domyślna wartość to 1000. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ustawia czcionkę używaną w przypadku, gdy źródłowa czcionka nie zostanie znaleziona. Zapisuje [System::String](../../system/string/). |
| void [set_ExportHiddenSlides](./set_exporthiddenslides/)(**bool**) override | Określa, czy ukryte slajdy będą eksportowane. Domyślna wartość to false. |
| void [set_FrameSize](./set_framesize/)([System::Drawing::Size](../../system.drawing/size/)) override | Ustawia rozmiar ramki. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ustawia styl wizualny gradientu. Zapisuje [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Reprezentuje obiekt wywołania zwrotnego służący do zapisywania aktualizacji postępu w procentach. Zobacz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Określa, czy pomijać hiperłącza z wywołaniami JavaScript podczas zapisywania prezentacji. Zapisz **bool**. Domyślna wartość to **false**. |
| void [set_TransitionFps](./set_transitionfps/)(**int32_t**) override | Ustawia FPS przejścia [klatki/sek] Domyślna wartość to 25. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Zwraca lub ustawia obiekt, który odbiera ostrzeżenia i decyduje, czy proces ładowania będzie kontynuowany, czy zostanie przerwany. Zapisz [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie niestandardowych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Uwagi


Poniższy przykład pokazuje, jak konwertować prezentacje na animowany GIF przy użyciu niestandardowych ustawień. 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto gifOptions = System::MakeObject<GifOptions>();

gifOptions->set_FrameSize(System::Drawing::Size(960, 720)); // rozmiar wynikowego GIF-a
gifOptions->set_DefaultDelay(2000); // jak długo każdy slajd będzie wyświetlany, zanim zostanie zmieniony na kolejny
gifOptions->set_TransitionFps(35); // zwiększ FPS, aby poprawić jakość animacji przejścia

pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Zobacz także

* Klasa [SaveOptions](../saveoptions/)
* Klasa [IGifOptions](../igifoptions/)
* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)