---
title: RSACryptoServiceProvider
second_title: Aspose.Slides för C++ API-referens
description: "RSA-algoritm i CSP-form. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kan leda till körningsfel och/eller påståendefel. Omge alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 469
url: /sv/system.security.cryptography/rsacryptoserviceprovider/
---
## RSACryptoServiceProvider klass


[RSA](../rsa/) algoritm i CSP-form. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av den här typen på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omge alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class RSACryptoServiceProvider : public System::Security::Cryptography::RSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | Frigör alla resurser. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)() | Skapar standardimplementering av [RSA](../rsa/)-algoritmen. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(const [String](../../system/string/)\&) | Skapar standardimplementering av [RSA](../rsa/)-algoritmen. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(**int32_t**) | Skapar standardimplementering av [RSA](../rsa/)-algoritmen med specificerad nyckelstorlek. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [Create](../rsa/create/)(const [RSAParameters](../rsaparameters/)\&) | Skapar standardimplementering av [RSA](../rsa/)-algoritmen med specificerade parametrar. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](../rsa/)\> [CreateFromXmlString](../rsa/createfromxmlstring/)(const [String](../../system/string/)\&) | Skapar standardimplementering av [RSA](../rsa/)-algoritmen med specificerade XML-kodade parametrar. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | Dekrypterar meddelande. Ej implementerad. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) override | Dekrypterar inmatningsdata med angivet paddningsläge. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [DecryptValue](../rsa/decryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | Dekrypterar värde med privat nyckel. |
| void [Dispose](./dispose/)() override | Frigör data associerad med objektet. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **bool**) | Krypterar meddelande. Ej implementerad. |
| [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) override | Krypterar inmatningsdata med angivet paddningsläge. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [EncryptValue](../rsa/encryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | Krypterar värde med privat nyckel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande jämförelse av flyttal där två NaN betraktas som lika, även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande jämförelse av flyttal där två NaN betraktas som lika, även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| [ByteArrayPtr](../../system/bytearrayptr/) [ExportCspBlob](./exportcspblob/)(**bool**) override | Exporterar blob med information om nyckel. Ej implementerad. |
| [RSAParameters](../rsaparameters/) [ExportParameters](./exportparameters/)(**bool**) override | Exporterar CSP-parametrar. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna syften. |
| void [FromXmlString](../rsa/fromxmlstring/)([String](../../system/string/)) override | Initierar objekt med XML-kodade parametrar. |
| [SharedPtr](../../system/sharedptr/)\<[CspKeyContainerInfo](../cspkeycontainerinfo/)\> [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | Hämtar ett [CspKeyContainerInfo](../cspkeycontainerinfo/)-objekt. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Kontrollerar nyckelutbytesalgoritm associerad med objektet. |
| **int32_t** [get_KeySize](./get_keysize/)() override | Hämtar nyckelstorlek som används av algoritmen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | Hämtar array av tillåtna nyckelstorlekar. |
| **bool** [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | Kontrollerar om nyckeln är beständig i CSP-objektet. |
| **bool** [get_PublicOnly](./get_publiconly/)() const | Kontrollerar om endast publik nyckel finns i CSP-objektet. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Hämtar signaturalgoritm associerad med CSP-objektet. |
| static **bool** [get_UseMachineKeyStore](./get_usemachinekeystore/)() | Kontrollerar om nyckeln är lagrad i maskinlagring istället för användarlagring. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastruktur associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktisk typ av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| void [ImportCspBlob](./importcspblob/)([ByteArrayPtr](../../system/bytearrayptr/)) override | Importerar blob med information om nyckel. Ej implementerad. |
| void [ImportParameters](./importparameters/)([RSAParameters](../rsaparameters/)) override | Importerar CSP-parametrar. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen beskriven av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-sats låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med specificerat värde. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)() | Konstruktor. Använder standardparametrar. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | Konstruktor. Ej implementerad. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const [RSAParameters](../rsaparameters/)\&) | Konstruktor. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(**int32_t**) | Konstruktor. |
|  [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(**int32_t**, const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | Konstruktor. Ej implementerad. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | Ställer in nyckelstorlek. |
| void [set_PersistKeyInCsp](./set_persistkeyincsp/)(**bool**) | Anger om nyckeln är beständig i CSP-objektet. |
| static void [set_UseMachineKeyStore](./set_usemachinekeystore/)(**bool**) | Anger om nyckeln är beständig i maskinlagring istället för användarlagring. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n:te mallargumentet till en svag pekare (istället för delad). Möjliggör att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Beräknar signatur för specificerat inmatningsvärde. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Beräknar signatur för specificerat inmatningsvärde. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Beräknar signatur för specificerat inmatningsvärde. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Beräknar hashvärdet för den specificerade dataarrayen med den angivna hash-algoritmen och paddning, och signerar resultatet. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Beräknar hashvärdet för den specificerade dataarrayen med den angivna hash-algoritmen och paddning, och signerar resultatet. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](../rsa/signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Beräknar hashvärdet för den specificerade binära strömmen med den angivna hash-algoritmen och paddning, och signerar resultatet. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)([ByteArrayPtr](../../system/bytearrayptr/), [HashAlgorithmName](../hashalgorithmname/), [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) override | Beräknar signatur för det specificerade hashvärdet. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Beräknar signatur för specificerat inmatningsvärde. Ej implementerad. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| [String](../../system/string/) [ToXmlString](../rsa/toxmlstring/)(**bool**) override | Exporterar alla parametrar i XML-format. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objekt. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Kontrollerar datasignatur. |
| **bool** [VerifyData](../rsa/verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Verifierar att signaturen för den specificerade datan är giltig. |
| **bool** [VerifyData](../rsa/verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Verifierar att signaturen för den specificerade datan är giltig. |
| **bool** [VerifyData](../rsa/verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Verifierar att signaturen för den specificerade binära strömmen är giltig. |
| **bool** [VerifyHash](./verifyhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Kontrollerar datasignatur. |
| **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/), const [HashAlgorithmName](../hashalgorithmname/)\&, [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) override | Verifierar att signaturen för den specificerade hashen är giltig. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Se också

* Klass [RSA](../rsa/)
* Klass [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* Namnrymd [System::Security::Cryptography](../)
* Bibliotek [Aspose.Slides](../../)