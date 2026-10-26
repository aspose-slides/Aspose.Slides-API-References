---
title: ProtectionManager
second_title: Aspose.Slides için Java API Referansı
description: Sunum şifre koruması yönetimi.
type: docs
url: /tr/com.aspose.slides/protectionmanager/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Sunum şifre koruması yönetimi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Sunum şifre korumalıysa bu özellik anlamlıdır. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Sunum şifre korumalıysa bu özellik anlamlıdır. |
| [isEncrypted()](#isEncrypted--) | Bu örneğin şifrelenip şifrelenmediğini gösteren bir değeri alır. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Sunum dosyası şifre korumalıysa ve bu dosyanın belge özellikleri herkese açıksa bu özellik anlamlıdır. |
| [isWriteProtected()](#isWriteProtected--) | Bu sunumun yazma korumalı olup olmadığını gösteren bir değeri alır. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Belirtilen şifreyle Sunumu şifreler. |
| [removeEncryption()](#removeEncryption--) | Şifrelemeyi kaldırır. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Bu sunum için belirtilen şifreyle yazma koruması ayarlar. |
| [removeWriteProtection()](#removeWriteProtection--) | Bu sunum için yazma korumasını kaldırır. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Bir sunumun değiştirme amacıyla şifre korumalı olup olmadığını belirler. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Sunum şifrelemesi için kullanılan şifreyi alır. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Salt-okunur önerisini alır veya ayarlar. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Salt-okunur önerisini alır veya ayarlar. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```


Bu özellik, sunum şifre korumalıysa anlamlıdır. Doğru ise belge özellikleri sunum dosyasında şifrelenir. Yanlış ise belge özellikleri şifrelenmiş sunum dosyası şifrelenirken herkese açıktır. Okuma/yazma boolean.

**Döndürür:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```


Bu özellik, sunum şifre korumalıysa anlamlıdır. Doğru ise belge özellikleri sunum dosyasında şifrelenir. Yanlış ise belge özellikleri şifrelenmiş sunum dosyası şifrelenirken herkese açıktır. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Bu örneğin şifrelenip şifrelenmediğini gösteren bir değeri alır. Salt-okunur boolean.

Değer: Sunum şifreli bir dosyadan yüklendiyse veya \#encrypt(String).encrypt(String) yöntemi çağrıldıysa true; aksi takdirde false.

**Döndürür:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```


Bu özellik, sunum dosyası şifre korumalıysa ve bu dosyanın belge özellikleri herkese açıksa anlamlıdır. True değeri, şifreli bir sunum dosyasından yalnızca belge özelliklerinin şifre kullanılmadan yüklendiğini gösterir. False değeri, tüm şifreli sunumun doğru şifre kullanılarak yüklendiğini gösterir; yalnızca belge özellikleri yüklenmez. Sunum şifreli değilse özellik değeri her zaman false olur. Şifreli bir dosyanın belge özellikleri herkese açık değilse özellik değeri her zaman false olur. Presentation.EncryptDocumentProperties true ise IsOnlyDocumentPropertiesLoaded özelliği her zaman false olur. Salt-okunur boolean.

**Döndürür:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```


Bu sunumun yazma korumalı olup olmadığını gösteren bir değeri alır. Salt-okunur boolean.

**Döndürür:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```


Belirtilen şifreyle Sunumu şifreler.

--------------------

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Şifre. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```


Şifrelemeyi kaldırır.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```


Bu sunum için belirtilen şifreyle yazma koruması ayarlar.

--------------------

> ```
> The following sample code shows you how to set a write protection to a presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | java.lang.String | Şifre. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```


Bu sunum için yazma korumasını kaldırır.

--------------------

> ```
> Bu örnek kod, bir PowerPoint Sunumundan yazma korumasını nasıl kaldıracağınızı gösterir.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```


Bir sunumun değiştirme amacıyla şifre korumalı olup olmadığını belirler.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | java.lang.String | Kontrol için şifre.

1. Bu yöntemi çağırmadan önce (\#isWriteProtected.isWriteProtected) özelliğini kontrol etmelisiniz. 2. Şifre null veya boş ise bu yöntem false döndürür. |

**Döndürür:**
boolean - Şifre geçerliyse true; aksi takdirde false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```


Sunum şifrelemesi için kullanılan şifreyi alır. Salt-okunur String.

**Döndürür:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```


Salt-okunur önerisini alır veya ayarlar. Okuma/yazma boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```


Salt-okunur önerisini alır veya ayarlar. Okuma/yazma boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |