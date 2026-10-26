---
title: AddFallBackFonts()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan font baru ke daftar font FallBack.
type: docs
weight: 40
url: /id/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) metode

Menambahkan font baru ke daftar font FallBack.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nama atau nama-nama font (dipisahkan dengan koma) untuk FallBack |
## Keterangan

```cpp
//Buat instance baru dari FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Tambahkan font kedua ke aturan
newRule->AddFallBackFonts(u"MS Gothic");
//Tambahkan font ketiga dan keempat ke aturan
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) metode

Menambahkan font baru ke daftar font FallBack.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nama atau nama-nama font (dipisahkan dengan koma) untuk FallBack |
## Keterangan

```cpp
//Buat instance baru dari FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Tambahkan tiga font lain ke aturan
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [IFontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)