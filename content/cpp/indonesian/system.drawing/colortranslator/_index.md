---
title: ColorTranslator
second_title: Aspose.Slides untuk Referensi API C++
description: "Melakukan translasi warna. Objek-objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi System::MakeObject(). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan mengakibatkan kesalahan runtime dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer System::SmartPtr dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen."
type: docs
weight: 66
url: /id/system.drawing/colortranslator/
---
## ColorTranslator kelas

Melakukan translasi warna. Objek dari kelas ini hanya boleh dialokasikan menggunakan fungsi [System::MakeObject()](../../system/makeobject/). Jangan pernah membuat instance tipe ini di stack atau menggunakan operator new, karena akan menyebabkan kesalahan runtime dan/atau kegagalan asersi. Selalu balut kelas ini ke dalam pointer [System::SmartPtr](../../system/smartptr/) dan gunakan pointer ini untuk melewatkannya ke fungsi sebagai argumen.

```cpp
class ColorTranslator
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | Mengubah representasi warna HTML yang ditentukan menjadi objek [Color](../color/) yang setara. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | Mengubah warna [Windows](../../system.windows/) yang ditentukan menjadi objek [Color](../color/) yang setara. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | Mengubah objek [Color](../color/) yang ditentukan menjadi representasi string dari warna HTML yang setara. |

## Lihat Juga

* Namespace [System::Drawing](../)
* Perpustakaan [Aspose.Slides](../../)