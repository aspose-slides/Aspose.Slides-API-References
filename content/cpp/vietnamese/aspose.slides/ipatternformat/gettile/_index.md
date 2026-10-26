---
title: GetTile()
second_title: Tham chiếu API Aspose.Slides cho C++
description: Tạo một hình ảnh ô cho việc lấp đầy mẫu với các màu được chỉ định.
type: docs
weight: 53
url: /vi/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) phương thức


Tạo một hình ảnh ô cho việc lấp đầy mẫu với các màu được chỉ định.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```


### Tham số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Màu nền [System::Drawing::Color](../../../system.drawing/color/) cho mẫu. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Màu trước [System::Drawing::Color](../../../system.drawing/color/) cho mẫu. |

### Giá trị trả về

Ô [IImage](../../iimage/).

## IPatternFormat::GetTile(System::Drawing::Color) phương thức


Tạo một hình ảnh ô cho việc lấp đầy mẫu.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```


### Tham số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | [System::Drawing::Color](../../../system.drawing/color/) mặc định, được định nghĩa trong đối tượng StyleEx của ShapeEx. Các màu của Fill có thể phụ thuộc vào nó. |

### Giá trị trả về

Ô [IImage](../../iimage/).

## Xem thêm

* Định nghĩa kiểu [SharedPtr](../../../system/sharedptr/)
* Lớp [IImage](../../iimage/)
* Lớp [Color](../../../system.drawing/color/)
* Lớp [IPatternFormat](../)
* Không gian tên [Aspose::Slides](../../)
* Thư viện [Aspose.Slides](../../../)