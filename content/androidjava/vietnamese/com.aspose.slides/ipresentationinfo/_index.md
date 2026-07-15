---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Thông tin về tệp trình chiếu
type: docs
url: /vi/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Thông tin về tệp trình chiếu
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Trả về True nếu trình chiếu đã liên kết được mã hóa, ngược lại trả về False. |
| [isPasswordProtected()](#isPasswordProtected--) | Trả về một giá trị cho biết liệu trình chiếu đã liên kết có được bảo vệ bằng mật khẩu để mở hay không. |
| [isWriteProtected()](#isWriteProtected--) | Trả về một giá trị cho biết liệu trình chiếu đã liên kết có được bảo vệ ghi hay không. |
| [getLoadFormat()](#getLoadFormat--) | Trả về định dạng của trình chiếu đã liên kết. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Kiểm tra xem mật khẩu có đúng cho một trình chiếu được bảo vệ bằng mật khẩu mở hay không. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Kiểm tra xem mật khẩu chỉnh sửa có đúng cho một trình chiếu được bảo vệ ghi hay không. |
| [readDocumentProperties()](#readDocumentProperties--) | Trả về các thuộc tính tài liệu của trình chiếu đã liên kết. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Cập nhật các thuộc tính của trình chiếu đã liên kết. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Ghi trình chiếu đã liên kết vào luồng. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Ghi trình chiếu đã liên kết vào tệp. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Trả về True nếu trình chiếu đã liên kết được mã hóa, ngược lại trả về False. Boolean chỉ đọc.

**Trả về:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Trả về một giá trị cho biết liệu trình chiếu đã liên kết có được bảo vệ bằng mật khẩu để mở hay không.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```


**Trả về:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

Trả về một giá trị cho biết liệu trình chiếu đã liên kết có được bảo vệ ghi hay không.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

Nếu trình chiếu được bảo vệ bằng mật khẩu để mở, giá trị thuộc tính bằng NotDefined. Xem enum [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Trả về định dạng của trình chiếu đã liên kết. [LoadFormat](../../com.aspose.slides/loadformat) chỉ đọc.

**Trả về:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Kiểm tra xem mật khẩu có đúng cho một trình chiếu được bảo vệ bằng mật khẩu mở hay không.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| password | java.lang.String | Mật khẩu cần kiểm tra. |

--------------------

Khi mật khẩu là null hoặc rỗng, phương thức này trả về false.

**Trả về:**
boolean - True nếu trình chiếu được bảo vệ bằng mật khẩu mở và mật khẩu đúng và false nếu không.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Kiểm tra xem mật khẩu chỉnh sửa có đúng cho một trình chiếu được bảo vệ ghi hay không.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| password | java.lang.String | Mật khẩu cần kiểm tra. |

--------------------

1. Bạn nên kiểm tra thuộc tính (\#isWriteProtected.isWriteProtected) trước khi gọi phương thức này. 2. Khi mật khẩu là null hoặc rỗng, phương thức này trả về false.

**Trả về:**
boolean - True nếu trình chiếu được bảo vệ ghi và mật khẩu đúng. False nếu không.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Trả về các thuộc tính tài liệu của trình chiếu đã liên kết.

**Trả về:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Các thuộc tính tài liệu [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

Cập nhật các thuộc tính của trình chiếu đã liên kết.

--------------------

> ```
> Ví dụ này cho thấy cách gọi phương thức #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) để cập nhật các thuộc tính tài liệu được trả về bởi cuộc gọi của phương thức #readDocumentProperties.readDocumentProperties.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Các thuộc tính tài liệu [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Ghi trình chiếu đã liên kết vào luồng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng phải có khả năng tìm vị trí và ghi được. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Ghi trình chiếu đã liên kết vào tệp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| file | java.lang.String | Tệp trình chiếu. |