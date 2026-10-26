---
title: IProtectionManager
second_title: Aspose.Slides for Android via Java API Reference
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
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Bu özellik, sunum şifreyle korunuyorsa anlamlıdır. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Bu özellik, sunum şifreyle korunuyorsa anlamlıdır. |
| [isEncrypted()](#isEncrypted--) | Bu örneğin şifrelenip şifrelenmediğini gösteren bir değer alır. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Bu özellik, sunum dosyası şifre korumalı ve bu dosyanın belge özellikleri herkese açık ise anlamlıdır. |
| [isWriteProtected()](#isWriteProtected--) | Bu sunumun yazma korumalı olup olmadığını gösteren bir değer alır. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Şifreleme parolasını döndürür. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Salt-okunur önerisini alır veya ayarlar. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Salt-okunur önerisini alır veya ayarlar. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Sunumu belirtilen parolayla şifreler. |
| [removeEncryption()](#removeEncryption--) | Şifrelemeyi kaldırır. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Bu sunum için belirtilen parolayla yazma koruması ayarlar. |
| [removeWriteProtection()](#removeWriteProtection--) | Bu sunuma ait yazma korumasını kaldırır. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Bir sunumun değiştirmek için şifre korumalı olup olmadığını belirler. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```


Bu özellik, sunum şifreyle korunuyorsa anlamlıdır. Eğer doğru ise belge özellikleri sunum dosyasında şifrelenir. Yanlış ise belge özellikleri herkese açıkken sunum şifrelenir. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```


Bu özellik, sunum şifreyle korunuyorsa anlamlıdır. Eğer doğru ise belge özellikleri sunum dosyasında şifrelenir. Yanlış ise belge özellikleri herkese açıkken sunum şifrelenir. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


Bu örneğin şifrelenip şifrelenmediğini gösteren bir değer alır. Salt-okunur boolean.

Değer: true ise sunum şifreli bir dosyadan yüklendi veya \#encrypt(String).encrypt(String) yöntemi çağrıldı; aksi takdirde false.

**Döndürür:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```


Bu özellik, sunum dosyası şifre korumalı ve bu dosyanın belge özellikleri herkese açık ise anlamlıdır. true değeri, şifreli bir sunum dosyasından yalnızca belge özelliklerinin, şifre kullanılmadan yüklendiğini gösterir. false değeri, doğru şifreyle tüm şifreli sunumun yüklendiğini, yalnızca belge özelliklerinin değil, tamamının yüklendiğini gösterir. Sunum şifreli değilse özellik değeri her zaman false olur. Şifreli bir dosyanın belge özellikleri herkese açık değilse özellik değeri her zaman false olur. PresentationEx.EncryptDocumentProperties true ise IsOnlyDocumentPropertiesLoaded özelliği her zaman false olur. Salt-okunur boolean.

**Döndürür:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```


Bu sunumun yazma korumalı olup olmadığını gösteren bir değer alır. Salt-okunur boolean.

**Döndürür:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```


Şifreleme parolasını döndürür. Salt-okunur String.

**Döndürür:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```


Salt-okunur önerisini alır veya ayarlar. Okunabilir/yazılabilir boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  ```


**Döndürür:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```


Salt-okunur önerisini alır veya ayarlar. Okunabilir/yazılabilir boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```


Sunumu belirtilen parolayla şifreler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Parola. |

### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```


Şifrelemeyi kaldırır.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```


Bu sunum için belirtilen parolayla yazma koruması ayarlar.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | Parola. |

### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```


Bu sunuma ait yazma korumasını kaldırır.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```


Bir sunumun değiştirmek için şifre korumalı olup olmadığını belirler.

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
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | Kontrol için şifre.

--------------------

1. Bu yöntemi çağırmadan önce (\#isWriteProtected.isWriteProtected) özelliğini kontrol etmelisiniz. 2. Parola null veya boş olduğunda bu yöntem false döndürür. |

**Döndürür:**
boolean - Parola geçerliyse true; aksi takdirde false.