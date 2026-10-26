---
title: AsyncCompletedEventArgs()
second_title: Referensi API Aspose.Slides untuk C++
description: Konstruktor.
type: docs
weight: 1
url: /id/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() konstruktor

Konstruktor.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) konstruktor

Menginisialisasi contoh baru dari kelas [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | Setiap kesalahan yang terjadi selama operasi asinkron. |
| canceled | **bool** | Nilai yang menunjukkan apakah operasi asinkron dibatalkan. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Objek status opsional yang disediakan pengguna yang diteruskan ke metode [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |

## Lihat Juga

* Typedef [Exception](../../../system/exception/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [AsyncCompletedEventArgs](../)
* Kelas [Object](../../../system/object/)
* Ruang nama [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)