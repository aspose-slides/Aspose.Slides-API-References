---
title: ResultTask
second_title: Referensi API Aspose.Slides untuk C++
description: Spesialisasi Task yang mengembalikan nilai hasil setelah selesai.
type: docs
weight: 40
url: /id/system.threading.tasks/resulttask/
---
## ResultTask kelas

Sebuah spesialisasi [Task](../task/) yang mengembalikan nilai hasil setelah selesai.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Jenis nilai hasil yang dikembalikan oleh tugas |
## Metode

| Metode | Deskripsi |
| --- | --- |
| void [Activate](../task/activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Mengaktifkan tugas untuk dijalankan pada penjadwal. |
| void [AddCompletionAction](../task/addcompletionaction/)(const [Action](../../system/action/)<>\&) | Menambahkan aksi lanjutan yang akan dieksekusi setelah selesai. |
| void [Cancel](../task/cancel/)() | Menandai tugas sebagai dibatalkan dan menyelesaikannya. |
| void [Complete](./complete/)(const T\&) | Mengatur nilai hasil untuk tugas dan menyelesaikannya. |
| void [Complete](../task/complete/)() | Menandai tugas sebagai selesai dan menyelesaikannya. |
| [Runtime::CompilerServices::ConfiguredResultTaskAwaitable](../../system.runtime.compilerservices/configuredresulttaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Mengonfigurasi bagaimana await pada tugas hasil ini harus berperilaku terkait penangkapan konteks. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>\>\&) | Membuat kelanjutan yang dieksekusi ketika tugas hasil selesai. |
| [RTaskPtr](../../system/rtaskptr/)\<TNewResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>, TNewResult\>\&) | Membuat kelanjutan yang dieksekusi ketika tugas hasil selesai. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Membuat kelanjutan yang dieksekusi ketika tugas selesai. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | Membuat kelanjutan yang dieksekusi ketika tugas selesai. |
| void [Deactivate](../task/deactivate/)() | Menonaktifkan tugas untuk dijalankan pada penjadwal saat ini bila ada. |
| void [Dispose](../task/dispose/)() override | Melepaskan sumber daya yang terkait dengan tugas. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Membandingkan objek menggunakan semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe referensi dengan gaya C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Membandingkan objek tipe nilai dengan gaya C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Meniru perbandingan titik mengambang ala C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Meniru perbandingan titik mengambang ala C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| void [Execute](../task/execute/)() | Mengeksekusi fungsi tugas. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Hanya untuk tujuan internal. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](../task/get_asyncstate/)() const | Mengambil objek status yang didefinisikan pengguna yang terkait dengan tugas. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](../task/get_completedtask/)() | Mengambil tugas yang selesai (singleton). |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](../task/get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](../task/get_exception/)() const | Mengambil ID untuk tugas. |
| **int32_t** [get_Id](../task/get_id/)() const |  |
| **bool** [get_IsCanceled](../task/get_iscanceled/)() const | Mengambil apakah tugas selesai karena pembatalan. |
| **bool** [get_IsCompleted](../task/get_iscompleted/)() const | Mengambil apakah tugas telah selesai. |
| **bool** [get_IsFaulted](../task/get_isfaulted/)() const | Mengambil apakah tugas selesai karena pengecualian yang tidak ditangani. |
| T [get_Result](./get_result/)() | Mengambil hasil operasi asinkron. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](../task/get_scheduler/)() const | Mengambil penjadwal yang terkait dengan tugas ini. |
| [TaskStatus](../taskstatus/) [get_Status](../task/get_status/)() const | Mengambil status terkini tugas. |
| [Runtime::CompilerServices::ResultTaskAwaiter](../../system.runtime.compilerservices/resulttaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Mengambil awaiter untuk tugas hasil ini untuk digunakan dengan Await. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Mengambil struktur data penghitung referensi yang terkait dengan objek. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metode C# [Object.GetHashCode()](../../system/object/gethashcode/). Mengaktifkan hashing objek kustom. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Mengambil tipe sebenarnya dari objek. Analog pemanggilan C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Memeriksa apakah objek merupakan instance dari tipe yang dijelaskan oleh targetType. Analog operator 'is' C#. |
| void [Lock](../../system/object/lock/)() | Mengimplementasikan penguncian pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Mengaktifkan kloning tipe kustom. |
|  [Object](../../system/object/object/)() | Membuat objek. Menginisialisasi semua struktur data internal. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor salin. Tidak menyalin apa pun, sebenarnya hanya menginisialisasi objek baru dan mengaktifkan konstruktor salin pada subclass. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator penugasan. Tidak menyalin apa pun, sebenarnya hanya menginisialisasi objek baru dan mengaktifkan konstruktor salin pada subclass. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Membandingkan objek berdasarkan referensi. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Membandingkan referensi objek tipe nilai dengan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string dan nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spesialisasi [Object::ReferenceEquals](../../system/object/referenceequals/) untuk kasus string. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Mengurangi penghitung referensi bersama sebesar nilai yang ditentukan. |
|  [ResultTask](./resulttask/)(const [Func](../../system/func/)\<T\>\&) | Membuat [ResultTask](./) dengan fungsi yang mengembalikan nilai. |
|  [ResultTask](./resulttask/)() | Implementasi internal. Tidak untuk kode pengguna. |
|  [ResultTask](./resulttask/)(const T\&) | Konstruktor internal untuk membuat tugas hasil dengan hasil yang ditentukan. |
| void [RunSynchronously](../task/runsynchronously/)() | Menjalankan tugas secara sinkron pada utas saat ini. |
| void [RunSynchronously](../task/runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Menjalankan tugas secara sinkron menggunakan penjadwal yang ditentukan. |
| void [set_Function](../task/set_function/)(const [FunctionT](../task/functiont/)\&) | Menetapkan fungsi internal untuk dieksekusi. |
| void [set_Result](./set_result/)(const T\&) | Menetapkan nilai hasil untuk tugas. |
| void [set_Scheduler](../task/set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Menetapkan penjadwal yang terkait dengan tugas ini. |
| void [set_Status](../task/set_status/)([TaskStatus](../taskstatus/)) | Menetapkan status tugas. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Menetapkan argumen template ke-n menjadi pointer lemah (bukan shared). Memungkinkan mengganti pointer dalam kontainer ke mode lemah. |
| int [SharedCount](../../system/object/sharedcount/)() const | Mengambil nilai saat ini dari penghitung referensi bersama. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Meningkatkan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Mengurangi dan mengembalikan penghitung referensi bersama. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [Start](../task/start/)() | Memulai eksekusi tugas menggunakan penjadwal bawaan. |
| void [Start](../task/start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Memulai eksekusi tugas menggunakan penjadwal yang ditentukan. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&) | Membuat [Task](../task/) dengan aksi untuk dieksekusi. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Membuat [Task](../task/) dengan aksi dan token pembatalan. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Membuat [Task](../task/) dengan aksi berstatus dan objek status. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Membuat [Task](../task/) dengan aksi berstatus, status, dan token pembatalan. |
|  [Task](../task/task/)() | Konstruktor internal untuk membuat tugas yang tidak diinisialisasi. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metode C# [Object.ToString()](../../system/object/tostring/). Mengaktifkan konversi objek kustom menjadi string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Mengimplementasikan konstruk C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Mengimplementasikan pelepasan pernyataan C# lock(). Panggil langsung atau gunakan objek penjaga [LockContext](../../system/lockcontext/). |
| void [Wait](../task/wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Menunggu tugas selesai dengan dukungan pembatalan. |
| void [Wait](../task/wait/)() | Menunggu tugas selesai. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Meningkatkan penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Mengurangi penghitung referensi lemah. Tidak boleh dipanggil langsung; gunakan smart pointer atau ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Menghancurkan objek. Membebaskan semua struktur data internal. |
|  [~Task](../task/~task/)() | Destruktor. |
## Catatan

Mewakili operasi asinkron yang menghasilkan hasil, mirip dengan System.Threading.Tasks.Task<TResult> di .NET 
## Lihat Juga

* Kelas [Task](../task/)
* Namespace [System::Threading::Tasks](../)
* Perpustakaan [Aspose.Slides](../../)