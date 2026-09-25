---
title: get_image method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Trả về một đối tượng Thumbnail Image (20% kích thước thực).

```python
def get_image(self):
    ...
```

## get_image(self, image_size) {#asposeslidessize}
Trả về một đối tượng Thumbnail Image với kích thước đã chỉ định.

### Returns
Đối tượng Image.

```python
def get_image(self, image_size):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/vi/aspose.slides/size) | Kích thước của hình ảnh sẽ tạo. |

## get_image(self, options) {#asposeslidesexportitiffoptions}
Trả về một đối tượng Thumbnail tiff image với các tham số đã chỉ định.

### Returns
Đối tượng Image.

```python
def get_image(self, options):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/vi/aspose.slides.export/itiffoptions) | Các tùy chọn Tiff. |

### Exceptions
| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Bị ném khi options.SlideLayoutOption là NotesCommentsLayoutingOptions và thuộc tính NotesPosition của nó có giá trị NotesPositions.BottomFull. |

## get_image(self, options) {#asposeslidesexportirenderingoptions}
Trả về một đối tượng Thumbnail Image.

### Returns
Đối tượng Image.

```python
def get_image(self, options):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/vi/aspose.slides.export/irenderingoptions) | Các tùy chọn Rendering. |

### Exceptions
| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Bị ném khi notesCommentsLayouting.NotesPosition có giá trị NotesPositions.BottomFull |

## get_image(self, scale_x, scale_y) {#float-float}
Trả về một đối tượng Thumbnail Image với tỷ lệ tùy chỉnh.

### Returns
Đối tượng IImage.

```python
def get_image(self, scale_x, scale_y):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| scale_x | **float** | Giá trị dùng để tỷ lệ Thumbnail này theo hướng trục x. |
| scale_y | **float** | Giá trị dùng để tỷ lệ Thumbnail này theo hướng trục y. |

## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Trả về một đối tượng Thumbnail Image với kích thước đã chỉ định.

### Returns
Đối tượng Image.

```python
def get_image(self, options, image_size):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/vi/aspose.slides.export/irenderingoptions) | Các tùy chọn Rendering. |
| image_size | [`Size`](/slides/python-net/vi/aspose.slides/size) | Kích thước của hình ảnh sẽ tạo. |

### Exceptions
| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Bị ném khi options.SlideLayoutOption là NotesCommentsLayoutingOptions và thuộc tính NotesPosition của nó có giá trị NotesPositions.BottomFull. |

## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Trả về một đối tượng Thumbnail Image với tỷ lệ tùy chỉnh.

### Returns
Các đối tượng Bitmap.

```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/vi/aspose.slides.export/irenderingoptions) | Các tùy chọn Rendering. |
| scale_x | **float** | Giá trị dùng để tỷ lệ Thumbnail này theo hướng trục x. |
| scale_y | **float** | Giá trị dùng để tỷ lệ Thumbnail này theo hướng trục y. |

### Exceptions
| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Bị ném khi notesCommentsLayouting.NotesPosition có giá trị NotesPositions.BottomFull |

### Xem thêm
* lớp [`IImage`](/slides/python-net/vi/aspose.slides/iimage)
* lớp [`IRenderingOptions`](/slides/python-net/vi/aspose.slides.export/irenderingoptions)
* lớp [`ITiffOptions`](/slides/python-net/vi/aspose.slides.export/itiffoptions)
* lớp [`Slide`](/slides/python-net/vi/aspose.slides/slide)
* lớp [`Size`](/slides/python-net/vi/aspose.slides/size)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)