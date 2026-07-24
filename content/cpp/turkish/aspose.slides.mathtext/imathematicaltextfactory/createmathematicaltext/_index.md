---
title: CreateMathematicalText()
second_title: Aspose.Slides için C++ API Referansı
description: Boş matematiksel metin öğesi oluştur
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() yöntemi

Boş matematiksel metin öğesi oluştur

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```

### Dönüş Değeri

yeni Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) yöntemi

Belirtilen değerle matematiksel metin öğesi oluştur

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathSymbol | char16_t | metin değeri olarak kullanılacak tek sembol |

### Dönüş Değeri

yeni Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) yöntemi

Belirtilen değerle boş matematiksel metin öğesi oluştur

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | metin değeri |

### Dönüş Değeri

yeni Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) yöntemi

Belirtilen değer ve biçimlendirme özellikleriyle boş matematiksel metin öğesi oluştur

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | metin değeri |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | metin biçim ayarları |

### Dönüş Değeri

yeni Mathematical Text

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathematicalText](../../imathematicaltext/)
* Class [IMathematicalTextFactory](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)