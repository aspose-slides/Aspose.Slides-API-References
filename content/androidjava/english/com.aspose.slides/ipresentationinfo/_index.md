---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Information about presentation file
type: docs
weight: 984
url: /com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Information about presentation file
## Methods

| Method | Description |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Gets True if binded presentation is encrypted, otherwise False. |
| [isPasswordProtected()](#isPasswordProtected--) | Gets a value that indicates whether a binded presentation is protected by a password to open. |
| [isWriteProtected()](#isWriteProtected--) | Gets a value that indicates whether a binded presentation is write protected. |
| [getLoadFormat()](#getLoadFormat--) | Gets format of the binded presentation. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Checks whether a password is correct for a presentation protected with open password. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Checks whether a password to modify is correct for a write protected presentation. |
| [readDocumentProperties()](#readDocumentProperties--) | Gets document properties of binded presentation. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Updates properties of binded presentation. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Writes binded presentation to stream. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Writes binded presentation to file. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


Gets True if binded presentation is encrypted, otherwise False. Read-only boolean.

**Returns:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


Gets a value that indicates whether a binded presentation is protected by a password to open.

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
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
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
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
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


Updates properties of binded presentation.

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
| Parameter | Type | Description |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Document properties [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```


Writes binded presentation to stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream must be seekable and writable. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```


Writes binded presentation to file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Presentation file. |

