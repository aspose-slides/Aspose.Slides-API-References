---
title: ProtectionManager
second_title: Aspose.Slides for Android via Java API Referansı
description: Sunum şifre koruma yönetimi.
type: docs
url: /tr/com.aspose.slides/protectionmanager/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Sunum şifre koruma yönetimi.
## Yöntemler

| Method | Description |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Bu özellik, sunum şifre korumalıysa anlamlıdır. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Bu özellik, sunum şifre korumalıysa anlamlıdır. |
| [isEncrypted()](#isEncrypted--) | Bu örneğin şifrelenip şifrelenmediğini gösteren bir değeri alır. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Bu özellik, sunum dosyası şifre korumalıysa ve bu dosyanın belge özellikleri herkese açıksa anlamlıdır. |
| [isWriteProtected()](#isWriteProtected--) | Bu sunumun yazma korumalı olup olmadığını gösteren bir değeri alır. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Sunumu belirtilen şifreyle şifreler. |
| [removeEncryption()](#removeEncryption--) | Şifrelemeyi kaldırır. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Bu sunum için belirtilen şifreyle yazma koruması ayarlar. |
| [removeWriteProtection()](#removeWriteProtection--) | Bu sunum için yazma korumasını kaldırır. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Bir sunumun değiştirilmek için şifre korumalı olup olmadığını belirler. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Sunum şifrelemesi için kullanılan şifreyi alır. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Yalnızca okunur önerisini alır veya ayarlar. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Yalnızca okunur önerisini alır veya ayarlar. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Bu özellik, sunum şifre korumalıysa anlamlıdır. Doğru ise belge özellikleri sunum dosyasında şifrelenir. Yanlış ise belge özellikleri sunum şifreli iken herkese açıktır. Okunabilir/yazılabilir boolean.

**Döndürür:**  
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Bu özellik, sunum şifre korumalıysa anlamlıdır. Doğru ise belge özellikleri sunum dosasında şifrelenir. Yanlış ise belge özellikleri sunum şifreli iken herkese açıktır. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Bu örneğin şifrelenip şifrelenmediğini gösteren bir değeri alır. Yalnızca okunur boolean.

Değer: Sunum şifreli bir dosyadan yüklendiyse veya \#encrypt(String).encrypt(String) yöntemi çağrıldıysa true; aksi takdirde false.

**Döndürür:**  
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Bu özellik, sunum dosyası şifre korumalıysa ve bu dosyanın belge özellikleri herkese açıksa anlamlıdır. True değeri, şifreli bir sunum dosyasından yalnızca belge özelliklerinin, şifre kullanılmadan yüklendiğini gösterir. False değeri, doğru şifre kullanılarak tüm şifreli sunumun yüklendiğini, yalnızca belge özelliklerinin değil, tümünün yüklendiğini gösterir. Sunum şifreli değilse özellik değeri her zaman false olur. Şifreli bir dosyanın belge özellikleri herkese açık değilse özellik değeri her zaman false olur. Presentation.EncryptDocumentProperties true ise IsOnlyDocumentPropertiesLoaded özelliği değeri her zaman false olur. Yalnızca okunur boolean.

**Döndürür:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Bu sunumun yazma korumalı olup olmadığını gösteren bir değeri alır. Yalnızca okunur boolean.

**Döndürür:**  
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Sunumu belirtilen şifreyle şifreler.

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
> This sample code shows you how to remove the write protection from a PowerPoint Presentation.
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

Bir sunumun değiştirilmek için şifre korumalı olup olmadığını belirler.

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

1. Bu yöntemi çağırmadan önce (\#isWriteProtected.isWriteProtected) özelliğini kontrol etmelisiniz. 2. Şifre null ya da boş olduğunda, bu yöntem false döndürür. |

**Döndürür:**  
boolean - Şifre geçerliyse true; aksi takdirde false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Sunum şifrelemesi için kullanılan şifreyi alır. Yalnızca okunur String.

**Döndürür:**  
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Yalnızca okunur önerisini alır veya ayarlar. Okunabilir/yazılabilir boolean.

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

Yalnızca okunur önerisini alır veya ayarlar. Okunabilir/yazılabilir boolean.

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