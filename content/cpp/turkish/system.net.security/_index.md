---
title: "System::Net::Security"
second_title: Aspose.Slides için C++ API Referansı
description: 
type: docs
weight: 716
url: /tr/system.net.security/
---
## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Bir akış üzerinden kimlik bilgilerini iletmek için yöntemleri içerir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örneği yığında veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın. |
| [SslStream](./sslstream/) | Sunucuyu ve isteğe bağlı olarak istemciyi kimlik doğrulamak için SSL protokolünü kullanan bir akış. |
## Enum'lar

| Enum | Açıklama |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | WebRequest'e özgü kimlik doğrulama bayrakları. |
| [SslPolicyErrors](./sslpolicyerrors/) | SSL'nin politika hatalarını listeler. |
| [EncryptionPolicy](./encryptionpolicy/) | Şifreleme politikalarını listeler. |
## Typedef'lar

| Typedef | Açıklama |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Uzak SSL sertifikasını doğrulamak için kullanılan bir kullanıcı delegesi. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Yerel SSL sertifikasını seçmek için kullanılan bir kullanıcı delegesi. |