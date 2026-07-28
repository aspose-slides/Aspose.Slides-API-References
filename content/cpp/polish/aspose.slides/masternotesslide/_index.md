---
title: MasterNotesSlide
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Reprezentuje slajd nadrzędny notatek.
type: docs
weight: 4447
url: /pl/aspose.slides/masternotesslide/
---
# MasterNotesSlide klasa

Reprezentuje slajd nadrzędny notatek.

```cpp
class MasterNotesSlide : public Aspose::Slides::BaseSlide,
                         public Aspose::Slides::IMasterNotesSlide
```

## Metody

| Metoda | Opis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | Zwraca efektywny motyw dla tego slajdu. |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | Określa, czy dwie instancje [IBaseSlide](../ibaseslide/) są równe. Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości. Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itd. są równe. Porównanie nie uwzględnia unikalnych wartości identyfikatorów, np. SlideId oraz dynamicznej zawartości, np. aktualnej wartości daty w Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uważane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | Znajduje pierwsze wystąpienie kształtu o określonym alternatywnym tekście. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | Zwraca tło slajdu. Tylko do odczytu [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | Zwraca kontrolkę ActiveX pod wskazanym indeksem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | Zwraca kolekcję kontrolek ActiveX na slajdzie. Tylko do odczytu [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | Zwraca niestandardowe dane slajdu. Tylko do odczytu [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() override | Zwraca kolekcję przewodników rysunkowych dla slajdu notatek głównych. Tylko do odczytu [IDrawingGuidesCollection](../idrawingguidescollection/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterNotesSlideHeaderFooterManager](../imasternotesslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | Zwraca menedżera nagłówka i stopki slajdu notatek głównych. Tylko do odczytu [IMasterHandoutSlideHeaderFooterManager](../imasterhandoutslideheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | Zapewnia łatwy dostęp do zawartych hiperłączy. Tylko do odczytu [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::String](../../system/string/) [get_Name](../baseslide/get_name/)() override | Zwraca nazwę slajdu. Odczyt [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_NotesStyle](./get_notesstyle/)() override | Zwraca styl tekstu notatek. Tylko do odczytu [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | Zwraca interfejs [IPresentation](../ipresentation/). Tylko do odczytu [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | Zwraca kształt pod wskazanym indeksem. Tylko do odczytu [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | Zwraca kształty slajdu. Tylko do odczytu [IShapeCollection](../ishapecollection/). |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | Określa, czy kształty na slajdzie nadrzędnym powinny być wyświetlane na slajdach, czy nie. Dla samego slajdu nadrzędnego ta właściwość zawsze zwraca **false**. Odczyt **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Zwraca slajd bazowy. Tylko do odczytu [IBaseSlide](../ibaseslide/). |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | Zwraca identyfikator slajdu. Tylko do odczytu **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | Zwraca obiekt Transition, który zawiera informacje o tym, jak określony slajd przechodzi w trakcie pokazu slajdów. Tylko do odczytu [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](./get_thememanager/)() override | Zwraca menedżera motywów. Tylko do odczytu [Theme::IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | Zwraca obiekt osi czasu animacji. Tylko do odczytu [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Uzyskuje strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Uzyskuje rzeczywisty typ obiektu. Analogiczna metoda C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analogiczny operator C# 'is'. |
| void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)() override | Łączy ciągi o tym samym formatowaniu we wszystkich akapitach wszystkich akceptowalnych kształtów. |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | Łączy ciągi o tym samym formatowaniu we wszystkich akapitach we wszystkich akceptowalnych kształtach. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, właściwie, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, właściwie, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_Name](../baseslide/set_name/)([System::String](../../system/string/)) override | Ustawia nazwę slajdu. Zapis [System::String](../../system/string/). |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | Określa, czy kształty na slajdzie nadrzędnym powinny być wyświetlane na slajdach, czy nie. Dla samego slajdu nadrzędnego ta właściwość zawsze zwraca **false**. Zapis **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Uzyskuje bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie niestandardowych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [BaseSlide](../baseslide/)
* Klasa [IMasterNotesSlide](../imasternotesslide/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)