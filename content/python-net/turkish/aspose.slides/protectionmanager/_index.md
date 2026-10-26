---
title: ProtectionManager class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/protectionmanager/
---
## ProtectionManager sınıfı

Sunum parola koruma yönetimi.

ProtectionManager türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/tr/aspose.slides/protectionmanager/encrypt_document_properties/) | Bu özellik, sunum parola korumalı ise anlamlıdır.<br/>            Eğer true ise belge özellikleri sunum dosyasında şifrelenir.<br/>            Eğer false ise belge özellikleri halka açıktır ancak sunum şifrelenmiştir.<br/>            Okuma/Yazma **bool**. |
| [`is_encrypted`](/slides/python-net/tr/aspose.slides/protectionmanager/is_encrypted/) | Bu örneğin şifrelenip şifrelenmediğini gösteren bir değer alır.<br/>            Salt-okunur **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/tr/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Bu özellik, sunum dosyası parola korumalı ve bu dosyanın belge özellikleri halka açıksa anlamlıdır.<br/>            true değeri, yalnızca belge özelliklerinin bir parola kullanılmadan şifreli bir sunum dosyasından yüklendiği anlamına gelir.<br/>            false değeri, tüm şifreli sunumun doğru parola kullanılarak yüklendiği ve yalnızca belge özelliklerinin değil, tümünün yüklendiği anlamına gelir.<br/>            Sunum şifreli değilse özellik değeri her zaman false olur.<br/>            Şifreli bir dosyanın belge özellikleri halka açık değilse özellik değeri her zaman false olur.<br/>            Presentation.EncryptDocumentProperties true ise IsOnlyDocumentPropertiesLoaded özelliği her zaman false olur.<br/>            Salt-okunur **bool**. |
| [`is_write_protected`](/slides/python-net/tr/aspose.slides/protectionmanager/is_write_protected/) | Bu sunumun yazma korumalı olup olmadığını gösteren bir değer alır.<br/>            Salt-okunur **bool**. |
| [`encryption_password`](/slides/python-net/tr/aspose.slides/protectionmanager/encryption_password/) | Sunumu şifrelemek için kullanılan parolayı alır.<br/>            Salt-okunur **str**. |
| [`read_only_recommended`](/slides/python-net/tr/aspose.slides/protectionmanager/read_only_recommended/) | Salt-okunur önerisini alır veya ayarlar.<br/>            Okuma/Yazma **bool**. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/tr/aspose.slides/protectionmanager/encrypt/#str) | Belirtilen parola ile Sunumu şifreler. |
| [`remove_encryption(self)`](/slides/python-net/tr/aspose.slides/protectionmanager/remove_encryption/#) | Şifrelemeyi kaldırır. |
| [`set_write_protection(self, password)`](/slides/python-net/tr/aspose.slides/protectionmanager/set_write_protection/#str) | Belirtilen parola ile bu sunuma yazma koruması ayarlar. |
| [`remove_write_protection(self)`](/slides/python-net/tr/aspose.slides/protectionmanager/remove_write_protection/#) | Bu sunum için yazma korumasını kaldırır. |
| [`check_write_protection(self, password)`](/slides/python-net/tr/aspose.slides/protectionmanager/check_write_protection/#str) | Bir sunumun değiştirmek için parola korumalı olup olmadığını belirler. |

### Ayrıca bakınız
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)