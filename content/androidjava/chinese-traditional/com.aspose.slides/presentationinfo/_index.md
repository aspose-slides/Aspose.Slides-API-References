---
title: PresentationInfo
second_title: Aspose.Slides Android 版 Java API 參考
description: 關於簡報檔案的資訊
type: docs
url: /zh-hant/com.aspose.slides/presentationinfo/
---
**繼承：**
java.lang.Object

**所有實作的介面：**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

關於簡報檔案的資訊
## 方法

| 方法 | 說明 |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | 如果已繫結的簡報已加密則傳回 True，否則傳回 False。 |
| [isPasswordProtected()](#isPasswordProtected--) | 取得指示已繫結的簡報是否以開啟密碼受保護的值。 |
| [isWriteProtected()](#isWriteProtected--) | 取得指示已繫結的簡報是否寫入受保護的值。 |
| [getLoadFormat()](#getLoadFormat--) | 取得已繫結的簡報的格式。 |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | 檢查對於以開啟密碼受保護的簡報，密碼是否正確。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 檢查對於寫入受保護的簡報，修改密碼是否正確。 |
| [readDocumentProperties()](#readDocumentProperties--) | 取得已繫結的簡報的文件屬性。 |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | 更新已繫結的簡報的屬性。 |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | 將已繫結的簡報寫入串流。 |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | 將已繫結的簡報寫入檔案。 |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

取得已繫結的簡報是否已加密的 True，否則為 False。唯讀布林值。

**Returns:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

取得指示已繫結的簡報是否以開啟密碼受保護的值。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**Returns:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

取得指示已繫結的簡報是否寫入受保護的值。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

如果簡報以開啟密碼受保護，屬性值等於 NotDefined。

**Returns:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

取得已繫結的簡報的格式。唯讀 [LoadFormat](../../com.aspose.slides/loadformat)。

**Returns:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

檢查對於以開啟密碼受保護的簡報，密碼是否正確。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parameters:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| password | java.lang.String | 要檢查的密碼。 |

--------------------

當密碼為 null 或空字串時，此方法傳回 false。

**Returns:**
boolean - True if the presentation is protected with open password and the password is correct and false otherwise.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

檢查對於寫入受保護的簡報，修改密碼是否正確。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parameters:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| password | java.lang.String | 要檢查的密碼。 |

--------------------

1. 呼叫此方法之前應先檢查 (\#isWriteProtected.isWriteProtected) 屬性。2. 當密碼為 null 或空字串時，此方法傳回 false。

**Returns:**
boolean - True if the presentation is write protected and the password is correct. False otherwise.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

取得已繫結的簡報的文件屬性。

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

更新已繫結的簡報的屬性。

--------------------

> ```
> This sample shows how to call the #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) method to
>  update the document properties returned by call of the #readDocumentProperties.readDocumentProperties method.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**Parameters:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

將已繫結的簡報寫入串流。

**Parameters:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 此串流必須可搜尋且可寫入。 |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

將已繫結的簡報寫入檔案。

**Parameters:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| file | java.lang.String | 簡報檔案。 |