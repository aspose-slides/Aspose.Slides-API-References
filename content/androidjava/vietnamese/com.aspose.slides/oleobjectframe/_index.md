---
title: OleObjectFrame
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một đối tượng OLE trên một slide.
type: docs
url: /vi/com.aspose.slides/oleobjectframe/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Biểu diễn một OLE object trên một slide.

--------------------

> ```
>  // Tải tệp PPTX vào đối tượng Presentation
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Truy cập slide đầu tiên
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Ép kiểu shape sang OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Đọc đối tượng OLE và ghi nó ra đĩa
>      if (oleObjectFrame != null) {
>          // Lấy dữ liệu tệp nhúng
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Lấy phần mở rộng tệp nhúng
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Tạo đường dẫn để lưu tệp đã trích xuất
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Lưu dữ liệu đã trích xuất
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream(extractedPath);
>              fos.write(data);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Trả về đối tượng thuộc tính tô màu hình ảnh OleObject. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Trả về hoặc đặt tiêu đề cho biểu tượng OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Trả về hoặc đặt tiêu đề cho biểu tượng OleObject. |
| [getObjectName()](#getObjectName--) | Trả về hoặc đặt tên của một đối tượng. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Trả về hoặc đặt tên của một đối tượng. |
| [getObjectProgId()](#getObjectProgId--) | Trả về ProgID của một đối tượng. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Trả về ProgID của một đối tượng. |
| [getLinkFileName()](#getLinkFileName--) | Trả về đường dẫn đầy đủ tới tệp tin được liên kết. |
| [getLinkPathLong()](#getLinkPathLong--) | Trả về đường dẫn đầy đủ tới tệp tin được liên kết. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Trả về đường dẫn đầy đủ tới tệp tin được liên kết. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Trả về đường dẫn tương đối tới tệp tin được liên kết nếu có, nếu không trả về chuỗi rỗng. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Trả về tên tệp của đối tượng OLE được nhúng |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Trả về đường dẫn của đối tượng OLE được nhúng |
| [getEmbeddedData()](#getEmbeddedData--) | Lấy hoặc đặt thông tin về dữ liệu OLE được nhúng. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Đặt thông tin về dữ liệu OLE được nhúng. |
| [isObjectIcon()](#isObjectIcon--) | Xác định xem một đối tượng có hiển thị dưới dạng biểu tượng hay không. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Xác định xem một đối tượng có hiển thị dưới dạng biểu tượng hay không. |
| [isObjectLink()](#isObjectLink--) | Xác định xem một đối tượng có được liên kết tới tệp tin bên ngoài hay không. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Xác định xem đối tượng được nhúng và liên kết có tự động cập nhật khi bản trình chiếu được mở hoặc in hay không. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Xác định xem đối tượng được nhúng và liên kết có tự động cập nhật khi bản trình chiếu được mở hoặc in hay không. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Trả về đối tượng thuộc tính tô màu hình ảnh OleObject. Chỉ đọc [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Trả về:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

Trả về hoặc đặt tiêu đề cho biểu tượng OleObject. Đọc/ghi String.

--------------------

Khi IsObjectIcon == false giá trị này sẽ bị bỏ qua. Chuỗi có thể bị cắt ngắn tùy theo kích thước của biểu tượng Ole.

**Trả về:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Trả về hoặc đặt tiêu đề cho biểu tượng OleObject. Đọc/ghi String.

--------------------

Khi IsObjectIcon == false giá trị này sẽ bị bỏ qua. Chuỗi có thể bị cắt ngắn tùy theo kích thước của biểu tượng Ole.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Trả về hoặc đặt tên của một đối tượng. Đọc/ghi String.

**Trả về:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Trả về hoặc đặt tên của một đối tượng. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

Trả về ProgID của một đối tượng. Chỉ đọc String.

**Trả về:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

Trả về ProgID của một đối tượng. Chỉ đọc String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

Trả về đường dẫn đầy đủ tới tệp tin được liên kết. Tên tệp ngắn sẽ được sử dụng. Chỉ đọc String.

**Trả về:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Trả về đường dẫn đầy đủ tới tệp tin được liên kết. Tên tệp dài sẽ được sử dụng. Đọc/ghi String.

**Trả về:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Trả về đường dẫn đầy đủ tới tệp tin được liên kết. Tên tệp dài sẽ được sử dụng. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

Trả về đường dẫn tương đối tới tệp tin được liên kết nếu có, nếu không trả về chuỗi rỗng. Chỉ đọc String.

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

Trong các bản trình chiếu Ppt, một số liên kết đối tượng Ole có thể có dạng đại diện tương đối.

**Trả về:**
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

Trả về tên tệp của đối tượng OLE được nhúng

**Trả về:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

Trả về đường dẫn của đối tượng OLE được nhúng

**Trả về:**
java.lang.String

### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

Lấy hoặc đặt thông tin về dữ liệu OLE được nhúng. Đọc/ghi [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Trả về:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Đặt thông tin về dữ liệu OLE được nhúng.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

Xác định xem một đối tượng có hiển thị dưới dạng biểu tượng hay không. Đọc/ghi boolean .

**Trả về:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

Xác định xem một đối tượng có hiển thị dưới dạng biểu tượng hay không. Đọc/ghi boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

Xác định xem một đối tượng có được liên kết tới tệp tin bên ngoài hay không. Chỉ đọc boolean .

**Trả về:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Xác định xem đối tượng nhúng được liên kết có tự động cập nhật khi bản trình chiếu được mở hoặc in hay không. Đọc/ghi boolean .

**Trả về:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Xác định xem đối tượng nhúng được liên kết có tự động cập nhật khi bản trình chiếu được mở hoặc in hay không. Đọc/ghi boolean .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |