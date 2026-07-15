---
title: License
second_title: Tham chiếu API Aspose.Slides cho Android qua Java
description: Cung cấp các phương thức để cấp phép cho thành phần.
type: docs
url: /vi/com.aspose.slides/license/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ILicense](../../com.aspose.slides/ilicense)
```
public final class License implements ILicense
```

Cung cấp các phương thức để cấp phép cho thành phần.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [License()](#License--) | Khởi tạo một thể hiện mới của lớp này. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Cấp phép cho thành phần. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Cấp phép cho thành phần. |
| [getVersion()](#getVersion--) | Trả về phiên bản của Aspose.Slides cho Android qua Java. |
| [resetLicense()](#resetLicense--) | Đặt lại giấy phép. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


Khởi tạo một thể hiện mới của lớp này.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream stream)
```


Cấp phép cho thành phần.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Luồng chứa giấy phép. Sử dụng null để chuyển sang chế độ đánh giá. |

### setLicense(String namePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String namePath)
```


Cấp phép cho thành phần.

```
In this example, an attempt will be made to find a license file named MyLicense.lic
 in the folder that contains the component, in the folder that contains the calling assembly,
 in the folder of the entry assembly and then in the embedded resources of the calling assembly.
```

--------------------

> ```
> License license = new License();
>  license.setLicense("MyLicense.lic");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| namePath | java.lang.String | Có thể là tên tệp đầy đủ hoặc ngắn hoặc tên của tài nguyên được nhúng. Sử dụng chuỗi trống để chuyển sang chế độ đánh giá. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Trả về phiên bản của Aspose.Slides cho Android qua Java.

**Trả về:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


Đặt lại giấy phép. Sử dụng phương pháp này để đặt lại giấy phép trong thành phần.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```


### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


Kiểm tra xem licence đã được áp dụng cho thành phần chưa

**Trả về:**
boolean