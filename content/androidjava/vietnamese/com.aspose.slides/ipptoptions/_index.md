---
title: IPptOptions
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Cung cấp các tùy chọn kiểm soát cách một bản trình bày được lưu dưới định dạng PPT.
type: docs
url: /vi/com.aspose.slides/ipptoptions/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

Cung cấp các tùy chọn kiểm soát cách một bản trình bày được lưu dưới dạng PPT.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | Biểu thị GUID lớp đối tượng (CLSID) được lưu trong mục nhập thư mục gốc. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | Biểu thị GUID lớp đối tượng (CLSID) được lưu trong mục nhập thư mục gốc. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```


Biểu thị GUID lớp đối tượng (CLSID) được lưu trong mục nhập thư mục gốc. Có thể được sử dụng để kích hoạt COM cho ứng dụng của tài liệu. Giá trị mặc định là '64818D11-4F9B-11CF-86EA-00AA00B929E8' tương ứng với 'Microsoft Powerpoint.Slide.8'.

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

**Trả về:**
java.util.UUID
### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```


Biểu thị GUID lớp đối tượng (CLSID) được lưu trong mục nhập thư mục gốc. Có thể được sử dụng để kích hoạt COM cho ứng dụng của tài liệu. Giá trị mặc định là '64818D11-4F9B-11CF-86EA-00AA00B929E8' tương ứng với 'Microsoft Powerpoint.Slide.8'.

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