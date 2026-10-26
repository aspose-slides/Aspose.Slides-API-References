---
title: Control
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một điều khiển ActiveX.
type: docs
url: /vi/com.aspose.slides/control/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

Đại diện cho một điều khiển ActiveX.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPersistence()](#getPersistence--) | Lấy phương thức được sử dụng để lưu các thuộc tính của điều khiển ActiveX. |
| [getName()](#getName--) | Lấy hoặc đặt tên của điều khiển này. |
| [setName(String value)](#setName-java.lang.String-) | Lấy hoặc đặt tên của điều khiển này. |
| [getClassId()](#getClassId--) | Lấy ID lớp của điều khiển này. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | Lấy ID lớp của điều khiển này. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Trả về đối tượng thuộc tính tô màu hình ảnh của điều khiển. |
| [getFrame()](#getFrame--) | Trả về hoặc đặt khung của điều khiển. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Trả về hoặc đặt khung của điều khiển. |
| [getProperties()](#getProperties--) | Trả về một bộ sưu tập các thuộc tính ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Xác định tính bền vững của một điều khiển ActiveX khi phương thức được sử dụng để duy trì là PersistStream, PersistStreamInit hoặc PersistStorage. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

Lấy phương thức được sử dụng để lưu các thuộc tính của điều khiển ActiveX. Chỉ đọc [PersistenceType](../../com.aspose.slides/persistencetype).

--------------------

> ```
> Next example shows the using Persistence property for checking if properties of ActiveX object may be changed as XML based ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Sử dụng phương thức của riêng bạn để quản lý các thuộc tính ActiveX được lưu trong tệp nhị phân của nó
>  }
> ```


**Trả về:**
int
### getName() {#getName--}
```
public final String getName()
```

Lấy hoặc đặt tên của điều khiển này. Đọc/ghi String.

**Trả về:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Lấy hoặc đặt tên của điều khiển này. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

Lấy ID lớp của điều khiển này. Chỉ đọc java.util.UUID.

**Trả về:**
java.util.UUID
### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

Lấy ID lớp của điều khiển này. Chỉ đọc java.util.UUID.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.UUID |  |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Trả về đối tượng thuộc tính tô màu hình ảnh của điều khiển. Chỉ đọc [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Trả về:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

Trả về hoặc đặt khung của điều khiển. Đọc/ghi [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Trả về:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

Trả về hoặc đặt khung của điều khiển. Đọc/ghi [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |
### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

Trả về một bộ sưu tập các thuộc tính ActiveX. Chỉ đọc [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

Lưu ý: Aspose.Slides chỉ hỗ trợ các thuộc tính ActiveX dựa trên XML. Nếu các thuộc tính được lưu ở định dạng nhị phân, thuộc tính này sẽ trả về null.

**Trả về:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

Xác định tính bền vững của một điều khiển ActiveX khi phương thức được sử dụng để duy trì là PersistStream, PersistStreamInit hoặc PersistStorage.

--------------------

> ```
> Next example shows the using ActiveXControlBinary property for changing ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Sử dụng phương thức của riêng bạn để quản lý các thuộc tính ActiveX được lưu trong tệp nhị phân của nó
>  }
> ```


**Trả về:**
byte[]
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cơ bản. Chỉ đọc [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình chiếu. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)