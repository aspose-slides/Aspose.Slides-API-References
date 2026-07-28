---
title: Portion
second_title: Aspose.Slides dla C++ – odniesienie API
description: Reprezentuje fragment tekstu w akapicie tekstowym.
type: docs
weight: 4772
url: /pl/aspose.slides/portion/
---
## Klasa Portion


Reprezentuje fragment tekstu wewnątrz akapitu tekstowego.

```cpp
class Portion : public Aspose::Slides::IPortion,
                public Aspose::Slides::IDOMObject
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [AddField](./addfield/)([System::SharedPtr](../../system/sharedptr/)\<[IFieldType](../ifieldtype/)\>) override | Konwertuje ten fragment na automatycznie aktualizowane pole. |
| void [AddField](./addfield/)([System::String](../../system/string/)) override | Konwertuje ten fragment na automatycznie aktualizowane pole. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::SharedPtr](../../system/sharedptr/)\<[IField](../ifield/)\> [get_Field](./get_field/)() override | Zwraca pole tego fragmentu. Tylko do odczytu [IField](../ifield/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_PortionFormat](./get_portionformat/)() override | Zwraca obiekt formatowania, który zawiera wyraźnie ustawione właściwości formatowania fragmentu tekstu bez zastosowanego dziedziczenia. Tylko do odczytu [IPortionFormat](../iportionformat/). |
| [System::String](../../system/string/) [get_Text](./get_text/)() override | Pobiera zwykły tekst fragmentu. Odczyt [System::String](../../system/string/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [GetCoordinates](./getcoordinates/)() override | Pobiera współrzędne początku fragmentu. Współrzędna X punktu reprezentuje początek fragmentu od pierwszego znaku, włączając lewy margines boczny. Współrzędna Y obejmuje górny margines boczny. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetRect](./getrect/)() override | Pobiera współrzędne prostokąta ograniczającego fragment. Prostokąt obejmuje wszystkie linie tekstu w fragmencie, w tym puste. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, naprawdę, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, naprawdę, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie konstruktorów podklas. |
|  [Portion](./portion/)() | Inicjalizuje nową instancję klasy [Portion](./). |
|  [Portion](./portion/)([System::String](../../system/string/)) | Inicjalizuje nową instancję klasy [Portion](./). |
|  [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Portion](./)\>) | Inicjalizuje nową instancję klasy [Portion](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o określoną wartość. |
| void [RemoveField](./removefield/)() override | Konwertuje ten fragment pola na prosty fragment. |
| void [set_Text](./set_text/)([System::String](../../system/string/)) override | Ustawia zwykły tekst fragmentu. Zapis [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IPortion](../iportion/)
* Klasa [IDOMObject](../idomobject/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)