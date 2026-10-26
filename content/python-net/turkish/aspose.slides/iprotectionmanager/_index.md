---
title: IProtectionManager class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iprotectionmanager/
---
## IProtectionManager sınıfı

Sunum parola koruma yönetimi.

IProtectionManager türü aşağıdaki üyeleri ortaya çıkarır:

## Özellikler

| Property | Description |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/tr/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Bu özellik, sunum parola korumalıysa anlamlıdır.<br/>If true then document properties is encrypted in presentation file.<br/>If false then document properties is public while presentation is encrypted.<br/>Okuma/Yazma **bool**. |
| [`is_encrypted`](/slides/python-net/tr/aspose.slides/iprotectionmanager/is_encrypted/) | Gets a value indicating whether this instance is encrypted.<br/>Salt Okunur **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/tr/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Bu özellik, sunum dosyası parola korumalı ve bu dosyanın belge özellikleri halka açıksa anlamlıdır.<br/>Value of true means that only document properties are loaded from an encrypted presentation file without use of password.<br/>Value of false means that entire encrypted presentation is loaded with use of right password, not only document properties are loaded.<br/>If presentation isn’t encrypted then property value is always false.<br/>If document properties of an encrypted file aren’t public then property value is always false.<br/>If PresentationEx.EncryptDocumentProperties is true than IsOnlyDocumentPropertiesLoaded property value is always false.<br/>Salt Okunur **bool**. |
| [`is_write_protected`](/slides/python-net/tr/aspose.slides/iprotectionmanager/is_write_protected/) | Gets a value indicating whether this presentation is write protected.<br/>Salt Okunur **bool**. |
| [`encryption_password`](/slides/python-net/tr/aspose.slides/iprotectionmanager/encryption_password/) | Returns encryption password.<br/>Salt Okunur **str**. |
| [`read_only_recommended`](/slides/python-net/tr/aspose.slides/iprotectionmanager/read_only_recommended/) | Gets or sets read-only recommendation.<br/>Okuma/Yazma **bool**. |

## Yöntemler

| Method | Description |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/tr/aspose.slides/iprotectionmanager/encrypt/#str) | Belirtilen parola ile Presentation şifrelenir. |
| [`remove_encryption(self)`](/slides/python-net/tr/aspose.slides/iprotectionmanager/remove_encryption/#) | Şifrelemeyi kaldırır. |
| [`set_write_protection(self, password)`](/slides/python-net/tr/aspose.slides/iprotectionmanager/set_write_protection/#str) | Belirtilen parola ile bu presentation için yazma koruması ayarlar. |
| [`remove_write_protection(self)`](/slides/python-net/tr/aspose.slides/iprotectionmanager/remove_write_protection/#) | Bu presentation için yazma korumasını kaldırır. |
| [`check_write_protection(self, password)`](/slides/python-net/tr/aspose.slides/iprotectionmanager/check_write_protection/#str) | Bir presentation'ın değişiklik yapılmak üzere parola korumalı olup olmadığını belirler. |


### Ayrıca Bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)