---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
description: 有关演示文稿文件的信息
type: docs
url: /zh/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

有关演示文稿文件的信息
## 方法

| Method | Description |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | 如果绑定的演示文稿已加密则返回 True，否则返回 False。 |
| [isPasswordProtected()](#isPasswordProtected--) | 获取指示绑定的演示文稿是否受打开密码保护的值。 |
| [isWriteProtected()](#isWriteProtected--) | 获取指示绑定的演示文稿是否受写保护的值。 |
| [getLoadFormat()](#getLoadFormat--) | 获取绑定的演示文稿的格式。 |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | 检查对受打开密码保护的演示文稿的密码是否正确。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 检查对受写保护的演示文稿的修改密码是否正确。 |
| [readDocumentProperties()](#readDocumentProperties--) | 获取绑定的演示文稿的文档属性。 |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | 更新绑定的演示文稿的属性。 |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | 将绑定的演示文稿写入流。 |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | 将绑定的演示文稿写入文件。 |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

如果绑定的演示文稿已加密则返回 True，否则返回 False。只读布尔值。

**Returns:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

获取指示绑定的演示文稿是否受打开密码保护的值。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```

**Returns:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

Gets a value that indicates whether a binded presentation is write protected.

--------------------

> ```
> IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```

--------------------

If the presentation is protected by a password to open, the property value equals NotDefined. See [NullableBool](../../com.aspose.slides/nullablebool) enumeration.

**Returns:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Gets format of the binded presentation. Read-only [LoadFormat](../../com.aspose.slides/loadformat).

**Returns:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Checks whether a password is correct for a presentation protected with open password.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
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
public abstract boolean checkWriteProtection(String password)
```

Checks whether a password to modify is correct for a write protected presentation.

--------------------

> ```
> IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
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
public abstract IDocumentProperties readDocumentProperties()
```

Gets document properties of binded presentation.

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Document properties [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

更新绑定的演示文稿的属性。

--------------------

> ```
> 此示例展示了如何调用 #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDDocumentProperties) 方法，以更新通过调用 #readDocumentProperties.readDocumentProperties 方法返回的文档属性。
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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Document properties [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

将绑定的演示文稿写入流。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 该流必须可定位且可写。 |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)

将绑定的演示文稿写入文件。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | 演示文稿文件。 |