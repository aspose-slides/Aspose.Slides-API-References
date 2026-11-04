---
title: Save
second_title: Aspose.Sildes için .NET API Referansı
description: Bir sunumun tüm slaytlarını belirtilen formatta bir dosyaya kaydeder.
type: docs
weight: 390
url: /tr/aspose.slides/ipresentation/save/
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

### Ayrıca Bakınız

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

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

### Ayrıca Bakınız

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Bir sunumun tüm slaytlarını belirtilen formatta ve ek seçeneklerle bir dosyaya kaydeder.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | String | Oluşturulan dosyanın yolu. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |
| options | ISaveOptions | Ek format seçenekleri. |

### Ayrıca Bakınız

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

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
| NotSupportedException | Şifreli bir dosyayı Office 2007-2010 dışındaki bir formatta kaydetmeye çalışırsanız |

### Ayrıca Bakınız

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Bir sunumun belirtilen slaytlarını belirtilen formatta bir dosyaya kaydeder.

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
| ArgumentNullException | Akış veya slayt parametresi null olduğunda. |
| ArgumentOutOfRangeException | Slayt parametresi hatalı sayfa numaraları içerdiğinde. |
| InvalidOperationException | Desteklenmeyen bir SaveFormat kullanıldığında, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Ayrıca Bakınız

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Bir sunumun belirtilen slaytlarını belirtilen formatta bir dosyaya kaydeder.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | String | Oluşturulan dosyanın yolu. |
| slides | Int32[] | 1'den başlayan slayt konumlarını içeren dizi. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |
| options | ISaveOptions | Ek format seçenekleri. |

### İstisnalar

| İstisna | koşul |
| --- | --- |
| ArgumentNullException | Akış veya slayt parametresi null olduğunda. |
| ArgumentOutOfRangeException | Slayt parametresi hatalı sayfa numaraları içerdiğinde. |
| InvalidOperationException | Desteklenmeyen bir SaveFormat kullanıldığında, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Ayrıca Bakınız

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Bir sunumun belirtilen slaytlarını belirtilen formatta bir akışa kaydeder.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Çıktı akışı. |
| slides | Int32[] | 1'den başlayan slayt konumlarını içeren dizi. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |

### İstisnalar

| İstisna | koşul |
| --- | --- |
| ArgumentNullException | Akış veya slayt parametresi null olduğunda. |
| ArgumentOutOfRangeException | Slayt parametresi hatalı sayfa numaraları içerdiğinde. |
| InvalidOperationException | Desteklenmeyen bir SaveFormat kullanıldığında, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Ayrıca Bakınız

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Bir sunumun belirtilen slaytlarını belirtilen formatta ve ek seçeneklerle bir akışa kaydeder.

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
| ArgumentNullException | Akış veya slayt parametresi null olduğunda. |
| ArgumentOutOfRangeException | Slayt parametresi hatalı sayfa numaraları içerdiğinde. |
| InvalidOperationException | Desteklenmeyen bir SaveFormat kullanıldığında, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### Ayrıca Bakınız

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Bir sunumun tüm slaytlarını XAML işaretlemesini temsil eden bir dosya kümesine kaydeder.

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

### Ayrıca Bakınız

* arayüz [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->