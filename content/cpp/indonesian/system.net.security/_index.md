---
title: "System::Net::Security"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 716
url: /id/system.net.security/
---
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | Mengandung metode untuk melewatkan kredensial melalui aliran. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen. |
| [SslStream](./sslstream/) | Sebuah aliran yang menggunakan protokol SSL untuk mengautentikasi server dan secara opsional klien. |
## Enum

| Enum | Deskripsi |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | Bendera otentikasi khusus WebRequest. |
| [SslPolicyErrors](./sslpolicyerrors/) | Menenumerasikan kesalahan kebijakan SSL. |
| [EncryptionPolicy](./encryptionpolicy/) | Menenumerasikan kebijakan enkripsi. |
## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | Delegasi pengguna yang digunakan untuk memverifikasi sertifikat SSL remote. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | Delegasi pengguna yang digunakan untuk memilih sertifikat SSL lokal. |