---
title: "System::Net::Security"
second_title: Aspose.Slides C++ API referencia
description: 
type: docs
weight: 716
url: /hu/system.net.security/
---
## Osztályok

| Osztály | Leírás |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Tartalmazza a hitelesítő adatok átadásához használt metódusokat egy folyamon. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stack-en vagy az operator new használatával, mert futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek. |
| [SslStream](./sslstream/) | Egy adatfolyam, amely az SSL protokollt használja a szerver és opcionálisan a kliens hitelesítésére. |
## Enumok

| Enum | Leírás |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | WebRequest-specifikus hitelesítési jelzők. |
| [SslPolicyErrors](./sslpolicyerrors/) | Felsorolja az SSL szabályzati hibákat. |
| [EncryptionPolicy](./encryptionpolicy/) | Felsorolja a titkosítási szabályzatokat. |
## Typedef-ek

| Typedef | Leírás |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Felhasználói delegált a távoli SSL tanúsítvány ellenőrzésére. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Felhasználói delegált a helyi SSL tanúsítvány kiválasztására. |