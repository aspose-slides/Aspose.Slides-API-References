---
title: ITiming
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Reprezentuje synchronizację animacji.
type: docs
weight: 443
url: /pl/aspose.slides.animation/itiming/
---
## ITiming klasa

Reprezentuje synchronizację animacji.

```cpp
class ITiming : public virtual System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | Opisuje procent trwania efektu przyspieszenia. Odczyt **float**. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | Opisuje, czy animacja ma być automatycznie odtwarzana w odwrotnym kierunku po odtworzeniu w kierunku do przodu. Odczyt **bool**. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | Opisuje procent trwania efektu zwolnienia. Odczyt **float**. |
| virtual **float** [get_Duration](./get_duration/)() | Opisuje czas trwania efektu animacji. Odczyt **float**. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | Opisuje liczbę powtórzeń efektu. Odczyt **float**. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | Opisuje liczbę powtórzeń efektu. Odczyt **float**. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | Ten atrybut określa, czy efekt będzie powtarzany aż do końca slajdu. Odczyt **bool**. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | Ten atrybut określa, czy efekt będzie powtarzany aż do następnego kliknięcia. Odczyt **bool**. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | Określa, czy efekt ma się restartować po zakończeniu. Odczyt [EffectRestartType](../effectrestarttype/). |
| virtual **bool** [get_Rewind](./get_rewind/)() | Ten atrybut określa, czy efekt zostanie przewinięty po zakończeniu odtwarzania. Odczyt **bool**. |
| virtual **float** [get_Speed](./get_speed/)() | Określa procent przyspieszenia (lub spowolnienia) czasu. Odczyt **float**. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | Opisuje czas opóźnienia po wyzwalaczu. Odczyt **float**. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | Opisuje typ wyzwalacza. Odczyt [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Tak naprawdę nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Tak naprawdę nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | Opisuje procent trwania efektu przyspieszenia. Zapis **float**. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | Opisuje, czy animacja ma być automatycznie odtwarzana w odwrotnym kierunku po odtworzeniu w kierunku do przodu. Zapis **bool**. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | Opisuje procent trwania efektu zwolnienia. Zapis **float**. |
| virtual void [set_Duration](./set_duration/)(**float**) | Opisuje czas trwania efektu animacji. Zapis **float**. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | Opisuje liczbę powtórzeń efektu. Zapis **float**. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | Opisuje liczbę powtórzeń efektu. Zapis **float**. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | Ten atrybut określa, czy efekt będzie powtarzany aż do końca slajdu. Zapis **bool**. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | Ten atrybut określa, czy efekt będzie powtarzany aż do następnego kliknięcia. Zapis **bool**. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | Określa, czy efekt ma się restartować po zakończeniu. Zapis [EffectRestartType](../effectrestarttype/). |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | Ten atrybut określa, czy efekt zostanie przewinięty po zakończeniu odtwarzania. Zapis **bool**. |
| virtual void [set_Speed](./set_speed/)(**float**) | Określa procent przyspieszenia (lub spowolnienia) czasu. Zapis **float**. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | Opisuje czas opóźnienia po wyzwalaczu. Zapis **float**. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | Opisuje typ wyzwalacza. Zapis [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia zmianę wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [Aspose::Slides::Animation](../)
* Biblioteka [Aspose.Slides](../../)