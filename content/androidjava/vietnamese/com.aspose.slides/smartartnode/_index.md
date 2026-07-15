---
title: SmartArtNode
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn nút của một đối tượng SmartArt
type: docs
url: /vi/com.aspose.slides/smartartnode/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Biểu diễn nút của một đối tượng SmartArt
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Trả về tập hợp các nút con của nút hiện tại. |
| [getShapes()](#getShapes--) | Trả về tập hợp tất cả các hình dạng liên kết với nút. |
| [getTextFrame()](#getTextFrame--) | Trả về khung văn bản của nút. |
| [isAssistant()](#isAssistant--) | Trả về hoặc đặt nút là trợ lý. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Trả về hoặc đặt nút là trợ lý. |
| [getLevel()](#getLevel--) | Trả về mức lồng nhau của nút. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho dấu đầu dòng của nút. |
| [getPosition()](#getPosition--) | Trả về hoặc đặt vị trí dựa trên chỉ số 0 của nút trong số các nút anh chị em. |
| [setPosition(int value)](#setPosition-int-) | Trả về hoặc đặt vị trí dựa trên chỉ số 0 của nút trong số các nút anh chị em. |
| [isHidden()](#isHidden--) | Trả về true nếu nút này là nút ẩn trong mô hình dữ liệu. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Trả về hoặc đặt kiểu bố trí biểu đồ tổ chức liên kết với nút hiện tại. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Trả về hoặc đặt kiểu bố trí biểu đồ tổ chức liên kết với nút hiện tại. |
| [remove()](#remove--) | Xóa nút hiện tại. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Trả về tập hợp các nút con của nút hiện tại. Chỉ đọc [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Trả về:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Trả về tập hợp tất cả các hình dạng liên kết với nút. Chỉ đọc [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Trả về:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Trả về khung văn bản của nút. Chỉ đọc [ITextFrame](../../com.aspose.slides/itextframe).

**Trả về:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

Trả về hoặc đặt nút là trợ lý. Đọc/ghi boolean.

**Trả về:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Trả về hoặc đặt nút là trợ lý. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

Trả về mức lồng nhau của nút. Chỉ đọc int.

**Trả về:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

Trả về đối tượng FillFormat chứa các thuộc tính định dạng tô màu cho dấu đầu dòng của nút. Lưu ý: có thể trả về null cho một số loại bố trí SmartArt không cung cấp dấu đầu dòng cho các nút. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Trả về hoặc đặt vị trí dựa trên chỉ số 0 của nút trong số các nút anh chị em. Đọc/ghi int.

**Trả về:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Trả về hoặc đặt vị trí dựa trên chỉ số 0 của nút trong số các nút anh chị em. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Trả về true nếu nút này là nút ẩn trong mô hình dữ liệu. Chỉ đọc boolean.

**Trả về:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Trả về hoặc đặt kiểu bố trí biểu đồ tổ chức liên kết với nút hiện tại. Đọc/ghi [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Trả về:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Trả về hoặc đặt kiểu bố trí biểu đồ tổ chức liên kết với nút hiện tại. Đọc/ghi [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

Xóa nút hiện tại.

**Trả về:**
boolean - true nếu xóa thành công, ngược lại false