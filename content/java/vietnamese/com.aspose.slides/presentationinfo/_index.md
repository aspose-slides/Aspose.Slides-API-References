---
title: PresentationInfo
second_title: Aspose.Slides cho Tham chiếu API Java
description: Thông tin về tệp trình chiếu
type: docs
url: /vi/com.aspose.slides/presentationinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Thông tin về tệp trình chiếu
## Methods

| Method | Description |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Trả về True nếu bản trình chiếu đã liên kết được mã hoá, ngược lại trả về False. |
| [isPasswordProtected()](#isPasswordProtected--) | Trả về một giá trị cho biết liệu bản trình chiếu đã liên kết có được bảo vệ bằng mật khẩu để mở hay không. |
| [isWriteProtected()](#isWriteProtected--) | Trả về một giá trị cho biết liệu bản trình chiếu đã liên kết có được bảo vệ ghi không. |
| [getLoadFormat()](#getLoadFormat--) | Trả về định dạng của bản trình chiếu đã liên kết. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Kiểm tra xem mật khẩu có đúng cho bản trình chiếu được bảo vệ bằng mật khẩu mở không. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Kiểm tra xem mật khẩu để chỉnh sửa có đúng cho bản trình chiếu được bảo vệ ghi không. |
| [readDocumentProperties()](#readDocumentProperties--) | Trả về các thuộc tính tài liệu của bản trình chiếu đã liên kết. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Cập nhật các thuộc tính của bản trình chiếu đã liên kết. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Ghi bản trình chiếu đã liên kết vào luồng. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Ghi bản trình chiếu đã liên kết vào tệp. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Trả về True nếu bản trình chiếu đã liên kết được mã hoá, ngược lại trả về False. Boolean chỉ đọc.

**Returns:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Trả về một giá trị cho biết liệu bản trình chiếu đã liên kết có được bảo vệ bằng mật khẩu để mở hay không.

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

Trả về một giá trị cho biết liệu bản trình chiếu đã liên kết có được bảo vệ ghi không.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


--------------------

Nếu bản trình chiếu được bảo vệ bằng mật khẩu mở, giá trị thuộc tính sẽ bằng NotDefined.

**Returns:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Trả về định dạng của bản trình chiếu đã liên kết. Chỉ đọc [LoadFormat](../../com.aspose.slides/loadformat).

**Returns:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Kiểm tra xem mật khẩu có đúng cho bản trình chiếu được bảo vệ bằng mật khẩu mở không.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | Mật khẩu để kiểm tra. |

--------------------

Khi mật khẩu là null hoặc rỗng, phương thức này trả về false. |

**Returns:**
True nếu bản trình chiếu được bảo vệ bằng mật khẩu mở và mật khẩu đúng, ngược lại false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Kiểm tra xem mật khẩu để chỉnh sửa có đúng cho bản trình chiếu được bảo vệ ghi không.

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
| password | java.lang.String | Mật khẩu để kiểm tra. |

--------------------

1. Bạn nên kiểm tra thuộc tính (\#isWriteProtected.isWriteProtected) trước khi gọi phương thức này. 2. Khi mật khẩu là null hoặc rỗng, phương thức này trả về false. |

**Returns:**
True nếu bản trình chiếu được bảo vệ ghi và mật khẩu đúng. False nếu ngược lại.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Trả về các thuộc tính tài liệu của bản trình chiếu đã liên kết.

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Cập nhật các thuộc tính của bản trình chiếu đã liên kết.

--------------------

> ```
> Ví dụ này cho thấy cách gọi phương thức #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) để
>  cập nhật các thuộc tính tài liệu được trả về bởi lời gọi phương thức #readDocumentProperties.readDocumentProperties.
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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

Ghi bản trình chiếu đã liên kết vào luồng.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng phải có khả năng di chuyển vị trí và có thể ghi. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

Ghi bản trình chiếu đã liên kết vào tệp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Tệp trình chiếu. |