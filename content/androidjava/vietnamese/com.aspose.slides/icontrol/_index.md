---
title: IControl
second_title: Aspose.Slides cho Android qua Tham khảo API Java
description: Đại diện cho một điều khiển ActiveX.
type: docs
url: /vi/com.aspose.slides/icontrol/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

Đại diện cho một điều khiển ActiveX.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getName()](#getName--) | Trả về tên của điều khiển này. |
| [setName(String value)](#setName-java.lang.String-) | Trả về tên của điều khiển này. |
| [getClassId()](#getClassId--) | Lấy class id của điều khiển này. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Trả về đối tượng thuộc tính fill ảnh ControlEx. |
| [getFrame()](#getFrame--) | Trả về hoặc đặt khung của điều khiển. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Trả về hoặc đặt khung của điều khiển. |
| [getProperties()](#getProperties--) | Trả về một tập hợp các thuộc tính ActiveX. |
| [getPersistence()](#getPersistence--) | Lấy phương thức được sử dụng để lưu trữ thuộc tính của điều khiển ActiveX. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | Xác định tính bền vững của một điều khiển ActiveX khi phương thức được sử dụng để lưu là PersistStream, PersistStreamInit hoặc PersistStorage. |
### getName() {#getName--}
```
public abstract String getName()
```


Trả về tên của điều khiển này. Đọc/ghi String.

**Trả về:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Trả về tên của điều khiển này. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```


Lấy class id của điều khiển này. Chỉ đọc java.util.UUID.

**Trả về:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


Trả về đối tượng thuộc tính fill ảnh ControlEx. Chỉ đọc [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Trả về:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```


Trả về hoặc đặt khung của điều khiển. Đọc/ghi [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Trả về:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```


Trả về hoặc đặt khung của điều khiển. Đọc/ghi [IShapeFrame](../../com.aspose.slides/ishapeframe).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```


Trả về một tập hợp các thuộc tính ActiveX. Chỉ đọc [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**Trả về:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```


Lấy phương thức được sử dụng để lưu trữ thuộc tính của điều khiển ActiveX. Chỉ đọc [PersistenceType](../../com.aspose.slides/persistencetype).

**Trả về:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```


Xác định tính bền vững của một điều khiển ActiveX khi phương thức được sử dụng để lưu là PersistStream, PersistStreamInit hoặc PersistStorage.

**Trả về:**
byte[]