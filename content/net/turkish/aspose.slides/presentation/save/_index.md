---
title: Save
second_title: Aspose.Sildes için .NET API Referansı
description: Bir sunumun tüm slaytlarını belirtilen formatta bir dosyaya kaydeder.
type: docs
weight: 400
url: /tr/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

Bir sunumun tüm slaytlarını belirtilen formatta bir dosyaya kaydeder.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | String | Oluşturulan dosyanın yolu. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Bir sunumun tüm slaytlarını belirtilen formatta bir akışa kaydeder.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Çıktı akışı. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Bir sunumun tüm slaytlarını belirtilen formatta ve ek seçeneklerle bir akışa kaydeder.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Çıktı akışı. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |
| options | ISaveOptions | Ek format seçenekleri. |

### İstisnalar

| İstisna | koşul |
| --- | --- |
| NotSupportedException | Şifrelenmiş bir dosyayı Office 2007-2010 dışı bir formatta kaydetmeye çalışırsanız |

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Bir sunumun tüm slaytlarını XAML işaretlemesini temsil eden bir dosya setine kaydeder.

```csharp
public void Save(IXamlOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | IXamlOptions | XAML format seçenekleri. |

### Örnekler

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### İlgili

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Bir sunumun belirtilen slaytlarını sayfa numaralarını koruyarak belirtilen formatta bir dosyaya kaydeder.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | String | Oluşturulan dosyanın yolu. |
| slides | Int32[] | 1'den başlayan slayt konumlarını içeren dizi. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |

### İstisnalar

| İstisna | koşul |
| --- | --- |
| ArgumentNullException | Akış veya slaytlar parametresi null olduğunda. |
| ArgumentOutOfRangeException | Slaytlar parametresi hatalı sayfa numaraları içerdiğinde. |
| InvalidOperationException | Desteklenmeyen bir SaveFormat kullanıldığında, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Bir sunumun belirtilen slaytlarını sayfa numaralarını koruyarak belirtilen formatta bir dosyaya kaydeder.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | String | Oluşturulan dosyanın yolu. |
| slides | Int32[] | 1'den başlayan slayt konumlarını içeren dizi. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |
| options | ISaveOptions | Ek format seçenekleri. |

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Bir sunumun belirtilen slaytlarını sayfa numaralarını koruyarak belirtilen formatta bir akışa kaydeder.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Çıktı akışı. |
| slides | Int32[] | 1'den başlayan slayt konumlarını içeren dizi. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Bir sunumun belirtilen slaytlarını sayfa numaralarını koruyarak belirtilen formatta bir akışa kaydeder.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Çıktı akışı. |
| slides | Int32[] | 1'den başlayan slayt konumlarını içeren dizi. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |
| options | ISaveOptions | Ek format seçenekleri. |

### İstisnalar

| İstisna | koşul |
| --- | --- |
| ArgumentNullException | Akış veya slaytlar parametresi null olduğunda. |
| ArgumentOutOfRangeException | Slaytlar parametresi hatalı sayfa numaraları içerdiğinde. |
| InvalidOperationException | Desteklenmeyen bir SaveFormat kullanıldığında, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Örnekler

Aşağıdaki örnek, PowerPoint'i PNG'ye nasıl dönüştüreceğinizi gösterir.

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

Aşağıdaki örnek, PowerPoint'i özel boyutlarla PNG'ye nasıl dönüştüreceğinizi gösterir.

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

Aşağıdaki örnek, PowerPoint'i özel boyutta PNG'ye nasıl dönüştüreceğinizi gösterir.

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

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->