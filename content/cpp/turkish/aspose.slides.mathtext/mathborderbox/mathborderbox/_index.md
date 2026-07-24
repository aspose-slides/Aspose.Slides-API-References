---
title: MathBorderBox()
second_title: Aspose.Slides for C++ API Referansı
description: Dikdörtgen kenarlıkla MathBorderBox öğesi oluşturur
type: docs
weight: 222
url: /tr/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) yapıcı

[MathBorderBox](../) öğesini dikdörtgen kenarlıkla oluşturur

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Kenarlık kutusunun uygulandığı temel öğe. Null olabilir. |
## Açıklamalar



Örnek: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) yapıcı

[MathBorderBox](../) öğesini oluşturur

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Kenarlık kutusunun uygulandığı temel öğe. |
| hideTop | **bool** | Üst Kenarı Gizle |
| hideBottom | **bool** | Alt Kenarı Gizle |
| hideLeft | **bool** | Sol Kenarı Gizle |
| hideRight | **bool** | Sağ Kenarı Gizle |
| strikethroughHorizontal | **bool** | Yatay Çizgi |
| strikethroughVertical | **bool** | Dikey Çizgi |
| strikethroughBottomLeftToTopRight | **bool** | Alt Sol’tan Üst Sağa Çizgi |
| strikethroughTopLeftToBottomRight | **bool** | Üst Sol’dan Alt Sağa Çizgi |
## Açıklamalar



Örnek: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathBorderBox](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)