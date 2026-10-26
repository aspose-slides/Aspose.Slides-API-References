---
title: SlideShowTransition
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Reprezentuje przejście pokazu slajdów.
type: docs
weight: 404
url: /pl/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition klasa

Represents slide show transition.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## Metody

| Metoda | Opis |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Określa, czy dwie instancje [SlideShowTransition](./) są równe. Odczyt/zapis **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie. Odczyt **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | Określa czas w milisekundach, po którym powinno rozpocząć się przejście. To ustawienie może być użyte razem z atrybutem advClick. Jeśli ten atrybut nie jest określony, zakłada się, że nie będzie automatycznego przejścia. Odczyt **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | Określa, czy kliknięcie myszy przejdzie do kolejnego slajdu. Jeśli ten atrybut nie jest określony, przyjmuje się wartość true. Odczyt **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | Pobiera czas trwania efektu przejścia slajdu w milisekundach. Odczyt **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | Zwraca osadzone dane audio. Odczyt [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | Określa, czy ten dźwięk jest wbudowany. Jeśli atrybut jest ustawiony na true, aplikacja generująca zostaje powiadomiona o sprawdzeniu atrybutu name określonego dla tego dźwięku na liście wbudowanych dźwięków i może wtedy wyświetlić niestandardową nazwę lub interfejs użytkownika w razie potrzeby. Odczytuje **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | Ten atrybut określa, czy dźwięk będzie powtarzany aż do wystąpienia kolejnego zdarzenia dźwiękowego w pokazie slajdów. Odczyt **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | Ustawia lub zwraca tryb dźwięku dla przejścia slajdu. Odczyt [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | Określa nazwę czytelną dla dźwięku przejścia. [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) musi być przypisany, aby pobrać lub ustawić nazwę dźwięku. Odczytuje [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | Określa prędkość przejścia używaną przy przechodzeniu z bieżącego slajdu do następnego. Odczyt [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | Typ przejścia. Odczyt [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) wartość przejścia pokazu. Tylko do odczytu [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji związaną z obiektem. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Służy jako funkcja skrótu dla określonego typu, odpowiednia do użycia w algorytmach haszowania i strukturach danych takich jak tablica haszująca. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogia wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogia operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstrukcji podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstrukcji podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | Ten atrybut określa, czy pokaz slajdów przejdzie do następnego slajdu po określonym czasie. Zapis **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | Określa czas w milisekundach, po którym powinno rozpocząć się przejście. To ustawienie może być użyte razem z atrybutem advClick. Jeśli ten atrybut nie jest określony, zakłada się, że nie będzie automatycznego przejścia. Zapis **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | Określa, czy kliknięcie myszy przejdzie do kolejnego slajdu. Jeśli ten atrybut nie jest określony, przyjmuje się wartość true. Zapis **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | Ustawia czas trwania efektu przejścia slajdu w milisekundach. Zapis **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | Ustawia osadzone dane audio. Zapis [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | Określa, czy ten dźwięk jest wbudowany. Jeśli atrybut jest ustawiony na true, aplikacja generująca zostaje powiadomiona o sprawdzeniu atrybutu name określonego dla tego dźwięku na liście wbudowanych dźwięków i może wtedy wyświetlić niestandardową nazwę lub interfejs użytkownika w razie potrzeby. Zapisuje **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | Ten atrybut określa, czy dźwięk będzie powtarzany aż do wystąpienia kolejnego zdarzenia dźwiękowego w pokazie slajdów. Zapis **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | Ustawia lub zwraca tryb dźwięku dla przejścia slajdu. Zapis [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | Określa nazwę czytelną dla dźwięku przejścia. [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) musi być przypisany, aby pobrać lub ustawić nazwę dźwięku. Zapisuje [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | Określa prędkość przejścia używaną przy przechodzeniu z bieżącego slajdu do następnego. Zapis [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | Typ przejścia. Zapis [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Ustaw n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję niestandardowych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [DomObject](../../aspose.slides/domobject/)
* Klasa [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* Przestrzeń nazw [Aspose::Slides::SlideShow](../)
* Biblioteka [Aspose.Slides](../../)