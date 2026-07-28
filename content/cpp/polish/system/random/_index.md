---
title: Random
second_title: Aspose.Slides – odniesienie API dla C++
description: "Reprezentuje generator liczb pseudolosowych. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operator new, ponieważ spowoduje to błędy czasu wykonania i/lub awarie asercji. Zawsze owiń tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania go funkcjom jako argument."
type: docs
weight: 1184
url: /pl/system/random/
---
## Klasa Random


Reprezentuje generator liczb pseudolosowych. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub awarie asercji. Zawsze owiń tę klasę wskaźnikiem [System::SmartPtr](../smartptr/) i używaj tego wskaźnika do przekazywania go funkcjom jako argument.

```cpp
class Random : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| **bool** [IsNull](./isnull/)() const | Zawsze zwraca false. |
| void [Lock](../object/lock/)() | Implementuje blokadę statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu wartownika [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| virtual **int32_t** [Next](./next/)() | Zwraca nieujemną liczbę losową mniejszą niż maksymalna wartość int32. |
| virtual **int32_t** [Next](./next/)(**int32_t**) | Zwraca nieujemną liczbę losową mniejszą niż określona maksymalna wartość. |
| virtual **int32_t** [Next](./next/)(**int32_t**, **int32_t**) | Zwraca liczbę losową w określonym przedziale. |
| virtual void [NextBytes](./nextbytes/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Wypełnia elementy określonej tablicy bajtów liczbami losowymi. |
| virtual **double** [NextDouble](./nextdouble/)() | Zwraca liczbę losową w przedziale od 0.0 do 1.0. |
|  [Object](../object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
|  [Random](./random/)() | Inicjalizuje nową instancję, używając zależnej od czasu domyślnej wartości ziarna. |
|  [Random](./random/)(**int32_t**) | Inicjalizuje nową instancję klasy [System.Random](./), używając określonej wartości ziarna. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako wskaźnik słaby (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach do trybu słabego. |
| int [SharedCount](../object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Inkrementuje licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Dekrementuje i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementuje odblokowanie statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu wartownika [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Inkrementuje licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Dekrementuje licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Uwagi



```cpp
#include "system/random.h"
#include "system/smart_ptr.h"
#include <iostream>

int main()
{
  const auto rnd = System::MakeObject<System::Random>();

  // Pobierz losowy numer miesiąca i wypisz go.
  auto monthNumber = rnd->Next(1, 13);
  std::cout << "Month: " << monthNumber << std::endl;

  // Wypełnij tablicę losowymi liczbami.
  auto arr = System::MakeObject<System::Array<uint8_t>>(12);
  rnd->NextBytes(arr);

  // Wypisz tablicę.
  for (auto i = 0; i < arr->get_Length(); ++i)
  {
    std::cout << static_cast<int>(arr[i]) << ' ';
  }
  std::cout << std::endl;

  return 0;
}
/*
Ten przykład kodu generuje następujący wynik:
Month: 4
177 213 89 240 68 182 18 96 109 131 1 78
*/
```

## Zobacz także

* Klasa [Object](../object/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)