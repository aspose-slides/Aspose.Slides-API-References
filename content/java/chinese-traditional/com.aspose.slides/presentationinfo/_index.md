---
title: PresentationInfo
second_title: Aspose.Slides for Java API 參考文件
description: 有關簡報檔案的資訊
type: docs
url: /zh-hant/com.aspose.slides/presentationinfo/
---
**繼承：**
java.lang.Object

**全部已實作的介面：**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

簡報檔案的資訊
## 方法

| 方法 | 描述 |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | 如果已綁定的簡報已加密則返回 True，否則返回 False。 |
| [isPasswordProtected()](#isPasswordProtected--) | 取得一個值，用於指示已綁定的簡報是否受開啟密碼保護。 |
| [isWriteProtected()](#isWriteProtected--) | 取得一個值，用於指示已綁定的簡報是否受到寫入保護。 |
| [getLoadFormat()](#getLoadFormat--) | 取得已綁定的簡報的格式。 |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | 檢查對於受開啟密碼保護的簡報，密碼是否正確。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 檢查對於受寫入保護的簡報，修改密碼是否正確。 |
| [readDocumentProperties()](#readDocumentProperties--) | 取得已綁定的簡報的文件屬性。 |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | 更新已綁定的簡報的屬性。 |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | 將已綁定的簡報寫入至串流。 |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | 將已綁定的簡報寫入至檔案。 |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

如果已綁定的簡報已加密則返回 True，否則返回 False。唯讀 boolean.

**傳回：**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

取得一個值，用於指示已綁定的簡報是否受開啟密碼保護。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**傳回：**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

取得一個值，用於指示已綁定的簡報是否受到寫入保護。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

如果簡報受開啟密碼保護，屬性值等於 NotDefined。

**傳回：**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

取得已綁定的簡報的格式。唯讀 [LoadFormat](../../com.aspose.slides/loadformat)。

**傳回：**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

檢查對於受開啟密碼保護的簡報，密碼是否正確。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| password | java.lang.String | 要檢查的密碼。 |

--------------------

當密碼為 null 或空字串時，此方法返回 false。|

**傳回：**
boolean - 如果簡報受開啟密碼保護且密碼正確則返回 True，否則返回 false。
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

檢查對於受寫入保護的簡報，修改密碼是否正確。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| password | java.lang.String | 要檢查的密碼。 |

--------------------

1. 呼叫此方法前應先檢查 (\#isWriteProtected.isWriteProtected) 屬性。2. 當密碼為 null 或空字串時，此方法返回 false。 |

**傳回：**
boolean - 如果簡報受寫入保護且密碼正確則返回 True，否則返回 False。
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

取得已綁定的簡報的文件屬性。

**傳回：**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

更新已綁定的簡報的屬性。

--------------------

> ```
> 此範例示範如何呼叫 #updateDocumentProperties(IDDocumentProperties).updateDocumentProperties(IDDocumentProperties) 方法以
>  更新透過呼叫 #readDocumentProperties.readDocumentProperties 方法回傳的文件屬性。
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

將已綁定的簡報寫入至串流。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 該串流必須可定位且可寫入。 |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

將已綁定的簡報寫入至檔案。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| file | java.lang.String | 簡報檔案。 |