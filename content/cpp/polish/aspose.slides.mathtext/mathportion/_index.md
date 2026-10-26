---
title: MathPortion
second_title: Aspose.Slides dla C++ - Referencja API
description: Reprezentuje część z kontekstem matematycznym wewnątrz.
type: docs
weight: 1041
url: /pl/aspose.slides.mathtext/mathportion/
---
## MathPortion klasa


Reprezentuje część z kontekstem matematycznym wewnątrz.

```cpp
class MathPortion : public Aspose::Slides::Portion,
                    public Aspose::Slides::MathText::IMathPortion
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [AddField](../../aspose.slides/portion/addfield/)([System::SharedPtr](../../system/sharedptr/)\<[IFieldType](../../aspose.slides/ifieldtype/)\>) override | Konwertuje tę część do automatycznie aktualizowanego pola. |
| void [AddField](../../aspose.slides/portion/addfield/)([System::String](../../system/string/)) override | Konwertuje tę część do automatycznie aktualizowanego pola. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwie wartości NaN są uznawane za równe, pomimo że zgodnie z IEC 60559:1989 NaN nie jest równa żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwie wartości NaN są uznawane za równe, pomimo że zgodnie z IEC 60559:1989 NaN nie jest równa żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::SharedPtr](../../system/sharedptr/)\<[IField](../../aspose.slides/ifield/)\> [get_Field](../../aspose.slides/portion/get_field/)() override | Zwraca pole tej części. Tylko do odczytu [IField](../../aspose.slides/ifield/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathParagraph](../imathparagraph/)\> [get_MathParagraph](./get_mathparagraph/)() override | Akapit matematyczny |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../../aspose.slides/iportionformat/)\> [get_PortionFormat](../../aspose.slides/portion/get_portionformat/)() override | Zwraca obiekt formatowania, który zawiera jawnie ustawione właściwości formatowania części tekstu bez zastosowania dziedziczenia. Tylko do odczytu [IPortionFormat](../../aspose.slides/iportionformat/). |
| [System::String](../../system/string/) [get_Text](../../aspose.slides/portion/get_text/)() override | Pobiera zwykły tekst części. Odczyt [System::String](../../system/string/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [GetCoordinates](../../aspose.slides/portion/getcoordinates/)() override | Pobiera współrzędne początku części. Współrzędna X punktu reprezentuje początek części od pierwszego znaku, włącznie z lewym marginesem. Współrzędna Y zawiera górny margines. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetRect](../../aspose.slides/portion/getrect/)() override | Pobiera współrzędne prostokąta ograniczającego część. Prostokąt obejmuje wszystkie wiersze tekstu w części, łącznie z pustymi. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| [MathPortion](./mathportion/)() | Inicjalizuje nową instancję klasy [MathPortion](./). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Portion](../../aspose.slides/portion/portion/)() | Inicjalizuje nową instancję klasy [Portion](../../aspose.slides/portion/). |
| [Portion](../../aspose.slides/portion/portion/)([System::String](../../system/string/)) | Inicjalizuje nową instancję klasy [Portion](../../aspose.slides/portion/). |
| [Portion](../../aspose.slides/portion/portion/)([System::SharedPtr](../../system/sharedptr/)\<[Portion](../../aspose.slides/portion/)\>) | Inicjalizuje nową instancję klasy [Portion](../../aspose.slides/portion/). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [RemoveField](../../aspose.slides/portion/removefield/)() override | Konwertuje tę część pola na prostą część. |
| void [set_Text](../../aspose.slides/portion/set_text/)([System::String](../../system/string/)) override | Ustawia zwykły tekst części. Zapis [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do ciągu znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Uwagi


Example: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## Zobacz także

* Klasa [Portion](../../aspose.slides/portion/)
* Klasa [IMathPortion](../imathportion/)
* Przestrzeń nazw [Aspose::Slides::MathText](../)
* Biblioteka [Aspose.Slides](../../)