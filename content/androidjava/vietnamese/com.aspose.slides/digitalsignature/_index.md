---
title: DigitalSignature
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Chữ ký kỹ thuật số trong tệp đã ký.
type: docs
url: /vi/com.aspose.slides/digitalsignature/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Chữ ký kỹ thuật số trong tệp đã ký.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Khởi tạo đối tượng Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Tạo đối tượng DigitalSignature với tệp PFX và mật khẩu PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Ghi chú chữ ký kỹ thuật số mới
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Thêm chữ ký kỹ thuật số vào bản trình bày
>      pres.getDigitalSignatures().add(signature);
>      // Lưu bản trình bày
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Khởi tạo đối tượng Presentation
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Kiểm tra xem tất cả chữ ký kỹ thuật số có hợp lệ không
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>              System.out.println(signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>              allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>              System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>              System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Hàm khởi tạo

| Constructor | Mô tả |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Tạo một đối tượng DigitalSignature mới với chứng chỉ được chỉ định. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Tạo một đối tượng DigitalSignature mới với đường dẫn tệp chứng chỉ và mật khẩu được chỉ định. |
## Phương thức

| Method | Mô tả |
| --- | --- |
| [getCertificate()](#getCertificate--) | Đối tượng chứng chỉ được sử dụng để ký tài liệu. |
| [isValid()](#isValid--) | Nếu chữ ký kỹ thuật số này hợp lệ và tài liệu không bị giả mạo, giá trị này sẽ là true. |
| [getSignTime()](#getSignTime--) | Thời gian tài liệu được ký. |
| [getComments()](#getComments--) | Mục đích của chữ ký. |
| [setComments(String value)](#setComments-java.lang.String-) | Mục đích của chữ ký. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```

Tạo một đối tượng DigitalSignature mới với chứng chỉ được chỉ định.

**Tham số:**
| Parameter | Type | Mô tả |
| --- | --- | --- |
| certData | byte[] | một mảng byte chứa chứng chỉ |
| password | java.lang.String | Mật khẩu cần thiết để truy cập chứng chỉ. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```

Tạo một đối tượng DigitalSignature mới với đường dẫn tệp chứng chỉ và mật khẩu được chỉ định.

**Tham số:**
| Parameter | Type | Mô tả |
| --- | --- | --- |
| filePath | java.lang.String | Đường dẫn tới tệp chứa chứng chỉ. |
| password | java.lang.String | Mật khẩu cần thiết để truy cập chứng chỉ. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```

Đối tượng chứng chỉ được sử dụng để ký tài liệu. Chỉ đọc byte[].

**Trả về:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```

Nếu chữ ký kỹ thuật số này hợp lệ và tài liệu không bị giả mạo, giá trị này sẽ là true. Chỉ đọc boolean.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```

Thời gian tài liệu được ký. Chỉ đọc java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```

Mục đích của chữ ký. Đọc/ghi String.

**Trả về:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Mục đích của chữ ký. Đọc/ghi String.

**Tham số:**
| Parameter | Type | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |