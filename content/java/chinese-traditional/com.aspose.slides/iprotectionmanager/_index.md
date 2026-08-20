---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
description: Presentation password protection management.
type: docs
url: /zh-hant/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Presentation password protection management.
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | 如果簡報受密碼保護，此屬性才有意義。 |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | 如果簡報受密碼保護，此屬性才有意義。 |
| [isEncrypted()](#isEncrypted--) | 取得一個值，指示此實例是否已加密。 |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | 如果簡報檔案受密碼保護且此檔案的文件屬性為公開，則此屬性有意義。 |
| [isWriteProtected()](#isWriteProtected--) | 取得一個值，指示此簡報是否受寫入保護。 |
| [getEncryptionPassword()](#getEncryptionPassword--) | 返回加密密碼。 |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | 取得或設定唯讀建議。 |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | 取得或設定唯讀建議。 |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | 使用指定的密碼加密簡報。 |
| [removeEncryption()](#removeEncryption--) | 移除加密。 |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | 使用指定的密碼為此簡報設定寫入保護。 |
| [removeWriteProtection()](#removeWriteProtection--) | 移除此簡報的寫入保護。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 判斷簡報是否受密碼保護以供修改。 |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```


如果簡報受密碼保護，此屬性才有意義。若為 true，則文件屬性在簡報檔案中被加密。若為 false，則文件屬性在簡報加密的同時保持公開。可讀寫布林值。

**返回:**  
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```


如果簡報受密碼保護，此屬性才有意義。若為 true，則文件屬性在簡報檔案中被加密。若為 false，則文件屬性在簡報加密的同時保持公開。可讀寫布林值。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


取得一個值，指示此實例是否已加密。唯讀布林值。

值：若簡報是從加密檔案載入或呼叫了 \#encrypt(String).encrypt(String) 方法，則為 true；否則為 false。

**返回:**  
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```


如果簡報檔案受密碼保護且此檔案的文件屬性為公開，則此屬性有意義。值為 true 表示僅從加密的簡報檔案中載入文件屬性而未使用密碼。值為 false 表示使用正確的密碼載入整個加密的簡報，而不僅載入文件屬性。若簡報未加密，屬性值始終為 false。若加密檔案的文件屬性不是公開，屬性值亦始終為 false。若 PresentationEx.EncryptDocumentProperties 為 true，則 IsOnlyDocumentPropertiesLoaded 屬性值始終為 false。唯讀布林值。

**返回:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```


取得一個值，指示此簡報是否受寫入保護。唯讀布林值。

**返回:**  
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```


返回加密密碼。唯讀 String。

**返回:**  
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```


取得或設定唯讀建議。可讀寫布林值。

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```

**返回:**  
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```


取得或設定唯讀建議。可讀寫布林值。

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```


使用指定的密碼加密簡報。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| encryptionPassword | java.lang.String | 密碼。 |

### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```


移除加密。

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```


使用指定的密碼為此簡報設定寫入保護。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| password | java.lang.String | 密碼。 |

### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```


移除此簡報的寫入保護。

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```


判斷簡報是否受密碼保護以供修改。

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| password | java.lang.String | 用於檢查的密碼。 |

1. 在呼叫此方法之前，您應該檢查 (\#isWriteProtected.isWriteProtected) 屬性。 2. 當密碼為 null 或空字串時，此方法返回 false。

**返回:**  
boolean - 若密碼有效則為 true；否則為 false。