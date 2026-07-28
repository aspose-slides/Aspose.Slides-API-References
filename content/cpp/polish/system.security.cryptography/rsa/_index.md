---
title: RSA
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Podstawowa klasa dla implementacji algorytmu RSA. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub awarie asercji. Zawsze owiń tę klasę wskaźnikiem System::SmartPtr i użyj tego wskaźnika do przekazania go jako argument do funkcji."
type: docs
weight: 456
url: /pl/system.security.cryptography/rsa/
---
## RSA klasa

Podstawowa klasa dla implementacji algorytmu [RSA](./). Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub awarie asercji. Zawsze owiń tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i użyj tego wskaźnika do przekazania go jako argument do funkcji.

```cpp
class RSA : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Metody

| Metoda | Opis |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | Zwalnia wszystkie zasoby. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [Create](./create/)() | Tworzy domyślną implementację algorytmu [RSA](./). |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Tworzy domyślną implementację algorytmu [RSA](./). |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [Create](./create/)(**int32_t**) | Tworzy domyślną implementację algorytmu [RSA](./) z określonym rozmiarem klucza. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [Create](./create/)(const [RSAParameters](../rsaparameters/)\&) | Tworzy domyślną implementację algorytmu [RSA](./) z określonymi parametrami. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [CreateFromXmlString](./createfromxmlstring/)(const [String](../../system/string/)\&) | Tworzy domyślną implementację algorytmu [RSA](./) z określonymi parametrami zakodowanymi w XML. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) | Odszyfrowuje dane wejściowe przy użyciu określonego trybu wypełnienia. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [DecryptValue](./decryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | Odszyfrowuje wartość przy użyciu klucza prywatnego. |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | Zwalnia zasoby należące do bieżącego obiektu. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) | Szyfruje dane wejściowe przy użyciu określonego trybu wypełnienia. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [EncryptValue](./encryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | Szyfruje wartość przy użyciu klucza prywatnego. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual [RSAParameters](../rsaparameters/) [ExportParameters](./exportparameters/)(**bool**) | Eksportuje wszystkie parametry. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| void [FromXmlString](./fromxmlstring/)([String](../../system/string/)) override | Inicjalizuje obiekt przy użyciu parametrów zakodowanych w XML. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Sprawdza algorytm wymiany kluczy powiązany z obiektem. |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | Pobiera rozmiar klucza. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | Pobiera tablicę dozwolonych rozmiarów kluczy. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Pobiera algorytm podpisu powiązany z obiektem CSP. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika odniesień powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [ImportParameters](./importparameters/)([RSAParameters](../rsaparameters/)) | Importuje wszystkie parametry ze struktury danych. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o określoną wartość. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | Ustawia rozmiar klucza. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Oblicza wartość skrótu podanej tablicy danych przy użyciu określonego algorytmu skrótu i wypełnienia oraz podpisuje wynik. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Oblicza wartość skrótu podanej tablicy danych przy użyciu określonego algorytmu skrótu i wypełnienia oraz podpisuje wynik. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Oblicza wartość skrótu określonego strumienia binarnego przy użyciu określonego algorytmu skrótu i wypełnienia oraz podpisuje wynik. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)([ByteArrayPtr](../../system/bytearrayptr/), [HashAlgorithmName](../hashalgorithmname/), [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) | Oblicza podpis dla określonej wartości skrótu. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na ciąg znaków. |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)(**bool**) override | Eksportuje wszystkie parametry w formacie XML. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie wyrażenia C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Sprawdza, czy podpis podanych danych jest prawidłowy. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Sprawdza, czy podpis podanych danych jest prawidłowy. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Sprawdza, czy podpis podanego strumienia binarnego jest prawidłowy. |
| virtual **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/), const [HashAlgorithmName](../hashalgorithmname/)\&, [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) | Sprawdza, czy podpis podanego skrótu jest prawidłowy. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Przestrzeń nazw [System::Security::Cryptography](../)
* Biblioteka [Aspose.Slides](../../)