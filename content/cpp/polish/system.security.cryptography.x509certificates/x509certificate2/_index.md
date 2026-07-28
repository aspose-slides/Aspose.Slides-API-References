---
title: X509Certificate2
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Reprezentuje certyfikat X509. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go funkcjom jako argument."
type: docs
weight: 40
url: /pl/system.security.cryptography.x509certificates/x509certificate2/
---
## X509Certificate2 klasa

Reprezentuje certyfikat X509. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy czasu wykonania i/lub awarie asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania go funkcjom jako argument.

```cpp
class X509Certificate2 : public System::Security::Cryptography::X509Certificates::X509Certificate
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromCertFile](../x509certificate/createfromcertfile/)(const [String](../../system/string/)\&) | Tworzy certyfikat z określonego pliku PKCS7. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromSignedFile](../x509certificate/createfromsignedfile/)(const [String](../../system/string/)\&) | Tworzy certyfikat z określonego podpisanego pliku. |
| void [Dispose](../x509certificate/dispose/)() override | Nie robi nic. |
| **bool** [Equals](../x509certificate/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Porównuje dwa certyfikaty. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/)) const | Eksportuje bieżący obiekt do tablicy bajtów przy użyciu określonego formatu. NIE ZAIMPLEMENTOWANE. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | Eksportuje bieżący obiekt do tablicy bajtów przy użyciu określonego formatu. NIE ZAIMPLEMENTOWANE. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | Eksportuje bieżący obiekt do tablicy bajtów przy użyciu określonego formatu. NIE ZAIMPLEMENTOWANE. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **bool** [get_Archived](./get_archived/)() const | Pobiera wartość wskazującą, że certyfikat jest archiwizowany. |
| [X509ExtensionCollectionPtr](../x509extensioncollectionptr/) [get_Extensions](./get_extensions/)() const | Pobiera kolekcję obiektów rozszerzeń powiązanych z certyfikatem. |
| [String](../../system/string/) [get_FriendlyName](./get_friendlyname/)() const | Pobiera przyjazną nazwę certyfikatu. |
| IntPtr [get_Handle](../x509certificate/get_handle/)() const | Pobiera uchwyt do kontekstu certyfikatu Microsoft Cryptographic API. |
| **bool** [get_HasPrivateKey](./get_hasprivatekey/)() const | Sprawdza, czy certyfikat ma klucz prywatny. |
| [String](../../system/string/) [get_Issuer](../x509certificate/get_issuer/)() const | Pobiera nazwę organu certyfikującego, który wydał certyfikat X.509v3. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_IssuerName](./get_issuername/)() const | Pobiera nazwę podmiotu, który wydał certyfikat. |
| [DateTime](../../system/datetime/) [get_NotAfter](./get_notafter/)() const | Pobiera lokalną datę i godzinę, po której certyfikat przestaje być ważny. |
| [DateTime](../../system/datetime/) [get_NotBefore](./get_notbefore/)() const | Pobiera lokalną datę i godzinę, od której certyfikat jest ważny. |
| [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\> [get_PrivateKey](./get_privatekey/)() const | Pobiera klucz prywatny powiązany z certyfikatem. |
| [SharedPtr](../../system/sharedptr/)\<[PublicKey](../publickey/)\> [get_PublicKey](./get_publickey/)() const | Pobiera obiekt [PublicKey](../publickey/) certyfikatu. |
| [ByteArrayPtr](../../system/bytearrayptr/) [get_RawData](./get_rawdata/)() const | Pobiera surowe dane certyfikatu. |
| [String](../../system/string/) [get_SerialNumber](./get_serialnumber/)() const | Pobiera numer seryjny certyfikatu. |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\> [get_SignatureAlgorithm](./get_signaturealgorithm/)() const | Pobiera algorytm używany do tworzenia podpisu certyfikatu. |
| [String](../../system/string/) [get_Subject](../x509certificate/get_subject/)() const | Pobiera odróżnialną nazwę podmiotu z certyfikatu. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_SubjectName](./get_subjectname/)() const | Pobiera nazwę podmiotu z certyfikatu. |
| [String](../../system/string/) [get_Thumbprint](./get_thumbprint/)() const | Pobiera odcisk certyfikatu. |
| **int32_t** [get_Version](./get_version/)() const | Pobiera wersję formatu certyfikatu. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Pobiera typ certyfikatu zawartego w podanej tablicy bajtów. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [String](../../system/string/)\&) | Pobiera typ certyfikatu zawartego w podanym pliku. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)() const | Pobiera hash bieżącego obiektu jako tablicę bajtów. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Pobiera hash bieżącego obiektu jako tablicę bajtów. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)() const | Pobiera hash [SHA1](../../system.security.cryptography/sha1/) bieżącego obiektu jako ciąg szesnastkowy. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Pobiera hash [SHA1](../../system.security.cryptography/sha1/) bieżącego obiektu jako ciąg szesnastkowy. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPrivateKey](./getdsaprivatekey/)() const | Pobiera klucz prywatny [RSA](../../system.security.cryptography/rsa/). |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPublicKey](./getdsapublickey/)() const | Pobiera klucz publiczny [RSA](../../system.security.cryptography/rsa/). |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPrivateKey](./getecdsaprivatekey/)() const | Pobiera klucz prywatny [RSA](../../system.security.cryptography/rsa/). |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPublicKey](./getecdsapublickey/)() const | Pobiera klucz publiczny [RSA](../../system.security.cryptography/rsa/). |
| virtual [String](../../system/string/) [GetEffectiveDateString](../x509certificate/geteffectivedatestring/)() const | Pobiera datę obowiązywania bieżącego certyfikatu. |
| virtual [String](../../system/string/) [GetExpirationDateString](../x509certificate/getexpirationdatestring/)() const | Pobiera datę wygaśnięcia bieżącego certyfikatu. |
| virtual [String](../../system/string/) [GetFormat](../x509certificate/getformat/)() const | Pobiera nazwę formatu certyfikatu. |
| **int32_t** [GetHashCode](../x509certificate/gethashcode/)() const override | Pobiera kod skrótu certyfikatu. |
| virtual [String](../../system/string/) [GetIssuerName](../x509certificate/getissuername/)() const | Pobiera nazwę organu certyfikującego, który wydał bieżący certyfikat. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](../x509certificate/getkeyalgorithm/)() const | Pobiera informacje o kluczu bieżącego certyfikatu jako ciąg znaków. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](../x509certificate/getkeyalgorithmparameters/)() const | Pobiera informacje o kluczu bieżącego certyfikatu jako tablicę bajtów. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](../x509certificate/getkeyalgorithmparametersstring/)() const | Pobiera informacje o kluczu bieżącego certyfikatu jako ciąg szesnastkowy. |
| virtual [String](../../system/string/) [GetName](../x509certificate/getname/)() const | Pobiera nazwę podmiotu, dla którego wydano bieżący certyfikat. |
| [String](../../system/string/) [GetNameInfo](./getnameinfo/)([X509NameType](../x509nametype/), **bool**) const | Pobiera nazwę podmiotu lub wystawcy z certyfikatu. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](../x509certificate/getpublickey/)() const | Pobiera klucz publiczny z certyfikatu jako tablicę bajtów. |
| virtual [String](../../system/string/) [GetPublicKeyString](../x509certificate/getpublickeystring/)() const | Pobiera klucz publiczny z certyfikatu jako ciąg szesnastkowy. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](../x509certificate/getrawcertdata/)() const | Pobiera surowe dane z certyfikatu jako tablicę bajtów. |
| virtual [String](../../system/string/) [GetRawCertDataString](../x509certificate/getrawcertdatastring/)() const | Pobiera surowe dane z certyfikatu jako ciąg szesnastkowy. |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPrivateKey](./getrsaprivatekey/)() const | Pobiera klucz prywatny [RSA](../../system.security.cryptography/rsa/). |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPublicKey](./getrsapublickey/)() const | Pobiera klucz publiczny [RSA](../../system.security.cryptography/rsa/). |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](../x509certificate/getserialnumber/)() const | Pobiera numer seryjny z certyfikatu jako tablicę bajtów. |
| virtual [String](../../system/string/) [GetSerialNumberString](../x509certificate/getserialnumberstring/)() const | Pobiera numer seryjny z certyfikatu jako ciąg szesnastkowy. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importuje informacje z określonego pliku certyfikatu. |
| void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importuje informacje z określonego pliku certyfikatu. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importuje informacje z określonych danych certyfikatu. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importuje informacje z określonych danych certyfikatu. |
| void [Import](./import/)(const [String](../../system/string/)\&) override | Importuje informacje z określonego pliku certyfikatu. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) override | Importuje informacje z określonych danych certyfikatu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [X509Certificate](../x509certificate/)\& [operator=](../x509certificate/operator_equal/)(const [X509Certificate](../x509certificate/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nic nie kopiuje, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [Reset](./reset/)() override | Resetuje stan certyfikatu. |
| void [set_Archived](./set_archived/)(**bool**) const | Ustawia wartość wskazującą, że certyfikat jest archiwizowany. |
| void [set_FriendlyName](./set_friendlyname/)(const [String](../../system/string/)\&) | Ustawia przyjazną nazwę certyfikatu. |
| void [set_PrivateKey](./set_privatekey/)(const [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\>\&) | Ustawia lub usuwa klucz prywatny powiązany z certyfikatem. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako wskaźnik słaby (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Inkrementuje współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Dekrementuje i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)(**bool**) const override | Zwraca informacje o certyfikacie w formacie tekstowym. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Zwraca informacje o certyfikacie w formacie tekstowym. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| **bool** [Verify](./verify/)() const | Weryfikuje łańcuch certyfikatów. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Inkrementuje licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Dekrementuje licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [X509Certificate](../x509certificate/)\&) |  |
|  [X509Certificate](../x509certificate/x509certificate/)() | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)() | Tworzy pusty [X509Certificate2](./). |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [X509Certificate](../x509certificate/)
* Przestrzeń nazw [System::Security::Cryptography::X509Certificates](../)
* Biblioteka [Aspose.Slides](../../)