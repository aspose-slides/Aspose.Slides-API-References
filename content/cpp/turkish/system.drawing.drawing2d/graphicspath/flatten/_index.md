---
title: Flatten()
second_title: Aspose.Slides for C++ API Referansı
description: Yoldaki her eğriyi, bağlı bir dizi çizgiye dönüştürerek düzleştirir. 0.25 düzlem değeri kullanılır.
type: docs
weight: 391
url: /tr/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() yöntemi

Yolu oluşturan her eğriyi, bağlı bir dizi çizgiye dönüştürerek düzleştirir. 0.25 düzlem değeri kullanılır.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```
## GraphicsPath::Flatten(const MatrixPtr\&) yöntemi

Yolu oluşturan her eğriyi, bağlı bir dizi çizgiye dönüştürerek düzleştirir. 0.25 düzlem değeri kullanılır.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Yolun düzleştirilmeden önce uygulanacak dönüştürme matrisi |

## GraphicsPath::Flatten(const MatrixPtr\&, float) yöntemi

Yolu oluşturan her eğriyi, bağlı bir dizi çizgiye dönüştürerek düzleştirir.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Yolun düzleştirilmeden önce uygulanacak dönüştürme matrisi |
| flatness | **float** | Eğri ile düzleştirilmiş yaklaşıklığı arasındaki izin verilen maksimum hatayı belirtir |

## İlgili

* Typedef [MatrixPtr](../../matrixptr/)
* Sınıf [GraphicsPath](../)
* İsim Uzayı [System::Drawing::Drawing2D](../../)
* Kütüphane [Aspose.Slides](../../../)