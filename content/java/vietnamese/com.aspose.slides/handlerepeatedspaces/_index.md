---
title: HandleRepeatedSpaces
second_title: Tham chiếu API Aspose.Slides cho Java
description: Chỉ định cách xử lý các ký tự khoảng trắng thường lặp lại trong quá trình xuất Markdown.
type: docs
url: /vi/com.aspose.slides/handlerepeatedspaces/
---
**Kế thừa:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Chỉ định cách xử lý các ký tự khoảng trống thường lặp lại trong quá trình xuất Markdown.
## Trường

| Trường | Mô tả |
| --- | --- |
| [None](#None) | Tất cả các khoảng trống được giữ nguyên dưới dạng ký tự khoảng trống thường mà không có bất kỳ thay đổi nào. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Chuyển đổi các chuỗi có hai hoặc nhiều khoảng trống thường liên tiếp bằng cách xen kẽ giữa ký tự khoảng trống thường và thực thể không gạch chất NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Chuyển đổi các chuỗi có hai hoặc nhiều khoảng trống thường liên tiếp bằng cách giữ nguyên khoảng trống đầu tiên dưới dạng ký tự khoảng trống thường và thay thế tất cả các khoảng trống tiếp theo bằng thực thể không gạch chất NBSP. |
### None {#None}
```
public static final int None
```


Tất cả các khoảng trống được giữ nguyên dưới dạng ký tự khoảng trống thường mà không có bất kỳ thay đổi nào. Không có bất kỳ chuyển đổi nào được áp dụng và các khoảng trống liên tiếp nhiều lần được xuất nguyên vẹn.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```


Chuyển đổi các chuỗi có hai hoặc nhiều khoảng trống thường liên tiếp bằng cách xen kẽ giữa ký tự khoảng trống thường và thực thể không gạch chất NBSP. Khoảng trống đầu tiên luôn được giữ nguyên dưới dạng khoảng trống thường.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```


Chuyển đổi các chuỗi có hai hoặc nhiều khoảng trống thường liên tiếp bằng cách giữ nguyên khoảng trống đầu tiên dưới dạng ký tự khoảng trống thường và thay thế tất cả các khoảng trống tiếp theo bằng thực thể không gạch chất NBSP.