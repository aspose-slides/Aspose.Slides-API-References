---
title: IProtectionManager
second_title: Aspose.Slides cho Android qua API Java
description: Quản lý bảo vệ mật khẩu cho bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Quản lý bảo vệ mật khẩu cho bản trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Thuộc tính này có ý nghĩa nếu bản trình chiếu được bảo vệ bằng mật khẩu. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Thuộc tính này có ý nghĩa nếu bản trình chiếu được bảo vệ bằng mật khẩu. |
| [isEncrypted()](#isEncrypted--) | Lấy giá trị cho biết liệu instance này có được mã hóa hay không. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo vệ bằng mật khẩu và các thuộc tính tài liệu của tệp này là công khai. |
| [isWriteProtected()](#isWriteProtected--) | Lấy giá trị cho biết liệu bản trình chiếu này có được bảo vệ ghi không. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Trả về mật khẩu mã hóa. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Lấy hoặc đặt khuyến nghị chỉ đọc. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Lấy hoặc đặt khuyến nghị chỉ đọc. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Mã hóa Bản trình chiếu với mật khẩu đã chỉ định. |
| [removeEncryption()](#removeEncryption--) | Gỡ bỏ mã hóa. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Đặt bảo vệ ghi cho bản trình chiếu này với mật khẩu đã chỉ định. |
| [removeWriteProtection()](#removeWriteProtection--) | Gỡ bỏ bảo vệ ghi cho bản trình chiếu này. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Xác định liệu bản trình chiếu có được bảo vệ bằng mật khẩu để chỉnh sửa hay không. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Thuộc tính này có ý nghĩa nếu bản trình chiếu được bảo vệ bằng mật khẩu. Nếu true thì các thuộc tính tài liệu được mã hóa trong tệp bản trình chiếu. Nếu false thì các thuộc tính tài liệu là công khai trong khi bản trình chiếu được mã hóa. Boolean đọc/ghi.

**Trả về:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Thuộc tính này có ý nghĩa nếu bản trình chiếu được bảo vệ bằng mật khẩu. Nếu true thì các thuộc tính tài liệu được mã hóa trong tệp bản trình chiếu. Nếu false thì các thuộc tính tài liệu là công khai trong khi bản trình chiếu được mã hóa. Boolean đọc/ghi.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Lấy giá trị cho biết liệu instance này có được mã hóa hay không. Boolean chỉ đọc.

Giá trị: true nếu bản trình chiếu được tải từ tệp đã mã hóa hoặc phương thức \#encrypt(String).encrypt(String) đã được gọi; nếu không, false.

**Trả về:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo vệ bằng mật khẩu và các thuộc tính tài liệu của tệp này là công khai. Giá trị true có nghĩa là chỉ các thuộc tính tài liệu được tải từ tệp bản trình chiếu đã mã hóa mà không cần mật khẩu. Giá trị false có nghĩa là toàn bộ bản trình chiếu đã mã hóa được tải bằng mật khẩu đúng, không chỉ các thuộc tính tài liệu được tải. Nếu bản trình chiếu không được mã hóa thì giá trị thuộc tính luôn là false. Nếu các thuộc tính tài liệu của tệp đã mã hóa không công khai thì giá trị thuộc tính luôn là false. Nếu PresentationEx.EncryptDocumentProperties là true thì giá trị IsOnlyDocumentPropertiesLoaded luôn là false. Boolean chỉ đọc.

**Trả về:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Lấy giá trị cho biết liệu bản trình chiếu này có được bảo vệ ghi không. Boolean chỉ đọc.

**Trả về:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Trả về mật khẩu mã hóa. String chỉ đọc.

**Trả về:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Lấy hoặc đặt khuyến nghị chỉ đọc. Boolean đọc/ghi.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Trả về:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Lấy hoặc đặt khuyến nghị chỉ đọc. Boolean đọc/ghi.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

Mã hóa Bản trình chiếu với mật khẩu đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Mật khẩu. |
### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

Gỡ bỏ mã hóa.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

Đặt bảo vệ ghi cho bản trình chiếu này với mật khẩu đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| password | java.lang.String | Mật khẩu. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Gỡ bỏ bảo vệ ghi cho bản trình chiếu này.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Xác định liệu bản trình chiếu có được bảo vệ bằng mật khẩu để chỉnh sửa hay không.

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
| password | java.lang.String | Mật khẩu để kiểm tra. |

1. Bạn nên kiểm tra thuộc tính (#isWriteProtected.isWriteProtected) trước khi gọi phương thức này. 2. Khi mật khẩu là null hoặc rỗng, phương thức này trả về false.

**Trả về:**
boolean - True nếu mật khẩu hợp lệ; nếu không, false.