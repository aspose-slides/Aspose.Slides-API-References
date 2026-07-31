---
title: "System::Net::Http"
second_title: "Referensi API Aspose.Slides untuk C++"
description: 
type: docs
weight: 677
url: /id/system.net.http/
---
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | Mewakili konten HTTP sebagai array byte. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau fault assertion. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk mengirimkannya ke fungsi sebagai argumen. |
| [Details_HttpRequestException](./details_httprequestexception/) | Kelas pengecualian dasar dilempar oleh kelas [HttpClient](./httpclient/) dan [HttpMessageHandler](./httpmessagehandler/). Jangan pernah membuat instance kelas ini secara manual. Gunakan kelas HttpRequestException sebagai gantinya. Jangan pernah membungkus instance kelas HttpRequestException ke dalam [System::SmartPtr](../system/smartptr/). |
| [HttpClient](./httpclient/) | Mewakili kelas dasar klien HTTP untuk mengirim permintaan dan menerima respons. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau fault assertion. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk mengirimkannya ke fungsi sebagai argumen. |
| [HttpClientHandler](./httpclienthandler/) | Mewakili penangan pesan default yang digunakan oleh kelas [HttpClient](./httpclient/). Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau fault assertion. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk mengirimkannya ke fungsi sebagai argumen. |
| [HttpContent](./httpcontent/) | Mewakili konten entitas HTTP. [Object](../system/object/) dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau fault assertion. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk mengirimkannya ke fungsi sebagai argumen. |
| [HttpMessageHandler](./httpmessagehandler/) | Mewakili tipe dasar untuk penangan pesan HTTP. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau fault assertion. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk mengirimkannya ke fungsi sebagai argumen. |
| [HttpMessageInvoker](./httpmessageinvoker/) | Memungkinkan aplikasi memanggil metode Send pada rantai penangan HTTP. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau fault assertion. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk mengirimkannya ke fungsi sebagai argumen. |
| [HttpMethod](./httpmethod/) | Mewakili metode HTTP. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau fault assertion. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk mengirimkannya ke fungsi sebagai argumen. |
| [HttpRequestMessage](./httprequestmessage/) | Mewakili pesan permintaan HTTP. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau fault assertion. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk mengirimkannya ke fungsi sebagai argumen. |
| [HttpResponseMessage](./httpresponsemessage/) | Mewakili pesan respons HTTP. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau fault assertion. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk mengirimkannya ke fungsi sebagai argumen. |
| [HttpUtilities](./httputilities/) | Berisi metode utilitas. |
| [StringContent](./stringcontent/) | Mewakili konten HTTP sebagai string. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau fault assertion. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer tersebut untuk mengirimkannya ke fungsi sebagai argumen. |
## Fungsi

| Fungsi | Deskripsi |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
## Enum

| Enum | Deskripsi |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | Menunjukkan kapan operasi [HttpClient](./httpclient/) harus diselesaikan. |
| [HttpParseResult](./httpparseresult/) | Menunjukkan hasil parsing. |
## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |