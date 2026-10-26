---
title: set_HandleRepeatedSpaces()
second_title: Aspose.Slides for C++ API Referansı
description: Markdown dışa aktarma sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirtir.
type: docs
weight: 248
url: /tr/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) metot

Markdown dışa aktarma sırasında yinelenen normal boşluk karakterlerinin nasıl işleneceğini belirler.

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## Açıklamalar

Bu özellik, art arda gelen boşlukların aşağıdakilerden biri olup olmadığını tanımlar:
* normal boşluk karakterleri olarak korunması,
* normal boşluklarla kırılmayan boşluk varlıkları (**&nbsp;**) arasında değiştirilmesi,
* ya da tamamen (ilk boşluktan sonra) **&nbsp;** ile değiştirilerek Markdown çıktısında görsel hizalamanın korunması.

Varsayılan değer [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/)'dir.

## Bakınız

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Sınıf [MarkdownSaveOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)