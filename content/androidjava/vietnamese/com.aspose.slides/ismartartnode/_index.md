---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: Biểu diễn nút của một sơ đồ SmartArt.
type: docs
url: /vi/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Biểu diễn nút của một sơ đồ SmartArt.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Trả về bộ sưu tập của tất cả các nút con của nút hiện tại. |
| [getShapes()](#getShapes--) | Trả về bộ sưu tập của tất cả các shape liên kết với nút. |
| [getTextFrame()](#getTextFrame--) | Trả về hoặc đặt văn bản của nút. |
| [isAssistant()](#isAssistant--) | Trả về hoặc đặt nút làm trợ lý. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Trả về hoặc đặt nút làm trợ lý. |
| [getLevel()](#getLevel--) | Trả về mức độ lồng nhau của nút. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho dấu đầu dòng của nút. |
| [getPosition()](#getPosition--) | Trả về hoặc đặt vị trí dựa trên chỉ số 0 của nút trong số các nút cùng cấp. |
| [setPosition(int value)](#setPosition-int-) | Trả về hoặc đặt vị trí dựa trên chỉ số 0 của nút trong số các nút cùng cấp. |
| [isHidden()](#isHidden--) | Trả về true nếu nút này là nút ẩn trong mô hình dữ liệu. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Trả về hoặc đặt kiểu bố cục biểu đồ tổ chức liên kết với nút hiện tại. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Trả về hoặc đặt kiểu bố cục biểu đồ tổ chức liên kết với nút hiện tại. |
| [remove()](#remove--) | Xóa nút hiện tại. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Trả về bộ sưu tập của tất cả các nút con của nút hiện tại. Chỉ đọc [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Trả về:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Trả về bộ sưu tập của tất cả các shape liên kết với nút. Chỉ đọc [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Trả về:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Trả về hoặc đặt văn bản của nút. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

Trả về hoặc đặt nút làm trợ lý. Đọc/ghi boolean.

**Trả về:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Trả về hoặc đặt nút làm trợ lý. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

Trả về mức độ lồng nhau của nút. Chỉ đọc int.

**Trả về:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho dấu đầu dòng của nút. Lưu ý: có thể trả về null cho một số loại bố cục SmartArt không cung cấp dấu đầu dòng cho các nút. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Trả về hoặc đặt vị trí dựa trên chỉ số 0 của nút trong số các nút cùng cấp. Đọc/ghi int.

**Trả về:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Trả về hoặc đặt vị trí dựa trên chỉ số 0 của nút trong số các nút cùng cấp. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Trả về true nếu nút này là nút ẩn trong mô hình dữ liệu. Chỉ đọc boolean.

**Trả về:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Trả về hoặc đặt kiểu bố cục biểu đồ tổ chức liên kết với nút hiện tại. Đọc/ghi [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Trả về:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Trả về hoặc đặt kiểu bố cục biểu đồ tổ chức liên kết với nút hiện tại. Đọc/ghi [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

Xóa nút hiện tại.

**Trả về:**
boolean - true nếu xóa thành công, ngược lại false.