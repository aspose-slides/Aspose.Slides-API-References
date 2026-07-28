---
title: Object
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Klasa bazowa, która umożliwia korzystanie z metod dostępnych dla klasy System.Object w C#. Wszystkie nie-trywialne klasy używane w tłumaczonym środowisku powinny po niej dziedziczyć.
type: docs
weight: 1132
url: /pl/system/object/
---
## Klasa Object


Klasa bazowa, która umożliwia korzystanie z metod dostępnych dla klasy [System.Object](./) w C#. Wszystkie nie-trywialne klasy używane w tłumaczonym środowisku powinny po niej dziedziczyć.

```cpp
class Object
```

## Metody

| Method | Opis |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](./equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](./gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](./gettype/). |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](./lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../lockcontext/). |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](./memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](./object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](./object/)([Object](./) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie przy tworzeniu podklas. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie przy tworzeniu podklas. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](./referenceequals/) dla przypadku łańcucha znaków i nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specjalizacja [Object::ReferenceEquals](./referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](./sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../string/) [ToString](./tostring/)() const | Odpowiednik metody C# [Object.ToString()](./tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Implementuje konstrukcję C# typeof([System.Object](./)). |
| void [Unlock](./unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](./weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](./~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typów

| Typedef | Opis |
| --- | --- |
| [ptr](./ptr/) | Alias for smart pointer type. |

## Uwagi


Oprócz metod dostępnych w klasie C# [System.Object](./), zapewnia także wsparcie dla niektórych koncepcji specyficznych dla tłumaczonego środowiska kodu. Obejmuje to liczenie referencji używane przez klasy inteligentnych wskaźników ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) oraz inne usługi związane z zarządzaniem pamięcią, debugowaniem itp.

Każdy [Object](./) posiada dwa liczniki referencji: licznik współdzielonych referencji oraz licznik słabych referencji. Licznik słabych referencji jest zawsze przechowywany w odłączonej strukturze danych, a nie w samym [Object](./), co pozwala słabym wskaźnikom przetrwać po obiekcie, do którego się odwołują. Licznik inteligentnych referencji jest przechowywany albo w samym obiekcie, albo w tej samej odłączonej strukturze, w zależności od stanu makra ENABLE_EXTERNAL_REFCOUNT. Domyślnie jest włączony w kompilacjach debug i wyłączony w kompilacjach release. Jeśli licznik inteligentnych wskaźników jest przechowywany w samym obiekcie, odłączona struktura danych jest tworzona tylko wtedy, gdy istnieją słabe wskaźniki do obiektu. W przeciwnym razie jest tworzona razem z obiektem.

Wszystkie inteligentne wskaźniki korzystają z tych dwóch liczników referencji i przyczyniają się do tej samej, jedynej grupy własności.

Jeśli podklasa [Object](./) zostanie utworzona na stosie, nie może być do niej tworzonych inteligentnych wskaźników, w przeciwnym razie wystąpi problem z usuwaniem ze stosu.

Ten typ może być alokowany albo na stosie jako typ wartościowy, albo na stercie przy użyciu funkcji [System::MakeObject()](../makeobject/). Po alokacji obiektu nie należy mieszać tych dwóch przypadków użycia: posiadanie wskaźników [SmartPtr](../smartptr/) do obiektów alokowanych na stosie jest surowo zabronione.

## Zobacz także

* Namespace [System](../)
* Library [Aspose.Slides](../../)