---
title: Timing
second_title: Referencja API Aspose.Slides dla C++
description: Reprezentuje synchronizację animacji.
type: docs
weight: 625
url: /pl/aspose.slides.animation/timing/
---
## Klasa Timing

Reprezentuje synchronizację animacji.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **float** [get_Accelerate](./get_accelerate/)() override | Opisuje procent trwania efektu przyspieszenia. Odczyt **float**. |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | Opisuje, czy animacja ma być automatycznie odtwarzana od tyłu po odtworzeniu w kierunku do przodu. Odczyt **bool**. |
| **float** [get_Decelerate](./get_decelerate/)() override | Opisuje procent trwania efektu zwolnienia. Odczyt **float**. |
| **float** [get_Duration](./get_duration/)() override | Opisuje czas trwania efektu animacji. Odczyt **float**. |
| **float** [get_RepeatCount](./get_repeatcount/)() override | Opisuje liczbę powtórzeń efektu. Odczyt **float**. |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | Opisuje liczbę powtórzeń efektu. Odczyt **float**. |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | Ten atrybut określa, czy efekt będzie powtarzany do końca slajdu. Odczyt **bool**. |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | Ten atrybut określa, czy efekt będzie powtarzany do następnego kliknięcia. Odczyt **bool**. |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | Określa, czy efekt ma zostać ponownie uruchomiony po zakończeniu. Odczyt [EffectRestartType](../effectrestarttype/). |
| **bool** [get_Rewind](./get_rewind/)() override | Ten atrybut określa, czy efekt zostanie przewinięty po zakończeniu odtwarzania. Odczyt **bool**. |
| **float** [get_Speed](./get_speed/)() override | Określa procent przyspieszenia (lub spowolnienia) czasu. Odczyt **float**. |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | Opisuje opóźnienie po wyzwalaczu. Odczyt **float**. |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | Opisuje typ wyzwalacza. Odczyt [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczne wywołanie C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny operator C# `is`. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę C# lock() statement. Wywołaj bezpośrednio lub użyj obiektu stróżującego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_Accelerate](./set_accelerate/)(**float**) override | Opisuje procent trwania efektu przyspieszenia. Zapis **float**. |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | Opisuje, czy animacja ma być automatycznie odtwarzana od tyłu po odtworzeniu w kierunku do przodu. Zapis **bool**. |
| void [set_Decelerate](./set_decelerate/)(**float**) override | Opisuje procent trwania efektu zwolnienia. Zapis **float**. |
| void [set_Duration](./set_duration/)(**float**) override | Opisuje czas trwania efektu animacji. Zapis **float**. |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | Opisuje liczbę powtórzeń efektu. Zapis **float**. |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | Opisuje liczbę powtórzeń efektu. Zapis **float**. |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | Ten atrybut określa, czy efekt będzie powtarzany do końca slajdu. Zapis **bool**. |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | Ten atrybut określa, czy efekt będzie powtarzany do następnego kliknięcia. Zapis **bool**. |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | Określa, czy efekt ma zostać ponownie uruchomiony po zakończeniu. Zapis [EffectRestartType](../effectrestarttype/). |
| void [set_Rewind](./set_rewind/)(**bool**) override | Ten atrybut określa, czy efekt zostanie przewinięty po zakończeniu odtwarzania. Zapis **bool**. |
| void [set_Speed](./set_speed/)(**float**) override | Określa procent przyspieszenia (lub spowolnienia) czasu. Zapis **float**. |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | Opisuje opóźnienie po wyzwalaczu. Zapis **float**. |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | Opisuje typ wyzwalacza. Zapis [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie C# lock() statement. Wywołaj bezpośrednio lub użyj obiektu stróżującego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie należy wywoływać bezpośrednio; używaj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [ITiming](../itiming/)
* Klasa [IDOMObject](../../aspose.slides/idomobject/)
* Przestrzeń nazw [Aspose::Slides::Animation](../)
* Biblioteka [Aspose.Slides](../../)