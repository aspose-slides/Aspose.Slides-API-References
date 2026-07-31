---
title: "System::Diagnostics"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 469
url: /id/system.diagnostics/
---
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | Menyediakan informasi tentang versi file. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan waktu jalan dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [PerformanceCounter](./performancecounter/) | Kelas dummy untuk kode terjemahan yang menggunakan PerformanceCounter agar dapat dikompilasi. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan waktu jalan dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [Process](./process/) | Mengkapsulkan informasi proses dan manipulasi. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan waktu jalan dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [ProcessStartInfo](./processstartinfo/) | Menjelaskan parameter mulai proses. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan waktu jalan dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [StackFrame](./stackframe/) | Mendapatkan informasi tentang satu frame stack. Hanya untuk MSVS. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan waktu jalan dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [StackTrace](./stacktrace/) | Koleksi frame stack. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan waktu jalan dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [Stopwatch](./stopwatch/) | Memungkinkan pengukuran waktu. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan waktu jalan dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [TraceListener](./tracelistener/) | Antarmuka untuk merespon informasi debug dan jejak. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini pada stack atau menggunakan operator new, karena akan menyebabkan kesalahan waktu jalan dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |

## Struktur

| Struct | Deskripsi |
| --- | --- |
| [Debug](./debug/) | Koleksi metode debug yang memungkinkan mengirim informasi debug ke pendengar yang terdaftar. Semua fungsi output hanya bekerja di [Debug](./debug/). Ini adalah tipe statis tanpa layanan instance. Anda tidak boleh membuat instance darinya dengan cara apapun. |
| [Debugger](./debugger/) | Antarmuka [Debugger](./debugger/). Ini adalah tipe statis tanpa layanan instance. Anda tidak boleh membuat instance darinya dengan cara apapun. |
| [Trace](./trace/) | Menyediakan antarmuka untuk mengakses jejak debugger (jika ada). Hanya berfungsi dalam mode [Debug](./debug/). Ini adalah tipe statis tanpa layanan instance. Anda tidak boleh membuat instance darinya dengan cara apapun. |

## Enum

| Enum | Deskripsi |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | Gaya jendela proses. |
| [TraceEventType](./traceeventtype/) | Mengidentifikasi tipe peristiwa yang menyebabkan jejak. |
| [TraceLevel](./tracelevel/) | Menentukan pesan apa yang akan dikeluarkan untuk kelas [System.Diagnostics.Debug](./debug/), [System.Diagnostics.Trace](./trace/) dan System.Diagnostics.TraceSwitch. |

## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | Tipe pointer. |