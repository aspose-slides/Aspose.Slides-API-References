---
title: AppendFormat()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan string terformat ke builder.
type: docs
weight: 131
url: /id/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String&, const TArgs&...) metode

Menambahkan string terformat ke builder.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TArgs | Tipe argumen. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | String format. |
| args | const TArgs\&... | Argumen untuk dimasukkan ke posisi string format. |

### Nilai Kembali

Pointer ini.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String&, const TArgs&...) metode

Menambahkan string terformat ke builder.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TArgs | Tipe argumen. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | Penyedia format; diabaikan. |
| format | const [String](../../../system/string/)\& | String format. |
| args | const TArgs\&... | Argumen untuk dimasukkan ke posisi string format. |

### Nilai Kembali

Pointer ini.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [StringBuilder](../)
* Kelas [String](../../../system/string/)
* Kelas [IFormatProvider](../../../system/iformatprovider/)
* Ruang Nama [System::Text](../../)
* Perpustakaan [Aspose.Slides](../../../)