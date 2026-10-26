---
title: IPresentationInfo class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ipresentationinfo/
---
## IPresentationInfo sınıfı

Sunum dosyası hakkında bilgi

IPresentationInfo türü aşağıdaki üyeleri sağlar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`is_encrypted`](/slides/python-net/tr/aspose.slides/ipresentationinfo/is_encrypted/) | Bağlanmış sunum şifrelenmişse True, aksi takdirde False döndürür.<br/>            Yalnızca okunabilir **bool**. |
| [`is_password_protected`](/slides/python-net/tr/aspose.slides/ipresentationinfo/is_password_protected/) | Bağlanmış sunumun açılmak için bir şifreyle korunup korunmadığını gösteren bir değer alır. |
| [`is_write_protected`](/slides/python-net/tr/aspose.slides/ipresentationinfo/is_write_protected/) | Bağlanmış sunumun yazma korumalı olup olmadığını gösteren bir değer alır. |
| [`load_format`](/slides/python-net/tr/aspose.slides/ipresentationinfo/load_format/) | Bağlanmış sunumun formatını alır.<br/>            Yalnızca okunabilir [`LoadFormat`](/slides/python-net/tr/aspose.slides/loadformat). |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/tr/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | Bağlanmış sunumu akışa yazar. |
| [`write_binded_presentation(self, file)`](/slides/python-net/tr/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | Bağlanmış sunumu dosyaya yazar. |
| [`check_password(self, password)`](/slides/python-net/tr/aspose.slides/ipresentationinfo/check_password/#str) | Açma şifresiyle korunan bir sunum için şifrenin doğru olup olmadığını kontrol eder. |
| [`check_write_protection(self, password)`](/slides/python-net/tr/aspose.slides/ipresentationinfo/check_write_protection/#str) | Yazma korumalı bir sunum için değiştirme şifresinin doğru olup olmadığını kontrol eder. |
| [`read_document_properties(self)`](/slides/python-net/tr/aspose.slides/ipresentationinfo/read_document_properties/#) | Bağlanmış sunumun belge özelliklerini alır. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/tr/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | Bağlanmış sunumun özelliklerini günceller. |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)