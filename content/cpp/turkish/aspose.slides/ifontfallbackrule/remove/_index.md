---
title: Remove()
second_title: Aspose.Slides for C++ API Referansı
description: Belirli bir FallBack yazı tipinin listeden ilk oluşumunu kaldırır.
type: docs
weight: 79
url: /tr/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) metot


Belirli bir FallBack yazı tipinin listeden ilk görünümünü kaldırır.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Listeden kaldırılacak yazı tipinin adı. |
## Açıklamalar



```cpp
// Yazı tiplerinin bir listesini içeren bir kural oluşturur.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Liste üzerinden Tahoma’yı kaldırma
newRule->Remove(u"Tahoma");
```


## İlgili

* Sınıf [String](../../../system/string/)
* Sınıf [IFontFallBackRule](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)