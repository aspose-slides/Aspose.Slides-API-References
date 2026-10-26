---
title: BinaryWriter
second_title: Aspose.Slides for C++ – odniesienie API
description: "Reprezentuje pisarz, który zapisuje wartości typów prymitywnych do strumienia bajtów. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz egzemplarza tego typu na stosie ani przy użyciu operatora new, ponieważ może to prowadzić do błędów w czasie wykonywania i/lub naruszeń asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 105
url: /pl/system.io/binarywriter/
---
## BinaryWriter klasa

Represents a writer that writes values of primitive types to a byte stream. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class BinaryWriter : public System::IDisposable
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [BinaryWriter](./binarywriter/)(const [StreamPtr](../../system/streamptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Tworzy instancję klasy [BinaryWriter](./), która zapisuje dane do określonego strumienia przy użyciu określonego kodowania. |
| void [Close](./close/)() | Zamyka bieżący obiekt [BinaryWriter](./) oraz leżący u jego podstaw strumień wyjściowy. |
| void [Dispose](./dispose/)() override | Zwalnia wszystkie zasoby używane przez bieżący obiekt i zamyka leżący u podstaw strumień. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| void [Flush](./flush/)() | Opróżnia strumień wyjściowy. |
| [StreamPtr](../../system/streamptr/) [get_BaseStream](./get_basestream/)() | Zwraca strumień wyjściowy. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstrukcji klas pochodnych. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie konstrukcji klas pochodnych. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| **int64_t** [Seek](./seek/)(int, [System::IO::SeekOrigin](../seekorigin/)) | Ustawia pozycję strumienia reprezentowanego przez bieżący obiekt. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączyć wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [Write](./write/)(**uint8_t**) | Zapisuje określoną bezsignowaną 8-bitową wartość całkowitą do strumienia wyjściowego. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Zapisuje określony podzakres bajtów z podanej tablicy bajtów do strumienia wyjściowego. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Zapisuje określony podzakres znaków UTF-16 z podanej tablicy znaków do strumienia wyjściowego. |
| virtual void [Write](./write/)(**bool**) | Zapisuje pojedynczy bajt o wartości 0, jeśli **value** jest 'true', oraz 1, jeśli **value** jest 'false', do strumienia wyjściowego. |
| virtual void [Write](./write/)(char16_t) | Zapisuje określoną 16-bitową wartość znaku szerokiego do strumienia wyjściowego. |
| virtual void [Write](./write/)(**int16_t**) | Zapisuje określoną 16-bitową wartość całkowitą do strumienia wyjściowego. |
| virtual void [Write](./write/)(int) | Zapisuje określoną 32-bitową wartość całkowitą do strumienia wyjściowego. |
| virtual void [Write](./write/)(**int64_t**) | Zapisuje określoną 64-bitową wartość całkowitą do strumienia wyjściowego. |
| virtual void [Write](./write/)(**uint16_t**) | Zapisuje określoną bezsignowaną 16-bitową wartość całkowitą do strumienia wyjściowego. |
| virtual void [Write](./write/)(**uint32_t**) | Zapisuje określoną bezsignowaną 32-bitową wartość całkowitą do strumienia wyjściowego. |
| virtual void [Write](./write/)(**uint64_t**) | Zapisuje określoną bezsignowaną 64-bitową wartość całkowitą do strumienia wyjściowego. |
| virtual void [Write](./write/)(**float**) | Zapisuje określoną wartość zmiennoprzecinkową pojedynczej precyzji do strumienia wyjściowego. |
| virtual void [Write](./write/)(**double**) | Zapisuje określoną wartość zmiennoprzecinkową podwójnej precyzji do strumienia wyjściowego. |
| virtual void [Write](./write/)(const [Decimal](../../system/decimal/)\&) | Zapisuje bajtową reprezentację określonej wartości [Decimal](../../system/decimal/) do strumienia wyjściowego. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Zapisuje ciąg znaków z prefiksem długości w bieżącym kodowaniu do strumienia wyjściowego. |
| virtual void [Write](./write/)(const char_t *) | Zapisuje ciąg znaków z prefiksem długości w bieżącym kodowaniu do strumienia wyjściowego. |
|  [~BinaryWriter](./~binarywriter/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz również

* Klasa [IDisposable](../../system/idisposable/)
* Przestrzeń nazw [System::IO](../)
* Biblioteka [Aspose.Slides](../../)