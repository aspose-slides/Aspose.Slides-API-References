---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
description: Presentation password protection management.
type: docs
url: /tr/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Sunum şifre koruması yönetimi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Bu özellik, sunum şifre korumalıysa anlamlıdır. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Bu özellik, sunum şifre korumalıysa anlamlıdır. |
| [isEncrypted()](#isEncrypted--) | Bu örnek şifrelenmiş mi olduğunu gösteren bir değer alır. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Bu özellik, sunum dosyası şifre korumalıysa ve bu dosyanın belge özellikleri herkese açıksa anlamlıdır. |
| [isWriteProtected()](#isWriteProtected--) | Bu sunumun yazma korumalı olup olmadığını gösteren bir değer alır. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Şifreleme şifresini döndürür. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Yalnızca okunabilir önerisini alır veya ayarlar. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Yalnızca okunabilir önerisini alır veya ayarlar. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Sunumu belirtilen şifre ile şifreler. |
| [removeEncryption()](#removeEncryption--) | Şifrelemeyi kaldırır. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Bu sunum için belirtilen şifreyle yazma koruması ayarlar. |
| [removeWriteProtection()](#removeWriteProtection--) | Bu sunumun yazma korumasını kaldırır. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Bir sunumun değiştirilmek için şifre korumalı olup olmadığını belirler. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Bu özellik, sunum şifre korumalıysa anlamlıdır. True ise belge özellikleri sunum dosasında şifrelenir. False ise belge özellikleri, sunum şifreli iken herkese açıktır. Okunabilir/yazılabilir boolean.

**Döndürür:**  
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Bu özellik, sunum şifre korumalıysa anlamlıdır. True ise belge özellikleri sunum dosasında şifrelenir. False ise belge özellikleri, sunum şifreli iken herkese açıktır. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Bu örnek şifrelenmiş mi olduğunu gösteren bir değer alır. Yalnızca okunabilir boolean.

Değer: true eğer sunum şifreli dosyadan yüklendiyse veya \#encrypt(String).encrypt(String) yöntemi çağrıldıysa; aksi takdirde false.

**Döndürür:**  
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Bu özellik, sunum dosyası şifre korumalıysa ve bu dosyanın belge özellikleri herkese açıksa anlamlıdır. true değeri, şifreli bir sunum dosyasından sadece belge özelliklerinin şifre kullanılmadan yüklendiği anlamına gelir. false değeri, bütün şifreli sunumun doğru şifre kullanılarak yüklendiği ve sadece belge özelliklerinin yüklenmediği anlamına gelir. Sunum şifreli değilse özellik değeri her zaman false olur. Şifreli bir dosyanın belge özellikleri herkese açık değilse özellik değeri her zaman false olur. PresentationEx.EncryptDocumentProperties true ise IsOnlyDocumentPropertiesLoaded özellik değeri her zaman false olur. Yalnızca okunabilir boolean.

**Döndürür:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Bu sunumun yazma korumalı olup olmadığını gösteren bir değer alır. Yalnızca okunabilir boolean.

**Döndürür:**  
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Şifreleme şifresini döndürür. Yalnızca okunabilir String.

**Döndürür:**  
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Yalnızca okunabilir önerisini alır veya ayarlar. Okunabilir/yazılabilir boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Döndürür:**  
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Yalnızca okunabilir önerisini alır veya ayarlar. Okunabilir/yazılabilir boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

Sunumu belirtilen şifre ile şifreler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Şifre. |
### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

Şifrelemeyi kaldırır.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

Bu sunum için belirtilen şifreyle yazma koruması ayarlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| password | java.lang.String | Şifre. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Bu sunumun yazma korumasını kaldırır.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
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
| password | java.lang.String | Kontrol için şifre. |

1. Bu yöntemi çağırmadan önce (\#isWriteProtected.isWriteProtected) özelliğini kontrol etmelisiniz. 2. Şifre null veya boş olduğunda, bu yöntem false döndürür. |

**Döndürür:**  
boolean - True şifre geçerliyse; aksi takdirde false.