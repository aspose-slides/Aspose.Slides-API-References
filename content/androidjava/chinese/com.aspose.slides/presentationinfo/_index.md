---
title: PresentationInfo
second_title: Aspose.Slides for Android via Java API 参考
description: 关于演示文稿文件的信息
type: docs
url: /zh/com.aspose.slides/presentationinfo/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

关于演示文稿文件的信息
## 方法

| 方法 | 描述 |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | 如果绑定的演示文稿已加密，则返回 True，否则返回 False。 |
| [isPasswordProtected()](#isPasswordProtected--) | 获取一个值，指示绑定的演示文稿是否受打开密码保护。 |
| [isWriteProtected()](#isWriteProtected--) | 获取一个值，指示绑定的演示文稿是否受到写保护。 |
| [getLoadFormat()](#getLoadFormat--) | 获取绑定的演示文稿的格式。 |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | 检查打开密码保护的演示文稿的密码是否正确。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 检查写保护演示文稿的修改密码是否正确。 |
| [readDocumentProperties()](#readDocumentProperties--) | 获取绑定的演示文稿的文档属性。 |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | 更新绑定的演示文稿的属性。 |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | 将绑定的演示文稿写入流。 |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | 将绑定的演示文稿写入文件。 |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

如果绑定的演示文稿已加密，则返回 True，否则返回 False。只读布尔值。

**返回值:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

获取一个值，指示绑定的演示文稿是否受打开密码保护。

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

Gets a value that indicates whether a binded presentation is write protected.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

If the presentation is protected by a password to open, the property value equals NotDefined.

**Returns:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Gets format of the binded presentation. Read-only [LoadFormat](../../com.aspose.slides/loadformat).

**Returns:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Checks whether a password is correct for a presentation protected with open password.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password to check.

--------------------

When the password is null or empty, this method returns false. |

**Returns:**
boolean - True if the presentation is protected with open password and the password is correct and false otherwise.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Checks whether a password to modify is correct for a write protected presentation.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password to check.

--------------------

1. You should check the (\#isWriteProtected.isWriteProtected) property before calling this method. 2. When password is null or empty, this method returns false. |

**Returns:**
boolean - True if the presentation is write protected and the password is correct. False otherwise.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Gets document properties of binded presentation.

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Updates properties of binded presentation.

--------------------

> ```
> This sample shows how to call the #updateDocumentProperties(IDDocumentProperties).updateDocumentProperties(IDDocumentProperties) method to
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
| Parameter | Type | Description |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/iddocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

Writes binded presentation to stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream must be seekable and writable. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
public final byte isWriteProtected()
public final int getLoadFormat()
public final boolean checkPassword(String password)
public final boolean checkWriteProtection(String password)
public final IDocumentProperties readDocumentProperties()
public final void updateDocumentProperties(IDocumentProperties documentProperties)
public final void writeBindedPresentation(OutputStream stream)
public final void writeBindedPresentation(String file)

将绑定的演示文稿写入文件。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| file | java.lang.String | 演示文稿文件。 |