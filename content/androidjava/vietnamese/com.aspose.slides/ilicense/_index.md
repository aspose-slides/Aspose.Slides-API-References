---
title: ILicense
second_title: Aspose.Slides for Android via Java API Reference
description: Cung cấp các phương thức để cấp phép cho thành phần.
type: docs
url: /vi/com.aspose.slides/ilicense/
---```
public interface ILicense
```

Cung cấp các phương thức để cấp phép cho thành phần.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Cấp phép cho thành phần. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Cấp phép cho thành phần. |
| [resetLicense()](#resetLicense--) | Đặt lại giấy phép |
| [isLicensed()](#isLicensed--) | Kiểm tra xem giấy phép đã được áp dụng cho thành phần chưa |
### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public abstract void setLicense(String licenseName)
```


Cấp phép cho thành phần.

--------------------

> ```
> In this example, an attempt will be made to find a license file named MyLicense.lic
>  in the folder that contains the component, in the folder that contains the calling assembly,
>  in the folder of the entry assembly and then in the embedded resources of the calling assembly.
>  
>  License license = new License();
>  license.setLicense("MyLicense.lic");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| licenseName | java.lang.String | Có thể là tên tệp đầy đủ hoặc ngắn hoặc tên của tài nguyên nhúng. Sử dụng chuỗi trống để chuyển sang chế độ đánh giá.

--------------------

Cố gắng tìm giấy phép ở các vị trí sau:

1. Đường dẫn rõ ràng.
2. Thư mục của assembly thành phần.
3. Thư mục của assembly gọi của khách hàng.
4. Thư mục của entry assembly.
5. Một tài nguyên nhúng trong assembly gọi của khách hàng. |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public abstract void setLicense(InputStream stream)
```


Cấp phép cho thành phần.

--------------------

> ```
> License license = new License();
>  license.setLicense(myStream);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| stream | java.io.InputStream | Một luồng chứa giấy phép.

--------------------

Sử dụng phương pháp này để tải giấy phép từ một luồng. |

### resetLicense() {#resetLicense--}
```
public abstract void resetLicense()
```


Đặt lại giấy phép

--------------------

> ```
> License license = new License();
>  license.resetLicense();
> ```

--------------------

Sử dụng phương pháp này để đặt lại giấy phép trong thành phần

### isLicensed() {#isLicensed--}
```
public abstract boolean isLicensed()
```


Kiểm tra xem giấy phép đã được áp dụng cho thành phần chưa

**Trả về:**
boolean - true nếu thành phần đã được cấp phép, ngược lại false