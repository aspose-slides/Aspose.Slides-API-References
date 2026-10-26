---
title: GetEnvironmentVariables()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan kamus yang berisi semua nama variabel lingkungan dan nilai-nilainya yang terkait dengan proses saat ini.
type: docs
weight: 326
url: /id/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() metode


Mengembalikan kamus yang berisi semua nama variabel lingkungan dan nilai-nilainya yang terkait dengan proses saat ini.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) metode


Mengembalikan kamus yang berisi semua nama variabel lingkungan dan nilai-nilainya dari lokasi yang ditentukan.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | Lokasi variabel |

### Nilai Kembali

Sebuah kamus yang berisi semua nama variabel lingkungan dan nilai-nilainya dari lokasi yang ditentukan

## Lihat Juga

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Kelas [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Kelas [String](../../string/)
* Struktur [Environment](../)
* Namespace [System](../../)
* Pustaka [Aspose.Slides](../../../)