---
title: DigitalSignature class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/digitalsignature/
---
## DigitalSignature sınıfı

Imzalı dosyada dijital imza.

DigitalSignature türü aşağıdaki üyeleri ortaya koyar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/tr/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | Belirtilen sertifika ile yeni bir DigitalSignature nesnesi oluşturur. |
| [`__init__(self, file_path, password)`](/slides/python-net/tr/aspose.slides/digitalsignature/__init__/#str-str) | Belirtilen sertifika dosyası yolu ve parola ile yeni bir DigitalSignature nesnesi oluşturur. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`certificate`](/slides/python-net/tr/aspose.slides/digitalsignature/certificate/) | Belgeyi imzalamak için kullanılan sertifika nesnesi.<br/>            Salt-okunur **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/tr/aspose.slides/digitalsignature/is_valid/) | Bu dijital imza geçerli ve belge değiştirilmemişse, bu değer true olacaktır.<br/>            Salt-okunur **bool**. |
| [`sign_time`](/slides/python-net/tr/aspose.slides/digitalsignature/sign_time/) | Belgenin imzalandığı zaman.<br/>            Salt-okunur **System.DateTime**. |
| [`comments`](/slides/python-net/tr/aspose.slides/digitalsignature/comments/) | İmzanın amacı.<br/>            Okunur-yazılabilir **str**. |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)