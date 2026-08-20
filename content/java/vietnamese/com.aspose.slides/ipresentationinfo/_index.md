---
title: IPresentationInfo
second_title: Aspose.Slides for Java API Reference
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
| [isEncrypted()](#isEncrypted--) | Lấy True nếu bản trình chiếu đã liên kết được mã hoá, nếu không thì False. |
| [isPasswordProtected()](#isPasswordProtected--) | Lấy giá trị cho biết liệu bản trình chiếu đã liên kết có được bảo vệ bằng mật khẩu để mở hay không. |
| [isWriteProtected()](#isWriteProtected--) | Lấy giá trị cho biết liệu bản trình chiếu đã liên kết có được bảo vệ khỏi việc ghi hay không. |
| [getLoadFormat()](#getLoadFormat--) | Lấy định dạng của bản trình chiếu đã liên kết. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Kiểm tra xem mật khẩu có đúng cho bản trình chiếu được bảo vệ bằng mật khẩu mở hay không. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Kiểm tra xem mật khẩu để sửa đổi có đúng cho bản trình chiếu được bảo vệ khỏi việc ghi hay không. |
| [readDocumentProperties()](#readDocumentProperties--) | Lấy thuộc tính tài liệu của bản trình chiếu đã liên kết. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Cập nhật thuộc tính của bản trình chiếu đã liên kết. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Ghi bản trình chiếu đã liên kết vào luồng. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Ghi bản trình chiếu đã liên kết vào tệp. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Lấy True nếu bản trình chiếu đã liên kết được mã hoá, nếu không thì False. Chỉ đọc boolean.

**Trả về:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Lấy giá trị cho biết liệu bản trình chiếu đã liên kết có được bảo vệ bằng mật khẩu để mở hay không.

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

Lấy giá trị cho biết liệu bản trình chiếu đã liên kết có được bảo vệ khỏi việc ghi hay không.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

Nếu bản trình chiếu được bảo vệ bằng mật khẩu để mở, giá trị thuộc tính bằng NotDefined. Xem liệt kê [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Lấy định dạng của bản trình chiếu đã liên kết. Chỉ đọc [LoadFormat](../../com.aspose.slides/loadformat).

**Trả về:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Kiểm tra xem mật khẩu có đúng cho bản trình chiếu được bảo vệ bằng mật khẩu mở hay không.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| password | java.lang.String | Mật khẩu để kiểm tra. |

--------------------

Khi mật khẩu là null hoặc rỗng, phương thức này trả về false.

**Trả về:**
boolean - True nếu bản trình chiếu được bảo vệ bằng mật khẩu mở và mật khẩu đúng, ngược lại là false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Kiểm tra xem mật khẩu để sửa đổi có đúng cho bản trình chiếu được bảo vệ khỏi việc ghi hay không.

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
| password | java.lang.String | Mật khẩu để kiểm tra. |

1. Bạn nên kiểm tra thuộc tính (#isWriteProtected.isWriteProtected) trước khi gọi phương thức này. 2. Khi mật khẩu là null hoặc rỗng, phương thức này trả về false.

**Trả về:**
boolean - True nếu bản trình chiếu được bảo vệ khỏi việc ghi và mật khẩu đúng. False nếu không.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Lấy thuộc tính tài liệu của bản trình chiếu đã liên kết.

**Trả về:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Thuộc tính tài liệu [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

Cập nhật thuộc tính của bản trình chiếu đã liên kết.

--------------------

> ```
> Ví dụ này cho thấy cách gọi phương thức #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) để
>  cập nhật các thuộc tính tài liệu được trả về bởi lời gọi của phương thức #readDocumentProperties.readDocumentProperties.
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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Thuộc tính tài liệu [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Ghi bản trình chiếu đã liên kết vào luồng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.OutputStream | Luồng phải có khả năng di chuyển vị trí và có thể ghi. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Ghi bản trình chiếu đã liên kết vào tệp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| file | java.lang.String | Tệp trình chiếu. |