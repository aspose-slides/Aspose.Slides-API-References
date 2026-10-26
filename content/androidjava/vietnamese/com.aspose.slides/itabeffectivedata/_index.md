---
title: ITabEffectiveData
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Đối tượng bất biến chứa các thuộc tính dừng tab của văn bản hiệu quả.
type: docs
url: /vi/com.aspose.slides/itabeffectivedata/
---
**Tất cả các giao diện được thực thi:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Đối tượng bất biến chứa các thuộc tính dừng tab của văn bản hiệu quả.

--------------------

Giao diện này được sử dụng như một phần của [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPosition()](#getPosition--) | Returns position of a tab. |
| [getAlignment()](#getAlignment--) | Returns align style of a tab. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```

Trả về vị trí của một tab. Gán thuộc tính này có thể thay đổi chỉ mục của tab trong bộ sưu tập và làm cho Enumerator không hợp lệ. Chỉ đọc double.

**Trả về:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Trả về kiểu căn chỉnh của một tab. Chỉ đọc [TabAlignment](../../com.aspose.slides/tabalignment).

**Trả về:**
int