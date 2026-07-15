---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Chữ ký số trong tệp đã ký.
type: docs
url: /vi/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Chữ ký số trong tệp đã ký.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCertificate()](#getCertificate--) | Đối tượng chứng chỉ đã được sử dụng để ký tài liệu. |
| [isValid()](#isValid--) | Nếu chữ ký số này hợp lệ và tài liệu chưa bị chỉnh sửa, giá trị này sẽ là true. |
| [getSignTime()](#getSignTime--) | Thời gian tài liệu được ký. |
| [getComments()](#getComments--) | Mục đích của chữ ký. |
| [setComments(String value)](#setComments-java.lang.String-) | Mục đích của chữ ký. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

Đối tượng chứng chỉ đã được sử dụng để ký tài liệu. Chỉ đọc byte[].

**Trả về:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

Nếu chữ ký số này hợp lệ và tài liệu chưa bị chỉnh sửa, giá trị này sẽ là true. Chỉ đọc boolean.

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
public abstract Date getSignTime()
```

Thời gian tài liệu được ký. Chỉ đọc java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.IsValid ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

Mục đích của chữ ký. Đọc/ghi String.

**Trả về:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Mục đích của chữ ký. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |