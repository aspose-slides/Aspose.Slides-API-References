---
title: CheckPassword()
second_title: Aspose.Slides untuk Referensi API C++
description: Memeriksa apakah kata sandi benar untuk presentasi yang dilindungi dengan kata sandi terbuka.
type: docs
weight: 53
url: /id/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) metode

Memeriksa apakah kata sandi benar untuk presentasi yang dilindungi dengan kata sandi terbuka.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Kata sandi yang akan diperiksa. |

### Nilai Kembalian

True jika presentasi dilindungi dengan kata sandi terbuka dan kata sandi tersebut benar, dan false jika tidak.

## Keterangan

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

Ketika kata sandi bernilai null atau kosong, metode ini mengembalikan false.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [PresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)