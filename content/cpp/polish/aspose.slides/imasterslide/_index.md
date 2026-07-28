---
title: IMasterSlide
second_title: Aspose.Slides dla C++ odniesienie API
description: Reprezentuje slajd-mistrz w prezentacji.
type: docs
weight: 2926
url: /pl/aspose.slides/imasterslide/
---
## IMasterSlide klasa

Represents a master slide in a presentation.

```cpp
class IMasterSlide : public virtual Aspose::Slides::IBaseSlide,
                     public Aspose::Slides::Theme::IMasterThemeable
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](./)\> [ApplyExternalThemeToDependingSlides](./applyexternalthemetodependingslides/)([System::String](../../system/string/)) | Tworzy nowy slajd master na podstawie bieżącego, stosując do niego zewnętrzny motyw i stosuje utworzony slajd master do wszystkich zależnych slajdów. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | Zwraca efektywny motyw dla tego obiektu obsługującego motywy. |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | Określa, czy dwie instancje [IBaseSlide](../ibaseslide/) są równe. Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości. Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są równe. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId oraz dynamicznej zawartości, np. bieżącej wartości daty w elemencie Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | Znajduje pierwsze wystąpienie kształtu o określonym alternatywnym tekście. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | Zwraca tło slajdu. Tylko do odczytu [IBackground](../ibackground/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_BodyStyle](./get_bodystyle/)() | Zwraca styl tekstu podstawowego. Tylko do odczytu [ITextStyle](../itextstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | Zwraca kontrolkę ActiveX o podanym indeksie. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | Zwraca kolekcję kontrolek ActiveX na slajdzie. Tylko do odczytu [IControlCollection](../icontrolcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | Zwraca własne dane slajdu. Tylko do odczytu [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() | Zwraca kolekcję przewodników rysowania dla slajdu master. Tylko do odczytu [IDrawingGuidesCollection](../idrawingguidescollection/) |
| virtual **bool** [get_HasDependingSlides](./get_hasdependingslides/)() | Zwraca true, jeśli istnieje co najmniej jeden slajd zależny od tego slajdu master. Tylko do odczytu **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | Zwraca menedżera nagłówka i stopki slajdu master. Tylko do odczytu [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | Zapewnia łatwy dostęp do zawartych hiperłączy. Tylko do odczytu [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) | Zwraca slajd układu podrzędnego tego slajdu master o podanym indeksie. Tylko do odczytu [Aspose::Slides::ILayoutSlide](../ilayoutslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() | Zwraca kolekcję slajdów układów podrzędnych dla tego slajdu master. Tylko do odczytu [IMasterLayoutSlideCollection](../imasterlayoutslidecollection/). |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | Zwraca nazwę slajdu. Odczyt [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_OtherStyle](./get_otherstyle/)() | Zwraca styl innego tekstu. Tylko do odczytu [ITextStyle](../itextstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Zwraca prezentację. Tylko do odczytu [IPresentation](../ipresentation/). |
| virtual **bool** [get_Preserve](./get_preserve/)() | Określa, czy odpowiadający master zostaje usunięty, gdy wszystkie slajdy po nim zostaną usunięte. Uwaga: [Aspose.Slides](../) nigdy nie usunie nieużywanego mastera samodzielnie; aby rzeczywiście usunąć nieużywane mastery, wywołaj [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/). Tylko odczyt **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | Zwraca kształt o podanym indeksie. Tylko do odczytu [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | Zwraca kształty slajdu. Tylko do odczytu [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | Określa, czy kształty na slajdzie master powinny być wyświetlane na slajdach, czy nie. Dla samego slajdu master własność zawsze zwraca **false**. Tylko odczyt **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Zwraca podstawowy slajd. Tylko do odczytu [IBaseSlide](../ibaseslide/). |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | Zwraca identyfikator slajdu. Tylko do odczytu **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | Zwraca obiekt TransitionEx zawierający informacje o tym, jak określony slajd przechodzi podczas pokazu slajdów. Tylko do odczytu [ISlideShowTransition](../islideshowtransition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](../../aspose.slides.theme/imasterthemeable/get_thememanager/)() | Zwraca menedżera motywu master. Tylko do odczytu [IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | Zwraca obiekt osi czasu animacji. Tylko do odczytu [IAnimationTimeLine](../ianimationtimeline/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TitleStyle](./get_titlestyle/)() | Zwraca styl tekstu tytułu. Tylko do odczytu [ITextStyle](../itextstyle/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() | Zwraca tablicę ze wszystkimi slajdami zależnymi od tego slajdu master. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia hashowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu wartownika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | Ustawia nazwę slajdu. Zapis [System::String](../../system/string/). |
| virtual void [set_Preserve](./set_preserve/)(**bool**) | Określa, czy odpowiadający master zostaje usunięty, gdy wszystkie slajdy po nim zostaną usunięte. Uwaga: [Aspose.Slides](../) nigdy nie usunie nieużywanego mastera samodzielnie; aby rzeczywiście usunąć nieużywane mastery, wywołaj [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/). Zapisz **bool**. |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | Określa, czy kształty na slajdzie master powinny być wyświetlane na slajdach, czy nie. Dla samego slajdu master własność zawsze zwraca **false**. Zapisz **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu wartownika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IBaseSlide](../ibaseslide/)
* Klasa [IMasterThemeable](../../aspose.slides.theme/imasterthemeable/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)