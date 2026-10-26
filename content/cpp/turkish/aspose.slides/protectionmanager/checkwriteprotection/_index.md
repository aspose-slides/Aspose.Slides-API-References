---
title: CheckWriteProtection()
second_title: Aspose.Slides için C++ API Referansı
description: Bir sunumun değiştirilmesi için şifre korumalı olup olmadığını belirler.
type: docs
weight: 157
url: /tr/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) yöntemi


Bir sunumun değiştirilmesi için parola korumalı olup olmadığını belirler.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Kontrol için kullanılan parola. |

### Dönüş Değeri

True ise şifre geçerlidir; aksi takdirde false.
## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. Bu yöntemi çağırmadan önce [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) özelliğini kontrol etmelisiniz.
1. Şifre null veya boş olduğunda, bu yöntem false döndürür.


## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [ProtectionManager](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)