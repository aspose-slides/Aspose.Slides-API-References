---
title: GetImage
second_title: Tham khảo API Aspose.Sildes cho .NET
description: Trả về một đối tượng hình ảnh thu nhỏ với tỷ lệ tùy chỉnh.
type: docs
weight: 80
url: /vi/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

Trả về một đối tượng hình thu nhỏ.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| scaleX | Single | Giá trị dùng để thay đổi tỷ lệ của Thumbnail này theo hướng trục x. |
| scaleY | Single | Giá trị dùng để thay đổi tỷ lệ của Thumbnail này theo hướng trục y. |

### Giá trị trả về

IImage object.

### Ví dụ

Ví dụ sau cho thấy cách tạo hình thu nhỏ từ PowerPoint Presentation.

```csharp
[C#]
// Khởi tạo một lớp Presentation đại diện cho tệp trình chiếu
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Truy cập slide đầu tiên
    ISlide sld = pres.Slides[0];
    // Tạo hình ảnh tỉ lệ đầy đủ
    IImage bmp = sld.GetImage(1f, 1f);
    // Lưu hình ảnh ra đĩa ở định dạng JPEG
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

Ví dụ sau cho thấy cách chuyển đổi các slide thành bitmap và lưu các hình ảnh ở định dạng PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Chuyển đổi slide đầu tiên trong bản trình chiếu thành đối tượng Bitmap
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Lưu hình ảnh ở định dạng PNG
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

Ví dụ sau cho thấy cách chuyển đổi PowerPoint PPT/PPTX sang JPG.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Tạo hình ảnh tỉ lệ đầy đủ
		IImage bmp = sld.GetImage(1f, 1f);
		// Lưu hình ảnh ra đĩa ở định dạng JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

Ví dụ sau cho thấy cách chuyển đổi PowerPoint PPT/PPTX sang JPG với kích thước tùy chỉnh.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Định nghĩa kích thước
	int desiredX = 1200;
	int desiredY = 800;
	// Lấy giá trị tỷ lệ của X và Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Tạo hình ảnh tỉ lệ đầy đủ
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Lưu hình ảnh ra đĩa ở định dạng JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### Xem thêm

* giao diện [IImage](../../iimage)
* lớp [Slide](../../slide)
* không gian tên [Aspose.Slides](../../slide)
* tập hợp [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Trả về một đối tượng hình thu nhỏ (20% kích thước thực).

```csharp
public IImage GetImage()
```

### Xem thêm

* giao diện [IImage](../../iimage)
* lớp [Slide](../../slide)
* không gian tên [Aspose.Slides](../../slide)
* tập hợp [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Trả về một đối tượng hình thu nhỏ với kích thước đã chỉ định.

```csharp
public IImage GetImage(Size imageSize)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| imageSize | Size | Kích thước của hình ảnh sẽ được tạo. |

### Giá trị trả về

Image object.

### Ví dụ

Ví dụ sau cho thấy cách chuyển đổi các slide thành hình ảnh với kích thước tùy chỉnh bằng C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Chuyển đổi slide đầu tiên trong bản trình chiếu thành Bitmap với kích thước đã chỉ định
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Lưu hình ảnh ở định dạng JPEG
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### Xem thêm

* giao diện [IImage](../../iimage)
* lớp [Slide](../../slide)
* không gian tên [Aspose.Slides](../../slide)
* tập hợp [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Trả về một đối tượng hình ảnh tiff hình thu nhỏ với các tham số đã chỉ định.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | ITiffOptions | Các tùy chọn Tiff. |

### Giá trị trả về

Image object.

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| InvalidOperationException | Được ném khi options.SlideLayoutOption là NotesCommentsLayoutOptions và thuộc tính NotesPosition của nó có giá trị NotesPositions.BottomFull. |

### Xem thêm

* giao diện [IImage](../../iimage)
* giao diện [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* lớp [Slide](../../slide)
* không gian tên [Aspose.Slides](../../slide)
* tập hợp [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Trả về một đối tượng hình thu nhỏ.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | IRenderingOptions | Các tùy chọn render. |

### Giá trị trả về

Image object.

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| InvalidOperationException | Được ném khi notesCommentsLayouting.NotesPosition có giá trị NotesPositions.BottomFull |

### Xem thêm

* giao diện [IImage](../../iimage)
* giao diện [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* lớp [Slide](../../slide)
* không gian tên [Aspose.Slides](../../slide)
* tập hợp [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Trả về một đối tượng hình thu nhỏ với tỷ lệ tùy chỉnh.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | IRenderingOptions | Các tùy chọn render. |
| scaleX | Single | Giá trị dùng để thay đổi tỷ lệ của Thumbnail này theo hướng trục x. |
| scaleY | Single | Giá trị dùng để thay đổi tỷ lệ của Thumbnail này theo hướng trục y. |

### Giá trị trả về

Đối tượng Bitmap.

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| InvalidOperationException | Được ném khi notesCommentsLayouting.NotesPosition có giá trị NotesPositions.BottomFull |

### Ví dụ

Ví dụ sau cho thấy cách chuyển đổi các slide có ghi chú và bình luận thành hình ảnh bằng C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Tạo các tùy chọn render
    IRenderingOptions options = new RenderingOptions();
    // Tạo tùy chọn bố cục ghi chú và bình luận
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Đặt vị trí của ghi chú trên trang
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Đặt vị trí của bình luận trên trang
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Đặt độ rộng của khu vực hiển thị bình luận
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Đặt màu cho khu vực bình luận
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Đặt tùy chọn bố cục cho việc render
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Chuyển đổi slide đầu tiên của bản trình chiếu thành đối tượng IImage
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Lưu hình ảnh ở định dạng GIF
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### Xem thêm

* giao diện [IImage](../../iimage)
* giao diện [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* lớp [Slide](../../slide)
* không gian tên [Aspose.Slides](../../slide)
* tập hợp [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Trả về một đối tượng hình thu nhỏ với kích thước đã chỉ định.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| options | IRenderingOptions | Các tùy chọn render. |
| imageSize | Size | Kích thước của hình ảnh sẽ được tạo. |

### Giá trị trả về

Image object.

### Ngoại lệ

| ngoại lệ | điều kiện |
| --- | --- |
| InvalidOperationException | Được ném khi options.SlideLayoutOption là NotesCommentsLayoutOptions và thuộc tính NotesPosition của nó có giá trị NotesPositions.BottomFull. |

### Xem thêm

* giao diện [IImage](../../iimage)
* giao diện [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* lớp [Slide](../../slide)
* không gian tên [Aspose.Slides](../../slide)
* tập hợp [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->