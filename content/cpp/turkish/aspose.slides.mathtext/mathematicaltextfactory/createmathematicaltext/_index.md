---
title: CreateMathematicalText()
second_title: Aspose.Slides for C++ API Referansı
description: Boş matematiksel metin öğesi oluştur
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() metod

Boş matematiksel metin öğesi oluştur

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```

### Return Value

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) metod

Belirtilen değerle matematiksel metin öğesi oluştur

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathSymbol | char16_t | metin değeri olarak kullanılacak tek sembol |

### Return Value

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) metod

Belirtilen değerle boş bir matematiksel metin öğesi oluştur

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | metin değeri |

### Return Value

new Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) metod

Belirtilen değer ve biçimlendirme özellikleriyle boş bir matematiksel metin öğesi oluştur

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | metin değeri |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | metin biçim ayarları |

### Return Value

new Mathematical Text

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathematicalText](../../imathematicaltext/)
* Sınıf [MathematicalTextFactory](../)
* Sınıf [String](../../../system/string/)
* Sınıf [IPortionFormat](../../../aspose.slides/iportionformat/)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)