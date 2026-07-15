---
title: IBiLevelEffectiveData
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đối tượng bất biến đại diện cho hiệu ứng Hai mức đen/trắng.
type: docs
url: /vi/com.aspose.slides/ibleveleffectivedata/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Đối tượng không thể thay đổi đại diện cho hiệu ứng Hai mức (đen/trắng). Các màu đầu vào có độ sáng ít hơn giá trị ngưỡng đã chỉ định sẽ được đổi thành màu đen. Các màu đầu vào có độ sáng lớn hơn hoặc bằng giá trị đã chỉ định sẽ được đặt thành màu trắng. Các giá trị hiệu ứng alpha không bị ảnh hưởng bởi hiệu ứng này.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getThreshold()](#getThreshold--) | Trả về giá trị ngưỡng. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Trả về giá trị ngưỡng. Float chỉ đọc.

**Trả về:**
float