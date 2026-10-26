---
title: ProtectionManager
second_title: 透過 Java API 的 Aspose.Slides for Android 參考文件
description: 簡報密碼保護管理。
type: docs
url: /zh-hant/com.aspose.slides/protectionmanager/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

簡報密碼保護管理。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | 如果簡報受密碼保護，則此屬性有意義。 |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | 如果簡報受密碼保護，則此屬性有意義。 |
| [isEncrypted()](#isEncrypted--) | 取得指示此實例是否已加密的值。 |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | 如果簡報檔案受密碼保護且該檔案的文件屬性為公開，則此屬性有意義。 |
| [isWriteProtected()](#isWriteProtected--) | 取得指示此簡報是否受寫入保護的值。 |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | 使用指定的密碼加密簡報。 |
| [removeEncryption()](#removeEncryption--) | 移除加密。 |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | 使用指定的密碼為此簡報設定寫入保護。 |
| [removeWriteProtection()](#removeWriteProtection--) | 移除此簡報的寫入保護。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 判斷簡報是否受密碼保護以進行修改。 |
| [getEncryptionPassword()](#getEncryptionPassword--) | 取得用於簡報加密的密碼。 |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | 取得或設定唯讀建議。 |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | 取得或設定唯讀建議。 |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```


如果簡報受密碼保護，則此屬性有意義。若為 true，則文件屬性在簡報檔案中被加密。若為 false，則文件屬性為公開，同時簡報已加密。可讀寫布林值。

**返回值:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```


如果簡報受密碼保護，則此屬性有意義。若為 true，則文件屬性在簡報檔案中被加密。若為 false，則文件屬性為公開，同時簡報已加密。可讀寫布林值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


取得指示此實例是否已加密的值。唯讀布林值。

值: 若簡報是從加密檔案載入或呼叫了 \#encrypt(String).encrypt(String) 方法，則為 true；否則為 false。

**返回值:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```


如果簡報檔案受密碼保護且該檔案的文件屬性為公開，則此屬性有意義。true 表示僅從加密的簡報檔案中載入文件屬性而不使用密碼。false 表示使用正確的密碼載入整個加密的簡報，而不僅載入文件屬性。若簡報未加密，則此屬性值始終為 false。若加密檔案的文件屬性不是公開的，則此屬性值始終為 false。若 Presentation.EncryptDocumentProperties 為 true，則 IsOnlyDocumentPropertiesLoaded 屬性值始終為 false。唯讀布林值。

**返回值:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```


取得指示此簡報是否受寫入保護的值。唯讀布林值。

**返回值:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```


使用指定的密碼加密簡報。

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


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| encryptionPassword | java.lang.String | 密碼。 |

### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```


移除加密。

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```


使用指定的密碼為此簡報設定寫入保護。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| password | java.lang.String | 密碼。 |

### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```


移除此簡報的寫入保護。

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


判斷簡報是否受密碼保護以進行修改。

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| password | java.lang.String | 用於檢查的密碼。 |

1. 在呼叫此方法前，應先檢查 (\#isWriteProtected.isWriteProtected) 屬性。2. 當密碼為 null 或空字串時，此方法會回傳 false. |

**返回值:**
boolean - 若密碼有效則返回 true；否則返回 false。
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```


取得用於簡報加密的密碼。唯讀字串。

**返回值:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```


取得或設定唯讀建議。可讀寫布林值。

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

**返回值:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```


取得或設定唯讀建議。可讀寫布林值。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |