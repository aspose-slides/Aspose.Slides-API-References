---
title: get_TileOffsetY()
second_title: Aspose.Slides for C++ API Referansı
description: Doku'nun şeklin orijinalinden nokta biriminde dikey ofsetini döndürür. Pozitif bir değer doku'yu aşağı hareket ettirirken, negatif bir değer yukarı hareket ettirir. Okunur float.
type: docs
weight: 300
url: /tr/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() method


Doku'nun şeklin orijinaline göre dikey ofsetini nokta biriminde döndürür. Pozitif bir değer doku'yu aşağı hareket ettirirken, negatif bir değer yukarı hareket ettirir. Okunur **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## Açıklamalar



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Şeklin resim doldurma formatını alır
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Resim doldurma modunu Tile olarak ayarlar
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Doku'nun dikey ofsetini -50 puana ayarlar
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## İlgili

* Sınıf [PictureFillFormat](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)