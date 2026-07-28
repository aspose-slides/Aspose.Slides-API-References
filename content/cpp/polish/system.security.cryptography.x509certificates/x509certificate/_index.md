---
title: X509Certificate
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Certyfikat X.509 v.3. Szyfrowane certyfikaty nie są obsługiwane. Obsługiwany jest jedynie znacznik X509KeyStorageFlags::DefaultKeySet. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ może to spowodować błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji."
type: docs
weight: 27
url: /pl/system.security.cryptography.x509certificates/x509certificate/
---
## klasa X509Certificate


X.509 v.3 certificate. Encrypted certificates are not supported. Only [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/) flag is supported. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## Metody

| Method | Description |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromCertFile](./createfromcertfile/)(const [String](../../system/string/)\&) | Tworzy certyfikat z określonego pliku PKCS7. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromSignedFile](./createfromsignedfile/)(const [String](../../system/string/)\&) | Tworzy certyfikat z określonego podpisanego pliku. |
| void [Dispose](./dispose/)() override | Nic nie robi. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Porównuje dwa certyfikaty. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/)) const | Eksportuje bieżący obiekt do tablicy bajtów przy użyciu określonego formatu. NIE ZIMPLEMENTOWANO. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | Eksportuje bieżący obiekt do tablicy bajtów przy użyciu określonego formatu. NIE ZIMPLEMENTOWANO. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | Eksportuje bieżący obiekt do tablicy bajtów przy użyciu określonego formatu. NIE ZIMPLEMENTOWANO. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| IntPtr [get_Handle](./get_handle/)() const | Pobiera uchwyt do kontekstu certyfikatu Microsoft Cryptographic API. |
| [String](../../system/string/) [get_Issuer](./get_issuer/)() const | Pobiera nazwę jednostki certyfikującej, która wydała certyfikat X.509v3. |
| [String](../../system/string/) [get_Subject](./get_subject/)() const | Pobiera odróżniającą nazwę podmiotu z certyfikatu. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)() const | Pobiera skrót bieżącego obiektu jako tablicę bajtów. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Pobiera skrót bieżącego obiektu jako tablicę bajtów. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)() const | Pobiera [SHA1](../../system.security.cryptography/sha1/) skrót bieżącego obiektu jako łańcuch szesnastkowy. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Pobiera [SHA1](../../system.security.cryptography/sha1/) skrót bieżącego obiektu jako łańcuch szesnastkowy. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual [String](../../system/string/) [GetEffectiveDateString](./geteffectivedatestring/)() const | Pobiera datę wejścia w życie bieżącego certyfikatu. |
| virtual [String](../../system/string/) [GetExpirationDateString](./getexpirationdatestring/)() const | Pobiera datę wygaśnięcia bieżącego certyfikatu. |
| virtual [String](../../system/string/) [GetFormat](./getformat/)() const | Pobiera nazwę formatu certyfikatu. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Pobiera kod skrótu certyfikatu. |
| virtual [String](../../system/string/) [GetIssuerName](./getissuername/)() const | Pobiera nazwę jednostki certyfikującej, która wydała bieżący certyfikat. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](./getkeyalgorithm/)() const | Pobiera informacje o kluczu bieżącego certyfikatu jako łańcuch. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | Pobiera informacje o kluczu bieżącego certyfikatu jako tablicę bajtów. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | Pobiera informacje o kluczu bieżącego certyfikatu jako łańcuch szesnastkowy. |
| virtual [String](../../system/string/) [GetName](./getname/)() const | Pobiera nazwę podmiotu, dla którego wydano bieżący certyfikat. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](./getpublickey/)() const | Pobiera klucz publiczny z certyfikatu jako tablicę bajtów. |
| virtual [String](../../system/string/) [GetPublicKeyString](./getpublickeystring/)() const | Pobiera klucz publiczny z certyfikatu jako łańcuch szesnastkowy. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](./getrawcertdata/)() const | Pobiera surowe dane z certyfikatu jako tablicę bajtów. |
| virtual [String](../../system/string/) [GetRawCertDataString](./getrawcertdatastring/)() const | Pobiera surowe dane z certyfikatu jako łańcuch szesnastkowy. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](./getserialnumber/)() const | Pobiera numer seryjny z certyfikatu jako tablicę bajtów. |
| virtual [String](../../system/string/) [GetSerialNumberString](./getserialnumberstring/)() const | Pobiera numer seryjny z certyfikatu jako łańcuch szesnastkowy. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importuje informacje z określonego pliku certyfikatu. NIE ZIMPLEMENTOWANO. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importuje informacje z określonego pliku certyfikatu. NIE ZIMPLEMENTOWANO. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importuje informacje z określonych danych certyfikatu. NIE ZIMPLEMENTOWANO. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importuje informacje z określonych danych certyfikatu. NIE ZIMPLEMENTOWANO. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&) | Importuje informacje z określonego pliku certyfikatu. NIE ZIMPLEMENTOWANO. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Importuje informacje z określonych danych certyfikatu. NIE ZIMPLEMENTOWANO. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [X509Certificate](./)\& [operator=](./operator_equal/)(const [X509Certificate](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| virtual void [Reset](./reset/)() | Resetuje stan certyfikatu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączyć wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](./tostring/)(**bool**) const | Zwraca informacje o certyfikacie w formacie tekstowym. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Zwraca informacje o certyfikacie w formacie tekstowym. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [X509Certificate](./x509certificate/)(const [X509Certificate](./)\&) |  |
|  [X509Certificate](./x509certificate/)() | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\>\&) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Definicje typów

| Definicja | Opis |
| --- | --- |
| [Ptr](./ptr/) | Typ wskaźnika. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Klasa [IDisposable](../../system/idisposable/)
* Przestrzeń nazw [System::Security::Cryptography::X509Certificates](../)
* Biblioteka [Aspose.Slides](../../)