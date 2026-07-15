---
title: IAlphaBiLevel
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu thị một hiệu ứng Alpha Bi-Level.
type: docs
url: /vi/com.aspose.slides/ialphabilevel/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Biểu thị một hiệu ứng Alpha Bi-Level. Các giá trị Alpha (Độ trong suốt) nhỏ hơn ngưỡng sẽ được thay đổi thành 0 (hoàn toàn trong suốt) và các giá trị alpha lớn hơn hoặc bằng ngưỡng sẽ được thay đổi thành 100% (hoàn toàn không trong suốt).

--------------------

Sử dụng ImageTransformOperationFactory để tạo các thể hiện trong COM.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getThreshold()](#getThreshold--) | Trả về ngưỡng hiệu ứng. |
| [setThreshold(float value)](#setThreshold-float-) | Trả về ngưỡng hiệu ứng. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Trả về ngưỡng hiệu ứng. Đọc/ghi float.

**Trả về:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

Trả về ngưỡng hiệu ứng. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |