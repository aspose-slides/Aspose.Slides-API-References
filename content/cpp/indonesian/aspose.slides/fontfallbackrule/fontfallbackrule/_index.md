---
title: FontFallBackRule()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat instance baru.
type: docs
weight: 66
url: /id/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) konstruktor


Membuat instance baru.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | **uint32_t** | Indeks mulai dari rentang unicode |
| endIndex | **uint32_t** | Indeks akhir dari rentang unicode |
| fontNames | [System::String](../../../system/string/) | Nama atau nama font (dipisahkan dengan koma) untuk FallBack |
## Keterangan



```cpp
// Buat instance baru dari FantFallBackRule dengan satu font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Buat instance baru dari FantFallBackRule dengan beberapa font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```


## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) konstruktor


Membuat instance baru.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | **uint32_t** | Indeks mulai dari rentang unicode |
| endIndex | **uint32_t** | Indeks akhir dari rentang unicode |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nama atau nama font (dipisahkan dengan koma) untuk FallBack |
## Keterangan



```cpp
// Buat instance baru dari FantFallBackRule dengan dua font
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Buat instance baru dari FantFallBackRule dengan beberapa font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)