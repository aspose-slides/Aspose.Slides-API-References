---
title: Save
second_title: Aspose.Sildes için .NET API Referansı
description: Sunumun tüm slaytlarını belirtilen formatta bir dosyaya kaydeder.
type: docs
weight: 380
url: /tr/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

Sunumun tüm slaytlarını belirtilen formatta bir dosyaya kaydeder.

```csharp
public void Save(string fname, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | String | Oluşturulan dosyanın yolu. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

Sunumun tüm slaytlarını belirtilen formatta bir akışa kaydeder.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Çıktı akışı. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

Sunumun tüm slaytlarını belirtilen formatta ve ek seçeneklerle bir dosyaya kaydeder.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | String | Oluşturulan dosyanın yolu. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |
| options | ISaveOptions | Ek format seçenekleri. |

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

Sunumun tüm slaytlarını belirtilen formatta ve ek seçeneklerle bir akışa kaydeder.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Çıktı akışı. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |
| options | ISaveOptions | Ek format seçenekleri. |

### İstisnalar

| İstisna | Koşul |
| --- | --- |
| NotSupportedException | Şifreli bir dosyayı Office 2007-2010 dışı bir formatta kaydetmeye çalışırsanız |

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

Belirtilen slaytları bir dosyaya belirtilen formatta kaydeder.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | String | Oluşturulan dosyanın yolu. |
| slides | Int32[] | 1’den başlayan slayt konumlarını içeren dizi. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |

### İstisnalar

| İstisna | Koşul |
| --- | --- |
| ArgumentNullException | stream veya slides parametresi null olduğunda. |
| ArgumentOutOfRangeException | slides parametresi hatalı sayfa numaraları içerdiğinde. |
| InvalidOperationException | desteklenmeyen bir SaveFormat kullanıldığında, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

Belirtilen slaytları bir dosyaya belirtilen formatta ve ek seçeneklerle kaydeder.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | String | Oluşturulan dosyanın yolu. |
| slides | Int32[] | 1’den başlayan slayt konumlarını içeren dizi. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |
| options | ISaveOptions | Ek format seçenekleri. |

### İstisnalar

| İstisna | Koşul |
| --- | --- |
| ArgumentNullException | stream veya slides parametresi null olduğunda. |
| ArgumentOutOfRangeException | slides parametresi hatalı sayfa numaraları içerdiğinde. |
| InvalidOperationException | desteklenmeyen bir SaveFormat kullanıldığında, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

Belirtilen slaytları bir akışa belirtilen formatta kaydeder.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Çıktı akışı. |
| slides | Int32[] | 1’den başlayan slayt konumlarını içeren dizi. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |

### İstisnalar

| İstisna | Koşul |
| --- | --- |
| ArgumentNullException | stream veya slides parametresi null olduğunda. |
| ArgumentOutOfRangeException | slides parametresi hatalı sayfa numaraları içerdiğinde. |
| InvalidOperationException | desteklenmeyen bir SaveFormat kullanıldığında, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

Belirtilen slaytları bir akışa belirtilen formatta ve ek seçeneklerle kaydeder.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Çıktı akışı. |
| slides | Int32[] | 1’den başlayan slayt konumlarını içeren dizi. |
| format | SaveFormat | Dışa aktarılan verinin formatı. |
| options | ISaveOptions | Ek format seçenekleri. |

### İstisnalar

| İstisna | Koşul |
| --- | --- |
| ArgumentNullException | stream veya slides parametresi null olduğunda. |
| ArgumentOutOfRangeException | slides parametresi hatalı sayfa numaraları içerdiğinde. |
| InvalidOperationException | desteklenmeyen bir SaveFormat kullanıldığında, ör. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### İlgili

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* arayüz [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

Sunumun tüm slaytlarını XAML işaretlemesini temsil eden bir dosya kümesine kaydeder.

```csharp
public void Save(IXamlOptions options)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | IXamlOptions | XAML formatı seçenekleri. |

### Örnekler

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### İlgili

* arayüz [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* arayüz [IPresentation](../../ipresentation)
* ad alanı [Aspose.Slides](../../ipresentation)
* derleme [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->