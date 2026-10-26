---
title: HandleRepeatedSpaces
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Xác định cách xử lý các ký tự khoảng trắng thường lặp lại trong quá trình xuất Markdown.
type: docs
url: /vi/com.aspose.slides/handlerepeatedspaces/
---
**Kế thừa:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Xác định cách xử lý các ký tự khoảng trắng thường lặp lại trong quá trình xuất Markdown.

## Trường

| Trường | Mô tả |
| --- | --- |
| [None](#None) | Tất cả các khoảng trắng được giữ nguyên dưới dạng ký tự khoảng trắng thông thường mà không có bất kỳ thay đổi nào. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Chuyển đổi các chuỗi gồm hai hoặc nhiều khoảng trắng thường liên tiếp bằng cách xen kẽ giữa ký tự khoảng trắng thông thường và thực thể không ngắt dòng NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Chuyển đổi các chuỗi gồm hai hoặc nhiều khoảng trắng thường liên tiếp bằng cách giữ lại khoảng trắng đầu tiên dưới dạng ký tự khoảng trắng thông thường và thay thế tất cả các khoảng trắng tiếp theo bằng thực thể không ngắt dòng NBSP. |

### None {#None}
```
public static final int None
```

Tất cả các khoảng trắng được giữ nguyên dưới dạng ký tự khoảng trắng thông thường mà không có bất kỳ thay đổi nào. Không áp dụng bất kỳ phép biến đổi nào, và các khoảng trắng liên tiếp nhiều lần được xuất nguyên trạng.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

Chuyển đổi các chuỗi gồm hai hoặc nhiều khoảng trắng thường liên tiếp bằng cách xen kẽ giữa ký tự khoảng trắng thông thường và thực thể không ngắt dòng NBSP. Khoảng trắng đầu tiên luôn được giữ lại dưới dạng khoảng trắng thông thường.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

Chuyển đổi các chuỗi gồm hai hoặc nhiều khoảng trắng thường liên tiếp bằng cách giữ lại khoảng trắng đầu tiên dưới dạng ký tự khoảng trắng thông thường và thay thế tất cả các khoảng trắng tiếp theo bằng thực thể không ngắt dòng NBSP.