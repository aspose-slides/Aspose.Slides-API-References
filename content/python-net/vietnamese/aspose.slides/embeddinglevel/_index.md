---
title: EmbeddingLevel enumeration
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/embeddinglevel/
---
## EmbeddingLevel liệt kê

Biểu thị các quyền cấp phép cho việc nhúng phông chữ.

Kiểu EmbeddingLevel hiển thị các thành viên sau:

## Trường

| Field | Description |
| :- | :- |
| INSTALLABLE | Phông chữ với cài đặt này cho biết chúng có thể được nhúng và cài đặt vĩnh viễn trên hệ thống từ xa bởi một ứng dụng. <br/>            Người dùng của hệ thống từ xa sẽ nhận được các quyền, nghĩa vụ và giấy phép giống hệt cho phông chữ đó như người mua ban đầu, <br/>            và chịu cùng một thỏa thuận giấy phép người dùng cuối, bản quyền, bằng sáng chế thiết kế và/hoặc nhãn hiệu như người mua ban đầu. |
| RESTRICTED | Phông chữ chỉ có bit này được đặt không được sửa đổi, nhúng hoặc trao đổi bằng bất kỳ cách nào nếu không trước tiên có được sự cho phép của chủ sở hữu pháp lý. |
| PREVIEW_PRINT | Khi bit này được đặt, phông chữ có thể được nhúng và tải tạm thời trên hệ thống từ xa. Tài liệu chứa phông chữ Preview & <br/>            Print phải được mở ở chế độ "chỉ-đọc"; không được thực hiện chỉnh sửa nào trên tài liệu. |
| EDITABLE | Khi bit này được đặt, phông chữ có thể được nhúng nhưng chỉ được cài đặt tạm thời trên các hệ thống khác. Trái ngược với phông chữ Preview & <br/>            Print, tài liệu chứa phông chữ Editable có thể được mở để đọc, cho phép chỉnh sửa và các thay đổi có thể được lưu lại. |
| NO_SUBSETTING | Khi bit này được đặt, phông chữ không được giảm mẫu trước khi nhúng. Các hạn chế nhúng khác được chỉ định trong các bit 0-3 và 9 cũng áp dụng. |
| BITMAP_ONLY | Khi bit này được đặt, chỉ các bitmap có trong phông chữ mới được nhúng. Không có dữ liệu đường viền nào được nhúng. Nếu không có bitmap nào có trong phông chữ, <br/>            thì phông chữ sẽ được coi là không thể nhúng và dịch vụ nhúng sẽ thất bại. |

### Xem Thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)