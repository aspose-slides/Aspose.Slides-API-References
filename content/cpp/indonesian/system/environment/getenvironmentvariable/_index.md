---
title: GetEnvironmentVariable()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai variabel lingkungan yang ditentukan yang terkait dengan proses saat ini.
type: docs
weight: 287
url: /id/system/environment/getenvironmentvariable/
---
## Environment::GetEnvironmentVariable(const String\&) metode

Mengembalikan nilai variabel lingkungan yang ditentukan yang terkait dengan proses saat ini.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| variable | const [String](../../string/)\& | String yang berisi nama variabel yang akan diambil |

### Nilai Kembalian

Nilai variabel yang ditentukan

## Environment::GetEnvironmentVariable(const String\&, EnvironmentVariableTarget) metode

Mengembalikan nilai variabel lingkungan yang ditentukan dari lokasi yang ditentukan.

```cpp
static String System::Environment::GetEnvironmentVariable(const String &variable, EnvironmentVariableTarget target)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| variable | const [String](../../string/)\& | String yang berisi nama variabel yang akan diambil |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | Lokasi variabel |

### Nilai Kembalian

Nilai variabel yang ditentukan

## Lihat Juga

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Kelas [String](../../string/)
* Struct [Environment](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)