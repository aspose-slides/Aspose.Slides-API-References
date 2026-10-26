---
title: FontFamily()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen adla bir font ailesi temsil eden FontFamily sınıfının yeni bir örneğini oluşturur.
type: docs
weight: 1
url: /tr/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) constructor

Belirtilen adla bir font ailesi temsil eden [FontFamily](../) sınıfının yeni bir örneğini oluşturur.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Bir font ailesi adı |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) constructor

Belirtilen adla ve belirtilen FontCollection içinde [FontFamily](../) sınıfının yeni bir örneğini oluşturur.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Bir font ailesi adı |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | Bu örneği içeren FontCollection. |

## FontFamily::FontFamily(Text::GenericFontFamilies) constructor

Belirtilen genel font ailesinden [FontFamily](../) sınıfının yeni bir örneğini oluşturur.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | [FontFamily](../) oluşturmak için GenericFontFamilies değeri. |

## Ayrıca Bakınız

* Enum [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [FontFamily](../)
* Class [FontCollection](../../../system.drawing.text/fontcollection/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)