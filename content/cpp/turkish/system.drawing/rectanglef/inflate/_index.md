---
title: Inflate()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli nesne tarafından temsil edilen dikdörtgenin genişliğini ve yüksekliğini artırır, dikdörtgenin geometrik merkezinin konumunu korur. Genişlik ve yükseklik, belirtilen miktarlar kadar her iki yönde artırılır.
type: docs
weight: 261
url: /tr/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) metodu


Geçerli nesne tarafından temsil edilen dikdörtgenin genişliğini ve yüksekliğini artırır, dikdörtgenin geometrik merkezinin konumunu korur. Genişlik ve yükseklik, belirtilen miktarlar kadar her iki yönde artırılır.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | **float** | Dikdörtgenin genişliğinin her iki yönde artırılacağı miktar |
| height | **float** | Dikdörtgenin yüksekliğinin her iki yönde artırılacağı miktar |

## RectangleF::Inflate(const SizeF\&) metodu


Geçerli nesne tarafından temsil edilen dikdörtgenin genişliğini ve yüksekliğini artırır, dikdörtgenin geometrik merkezinin konumunu korur. Genişlik ve yükseklik, belirtilen boyut nesnesinin genişlik ve yükseklik değerleriyle karşılıklı olarak belirtilen miktarlar kadar artırılır.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | Genişlik ve yüksekliğin artırılacağı miktarları belirten [SizeF](../../sizef/) nesnesi |

## RectangleF::Inflate(const RectangleF\&, float, float) metodu


Belirtilen nesne tarafından temsil edilen dikdörtgenin genişliğini ve yüksekliğini artırır, dikdörtgenin geometrik merkezinin konumunu korur. Genişlik ve yükseklik, belirtilen miktarlar kadar her iki yönde artırılır.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | Şişirilecek bir dikdörtgen |
| x | **float** | Dikdörtgenin genişliğinin her iki yönde artırılacağı miktar |
| y | **float** | Dikdörtgenin yüksekliğinin her iki yönde artırılacağı miktar |

### Dönüş Değeri

Büyütülmüş dikdörtgeni temsil eden [RectangleF](../) nesnesi

## Ayrıca Bakınız

* Sınıf [RectangleF](../)
* Sınıf [SizeF](../../sizef/)
* Ad alanı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)