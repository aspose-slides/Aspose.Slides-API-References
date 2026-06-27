---
title: AddFromHtml
second_title: Aspose.Sildes .NET için API Referansı
description: HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.
type: docs
weight: 70
url: /tr/aspose.slides/slidecollection/addfromhtml/
---
## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlText | String | Eklenecek HTML. |
| resolver | IExternalResourceResolver | Harici nesneleri almak için kullanılan bir geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yok sayılacaktır. |
| uri | String | Belirtilen HTML'nin bir URI'si. Göreceli bağlantıların çözülmesinde kullanılır. |

### Dönüş Değeri

Eklenen slaytlar.

### Ayrıca Bakınız

* arayüz [ISlide](../../islide)
* arayüz [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* sınıf [SlideCollection](../../slidecollection)
* ad alanı [Aspose.Slides](../../slidecollection)
* derleme [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlText | String | Eklenecek HTML. |

### Dönüş Değeri

Eklenen slaytlar

### Ayrıca Bakınız

* arayüz [ISlide](../../islide)
* sınıf [SlideCollection](../../slidecollection)
* ad alanı [Aspose.Slides](../../slidecollection)
* derleme [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlReader | TextReader | HTML dosyasının kaynağı olarak kullanılacak TextReader nesnesi. |
| resolver | IExternalResourceResolver | Harici nesneleri almak için kullanılan bir geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yok sayılacaktır. |
| uri | String | Belirtilen HTML'nin bir URI'si. Göreceli bağlantıların çözülmesinde kullanılır. |

### Dönüş Değeri

Eklenen slaytlar.

### Ayrıca Bakınız

* arayüz [ISlide](../../islide)
* arayüz [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* sınıf [SlideCollection](../../slidecollection)
* ad alanı [Aspose.Slides](../../slidecollection)
* derleme [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlReader | TextReader | HTML dosyasının kaynağı olarak kullanılacak TextReader nesnesi. |

### Dönüş Değeri

Eklenen slaytlar

### Ayrıca Bakınız

* arayüz [ISlide](../../islide)
* sınıf [SlideCollection](../../slidecollection)
* ad alanı [Aspose.Slides](../../slidecollection)
* derleme [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlStream | Stream | HTML dosyasının kaynağı olarak kullanılacak Stream nesnesi. |
| resolver | IExternalResourceResolver | Harici nesneleri almak için kullanılan bir geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yok sayılacaktır. |
| uri | String | Belirtilen HTML'nin bir URI'si. Göreceli bağlantıların çözülmesinde kullanılır. |

### Dönüş Değeri

Eklenen slaytlar.

### Ayrıca Bakınız

* arayüz [ISlide](../../islide)
* arayüz [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* sınıf [SlideCollection](../../slidecollection)
* ad alanı [Aspose.Slides](../../slidecollection)
* derleme [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlStream | Stream | HTML dosyasının kaynağı olarak kullanılacak Stream nesnesi. |

### Dönüş Değeri

Eklenen slaytlar

### Örnekler

```csharp
[C#]
// Presentation sınıfının bir örneğini oluştur.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
		// AddFromHtml yöntemini çağır ve HTML dosyasını geçir.
        presentation.Slides.AddFromHtml(htmlStream);
    }
	// Save yöntemini kullanarak dosyayı PowerPoint belgesi olarak kaydet.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### Ayrıca Bakınız

* arayüz [ISlide](../../islide)
* sınıf [SlideCollection](../../slidecollection)
* ad alanı [Aspose.Slides](../../slidecollection)
* derleme [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->