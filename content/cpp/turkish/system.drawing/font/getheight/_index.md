---
title: GetHeight()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli nesne tarafından temsil edilen yazı tipinin satır aralığını, belirtilen Graphics nesnesinin mevcut biriminde döndürür.
type: docs
weight: 14
url: /tr/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) method

Geçerli nesne tarafından temsil edilen yazı tipinin satır aralığını, belirtilen [Graphics](../../graphics/) nesnesinin mevcut biriminde döndürür.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Ölçüm birimlerini belirten bir [Graphics](../../graphics/) nesnesi |

## Font::GetHeight(float) method

Geçerli nesne tarafından temsil edilen yazı tipinin, belirtilen dikey çözünürlüğe sahip bir ekran cihazına çizildiğinde yüksekliğini döndürür.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dpi | **float** | Ekran cihazının dikey çözünürlüğü |

### Dönüş Değeri

Yazı tipinin piksel cinsinden yüksekliği

## Diğer

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Graphics](../../graphics/)
* Sınıf [Font](../)
* AdAlanı [System::Drawing](../../)
* Library [Aspose.Slides](../../../)