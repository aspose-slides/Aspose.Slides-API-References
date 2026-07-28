---
title: GC
second_title: Aspose.Slides dla C++ – referencja API
description: Reprezentuje emulowaną zbiórkę śmieci, która zachowuje się bardziej jak szkielet i w praktyce nie robi nic. Jest to typ statyczny bez usług instancji. Nigdy nie powinieneś tworzyć jego instancji w żaden sposób.
type: docs
weight: 872
url: /pl/system/gc/
---
## Klasa GC


Reprezentuje emulowaną zbiórkę śmieci, która działa bardziej jak szkielet i w praktyce nie robi nic. Jest to typ statyczny bez usług instancji. Nigdy nie należy tworzyć jego instancji w żaden sposób.

```cpp
class GC : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| static **int64_t** [GetTotalAllocatedBytes](./gettotalallocatedbytes/)(**bool**) | Zwraca całkowitą liczbę przydzielonych bajtów. |
| static **int64_t** [GetTotalMemory](./gettotalmemory/)(**bool**) | Zwraca liczbę bajtów prywatnej pamięci aktualnie przydzielonej przez bieżący proces. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../object/object/)([Object](../object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, naprawdę, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie przy tworzeniu podklas. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operator przypisania. Nie kopiuje nic, naprawdę, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie przy tworzeniu podklas. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specjalizacja [Object::ReferenceEquals](../object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o określoną wartość. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../object/tostring/). Umożliwia konwersję własnych obiektów do ciągu znaków. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../object/~object/)() | Zniszcza obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../object/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)