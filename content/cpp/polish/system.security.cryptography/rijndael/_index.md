---
title: Rijndael
second_title: Aspose.Slides dla C++ - odniesienie do API
description: "Klasa bazowa dla algorytmu Rijndael. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to skutkować błędami w czasie wykonania i/lub naruszeniami asercji. Zawsze opakowuj tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania jej funkcjom jako argument."
type: docs
weight: 404
url: /pl/system.security.cryptography/rijndael/
---
## Rijndael klasa

Base class for [Rijndael](./) algorithm. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Rijndael : public System::Security::Cryptography::SymmetricAlgorithm
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](../symmetricalgorithm/)\> [Create](../symmetricalgorithm/create/)(const [String](../../system/string/)\&) | Tworzy instancję algorytmu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](../symmetricalgorithm/createdecryptor/)() | Tworzy deszyfrator z parametrami powiązanymi z obiektem algorytmu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](../symmetricalgorithm/createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Tworzy deszyfrator z wyraźnymi parametrami. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](../symmetricalgorithm/createencryptor/)() | Tworzy szyfrator z parametrami powiązanymi z obiektem algorytmu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](../symmetricalgorithm/createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Tworzy szyfrator z wyraźnymi parametrami. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual void [GenerateIV](../symmetricalgorithm/generateiv/)() | Generuje losową wartość początkową dla algorytmu. Nadpisuje istniejącą (jeśli istnieje). |
| virtual void [GenerateKey](../symmetricalgorithm/generatekey/)() | Generuje losowy klucz dla algorytmu. Nadpisuje istniejący (jeśli istnieje). |
| virtual int [get_BlockSize](../symmetricalgorithm/get_blocksize/)() | Pobiera rozmiar bloku operacji kryptograficznej. |
| virtual int [get_FeedbackSize](../symmetricalgorithm/get_feedbacksize/)() | Pobiera rozmiar sprzężenia zwrotnego operacji kryptograficznej. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](../symmetricalgorithm/get_iv/)() | Pobiera wartość początkową operacji kryptograficznej. Tworzy nową, jeśli nie została jeszcze utworzona. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](../symmetricalgorithm/get_key/)() | Pobiera klucz operacji kryptograficznej. Tworzy nowy, jeśli nie został jeszcze utworzony. |
| virtual int [get_KeySize](../symmetricalgorithm/get_keysize/)() | Pobiera rozmiar klucza operacji kryptograficznej. |
| virtual [CipherMode](../ciphermode/) [get_Mode](../symmetricalgorithm/get_mode/)() | Pobiera tryb operacji kryptograficznej. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](../symmetricalgorithm/get_padding/)() | Pobiera wypełnienie operacji kryptograficznej. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczne wywołanie C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczny operator C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie w instrukcji C# lock(). Wywołaj bezpośrednio lub użyj [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [set_BlockSize](../symmetricalgorithm/set_blocksize/)(int) | Ustawia rozmiar bloku operacji kryptograficznej. |
| virtual void [set_FeedbackSize](../symmetricalgorithm/set_feedbacksize/)(int) | Ustawia rozmiar sprzężenia zwrotnego operacji kryptograficznej. |
| virtual void [set_IV](../symmetricalgorithm/set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ustawia wartość początkową operacji kryptograficznej. |
| virtual void [set_Key](../symmetricalgorithm/set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Ustawia klucz operacji kryptograficznej. |
| virtual void [set_KeySize](../symmetricalgorithm/set_keysize/)(int) | Ustawia rozmiar klucza operacji kryptograficznej. |
| virtual void [set_Mode](../symmetricalgorithm/set_mode/)([CipherMode](../ciphermode/)) | Ustawia tryb operacji kryptograficznej. |
| virtual void [set_Padding](../symmetricalgorithm/set_padding/)([PaddingMode](../paddingmode/)) | Ustawia wypełnienie operacji kryptograficznej. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie w instrukcji C# lock(). Wywołaj bezpośrednio lub użyj [LockContext](../../system/lockcontext/). |
| **bool** [ValidKeySize](../symmetricalgorithm/validkeysize/)(int) | Sprawdza, czy rozmiar klucza jest prawidłowy. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [SymmetricAlgorithm](../symmetricalgorithm/)
* Przestrzeń nazw [System::Security::Cryptography](../)
* Biblioteka [Aspose.Slides](../../)