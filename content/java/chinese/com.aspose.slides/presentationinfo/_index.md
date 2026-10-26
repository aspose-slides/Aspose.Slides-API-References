---
title: PresentationInfo
second_title: Aspose.Slides for Java API 参考
description: 关于演示文稿文件的信息
type: docs
url: /zh/com.aspose.slides/presentationinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

关于演示文稿文件的信息
## Methods

| 方法 | 描述 |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | 如果绑定的演示文稿已加密则返回 True，否则返回 False。 |
| [isPasswordProtected()](#isPasswordProtected--) | 获取一个值，指示绑定的演示文稿是否受打开密码保护。 |
| [isWriteProtected()](#isWriteProtected--) | 获取一个值，指示绑定的演示文稿是否受写入保护。 |
| [getLoadFormat()](#getLoadFormat--) | 获取绑定的演示文稿的格式。 |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | 检查用于打开受密码保护的演示文稿的密码是否正确。 |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | 检查用于修改写保护演示文稿的密码是否正确。 |
| [readDocumentProperties()](#readDocumentProperties--) | 获取绑定的演示文稿的文档属性。 |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | 更新绑定的演示文稿的属性。 |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | 将绑定的演示文稿写入流。 |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | 将绑定的演示文稿写入文件。 |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


如果绑定的演示文稿已加密则返回 True，否则返回 False。只读 boolean。

**返回值：**
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


**返回值：**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```


获取一个值，指示绑定的演示文稿是否受写入保护。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


--------------------

如果演示文稿受打开密码保护，则属性值等于 NotDefined。

**返回值：**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```


获取绑定的演示文稿的格式。只读 [LoadFormat](../../com.aspose.slides/loadformat)。

**返回值：**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```


检查用于打开受密码保护的演示文稿的密码是否正确。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | java.lang.String | 要检查的密码。

--------------------

当 password 为 null 或为空时，此方法返回 false. |

**返回值：**
boolean - 如果演示文稿受打开密码保护且密码正确则返回 True，否则返回 false。
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```


检查用于修改写保护演示文稿的密码是否正确。

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | java.lang.String | 要检查的密码。

--------------------

1. 在调用此方法之前，您应检查 (\#isWriteProtected.isWriteProtected) 属性。 2. 当 password 为 null 或空时，此方法返回 false. |

**返回值：**
boolean - 如果演示文稿受写保护且密码正确则返回 True，否则返回 False。
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```


获取绑定的演示文稿的文档属性。

**返回值：**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```


更新绑定的演示文稿的属性。

--------------------

> ```
> 此示例展示如何调用 #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDDocumentProperties) 方法来
>  更新通过调用 #readDocumentProperties.readDocumentProperties 方法返回的文档属性。
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```


将绑定的演示文稿写入流。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | |
| stream | java.io.OutputStream | 该流必须可定位且可写。 |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```


将绑定的演示文稿写入文件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | |
| file | java.lang.String | 演示文稿文件。 |