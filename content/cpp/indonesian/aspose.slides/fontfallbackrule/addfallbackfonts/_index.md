---
title: AddFallBackFonts()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan font baru ke daftar font FallBack.
type: docs
weight: 79
url: /id/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) metode

Menambahkan font baru ke daftar font FallBack.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nama font atau nama-nama (dipisahkan dengan koma) untuk FallBack |

## Catatan

```cpp
// Buat instance baru dari FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Tambahkan font kedua ke aturan
newRule->AddFallBackFonts(u"MS Gothic");
//Tambahkan font ketiga dan keempat ke aturan
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) metode

Menambahkan font baru ke daftar font FallBack.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nama font atau nama-nama (dipisahkan dengan koma) untuk FallBack |

## Catatan

```cpp
//Buat instance baru dari FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Tambah tiga font lainnya ke aturan
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [FontFallBackRule](../)
* RuangNama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)