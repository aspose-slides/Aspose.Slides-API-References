---
title: ProtectionManager
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Quản lý bảo vệ mật khẩu bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/protectionmanager/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Quản lý bảo vệ mật khẩu bản trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Thuộc tính này có ý nghĩa nếu bản trình chiếu được bảo vệ bằng mật khẩu. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Thuộc tính này có ý nghĩa nếu bản trình chiếu được bảo vệ bằng mật khẩu. |
| [isEncrypted()](#isEncrypted--) | Lấy giá trị cho biết liệu thể hiện này có được mã hóa hay không. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo vệ bằng mật khẩu và thuộc tính tài liệu của tệp này là công khai. |
| [isWriteProtected()](#isWriteProtected--) | Lấy giá trị cho biết liệu bản trình chiếu này có được bảo vệ ghi hay không. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Mã hóa bản trình chiếu bằng mật khẩu đã chỉ định. |
| [removeEncryption()](#removeEncryption--) | Xóa bỏ việc mã hóa. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Đặt bảo vệ ghi cho bản trình chiếu này bằng mật khẩu đã chỉ định. |
| [removeWriteProtection()](#removeWriteProtection--) | Xóa bỏ bảo vệ ghi cho bản trình chiếu này. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Xác định xem bản trình chiếu có được bảo vệ bằng mật khẩu để sửa đổi hay không. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Lấy mật khẩu được sử dụng để mã hóa bản trình chiếu. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Lấy hoặc đặt khuyến nghị chỉ-đọc. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Lấy hoặc đặt khuyến nghị chỉ-đọc. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```


Thuộc tính này có ý nghĩa nếu bản trình chiếu được bảo vệ bằng mật khẩu. Nếu true thì thuộc tính tài liệu được mã hóa trong tệp bản trình chiếu. Nếu false thì thuộc tính tài liệu là công khai trong khi bản trình chiếu được mã hóa. Đọc/ghi boolean.

**Giá trị trả về:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```


Thuộc tính này có ý nghĩa nếu bản trình chiếu được bảo vệ bằng mật khẩu. Nếu true thì thuộc tính tài liệu được mã hóa trong tệp bản trình chiếu. Nếu false thì thuộc tính tài liệu là công khai trong khi bản trình chiếu được mã hóa. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Lấy giá trị cho biết liệu thể hiện này có được mã hóa hay không. Chỉ-đọc boolean.

Giá trị: true nếu bản trình chiếu được tải từ tệp đã mã hóa hoặc phương thức \#encrypt(String).encrypt(String) đã được gọi; nếu không, false.

**Giá trị trả về:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```


Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo vệ bằng mật khẩu và thuộc tính tài liệu của tệp này là công khai. Giá trị true có nghĩa là chỉ có thuộc tính tài liệu được tải từ tệp bản trình chiếu đã mã hóa mà không cần mật khẩu. Giá trị false có nghĩa là toàn bộ bản trình chiếu đã mã hóa được tải với việc sử dụng mật khẩu đúng, không chỉ thuộc tính tài liệu được tải. Nếu bản trình chiếu không được mã hóa thì giá trị thuộc tính luôn là false. Nếu thuộc tính tài liệu của tệp đã mã hóa không công khai thì giá trị thuộc tính luôn là false. Nếu Presentation.EncryptDocumentProperties là true thì giá trị IsOnlyDocumentPropertiesLoaded luôn là false. Chỉ-đọc boolean.

**Giá trị trả về:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```


Lấy giá trị cho biết liệu bản trình chiếu này có được bảo vệ ghi hay không. Chỉ-đọc boolean.

**Giá trị trả về:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```


Mã hóa bản trình chiếu bằng mật khẩu đã chỉ định.

--------------------

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Mật khẩu. |

### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```


Xóa bỏ việc mã hóa.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```


Đặt bảo vệ ghi cho bản trình chiếu này bằng mật khẩu đã chỉ định.

--------------------

> ```
> Đoạn mã mẫu dưới đây cho bạn thấy cách đặt bảo vệ ghi cho một bản trình chiếu.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| password | java.lang.String | Mật khẩu. |

### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```


Xóa bỏ bảo vệ ghi cho bản trình chiếu này.

--------------------

> ```
> Đoạn mã mẫu này cho bạn thấy cách xóa bảo vệ ghi khỏi một bản trình chiếu PowerPoint.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```


Xác định xem bản trình chiếu có được bảo vệ mật khẩu để sửa đổi hay không.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| password | java.lang.String | Mật khẩu để kiểm tra.

1. Bạn nên kiểm tra thuộc tính (\#isWriteProtected.isWriteProtected) trước khi gọi phương thức này. 2. Khi mật khẩu là null hoặc rỗng, phương thức này trả về false. |

**Giá trị trả về:**
boolean - True nếu mật khẩu hợp lệ; nếu không, false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```


Lấy mật khẩu được sử dụng để mã hóa bản trình chiếu. Chỉ-đọc String.

**Giá trị trả về:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```


Lấy hoặc đặt khuyến nghị chỉ-đọc. Đọc/ghi boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Giá trị trả về:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```


Lấy hoặc đặt khuyến nghị chỉ-đọc. Đọc/ghi boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |