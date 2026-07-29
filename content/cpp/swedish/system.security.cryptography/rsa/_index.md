---
title: RSA
second_title: Aspose.Slides för C++ API-referens
description: "Basisklass för implementationer av RSA-algoritmen. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass med en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument."
type: docs
weight: 456
url: /sv/system.security.cryptography/rsa/
---
## RSA klass

Basisklass för implementationer av [RSA](./)-algoritmen. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omge alltid denna klass med en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class RSA : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | Frigör alla resurser. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [Create](./create/)() | Skapar en standardimplementation av [RSA](./)-algoritmen. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Skapar en standardimplementation av [RSA](./)-algoritmen. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [Create](./create/)(**int32_t**) | Skapar en standardimplementation av [RSA](./)-algoritmen med angiven nyckelstorlek. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [Create](./create/)(const [RSAParameters](../rsaparameters/)\&) | Skapar en standardimplementation av [RSA](./)-algoritmen med angivna parametrar. |
| static [SharedPtr](../../system/sharedptr/)\<[RSA](./)\> [CreateFromXmlString](./createfromxmlstring/)(const [String](../../system/string/)\&) | Skapar en standardimplementation av [RSA](./)-algoritmen med angivna XML-kodade parametrar. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Decrypt](./decrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) | Dekrypterar indata med angivet fyllningsläge. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [DecryptValue](./decryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | Dekrypterar värde med privat nyckel. |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | Frigör resurser som ägs av det aktuella objektet. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Encrypt](./encrypt/)([ByteArrayPtr](../../system/bytearrayptr/), [SharedPtr](../../system/sharedptr/)\<[RSAEncryptionPadding](../rsaencryptionpadding/)\>) | Krypterar indata med angivet fyllningsläge. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [EncryptValue](./encryptvalue/)([ByteArrayPtr](../../system/bytearrayptr/)) | Krypterar värde med privat nyckel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C#-[Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| virtual [RSAParameters](../rsaparameters/) [ExportParameters](./exportparameters/)(**bool**) | Exporterar alla parametrar. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| void [FromXmlString](./fromxmlstring/)([String](../../system/string/)) override | Initierar objekt med XML-kodade parametrar. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Kontrollerar nyckelutbytesalgoritm associerad med objektet. |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | Hämtar nyckelstorlek. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | Hämtar en matris av tillåtna nyckelstorlekar. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Hämtar signaturalgoritm associerad med CSP-objektet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C#-[Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C#-[System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual void [ImportParameters](./importparameters/)([RSAParameters](../rsaparameters/)) | Importerar alla parametrar från datastrukturen. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet är en instans av den typ som beskrivs av targetType. Analog till C#-'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C#-lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C#-[Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar räknaren för delade referenser med angivet värde. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | Ställer in nyckelstorlek. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te template-argumentet till en svag pekare (istället för delad). Möjliggör byte av pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referenstillräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar räknaren för delade referenser. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar räknaren för delade referenser. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och fyllning, och signerar resultatet. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Beräknar hashvärdet för den angivna dataarrayen med den angivna hash-algoritmen och fyllning, och signerar resultatet. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Beräknar hashvärdet för den angivna binära strömmen med den angivna hash-algoritmen och fyllning, och signerar resultatet. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)([ByteArrayPtr](../../system/bytearrayptr/), [HashAlgorithmName](../hashalgorithmname/), [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) | Beräknar signaturen för det angivna hash-värdet. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C#-[Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)(**bool**) override | Exporterar alla parametrar i XML-format. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C#-typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C#-lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-sentry-objektet. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Verifierar att signaturen för de angivna data är giltig. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Verifierar att signaturen för de angivna data är giltig. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&, const [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>\&) | Verifierar att signaturen för den angivna binära strömmen är giltig. |
| virtual **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/), const [HashAlgorithmName](../hashalgorithmname/)\&, [SharedPtr](../../system/sharedptr/)\<[RSASignaturePadding](../rsasignaturepadding/)\>) | Verifierar att signaturen för den angivna hash-en är giltig. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar räknaren för svaga referenser. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar räknaren för svaga referenser. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigir alla interna datastrukturer. |

## Se även

* Klass [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Namnrymd [System::Security::Cryptography](../)
* Bibliotek [Aspose.Slides](../../)