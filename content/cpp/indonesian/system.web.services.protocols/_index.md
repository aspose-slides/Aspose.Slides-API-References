---
title: "System::Web::Services::Protocols"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 1080
url: /id/system.web.services.protocols/
---
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | Mewakili pengecualian yang dilempar ketika metode dipanggil melalui SOAP dan terjadi kesalahan. Jangan pernah membuat instance kelas ini secara manual. Gunakan kelas SoapException sebagai gantinya. Jangan pernah membungkus instance kelas SoapException ke dalam [System::SmartPtr](../system/smartptr/). |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | Kelas dasar ini digunakan di semua proxy klien layanan XML [Web](../system.web/) yang menggunakan HTTP. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | Sebuah instance kelas ini diteruskan sebagai argumen ke delegate InvokeCompletedEventHandler. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [SoapClientMessage](./soapclientmessage/) | Mewakili data dalam permintaan SOAP yang dikirim atau respons SOAP yang diterima. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | Menentukan bahwa semua pesan SOAP yang dikirim atau dikembalikan dari metode menggunakan format Document. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | Mengatur format default untuk permintaan dan respons SOAP. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [SoapHeader](./soapheader/) | Mewakili konten header SOAP. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [SoapHeaderAttribute](./soapheaderattribute/) | Menentukan header SOAP yang dapat diproses oleh metode layanan XML [Web](../system.web/) atau klien layanan XML [Web](../system.web/). Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [SoapHeaderCollection](./soapheadercollection/) | Berisi kumpulan instance kelas [SoapHeader](./soapheader/). |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | Layanan proxy klien harus mewarisi kelas ini ketika SOAP digunakan. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [SoapMessage](./soapmessage/) | Mewakili pesan SOAP. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [WebClientProtocol](./webclientprotocol/) | Kelas dasar ini digunakan di semua proxy klien layanan XML [Web](../system.web/) yang dibuat menggunakan ASP.NET. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
## Enumerasi

| Enum | Deskripsi |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | Menumerasikan arah header SOAP. |
| [SoapMessageStage](./soapmessagestage/) | Menumerasikan tahap pemrosesan pesan SOAP. |
| [SoapParameterStyle](./soapparameterstyle/) | Menumerasikan format parameter dalam pesan SOAP. |
| [SoapProtocolVersion](./soapprotocolversion/) | Menumerasikan versi SOAP. |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | Menumerasikan opsi bagaimana pesan SOAP diarahkan ke layanan XML [Web](../system.web/). |
## Tipedefinisi

| Tipedef | Deskripsi |
| --- | --- |
| [SoapException](./soapexception/) |  |