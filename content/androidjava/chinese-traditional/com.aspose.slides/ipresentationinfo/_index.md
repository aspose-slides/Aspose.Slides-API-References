---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
description: 簡報檔案資訊
type: docs
url: /zh-hant/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

簡報檔案資訊
## 方法

| 方法 | 說明 |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | 如果已綁定的簡報已加密則回傳 True，否則回傳 False。 |
| [isPasswordProtected()](#isPasswordProtected--) | 取得指示已綁定簡報是否受開啟密碼保護的值。 |
| [isWriteProtected()](#isWriteProtected--) | 取得指示已綁定簡報是否被寫入保護的值。 |
| [getLoadFormat()](#getLoadFormat--) | 取得已綁定簡報的格式。 |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | 檢查受開啟密碼保護的簡報密碼是否正確。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 檢查針對受寫入保護的簡報的修改密碼是否正確。 |
| [readDocumentProperties()](#readDocumentProperties--) | 取得已綁定簡報的文件屬性。 |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | 更新已綁定簡報的屬性。 |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | 將已綁定簡報寫入至串流。 |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | 將已綁定簡報寫入至檔案。 |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


如果已綁定的簡報已加密則回傳 True，否則回傳 False。唯讀 boolean。

**回傳：**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


取得指示已綁定簡報是否受開啟密碼保護的值。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```


**回傳：**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```


取得指示已綁定簡報是否被寫入保護的值。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

如果簡報受開啟密碼保護，屬性值等於 NotDefined。請參閱 [NullableBool](../../com.aspose.slides/nullablebool) 列舉。

**回傳：**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```


取得已綁定簡報的格式。唯讀 [LoadFormat](../../com.aspose.slides/loadformat)。

**回傳：**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```


檢查受開啟密碼保護的簡報密碼是否正確。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| password | java.lang.String | 要檢查的密碼。 |

--------------------

當密碼為 null 或空字串時，此方法回傳 false. |

**回傳：**
boolean - 如果簡報受開啟密碼保護且密碼正確則回傳 True，否則回傳 false。
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```


檢查針對受寫入保護的簡報的修改密碼是否正確。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
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

1. 在呼叫此方法之前，您應先檢查 (\#isWriteProtected.isWriteProtected) 屬性。 2. 當密碼為 null 或空字串時，此方法回傳 false. |

**回傳：**
boolean - 如果簡報受寫入保護且密碼正確則回傳 True。否則回傳 False。
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```


取得已綁定簡報的文件屬性。

**回傳：**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - 文件屬性 [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```


更新已綁定簡報的屬性。

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


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | 文件屬性 [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```


將已綁定簡報寫入至串流。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 此串流必須可搜尋且可寫入。 |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```


將已綁定簡報寫入至檔案。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| file | java.lang.String | 簡報檔案。 |