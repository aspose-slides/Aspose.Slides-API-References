---
title: MathematicalText()
second_title: Aspose.Slides for C++ API Referansı
description: "Varsayılan yapıcı (String::Empty Değerini oluştur)"
type: docs
weight: 40
url: /tr/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() yapıcı

Varsayılan yapıcı (String::Empty Değerini oluştur)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## Açıklamalar

Örnek: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) yapıcı

Tek bir sembolle [MathText](../../) oluştur

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char16_t | tek sembol |

## Açıklamalar

Örnek: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) yapıcı

Metinden [MathematicalText](../) oluştur

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | metin değeri |

## Açıklamalar

Örnek: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) yapıcı

Metinden ve biçim ayarlarından [MathematicalText](../) oluştur

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | metin değeri |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | metin biçim ayarları |

## Açıklamalar

Örnek: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## İlgili Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MathematicalText](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)