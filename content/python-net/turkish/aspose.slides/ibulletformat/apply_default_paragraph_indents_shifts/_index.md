---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Varsayılan sıfır olmayan kaydırmaları, maddeler etkin olduğunda (PowerPoint'in paragraf maddeleri/numaralandırmasını etkinleştirdiğinde yaptığı gibi) etkili paragraf **Indent** ve **MarginLeft** için ayarlar. Maddeler devre dışı bırakıldığında sadece paragraf **Indent** ve **MarginLeft** sıfırlanır (PowerPoint'in paragraf maddeleri/numaralandırmasını devre dışı bıraktığında yaptığı gibi). Girinti kaydırmaları, mevcut madde bağlamına göre uygulanır – **IBulletFormat.Type**, **.NumberedBulletStyle** ve ilk bölümün **FontHeight** değerine göre. Sıfır olmayan girinti kaydırmaları, mevcut paragrafın etkili **Indent** ve **MarginLeft** değerlerine uygulanır (sonuç değerleri yerel değerler olur).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Bu yöntemi çağırmak önemsizdir ve aşağıdaki durumlarda **System.InvalidOperationException** hatasını fırlatır:<br/>            eğer üst biçimlendirilmiş nesne bir paragraf değilse (örneğin ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() çağrısı bir istisna fırlatır);<br/>            veya paragraf, herhangi bir ITextFrame.Paragraphs koleksiyonuna eklenmemişse (önce ekleyin); |



### Ayrıca Bakınız
* sınıf [`IBulletFormat`](/slides/python-net/tr/aspose.slides/ibulletformat)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)