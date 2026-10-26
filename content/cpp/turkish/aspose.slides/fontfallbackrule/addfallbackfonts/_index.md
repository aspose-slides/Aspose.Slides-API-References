---
title: AddFallBackFonts()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir font(lar)ı FallBack fontları listesine ekler.
type: docs
weight: 79
url: /tr/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) metod

Yeni bir font(lar)ı FallBack fontları listesine ekler.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | FallBack için fontun adı veya adları (virgülle ayrılmış) |
## Açıklamalar

```cpp
// FontFallBackRule yeni bir örnek oluştur
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Kurala ikinci bir font ekle
newRule->AddFallBackFonts(u"MS Gothic");
//Kurala üçüncü ve dördüncü fontları ekle
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) metod

Yeni fontları FallBack fontları listesine ekler.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | FallBack için fontun adı veya adları (virgülle ayrılmış) |
## Açıklamalar

```cpp
//FontFallBackRule yeni bir örnek oluştur
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Kurala başka üç font ekle
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [FontFallBackRule](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)