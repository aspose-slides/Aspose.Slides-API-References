---
title: PptOptions
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng PPT.
type: docs
url: /vi/com.aspose.slides/pptoptions/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng PPT.
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Đại diện cho GUID lớp đối tượng (CLSID) được lưu trong mục nhập thư mục gốc. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Đại diện cho GUID lớp đối tượng (CLSID) được lưu trong mục nhập thư mục gốc. |
### PptOptions() {#PptOptions--}
```
public PptOptions()
```


### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```


Đại diện cho GUID lớp đối tượng (CLSID) được lưu trong mục nhập thư mục gốc. Có thể được sử dụng để kích hoạt COM của ứng dụng tài liệu. Giá trị mặc định là '64818D11-4F9B-11CF-86EA-00AA00B929E8' tương ứng với 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// đặt CLSID thành 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Giá trị trả về:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```


Đại diện cho GUID lớp đối tượng (CLSID) được lưu trong mục nhập thư mục gốc. Có thể được sử dụng để kích hoạt COM của ứng dụng tài liệu. Giá trị mặc định là '64818D11-4F9B-11CF-86EA-00AA00B929E8' tương ứng với 'Microsoft Powerpoint.Slide.8'.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// đặt CLSID thành 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.UUID |  |