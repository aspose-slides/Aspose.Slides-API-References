---
title: GetImage
second_title: Aspose.Sildes için .NET API Referansı
description: Özel ölçeklendirme ile bir Thumbnail Image nesnesi döndürür.
type: docs
weight: 80
url: /tr/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

Özel ölçeklendirme ile bir Thumbnail Image nesnesi döndürür.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scaleX | Single | Bu Thumbnail'ı x ekseni yönünde ölçeklendirecek değer. |
| scaleY | Single | Bu Thumbnail'ı y ekseni yönünde ölçeklendirecek değer. |

### Dönüş Değeri

IImage nesnesi.

### Örnekler

Aşağıdaki örnek, PowerPoint Sunumundan thumbnail'lar oluşturmayı gösterir.

```csharp
[C#]
// Sunum dosyasını temsil eden bir Presentation sınıfı örnekleyin
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // İlk slayta erişin
    ISlide sld = pres.Slides[0];
    // Tam ölçekli bir görsel oluşturun
    IImage bmp = sld.GetImage(1f, 1f);
    // Görüntüyü JPEG formatında diske kaydedin
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

Aşağıdaki örnek, slaytları bitmap'e dönüştürüp görüntüleri PNG olarak kaydetmeyi gösterir.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Sunumdaki ilk slaytı bir Bitmap nesnesine dönüştürür
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Görüntüyü PNG formatında kaydeder
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

Aşağıdaki örnek, PowerPoint PPT/PPTX dosyalarını JPG'ye dönüştürmeyi gösterir.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Tam ölçekli bir görüntü oluştur
		IImage bmp = sld.GetImage(1f, 1f);
		// Görüntüyü JPEG formatında diske kaydet
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

Aşağıdaki örnek, PowerPoint PPT/PPTX dosyalarını özelleştirilmiş boyutlarla JPG'ye dönüştürmeyi gösterir.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Boyutları tanımla
	int desiredX = 1200;
	int desiredY = 800;
	// X ve Y'nin ölçekli değerlerini al
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Tam ölçekli bir görüntü oluştur
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Görüntüyü JPEG formatında diske kaydet
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### Ayrıca Bakınız

* arayüz [IImage](../../iimage)
* sınıf [Slide](../../slide)
* ad alanı [Aspose.Slides](../../slide)
* derleme [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Gerçek boyutun %20'si kadar bir Thumbnail Image nesnesi döndürür.

```csharp
public IImage GetImage()
```

### Ayrıca Bakınız

* arayüz [IImage](../../iimage)
* sınıf [Slide](../../slide)
* ad alanı [Aspose.Slides](../../slide)
* derleme [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Belirtilen boyutta bir Thumbnail Image nesnesi döndürür.

```csharp
public IImage GetImage(Size imageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageSize | Size | Oluşturulacak görüntünün boyutu. |

### Dönüş Değeri

Image nesnesi.

### Örnekler

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Sunumdaki ilk slaytı belirtilen boyutta bir Bitmap'e dönüştürür
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Görüntüyü JPEG formatında kaydeder
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### Ayrıca Bakınız

* arayüz [IImage](../../iimage)
* sınıf [Slide](../../slide)
* ad alanı [Aspose.Slides](../../slide)
* derleme [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Belirtilen parametrelerle bir Thumbnail tiff görüntü nesnesi döndürür.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | ITiffOptions | Tiff seçenekleri. |

### Dönüş Değeri

Image nesnesi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| InvalidOperationException | options.SlideLayoutOption, NotesCommentsLayoutOptions olduğunda ve NotesPosition özelliği NotesPositions.BottomFull değerini aldığında fırlatılır. |

### Ayrıca Bakınız

* arayüz [IImage](../../iimage)
* arayüz [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* sınıf [Slide](../../slide)
* ad alanı [Aspose.Slides](../../slide)
* derleme [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Bir Thumbnail Image nesnesi döndürür.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | IRenderingOptions | Rendering seçenekleri. |

### Dönüş Değeri

Image nesnesi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| InvalidOperationException | notesCommentsLayouting.NotesPosition, NotesPositions.BottomFull değerini aldığında fırlatılır. |

### Ayrıca Bakınız

* arayüz [IImage](../../iimage)
* arayüz [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* sınıf [Slide](../../slide)
* ad alanı [Aspose.Slides](../../slide)
* derleme [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Özel ölçeklendirme ile bir Thumbnail Image nesnesi döndürür.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | IRenderingOptions | Rendering seçenekleri. |
| scaleX | Single | Bu Thumbnail'ı x ekseni yönünde ölçeklendirecek değer. |
| scaleY | Single | Bu Thumbnail'ı y ekseni yönünde ölçeklendirecek değer. |

### Dönüş Değeri

Bitmap nesneleri.

### İstisnalar

| istisna | koşul |
| --- | --- |
| InvalidOperationException | notesCommentsLayouting.NotesPosition, NotesPositions.BottomFull değerini aldığında fırlatılır. |

### Örnekler

Aşağıdaki örnek, notlar ve yorumlarla slaytları C# kullanarak görüntülere dönüştürmeyi gösterir.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Rendering seçeneklerini oluştur
    IRenderingOptions options = new RenderingOptions();
    // Notlar ve yorumlar yerleşim seçeneklerini oluştur
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Sayfadaki notların konumunu ayarlar
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Sayfadaki yorumların konumunu ayarlar
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Yorum çıkış alanının genişliğini ayarlar
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Yorum alanı için rengi ayarlar
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Render için yerleşim seçeneklerini ayarla
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Sunumdaki ilk slaytı bir IImage nesnesine dönüştürür
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Görüntüyü GIF formatında kaydeder
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### Ayrıca Bakınız

* arayüz [IImage](../../iimage)
* arayüz [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* sınıf [Slide](../../slide)
* ad alanı [Aspose.Slides](../../slide)
* derleme [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Belirtilen boyutta bir Thumbnail Image nesnesi döndürür.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | IRenderingOptions | Rendering seçenekleri. |
| imageSize | Size | Oluşturulacak görüntünün boyutu. |

### Dönüş Değeri

Image nesnesi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| InvalidOperationException | options.SlideLayoutOption, NotesCommentsLayoutOptions olduğunda ve NotesPosition özelliği NotesPositions.BottomFull değerini aldığında fırlatılır. |

### Ayrıca Bakınız

* arayüz [IImage](../../iimage)
* arayüz [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* sınıf [Slide](../../slide)
* ad alanı [Aspose.Slides](../../slide)
* derleme [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->