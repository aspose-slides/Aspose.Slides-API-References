---
title: BaseSlide
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đại diện cho dữ liệu chung cho tất cả các loại slide.
type: docs
url: /vi/com.aspose.slides/baseslide/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện được triển khai:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Đại diện cho dữ liệu chung cho tất cả các loại slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShapes()](#getShapes--) | Trả về các hình dạng của một slide. |
| [getControls()](#getControls--) | Trả về bộ sưu tập các điều khiển ActiveX trên một slide. |
| [getName()](#getName--) | Trả về hoặc đặt tên của một slide. |
| [setName(String value)](#setName-java.lang.String-) | Trả về hoặc đặt tên của một slide. |
| [getSlideId()](#getSlideId--) | Trả về ID của một slide. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Xác định liệu hai đối tượng IBaseSlide có bằng nhau hay không. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Nối các chuỗi có cùng định dạng trong tất cả các đoạn văn và tất cả các hình dạng chấp nhận được. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Nối các chuỗi có cùng định dạng trong tất cả các đoạn văn và trong tất cả các hình dạng chấp nhận được. |
| [createThemeEffective()](#createThemeEffective--) | Trả về một theme hiệu quả cho slide này. |
| [getCustomData()](#getCustomData--) | Trả về dữ liệu tùy chỉnh của slide. |
| [getTimeline()](#getTimeline--) | Trả về đối tượng timeline hoạt ảnh. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Trả về đối tượng Transition chứa thông tin về cách slide đã chỉ định tiến triển trong một buổi trình chiếu. |
| [getBackground()](#getBackground--) | Trả về nền của slide. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Cung cấp quyền truy cập dễ dàng tới các hyperlink đã chứa. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Chỉ định xem các hình dạng trên master slide có nên được hiển thị trên các slide hay không. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Chỉ định xem các hình dạng trên master slide có nên được hiển thị trên các slide hay không. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Tìm kiếm lần xuất hiện đầu tiên của một hình dạng có văn bản thay thế được chỉ định. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Trả về giao diện IPresentation. |
| [getSlide()](#getSlide--) |  |
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Trả về các hình dạng của một slide. Chỉ đọc [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Trả về:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```


Trả về bộ sưu tập các điều khiển ActiveX trên một slide. Chỉ đọc [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Trả về:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```


Trả về hoặc đặt tên của một slide. Đọc/ghi String.

**Trả về:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Trả về hoặc đặt tên của một slide. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```


Trả về ID của một slide. Chỉ đọc long.

**Trả về:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```


Xác định liệu hai đối tượng IBaseSlide có bằng nhau hay không. Giá trị trả về được tính dựa trên cấu trúc và nội dung tĩnh của slide. Hai slide được coi là bằng nhau nếu tất cả các hình dạng, kiểu dáng, văn bản, hoạt ảnh và các cài đặt khác, v.v. đều bằng nhau. So sánh không xét đến các giá trị định danh duy nhất, ví dụ SlideId và nội dung động, ví dụ giá trị ngày hiện tại trong Date Placeholder.

--------------------

> ```
> Ví dụ sau đây cho thấy cách so sánh hai slide.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide để so sánh với IBaseSlide hiện tại. |

**Trả về:**
boolean -  **true**  nếu IBaseSlide đã chỉ định bằng với IBaseSlide hiện tại; ngược lại,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```


Nối các chuỗi có cùng định dạng trong tất cả các đoạn văn và tất cả các hình dạng chấp nhận được.
### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```


Nối các chuỗi có cùng định dạng trong tất cả các đoạn văn và trong tất cả các hình dạng chấp nhận được.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Trả về một theme hiệu quả cho slide này.

**Trả về:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Trả về dữ liệu tùy chỉnh của slide. Chỉ đọc [ICustomData](../../com.aspose.slides/icustomdata).

**Trả về:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```


Trả về đối tượng timeline hoạt ảnh. Chỉ đọc [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Trả về:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```


Trả về đối tượng Transition chứa thông tin về cách slide đã chỉ định tiến triển trong một buổi trình chiếu. Chỉ đọc [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Trả về:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```


Trả về nền của slide. Chỉ đọc [IBackground](../../com.aspose.slides/ibackground).

**Trả về:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Cung cấp quyền truy cập dễ dàng tới các hyperlink đã chứa. Chỉ đọc [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Trả về:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


Chỉ định xem các hình dạng trên master slide có nên được hiển thị trên các slide hay không. Đối với master slide tự nó thuộc tính này luôn trả về false. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


Chỉ định xem các hình dạng trên master slide có nên được hiển thị trên các slide hay không. Đối với master slide tự nó thuộc tính này luôn trả về false. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```


Tìm kiếm lần xuất hiện đầu tiên của một hình dạng có văn bản thay thế được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| altText | java.lang.String | Văn bản thay thế. |

**Trả về:**
[IShape](../../com.aspose.slides/ishape) - Shape object or null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Trả về giao diện IPresentation. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Trả về slide cơ bản. Chỉ đọc [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)