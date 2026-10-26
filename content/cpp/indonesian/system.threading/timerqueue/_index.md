---
title: TimerQueue
second_title: Referensi API Aspose.Slides untuk C++
description: Antrian yang menangani objek Timer. Ini hanya sebuah implementasi. Objek Timer mendaftar sendiri, Anda tidak perlu melakukannya untuk menggunakannya – gunakan API kelas Timer sebagai gantinya. Ini adalah tipe singleton dengan manajemen memori yang dilakukan oleh fungsi akses. Anda tidak pernah boleh membuat instance secara langsung.
type: docs
weight: 261
url: /id/system.threading/timerqueue/
---
## TimerQueue kelas

Antrian yang menangani objek [Timer](../timer/). Ini hanya sebuah implementasi. Objek [Timer](../timer/) mendaftar sendiri, Anda tidak perlu melakukannya untuk menggunakannya – gunakan API kelas [Timer](../timer/) sebagai gantinya. Ini adalah tipe singleton dengan manajemen memori yang dilakukan oleh fungsi akses. Anda tidak pernah boleh membuat instance secara langsung.

```cpp
class TimerQueue
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | Mendaftarkan timer ke dalam antrian. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | Menghapus timer dari antrian. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Singleton implementasi. |
| static void [JoinWorkerThread](./joinworkerthread/)() | Menggabungkan thread pekerja. Menunggu tak terbatas jika diperlukan. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | Tidak menyalin. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | Tidak menyalin. |
## Lihat Juga

* Ruang nama [System::Threading](../)
* Perpustakaan [Aspose.Slides](../../)