---
title: Remove()
second_title: Aspose.Slides for C++ API Referansı
description: Belirli bir FallBack fontunun listeden ilk görünümünü kaldırır.
type: docs
weight: 118
url: /tr/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) metodu

Belirli bir FallBack fontunun listeden ilk görünümünü kaldırır.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Listeden kaldırılacak fontun adı. |
## Açıklamalar

```cpp
// Bir kural oluşturur ve bir font listesi içerir.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Tahoma'yı listeden kaldır.
newRule->Remove(u"Tahoma");
```

## Ayrıca

* Sınıf [String](../../../system/string/)
* Sınıf [FontFallBackRule](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)