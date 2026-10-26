---
title: EmbeddingLevel
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị quyền cấp phép cho việc nhúng phông chữ.
type: docs
url: /vi/com.aspose.slides/embeddinglevel/
---
**Kế thừa:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Biểu thị quyền cấp phép cho việc nhúng phông chữ.

## Trường

| Trường | Mô tả |
| --- | --- |
| [Installable](#Installable) | Phông chữ với cài đặt này cho biết chúng có thể được nhúng và cài đặt vĩnh viễn trên hệ thống từ xa bởi một ứng dụng. |
| [Restricted](#Restricted) | Phông chữ chỉ có bit này được bật không được chỉnh sửa, nhúng hoặc trao đổi bằng bất kỳ cách nào nếu không có sự cho phép của chủ sở hữu hợp pháp. |
| [PreviewPrint](#PreviewPrint) | Khi bit này được bật, phông chữ có thể được nhúng và tải tạm thời trên hệ thống từ xa. |
| [Editable](#Editable) | Khi bit này được bật, phông chữ có thể được nhúng nhưng chỉ được cài đặt tạm thời trên các hệ thống khác. |
| [NoSubsetting](#NoSubsetting) | Khi bit này được bật, phông chữ không được cắt nhỏ trước khi nhúng. |
| [BitmapOnly](#BitmapOnly) | Khi bit này được bật, chỉ các bitmap có trong phông chữ mới được nhúng. |

### Có thể Cài đặt {#Installable}
```
public static final int Installable
```

Phông chữ với cài đặt này cho biết chúng có thể được nhúng và cài đặt vĩnh viễn trên hệ thống từ xa bởi một ứng dụng. Người dùng của hệ thống từ xa có được các quyền, nghĩa vụ và giấy phép giống hệt như người mua gốc của phông chữ, và phải tuân thủ cùng một thỏa thuận giấy phép người dùng cuối, bản quyền, sáng chế thiết kế và/hoặc nhãn hiệu như người mua gốc.

### Hạn chế {#Restricted}
```
public static final int Restricted
```

Phông chữ chỉ có bit này được bật không được chỉnh sửa, nhúng hoặc trao đổi bằng bất kỳ cách nào nếu không có sự cho phép của chủ sở hữu hợp pháp.

### Xem Trước & In {#PreviewPrint}
```
public static final int PreviewPrint
```

Khi bit này được bật, phông chữ có thể được nhúng và tải tạm thời trên hệ thống từ xa. Tài liệu chứa phông chữ Xem Trước & In phải được mở ở chế độ “chỉ đọc”; không được thực hiện chỉnh sửa nào trên tài liệu.

### Có Thể Chỉnh Sửa {#Editable}
```
public static final int Editable
```

Khi bit này được bật, phông chữ có thể được nhúng nhưng chỉ được cài đặt tạm thời trên các hệ thống khác. Ngược lại với phông chữ Xem Trước & In, tài liệu chứa phông chữ có thể chỉnh sửa có thể được mở để đọc, cho phép chỉnh sửa và có thể lưu các thay đổi.

### Không Cắt Nhỏ {#NoSubsetting}
```
public static final int NoSubsetting
```

Khi bit này được bật, phông chữ không được cắt nhỏ trước khi nhúng. Các hạn chế nhúng khác được chỉ định trong các bit 0-3 và 9 cũng áp dụng.

### Chỉ Bitmap {#BitmapOnly}
```
public static final int BitmapOnly
```

Khi bit này được bật, chỉ các bitmap có trong phông chữ mới được nhúng. Không có dữ liệu đường viền nào được nhúng. Nếu phông chữ không có bitmap nào, thì phông chữ được coi là không thể nhúng và dịch vụ nhúng sẽ thất bại.