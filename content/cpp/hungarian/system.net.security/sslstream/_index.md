---
title: SslStream
second_title: Aspose.Slides C++ API referenciája
description: Egy adatfolyam, amely az SSL protokollt használja a szerver és opcionálisan a kliens hitelesítésére.
type: docs
weight: 14
url: /hu/system.net.security/sslstream/
---
## SslStream osztály


A stream that uses the SSL protocol to authenticate the server and optionally the client.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## Módszerek

| Method | Description |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | Hitelesíti a kapcsolat kliensoldalát. |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | Hitelesíti a kapcsolat kliensoldalát. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Elindít egy aszinkron olvasási műveletet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron olvasási műveletet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Elindít egy aszinkron írási műveletet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron írási műveletet. |
| void [Close](./close/)() override | Lezárja az adatfolyamot. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Átmásolja a bájtokat a megadott adatfolyamra. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Átmásolja a bájtokat a megadott adatfolyamra, a megadott pufferméret használatával. |
| void [Dispose](./dispose/)(**bool**) override | Felszabadítja az aktuális objektum által használt összes erőforrást, és lezárja az adatfolyamot. |
| void [Dispose](../../system.io/stream/dispose/)() override | Felszabadítja az aktuális objektum által használt összes erőforrást, és lezárja az adatfolyamot. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Megvárja, amíg a megadott aszinkron olvasási művelet befejeződik. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Megvárja, amíg a megadott aszinkron olvasási művelet befejeződik. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Befejez egy aszinkron írási műveletet. Megvárja, amíg a megadott aszinkron írási művelet befejeződik. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Befejez egy aszinkron írási műveletet. Megvárja, amíg a megadott aszinkron írási művelet befejeződik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| void [Flush](./flush/)() override | Törli az adatfolyam puffereit, és a pufferelt adatot a mögöttes tárolóba írja. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon törli az adatfolyam összes puffert, az esetlegesen pufferelt adatot a mögöttes eszközbe írja, és figyeli a megszakítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Aszinkron módon törli az adatfolyam összes puffert, az esetlegesen pufferelt adatot a mögöttes eszközbe írja, és figyeli a megszakítási kéréseket. |
| **bool** [get_CanRead](./get_canread/)() const override | Megállapítja, hogy az adatfolyam olvasható-e. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Megállapítja, hogy az adatfolyam támogatja-e a pozicionálást. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Lekér egy értéket, amely meghatározza, hogy az aktuális adatfolyam időtúllépést okozhat-e. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Megállapítja, hogy az adatfolyam írható-e. |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | Visszaad egy értéket, amely jelzi, hogy a tanúsítvány visszavonási lista ellenőrzésre kerül-e a tanúsítvány validálási folyamatában. |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | Visszaadja a titkosítási algoritmust. |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | Visszaadja a használt titkosítási algoritmus erősségét. |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | Visszaadja a hash algoritmust. |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | Visszaadja a használt hash algoritmus erősségét. |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | Visszaad egy értéket, amely jelzi, hogy a hitelesítés sikeresen megtörtént-e. |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | Visszaad egy értéket, amely jelzi, hogy ezzel az adatfolyammal küldött adat titkosított-e. |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | Visszaad egy értéket, amely jelzi, hogy a szerver és a kliens hitelesítve van-e. |
| **bool** [get_IsServer](./get_isserver/)() const override | Visszaad egy értéket, amely jelzi, hogy a kapcsolat helyi oldala a szerver-e. |
| **bool** [get_IsSigned](./get_issigned/)() const override | Visszaad egy értéket, amely jelzi, hogy ezzel az adatfolyammal küldött adat alá van-e írva. |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | Visszaadja a használt kulcscserélő algoritmus erősségét. |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | Visszaadja azt az adatfolyamot, amelyet a jelenlegi osztálypéldányok az adatok küldésére és fogadására használnak. |
| **int64_t** [get_Length](./get_length/)() const override | Visszaadja az adatfolyam hosszát bájtokban. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | Visszaadja a tanúsítványt, amelyet a helyi végpont hitelesítésére használnak. |
| **int64_t** [get_Position](./get_position/)() const override | Visszaadja az adatfolyam aktuális pozícióját. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Lekér egy értéket milliszekundumban, amely meghatározza, milyen hosszú ideig próbálja az adatfolyam olvasni, mielőtt időtúllépés következik be. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | Visszaadja a tanúsítványt, amelyet a távoli végpont hitelesítésére használnak. |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | Visszaadja az SSL protokollt. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Lekér egy értéket milliszekundumban, amely meghatározza, milyen hosszú ideig próbálja az adatfolyam írni, mielőtt időtúllépés következik be. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekér a objektummal összefüggő referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyéni objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekérdezi az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktorát. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Beolvasza a megadott számú bájtot az adatfolyamból, és a megadott bájt tömbbe írja. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Beolvasza a megadott számú bájtot az adatfolyamból, és a megadott bájt tömbbe írja. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Beolvasza a megadott számú bájtot az adatfolyamból, és a megadott bájt tömbbe írja. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Beolvasza a megadott számú bájtot az adatfolyamból, és a megadott bájt nyújtásba (byte span) írja. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon beolvas egy bájtsort a jelenlegi adatfolyamból, a pozíciót a beolvasott bájtok számával növeli, és figyeli a megszakítási kéréseket. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon beolvas egy bájtsort a jelenlegi adatfolyamból, a pozíciót a beolvasott bájtok számával növeli, és figyeli a megszakítási kéréseket. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Beolvas egyetlen bájtot az adatfolyamból, és visszaad egy 32 bites egész értéket, amely megegyezik a beolvasott bájt értékével. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Beállítja a jelenlegi objektum által képviselt adatfolyam pozícióját. |
| void [set_Position](./set_position/)(**int64_t**) override | Beállítja az adatfolyam pozícióját. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Beállít egy értéket, amely meghatározza, hogy a jelenlegi adatfolyam időtúllépést okozhat-e. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Beállít egy értéket, amely meghatározza, hogy a jelenlegi adatfolyam időtúllépést okozhat-e. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Beállít egy értéket milliszekundumban, amely meghatározza, milyen hosszú ideig próbálja az adatfolyam olvasni, mielőtt időtúllépés következik be. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Beállít egy értéket milliszekundumban, amely meghatározza, milyen hosszú ideig próbálja az adatfolyam olvasni, mielőtt időtúllépés következik be. |
| void [SetLength](./setlength/)(**int64_t**) override | Beállítja a jelenlegi objektum által képviselt adatfolyam hosszát. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonparamétert gyenge pointerként (a megosztott helyett). Lehetővé teszi a pointerek átváltását gyenge módra a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekérdezi a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Létrehoz egy új példányt. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | Létrehoz egy új példányt. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | Létrehoz egy új példányt. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | Létrehoz egy új példányt. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | Létrehoz egy új példányt. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyéni objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítást. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Kiírja a megadott bájt tömböt az adatfolyamba. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Az adatfolyamba írja a megadott bájt tömb meghatározott részhalmazát. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Kiírja a megadott bájt tömböt az adatfolyamba. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Az adatfolyamba írja a megadott bájt tömb meghatározott részhalmazát. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Az adatfolyamba írja a megadott bájt tömb meghatározott részhalmazát. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Az adatfolyamba írja a megadott bájtnyújtás (byte span) meghatározott részhalmazát. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon ír egy bájtsort a jelenlegi adatfolyamba, a pozíciót a megírt bájtok számával növeli, és figyeli a megszakítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon ír egy bájtsort a jelenlegi adatfolyamba, a pozíciót a megírt bájtok számával növeli, és figyeli a megszakítási kéréseket. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Kiírja a megadott előjeles 8 bites egész értéket az adatfolyamba. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Egy adatfolyam, amelynek nincs alapul szolgáló tárolója. |

## Típusdefiníciók

| Typedef | Description |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | Az AsyncResultType típusa. |
| [StreamImplementationPtr](./streamimplementationptr/) | Az implementációra mutató pointer típusa. |

## Lásd még

* Osztály [AuthenticatedStream](../authenticatedstream/)
* Névtere [System::Net::Security](../)
* Könyvtár [Aspose.Slides](../../)