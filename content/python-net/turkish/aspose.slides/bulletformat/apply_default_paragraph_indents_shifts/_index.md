---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
İşaretlemeler etkin olduğunda (PowerPoint'te paragraf işaretlemeleri/numaralandırması etkinleştirildiğinde olduğu gibi) etkili paragraf Indent ve MarginLeft için varsayılan sıfır olmayan kaydırmalar ayarlar. İşaretlemeler devre dışı bırakıldığında yalnızca paragraf Indent ve MarginLeft'i sıfırlar (PowerPoint'te paragraf işaretlemeleri/numaralandırması devre dışı bırakıldığında olduğu gibi). Kaydırma değerleri mevcut işaretleme bağlamına - IBulletFormat.Type, .NumberedBulletStyle ve ilk bölümün FontHeight değerine göre uygulanır. Sıfır olmayan kaydırmalar mevcut paragrafın etkili Indent ve MarginLeft'ine uygulanır (sonuç değerlerinin yerel değerler olmasını sağlar).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Bu yöntemi çağırmak önemsizdir ve aşağıdaki durumlarda **System.InvalidOperationException** hatası fırlatır:<br/>            ebeveyn biçimlendirilmiş nesne bir paragraf değilse (örnek olarak ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() çağrısı bir istisna fırlatır);<br/>            veya paragraf herhangi bir ITextFrame.Paragraphs koleksiyonuna eklenmemişse (önce ekleyin); |



### Ayrıca Bakınız
* sınıf [`BulletFormat`](/slides/python-net/tr/aspose.slides/bulletformat)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)