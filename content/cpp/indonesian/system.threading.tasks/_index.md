---
title: "System::Threading::Tasks"
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 1015
url: /id/system.threading.tasks/
---
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [Parallel](./parallel/) | Menyediakan dukungan untuk loop paralel dan region. |
| [ParallelLoopResult](./parallelloopresult/) | Menyediakan status penyelesaian dari loop [Parallel](./parallel/). |
| [ParallelOptions](./paralleloptions/) | Menyimpan opsi yang mengonfigurasi operasi metode pada kelas [Parallel](./parallel/). |
| [ResultTask](./resulttask/) | Spesialisasi [Task](./task/) yang mengembalikan nilai hasil saat selesai. |
| [ResultValueTask](./resultvaluetask/) | Mewakili tipe mirip tugas hibrida yang dapat membungkus baik nilai hasil langsung maupun ResultTask<T>. |
| [Task](./task/) | Mewakili operasi asinkron yang dapat ditunggu dan digabungkan dengan tugas lain. |
| [TaskScheduler](./taskscheduler/) | Mewakili objek yang menangani pekerjaan tingkat rendah dalam mengantrikan tugas ke thread. |
| [ValueTask](./valuetask/) | Menyediakan hasil yang dapat ditunggu dari operasi asinkron. |
## Fungsi

| Fungsi | Deskripsi |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Membuat tugas yang selesai setelah penundaan waktu. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Membuat tugas yang selesai setelah penundaan waktu dan dapat dibatalkan. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Membuat tugas yang telah selesai karena pembatalan dengan token yang ditentukan. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Membuat tugas yang telah selesai dengan pengecualian yang ditentukan. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Membuat tugas yang telah selesai dengan pengecualian dan tipe hasil yang ditentukan. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Membuat tugas yang berhasil selesai dengan hasil yang ditentukan. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | Mengantrikan pekerjaan yang ditentukan untuk dijalankan pada pool thread dan mengembalikan handle [Task](./task/) untuk pekerjaan tersebut. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Mengantrikan pekerjaan yang ditentukan untuk dijalankan pada pool thread dan mengembalikan handle [Task](./task/) untuk pekerjaan tersebut. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | Mengantrikan pekerjaan yang ditentukan untuk dijalankan pada pool thread dan mengembalikan proxy untuk [Task](./task/) yang dikembalikan oleh fungsi. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | Mengantrikan pekerjaan yang ditentukan untuk dijalankan pada pool thread dan mengembalikan handle Task<TResult> untuk pekerjaan tersebut. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Menunggu semua objek [Task](./task/) yang diberikan selesai dieksekusi. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Menunggu semua objek [Task](./task/) yang diberikan selesai dieksekusi. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Menunggu salah satu objek [Task](./task/) yang diberikan selesai dieksekusi. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Menunggu salah satu objek [Task](./task/) yang diberikan selesai dieksekusi. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Membuat tugas yang akan selesai ketika semua tugas yang disediakan telah selesai. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Membuat tugas yang akan selesai ketika semua tugas yang disediakan telah selesai. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Membuat tugas yang akan selesai ketika semua tugas yang disediakan telah selesai. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Membuat tugas yang akan selesai ketika semua tugas yang disediakan telah selesai. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Membuat tugas yang akan selesai ketika salah satu tugas yang disediakan selesai. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Membuat tugas yang akan selesai ketika salah satu tugas yang disediakan selesai. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Membuat tugas yang akan selesai ketika salah satu tugas yang disediakan selesai. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Membuat tugas yang akan selesai ketika salah satu tugas yang disediakan selesai. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Membuat tugas yang dapat ditunggu yang secara asinkron mengembalikan kontrol ke konteks saat ini ketika ditunggu. |
## Enums

| Enum | Deskripsi |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |