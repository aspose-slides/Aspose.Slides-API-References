---
title: EmbeddingLevel
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho các quyền cấp phép cho việc nhúng phông chữ.
type: docs
url: /vi/com.aspose.slides/embeddinglevel/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Đại diện cho quyền cấp phép cho việc nhúng phông chữ.
## Trường

| Trường | Mô tả |
| --- | --- |
| [Installable](#Installable) | Phông chữ có cài đặt này cho biết chúng có thể được nhúng và cài đặt vĩnh viễn trên hệ thống từ xa bởi một ứng dụng. |
| [Restricted](#Restricted) | Phông chữ chỉ có bit này được bật không được sửa đổi, nhúng hoặc trao đổi dưới bất kỳ hình thức nào nếu không trước tiên nhận được sự cho phép của chủ sở hữu hợp pháp. |
| [PreviewPrint](#PreviewPrint) | Khi bit này được bật, phông chữ có thể được nhúng và tải tạm thời trên hệ thống từ xa. |
| [Editable](#Editable) | Khi bit này được bật, phông chữ có thể được nhúng nhưng chỉ được cài đặt tạm thời trên các hệ thống khác. |
| [NoSubsetting](#NoSubsetting) | Khi bit này được bật, phông chữ không được chia nhỏ trước khi nhúng. |
| [BitmapOnly](#BitmapOnly) | Khi bit này được bật, chỉ các bitmap có trong phông chữ mới được nhúng. |
### Installable {#Installable}
```
public static final int Installable
```

Phông chữ có cài đặt này cho biết chúng có thể được nhúng và cài đặt vĩnh viễn trên hệ thống từ xa bởi một ứng dụng. Người dùng của hệ thống từ xa sẽ nhận được các quyền, nghĩa vụ và giấy phép giống hệt như người mua ban đầu của phông chữ, và chịu cùng một thỏa thuận cuối-người dùng, bản quyền, bằng sáng chế thiết kế và/hoặc nhãn hiệu như người mua ban đầu.

### Restricted {#Restricted}
```
public static final int Restricted
```

Phông chữ chỉ có bit này được bật không được sửa đổi, nhúng hoặc trao đổi dưới bất kỳ hình thức nào nếu không trước tiên nhận được sự cho phép của chủ sở hữu hợp pháp.

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```

Khi bit này được bật, phông chữ có thể được nhúng và tải tạm thời trên hệ thống từ xa. Tài liệu chứa phông chữ Preview & Print phải được mở ở chế độ “chỉ-đọc”; không thể thực hiện chỉnh sửa nào đối với tài liệu.

### Editable {#Editable}
```
public static final int Editable
```

Khi bit này được bật, phông chữ có thể được nhúng nhưng chỉ được cài đặt tạm thời trên các hệ thống khác. Trái ngược với phông chữ Preview & Print, tài liệu chứa phông chữ Editable có thể được mở để đọc, cho phép chỉnh sửa và có thể lưu các thay đổi.

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```

Khi bit này được bật, phông chữ không được chia nhỏ trước khi nhúng. Các hạn chế nhúng khác được chỉ định trong các bit 0-3 và 9 cũng áp dụng.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```

Khi bit này được bật, chỉ các bitmap có trong phông chữ mới được nhúng. Không có dữ liệu đường viền nào được nhúng. Nếu không có bitmap nào có sẵn trong phông chữ, thì phông chữ được coi là không thể nhúng và dịch vụ nhúng sẽ thất bại.