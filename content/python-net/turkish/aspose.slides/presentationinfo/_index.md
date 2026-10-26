---
title: PresentationInfo class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/presentationinfo/
---
## PresentationInfo sınıfı

Sunum dosyası hakkında bilgi

PresentationInfo türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_encrypted`](/slides/python-net/tr/aspose.slides/presentationinfo/is_encrypted/) | Bağlı sunum şifrelenmişse True, aksi takdirde False döndürür.<br/>            Salt okunur **bool**. |
| [`is_password_protected`](/slides/python-net/tr/aspose.slides/presentationinfo/is_password_protected/) | Bir bağlanmış sunumun açmak için şifreyle korunup korunmadığını gösteren bir değer döndürür. |
| [`is_write_protected`](/slides/python-net/tr/aspose.slides/presentationinfo/is_write_protected/) | Bir bağlanmış sunumun yazma korumalı olup olmadığını gösteren bir değer döndürür. |
| [`load_format`](/slides/python-net/tr/aspose.slides/presentationinfo/load_format/) | Bağlı sunumun biçimini döndürür.<br/>            Salt okunur [`LoadFormat`](/slides/python-net/tr/aspose.slides/loadformat). |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/tr/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | Bağlı sunumu akışa yazar. |
| [`write_binded_presentation(self, file)`](/slides/python-net/tr/aspose.slides/presentationinfo/write_binded_presentation/#str) | Bağlı sunumu dosyaya yazar. |
| [`check_password(self, password)`](/slides/python-net/tr/aspose.slides/presentationinfo/check_password/#str) | Açma şifresiyle korunmuş bir sunum için şifrenin doğru olup olmadığını kontrol eder. |
| [`check_write_protection(self, password)`](/slides/python-net/tr/aspose.slides/presentationinfo/check_write_protection/#str) | Yazma korumalı bir sunum için değiştirme şifresinin doğru olup olmadığını kontrol eder. |
| [`read_document_properties(self)`](/slides/python-net/tr/aspose.slides/presentationinfo/read_document_properties/#) | Bağlı sunumun belge özelliklerini döndürür. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/tr/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | Bağlı sunumun özelliklerini günceller. |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)