---
title: Start()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai proses dengan parameter yang telah ditentukan.
type: docs
weight: 14
url: /id/system.diagnostics/process/start/
---
## Process::Start() metode

Memulai proses dengan parameter yang telah ditentukan.

```cpp
bool System::Diagnostics::Process::Start()
```

## Process::Start(const String\&, const String\&) metode

Memulai proses dengan jalur dan argumen yang ditentukan.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const String &filename, const String &arguments=String::Empty)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | [Process](../) jalur. |
| arguments | const [String](../../../system/string/)\& | [Process](../) parameter. |

### Nilai Kembali

[Object](../../../system/object/) dilampirkan ke proses yang baru dimulai.

## Process::Start(const SharedPtr\<ProcessStartInfo\>\&) metode

Memulai proses dengan jalur dan argumen yang ditentukan.

```cpp
static SharedPtr<Process> System::Diagnostics::Process::Start(const SharedPtr<ProcessStartInfo> &start_info)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| start_info | const [SharedPtr](../../../system/sharedptr/)\<[ProcessStartInfo](../../processstartinfo/)\>\& | Informasi tentang proses yang akan dimulai. |

### Nilai Kembali

[Object](../../../system/object/) dilampirkan ke proses yang baru dimulai.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Process](../)
* Kelas [String](../../../system/string/)
* Kelas [ProcessStartInfo](../../processstartinfo/)
* Ruang Nama [System::Diagnostics](../../)
* Library [Aspose.Slides](../../../)