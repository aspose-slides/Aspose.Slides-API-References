---
title: License
second_title: Tham chiếu API Aspose.Slides cho Java
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

## Các phương thức khởi tạo

| Constructor | Description |
| --- | --- |
| [License()](#License--) | Khởi tạo một thể hiện mới của lớp này. |
## Các phương thức

| Method | Description |
| --- | --- |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Cấp phép cho thành phần. |
| [setLicense(String namePath)](#setLicense-java.lang.String-) | Cấp phép cho thành phần. |
| [getVersion()](#getVersion--) | Trả về phiên bản của Aspose.Slides cho Java. |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| namePath | java.lang.String | Có thể là tên tệp đầy đủ hoặc ngắn hoặc tên của tài nguyên nhúng. Sử dụng chuỗi rỗng để chuyển sang chế độ đánh giá. |

### getVersion() {#getVersion--}
```
public static final String getVersion()
```


Trả về phiên bản của Aspose.Slides cho Java.

**Giá trị trả về:**
java.lang.String
### resetLicense() {#resetLicense--}
```
public final void resetLicense()
```


Đặt lại giấy phép. Sử dụng phương thức này để đặt lại giấy phép trong thành phần.

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```


Kiểm tra xem giấy phép đã được áp dụng cho thành phần hay chưa

**Giá trị trả về:**
boolean