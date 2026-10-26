---
title: IBaseSlide
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn dữ liệu chung cho tất cả các loại slide.
type: docs
url: /vi/com.aspose.slides/ibaseslide/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Biểu diễn dữ liệu chung cho tất cả các loại slide.
## Phương thức

| Method | Description |
| --- | --- |
| [getShapes()](#getShapes--) | Trả về các shape của một slide. |
| [getControls()](#getControls--) | Trả về tập hợp các điều khiển ActiveX trên một slide. |
| [getName()](#getName--) | Trả về hoặc đặt tên của một slide. |
| [setName(String value)](#setName-java.lang.String-) | Trả về hoặc đặt tên của một slide. |
| [getSlideId()](#getSlideId--) | Trả về ID của một slide. |
| [getCustomData()](#getCustomData--) | Trả về dữ liệu tuỳ chỉnh của slide. |
| [getTimeline()](#getTimeline--) | Trả về đối tượng animation timeline. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Trả về đối tượng TransitionEx chứa thông tin về cách slide được chỉ định chuyển tiếp trong buổi trình chiếu. |
| [getBackground()](#getBackground--) | Trả về nền của slide. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Cung cấp truy cập dễ dàng tới các hyperlink được chứa. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Xác định xem các shape trên master slide có được hiển thị trên các slide hay không. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Xác định xem các shape trên master slide có được hiển thị trên các slide hay không. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Tìm lần xuất hiện đầu tiên của một shape có văn bản thay thế được chỉ định. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Nối các run có định dạng giống nhau trong tất cả các đoạn trong tất cả các shape có thể chấp nhận. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Xác định liệu hai đối tượng IBaseSlide có bằng nhau hay không. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

Trả về các shape của một slide. Chỉ đọc [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Trả về:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

Trả về tập hợp các điều khiển ActiveX trên một slide. Chỉ đọc [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Trả về:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```

Trả về hoặc đặt tên của một slide. Đọc/ghi String.

**Trả về:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Trả về hoặc đặt tên của một slide. Đọc/ghi String.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

Trả về ID của một slide. Chỉ đọc long.

**Trả về:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Trả về dữ liệu tuỳ chỉnh của slide. Chỉ đọc [ICustomData](../../com.aspose.slides/icustomdata).

**Trả về:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

Trả về đối tượng animation timeline. Chỉ đọc [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Trả về:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

Trả về đối tượng TransitionEx chứa thông tin về cách slide được chỉ định chuyển tiếp trong buổi trình chiếu. Chỉ đọc [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Trả về:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

Trả về nền của slide. Chỉ đọc [IBackground](../../com.aspose.slides/ibackground).

**Trả về:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Cung cấp truy cập dễ dàng tới các hyperlink được chứa. Chỉ đọc [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Trả về:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Xác định xem các shape trên master slide có được hiển thị trên các slide hay không. Đối với master slide, thuộc tính này luôn trả về false. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Xác định xem các shape trên master slide có được hiển thị trên các slide hay không. Đối với master slide, thuộc tính này luôn trả về false. Đọc/ghi boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

Tìm lần xuất hiện đầu tiên của một shape có văn bản thay thế được chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| altText | java.lang.String | Văn bản thay thế. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx object hoặc null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Nối các run có định dạng giống nhau trong tất cả các đoạn trong tất cả các shape có thể chấp nhận.
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

Xác định liệu hai đối tượng IBaseSlide có bằng nhau hay không. Giá trị trả về được tính dựa trên cấu trúc slide và nội dung tĩnh. Hai slide được coi bằng nhau nếu tất cả các shape, kiểu, văn bản, animation và các thiết lập khác, v.v. đều bằng nhau. So sánh không xét đến các giá trị định danh duy nhất, chẳng hạn SlideId, và nội dung động, chẳng hạn giá trị ngày hiện tại trong Placeholder ngày.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | The IBaseSlide to compare with the current IBaseSlide. |

**Trả về:**
boolean - **true** nếu IBaseSlide được chỉ định bằng với IBaseSlide hiện tại; nếu không, **false**.