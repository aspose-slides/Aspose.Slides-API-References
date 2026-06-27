---
title: Save
second_title: Aspose.Sildes için .NET API Referansı
description: Bir sunumun tüm slaytlarını belirtilen formatta bir dosyaya kaydeder.
type: docs
weight: 390
url: /tr/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Belirtilen formatta bir dosyaya sunumun tüm slaytlarını kaydeder.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | String | Oluşturulan dosyanın yolu. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Belirtilen formatta bir akışa sunumun tüm slaytlarını kaydeder.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Çıktı akışı. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Belirtilen formatta bir akışa ve ek seçeneklerle sunumun tüm slaytlarını kaydeder.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Çıktı akışı. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |
| options | ISaveOptions | Ek format seçenekleri. |

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | Şifreli dosyayı Office 2007-2010 dışı bir formatta kaydetmeye çalışırsanız |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Sunumun tüm slaytlarını XAML işaretlemesini temsil eden bir dosya kümesine kaydeder.

```csharp
public void Save(IXamlOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | IXamlOptions | XAML format seçenekleri. |

### Examples

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### See Also

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Belirtilen sayfa numaralarını koruyarak bir dosyaya sunumun belirli slaytlarını kaydeder.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | String | Oluşturulan dosyanın yolu. |
| slides | Int32[] | 1’den başlayan slayt konumlarını içeren dizi. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | stream ya da slides parametresi null ise. |
| ArgumentOutOfRangeException | slides parametresi hatalı sayfa numaraları içeriyorsa. |
| InvalidOperationException | Desteklenmeyen bir SaveFormat kullanılırsa, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Belirtilen sayfa numaralarını koruyarak bir dosyaya sunumun belirli slaytlarını ek seçeneklerle kaydeder.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | String | Oluşturulan dosyanın yolu. |
| slides | Int32[] | 1’den başlayan slayt konumlarını içeren dizi. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |
| options | ISaveOptions | Ek format seçenekleri. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Belirtilen sayfa numaralarını koruyarak bir akışa sunumun belirli slaytlarını kaydeder.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Çıktı akışı. |
| slides | Int32[] | 1’den başlayan slayt konumlarını içeren dizi. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Belirtilen sayfa numaralarını koruyarak bir akışa sunumun belirli slaytlarını ek seçeneklerle kaydeder.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Çıktı akışı. |
| slides | Int32[] | 1’den başlayan slayt konumlarını içeren dizi. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |
| options | ISaveOptions | Ek format seçenekleri. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | stream ya da slides parametresi null ise. |
| ArgumentOutOfRangeException | slides parametresi hatalı sayfa numaraları içeriyorsa. |
| InvalidOperationException | Desteklenmeyen bir SaveFormat kullanılırsa, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Examples

Aşağıdaki örnek PowerPoint dosyasını PNG’ye dönüştürmeyi gösterir.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail().Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

Aşağıdaki örnek PowerPoint dosyasını özel boyutlarla PNG’ye dönüştürmeyi gösterir.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    float scaleX = 2f;
    float scaleY = 2f;
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(scaleX, scaleY).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

Aşağıdaki örnek PowerPoint dosyasını özel ebatlarla PNG’ye dönüştürmeyi gösterir.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    Size size = new Size(960, 720);
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(size).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

### See Also

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->