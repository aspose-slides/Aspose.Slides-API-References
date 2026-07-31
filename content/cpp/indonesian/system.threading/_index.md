---
title: "System::Threading"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 1002
url: /id/system.threading/
---
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | Peristiwa untuk memberi tahu thread yang menunggu yang mengatur ulang secara otomatis. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [CancellationToken](./cancellationtoken/) | Menyebarkan notifikasi bahwa operasi harus dibatalkan. Kelas ini menyediakan mekanisme pembatalan kooperatif antar thread, memungkinkan satu thread memberi tahu thread lain bahwa operasi harus dibatalkan. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | Mewakili pendaftaran untuk callback token pembatalan. |
| [CancellationTokenSource](./cancellationtokensource/) | Sumber token pembatalan yang dapat digunakan untuk memicu notifikasi pembatalan. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | Peristiwa yang dapat dikirim ke thread yang menunggu. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [Interlocked](./interlocked/) | Menyediakan API untuk operasi yang aman terhadap thread. Ini adalah tipe statis tanpa layanan instance. Anda tidak pernah harus membuat instance darinya dengan cara apapun. |
| [ManualResetEvent](./manualresetevent/) | Peristiwa untuk memberi tahu thread yang menunggu yang tidak mengatur ulang secara otomatis. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [Monitor](./monitor/) | Kelas [Monitor](./monitor/) menyediakan mekanisme yang menyinkronkan akses ke objek. |
| [Mutex](./mutex/) | [Mutex](./mutex/) implementasi. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) implementasi. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [SynchronizationContext](./synchronizationcontext/) | Menyediakan fungsionalitas dasar untuk menyebarkan konteks sinkronisasi di berbagai operasi sinkronisasi. |
| [Thread](./thread/) | [Thread](./thread/) implementasi. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [ThreadPool](./threadpool/) | API [Thread](./thread/) pool yang memungkinkan menambahkan pekerjaan ke antrean untuk dibaca oleh kumpulan thread pekerja. Ini adalah tipe statis tanpa layanan instance. Anda tidak pernah harus membuat instance darinya dengan cara apapun. |
| [ThreadPoolImpl](./threadpoolimpl/) | Data internal [Thread](./thread/) pool. Ini adalah tipe singleton dengan manajemen memori yang dilakukan oleh fungsi akses. Anda tidak pernah harus membuat instance darinya secara langsung. |
| [Timer](./timer/) | [Timer](./timer/) kelas yang mengeksekusi item pekerjaan di thread terpisah setelah penundaan. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
| [TimerQueue](./timerqueue/) | Antrian yang menangani objek [Timer](./timer/). Ini hanya sebuah implementasi. Objek [Timer](./timer/) mendaftar di sana secara otomatis, Anda tidak perlu melakukannya untuk menggunakannya – gunakan API kelas [Timer](./timer/) sebagai gantinya. Ini adalah tipe singleton dengan manajemen memori yang dilakukan oleh fungsi akses. Anda tidak pernah harus membuat instance darinya secara langsung. |
| [WaitHandle](./waithandle/) | Kelas dasar primitif penunggu. Objek kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menghasilkan kesalahan runtime dan/atau kegagalan asersi. Selalu bungkus kelas ini ke dalam pointer [System::SmartPtr](../system/smartptr/) dan gunakan pointer ini untuk meneruskannya ke fungsi sebagai argumen. |
## Struktur

| Struktur | Deskripsi |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./) nilai khusus timeout. Ini adalah tipe statis tanpa layanan instance. Anda tidak pernah harus membuat instance darinya dengan cara apapun. |
## Enum

| Enum | Deskripsi |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Mengatur status apartemen dari thread. |
| [EventResetMode](./eventresetmode/) | Menunjukkan cara status peristiwa direset. |
| [ThreadState](./threadstate/) | Status thread. |
## Typedef

| Typedef | Deskripsi |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | fungsi [Thread](./thread/) dengan satu parameter. |
| [ThreadStart](./threadstart/) | fungsi [Thread](./thread/) tanpa parameter. |
| [WaitCallback](./waitcallback/) | Item callback yang akan dieksekusi begitu ada slot. |
| [TimerCallback](./timercallback/) | Fungsi callback yang dipanggil oleh timer. |
| [wait_handle_t](./wait_handle_t/) | Tipe handle. |