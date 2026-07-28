---
title: ISlide
second_title: Aspose.Slides dla C++ Referencja API
description: Reprezentuje slajd w prezentacji.
type: docs
weight: 3758
url: /pl/aspose.slides/islide/
---
## ISlide klasa

Represents a slide in a presentation.

```cpp
class ISlide : public virtual Aspose::Slides::IBaseSlide,
               public Aspose::Slides::Theme::IOverrideThemeable
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | Zwraca efektywny motyw dla tego obiektu obsługującego motyw. |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | Określa, czy dwie instancje [IBaseSlide](../ibaseslide/) są równe. Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości. Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są równe. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId oraz dynamicznej zawartości, np. bieżącej wartości daty w [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki [Object.Equals](../../system/object/equals/) w C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | Znajduje pierwsze wystąpienie kształtu z określonym tekstem alternatywnym. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | Zwraca tło slajdu. Tylko do odczytu [IBackground](../ibackground/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | Zwraca kontrolkę ActiveX pod określonym indeksem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | Zwraca kolekcję kontrolek ActiveX na slajdzie. Tylko do odczytu [IControlCollection](../icontrolcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | Zwraca dane niestandardowe slajdu. Tylko do odczytu [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideHeaderFooterManager](../islideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | Zwraca menedżera nagłówka i stopki slajdu. Tylko do odczytu [ISlideHeaderFooterManager](../islideheaderfootermanager/). |
| virtual **bool** [get_Hidden](./get_hidden/)() | Określa, czy określony slajd jest ukryty podczas pokazu slajdów. Zwraca **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | Zapewnia łatwy dostęp do zawartych hiperłączy. Tylko do odczytu [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)() | Zwraca slajd układu dla bieżącego slajdu. Odczyt [ILayoutSlide](../ilayoutslide/). |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | Zwraca nazwę slajdu. Odczyt [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INotesSlideManager](../inotesslidemanager/)\> [get_NotesSlideManager](./get_notesslidemanager/)() | Umożliwia dostęp do slajdu notatek, dodawanie i usuwanie go. Tylko do odczytu [INotesSlideManager](../inotesslidemanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Zwraca prezentację. Tylko do odczytu [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | Zwraca kształt pod określonym indeksem. Tylko do odczytu [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | Zwraca kształty slajdu. Tylko do odczytu [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | Określa, czy kształty na slajdzie głównym powinny być wyświetlane na slajdach, czy nie. Dla samego slajdu głównego ta właściwość zawsze zwraca **false**. Odczyt **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Zwraca bazowy slajd. Tylko do odczytu [IBaseSlide](../ibaseslide/). |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | Zwraca identyfikator slajdu. Tylko do odczytu **uint32_t**. |
| virtual **int32_t** [get_SlideNumber](./get_slidenumber/)() | Zwraca numer slajdu. Indeks slajdu w kolekcji [IPresentation::get_Slides()](../ipresentation/get_slides/) jest zawsze równy SlideNumber - 1. Odczyt **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | Zwraca obiekt TransitionEx zawierający informacje o tym, jak określony slajd przechodzi podczas pokazu slajdów. Tylko do odczytu [ISlideShowTransition](../islideshowtransition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | Zwraca menedżera nadpisującego motywu. Tylko do odczytu [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | Zwraca obiekt osi czasu animacji. Tylko do odczytu [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda do [Object.GetHashCode()](../../system/object/gethashcode/) w C#. Umożliwia haszowanie obiektów niestandardowych. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)(**float**, **float**) | Zwraca obiekt obrazu z niestandardowym skalowaniem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() | Zwraca obiekt miniatury obrazu (20% rzeczywistego rozmiaru). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::Drawing::Size](../../system.drawing/size/)) | Zwraca obiekt obrazu o określonym rozmiarze. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>) | Zwraca obiekt miniatury bitmapy tiff z określonymi parametrami. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Zwraca obiekt miniatury bitmapy. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) | Zwraca obiekt miniatury bitmapy z niestandardowym skalowaniem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) | Zwraca obiekt miniatury bitmapy o określonym rozmiarze. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>\> [GetSlideComments](./getslidecomments/)([System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\>) | Zwraca wszystkie komentarze slajdu dodane przez konkretnego autora. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczny wywołaniu [System.Object.GetType()](../../system/object/gettype/) w C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny operatorowi 'is' w C#. |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu straży [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda do [Object.MemberwiseClone()](../../system/object/memberwiseclone/) w C#. Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| virtual void [Remove](./remove/)() | Usuwa slajd z prezentacji. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o określoną wartość. |
| virtual void [Reset](./reset/)() | Resetuje pozycję, rozmiar i formatowanie każdego kształtu, który ma prototyp na [LayoutSlide](../layoutslide/). |
| virtual void [set_Hidden](./set_hidden/)(**bool**) | Określa, czy określony slajd jest ukryty podczas pokazu slajdów. Zapis **bool**. |
| virtual void [set_LayoutSlide](./set_layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) | Ustawia slajd układu dla bieżącego slajdu. Zapis [ILayoutSlide](../ilayoutslide/). |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | Ustawia nazwę slajdu. Zapis [System::String](../../system/string/). |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | Określa, czy kształty na slajdzie macierzystym powinny być wyświetlane na slajdach, czy nie. Dla samego slajdu macierzystego właściwość ta zawsze zwraca **false**. Zapis **bool**. |
| virtual void [set_SlideNumber](./set_slidenumber/)(**int32_t**) | Zwraca numer slajdu. Indeks slajdu w kolekcji [IPresentation::get_Slides()](../ipresentation/get_slides/) jest zawsze równy SlideNumber - 1. Zapis **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda do [Object.ToString()](../../system/object/tostring/) w C#. Umożliwia konwertowanie obiektów niestandardowych na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję typeof([System.Object](../../system/object/)) w C#. |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu straży [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabego odwołania. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabego odwołania. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [WriteAsEmf](./writeasemf/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Zapisuje zawartość slajdu jako plik EMF. |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Zapisuje zawartość slajdu jako plik SVG. |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Zapisuje zawartość slajdu jako plik SVG. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IBaseSlide](../ibaseslide/)
* Klasa [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)