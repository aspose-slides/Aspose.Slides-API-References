---
title: Inflate()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli nesne tarafından temsil edilen dikdörtgenin genişliğini ve yüksekliğini artırır, dikdörtgenin geometrik merkezinin konumunu korur. Genişlik ve yükseklik, belirtilen miktarlar kadar her iki yönde artırılır.
type: docs
weight: 261
url: /tr/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) metot


Geometrik orta noktasının konumunu koruyarak, geçerli nesne tarafından temsil edilen dikdörtgenin width ve height değerlerini artırır. width ve height, belirtilen miktarlar kadar iki yönde artırılır.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | int | Dikdörtgenin width değerinin iki yönde artırılacağı miktar |
| height | int | Dikdörtgenin height değerinin iki yönde artırılacağı miktar |

## Rectangle::Inflate(const Size\&) metot


Geometrik orta noktasının konumunu koruyarak, geçerli nesne tarafından temsil edilen dikdörtgenin width ve height değerlerini artırır. width ve height, belirtilen boyut nesnesinin width ve height değerleriyle belirtilen miktarlar kadar iki yönde artırılır.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | const [Size](../../size/)\& | [Size](../../size/) nesnesi, dikdörtgenin width ve height değerlerinin ne kadar artırılacağını belirler |

## Rectangle::Inflate(const Rectangle\&, int, int) metot


Geometrik orta noktasının konumunu koruyarak, belirtilen nesne tarafından temsil edilen dikdörtgenin width ve height değerlerini artırır. width ve height, belirtilen miktarlar kadar iki yönde artırılır.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | Inflate edilecek bir dikdörtgen |
| x | int | Dikdörtgenin width değerinin iki yönde artırılacağı miktar |
| y | int | Dikdörtgenin height değerinin iki yönde artırılacağı miktar |

### Dönüş Değeri

[Rectangle](../) nesnesi, büyütülmüş dikdörtgeni temsil eder.

## İlgili

* Sınıf [Rectangle](../)
* Sınıf [Size](../../size/)
* Ad alanı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)