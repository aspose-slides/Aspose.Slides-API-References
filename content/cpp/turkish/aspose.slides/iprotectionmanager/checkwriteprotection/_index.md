---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API Referansı
description: Bir sunumun değiştirilmesi için şifre korumalı olup olmadığını belirler.
type: docs
weight: 157
url: /tr/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) metodu


Bir sunumun değiştirilmesi için şifre korumalı olup olmadığını belirler.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Kontrol için kullanılan şifre. |

### Dönüş Değeri

Şifre geçerliyse doğru; aksi takdirde yanlış.
## Açıklamalar



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. Bu metodu çağırmadan önce [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) özelliğini kontrol etmelisiniz.
1. Şifre null veya boş olduğunda, bu metot false döner.


## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [IProtectionManager](../)
* İsim alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)