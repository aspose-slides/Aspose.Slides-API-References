---
title: AddFallBackFonts()
second_title: Aspose.Slides için C++ API Referansı
description: FallBack yazı tipleri listesine yeni bir yazı tipi ekler.
type: docs
weight: 40
url: /tr/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) metot

FallBack yazı tipleri listesine yeni bir yazı tipi ekler.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | FallBack için yazı tipinin adı veya adları (virgülle ayrılmış) |
## Açıklamalar

```cpp
//Yeni bir FantFallBackRule örneği oluştur
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Kurala ikinci yazı tipini ekle
newRule->AddFallBackFonts(u"MS Gothic");
//Kurala üçüncü ve dördüncü yazı tiplerini ekle
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) metot

FallBack yazı tipleri listesine yeni yazı tipleri ekler.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | FallBack için yazı tipinin adı veya adları (virgülle ayrılmış) |
## Açıklamalar

```cpp
//Yeni bir FontFallBackRule örneği oluştur
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Kurala başka üç yazı tipi ekle
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IFontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)