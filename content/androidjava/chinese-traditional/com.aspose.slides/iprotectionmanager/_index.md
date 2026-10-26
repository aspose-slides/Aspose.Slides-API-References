---
title: IProtectionManager
second_title: Aspose.Slides for Android via Java API Reference
description: Presentation password protection management.
type: docs
url: /zh-hant/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

簡報密碼保護管理。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | 若簡報已設定密碼保護，則此屬性有意義。 |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | 若簡報已設定密碼保護，則此屬性有意義。 |
| [isEncrypted()](#isEncrypted--) | 取得指示此實例是否已加密的值。 |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | 若簡報檔案已設定密碼保護且該檔案的文件屬性為公開，則此屬性有意義。 |
| [isWriteProtected()](#isWriteProtected--) | 取得指示此簡報是否受寫入保護的值。 |
| [getEncryptionPassword()](#getEncryptionPassword--) | 傳回加密密碼。 |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | 取得或設定唯讀建議。 |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | 取得或設定唯讀建議。 |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | 使用指定的密碼加密簡報。 |
| [removeEncryption()](#removeEncryption--) | 移除加密。 |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | 使用指定的密碼為此簡報設定寫入保護。 |
| [removeWriteProtection()](#removeWriteProtection--) | 移除此簡報的寫入保護。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 判斷簡報是否因密碼保護而無法修改。 |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

此屬性在簡報已設定密碼保護時才有意義。若為 true，則文件屬性在簡報檔案中被加密；若為 false，則文件屬性為公開，同時簡報已加密。讀寫 boolean。

**傳回：**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

此屬性在簡報已設定密碼保護時才有意義。若為 true，則文件屬性在簡報檔案中被加密；若為 false，則文件屬性為公開，同時簡報已加密。讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

取得指示此實例是否已加密的值。唯讀 boolean。

值：若簡報是從加密檔案載入或呼叫 \#encrypt(String).encrypt(String) 方法，則為 true；否則為 false。

**傳回：**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

此屬性在簡報檔案已設定密碼保護且該檔案的文件屬性為公開時才有意義。值為 true 表示僅從加密的簡報檔案載入文件屬性而未使用密碼；值為 false 表示使用正確密碼載入整個加密的簡報，而不僅載入文件屬性。若簡報未加密，則此屬性永遠為 false。若加密檔案的文件屬性不是公開的，則此屬性永遠為 false。若 PresentationEx.EncryptDocumentProperties 為 true，則 IsOnlyDocumentPropertiesLoaded 屬性永遠為 false。唯讀 boolean。

**傳回：**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

取得指示此簡報是否受寫入保護的值。唯讀 boolean。

**傳回：**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

傳回加密密碼。唯讀 String。

**傳回：**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

取得或設定唯讀建議。讀寫 boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**傳回：**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

取得或設定唯讀建議。讀寫 boolean。

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

使用指定的密碼加密簡報。

**參數：**
| 參數 | 型別 | 說明 |
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

**參數：**
| 參數 | 型別 | 說明 |
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

判斷簡報是否因密碼保護而無法修改。

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| password | java.lang.String | 用於檢查的密碼。

--------------------

1. 在呼叫此方法前，應先檢查 (\#isWriteProtected.isWriteProtected) 屬性。2. 當密碼為 null 或空字串時，此方法傳回 false。 |

**傳回：**
boolean - 若密碼有效則為 True；否則為 false。