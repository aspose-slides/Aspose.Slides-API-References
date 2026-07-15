---
title: IOleObjectFrame
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một đối tượng OLE trên một slide.
type: docs
url: /vi/com.aspose.slides/ioleobjectframe/
---
**Tất cả Các Giao Diện Đã Triển Khai:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Đại diện cho một đối tượng OLE trên một slide.
## Phương thức

| Method | Description |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Trả về đối tượng thuộc tính điền hình ảnh OleObject. |
| [getObjectName()](#getObjectName--) | Trả về hoặc đặt tên của một đối tượng. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Trả về hoặc đặt tên của một đối tượng. |
| [getEmbeddedData()](#getEmbeddedData--) | Lấy thông tin về dữ liệu OLE được nhúng. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Đặt thông tin về dữ liệu OLE được nhúng. |
| [getObjectProgId()](#getObjectProgId--) | Trả về ProgID của một đối tượng. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Trả về ProgID của một đối tượng. |
| [getLinkFileName()](#getLinkFileName--) | Trả về đường dẫn đầy đủ tới tệp được liên kết. |
| [getLinkPathLong()](#getLinkPathLong--) | Trả về đường dẫn đầy đủ tới tệp được liên kết. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Trả về đường dẫn đầy đủ tới tệp được liên kết. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Trả về đường dẫn tương đối tới tệp được liên kết nếu có, nếu không trả về chuỗi trống. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Trả về tên tệp của đối tượng OLE đã nhúng |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Trả về đường dẫn của đối tượng OLE đã nhúng |
| [isObjectIcon()](#isObjectIcon--) | Xác định xem một đối tượng có hiển thị dưới dạng biểu tượng hay không. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Xác định xem một đối tượng có hiển thị dưới dạng biểu tượng hay không. |
| [isObjectLink()](#isObjectLink--) | Xác định xem một đối tượng có được liên kết tới tệp bên ngoài hay không. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Xác định xem đối tượng nhúng đã liên kết có tự động cập nhật khi bản trình chiếu được mở hoặc in hay không. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Xác định xem đối tượng nhúng đã liên kết có tự động cập nhật khi bản trình chiếu được mở hoặc in hay không. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Trả về hoặc đặt tiêu đề cho biểu tượng OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Trả về hoặc đặt tiêu đề cho biểu tượng OleObject. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Trả về đối tượng thuộc tính điền hình ảnh OleObject. Chỉ đọc [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Trả về:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

Trả về hoặc đặt tên của một đối tượng. Đọc/ghi String.

**Trả về:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

Trả về hoặc đặt tên của một đối tượng. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

Lấy thông tin về dữ liệu OLE được nhúng. Chỉ đọc [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Trả về:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Đặt thông tin về dữ liệu OLE được nhúng.

--------------------

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Dữ liệu nhúng [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

Phương thức này thay đổi các thuộc tính của đối tượng để phản ánh dữ liệu mới và đặt cờ IsObjectLink thành false, cho biết đối tượng OLE được nhúng. |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

Trả về ProgID của một đối tượng. Chỉ đọc String.

**Trả về:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

Trả về ProgID của một đối tượng. Chỉ đọc String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

Trả về đường dẫn đầy đủ tới tệp được liên kết. Tên tệp ngắn sẽ được sử dụng. Chỉ đọc String.

**Trả về:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Trả về đường dẫn đầy đủ tới tệp được liên kết. Tên tệp dài sẽ được sử dụng. Đọc/ghi String.

**Trả về:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Trả về đường dẫn đầy đủ tới tệp được liên kết. Tên tệp dài sẽ được sử dụng. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

Trả về đường dẫn tương đối tới tệp được liên kết nếu có, nếu không trả về chuỗi trống. Chỉ đọc String.

--------------------

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


--------------------

Trong các bản trình chiếu Ppt, một số liên kết đối tượng Ole có thể có dạng biểu diễn tương đối.

**Trả về:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

Trả về tên tệp của đối tượng OLE đã nhúng

**Trả về:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

Trả về đường dẫn của đối tượng OLE đã nhúng

**Trả về:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

Xác định xem một đối tượng có hiển thị dưới dạng biểu tượng hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

Xác định xem một đối tượng có hiển thị dưới dạng biểu tượng hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

Xác định xem một đối tượng có được liên kết tới tệp bên ngoài hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

Xác định xem đối tượng nhúng đã liên kết có tự động cập nhật khi bản trình chiếu được mở hoặc in hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

Xác định xem đối tượng nhúng đã liên kết có tự động cập nhật khi bản trình chiếu được mở hoặc in hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

Trả về hoặc đặt tiêu đề cho biểu tượng OleObject. Đọc/ghi String.

--------------------

Khi IsObjectIcon == false giá trị này sẽ bị bỏ qua. Chuỗi có thể bị cắt ngắn tùy theo kích thước của biểu tượng OLE.

**Trả về:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

Trả về hoặc đặt tiêu đề cho biểu tượng OleObject. Đọc/ghi String.

--------------------

Khi IsObjectIcon == false giá trị này sẽ bị bỏ qua. Chuỗi có thể bị cắt ngắn tùy theo kích thước của biểu tượng OLE.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |