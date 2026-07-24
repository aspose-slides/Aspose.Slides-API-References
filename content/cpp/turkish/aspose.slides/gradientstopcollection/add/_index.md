---
title: Add()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni gradient durak oluşturur ve koleksiyonun sonuna ekler.
type: docs
weight: 53
url: /tr/aspose.slides/gradientstopcollection/add/
---
## GradientStopCollection::Add(float, System::Drawing::Color) metodu


Yeni gradient durak oluşturur ve koleksiyonun sonuna ekler.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, System::Drawing::Color color) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | **float** | Yeni gradient durak konumu. |
| color | [System::Drawing::Color](../../../system.drawing/color/) | Yeni gradient durak rengi. |

### Dönüş Değeri

Koleksiyondaki yeni gradient durak indeksidir.

## GradientStopCollection::Add(float, PresetColor) metodu


Yeni gradient durak oluşturur ve koleksiyonun sonuna ekler.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, PresetColor presetColor) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | **float** | Yeni gradient durak konumu. |
| presetColor | [PresetColor](../../presetcolor/) | Yeni gradient durak rengi. |

### Dönüş Değeri

Koleksiyondaki yeni gradient durak indeksidir.

## GradientStopCollection::Add(float, SchemeColor) metodu


Yeni gradient durak oluşturur ve koleksiyonun sonuna ekler.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, SchemeColor schemeColor) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | **float** | Yeni gradient durak konumu. |
| schemeColor | [SchemeColor](../../schemecolor/) | Yeni gradient durak rengi. |

### Dönüş Değeri

Koleksiyondaki yeni gradient durak indeksidir.

## İlgili

* Enum [PresetColor](../../presetcolor/)
* Enum [SchemeColor](../../schemecolor/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGradientStop](../../igradientstop/)
* Class [Color](../../../system.drawing/color/)
* Class [GradientStopCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)