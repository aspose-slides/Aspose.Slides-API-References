---
title: PresentationLockingBehavior enumeration
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum

Biểu diễn hành vi liên quan đến việc xử lý nguồn [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation) (tệp hoặc **io.RawIOBase**) khi tải và làm việc với một thể hiện của [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation).

Kiểu PresentationLockingBehavior cung cấp các thành viên sau:

## Trường

| Trường | Mô tả |
| :- | :- |
| LOAD_AND_RELEASE | Nguồn sẽ bị khóa chỉ trong thời gian thực thi constructor [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation).<br/>Nếu [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/vi/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) được đặt thành false, tất cả BLOB sẽ được tải vào bộ nhớ. Ngược lại, có thể sử dụng các phương pháp khác như tệp tạm thời. Hành vi này chậm hơn [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/vi/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), và nếu có thể chuyển quyền sở hữu nguồn cho [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation), thì nên sử dụng [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/vi/aspose.slides/presentationlockingbehavior/KEEP_LOCKED). |
| KEEP_LOCKED | Nguồn sẽ bị khóa trong suốt vòng đời của thể hiện [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation), cho đến khi nó được giải phóng.<br/>[`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/vi/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) phải được đặt thành true để sử dụng hành vi này, nếu không sẽ ném ngoại lệ. Hành vi này được khuyến nghị, nó nhanh hơn và tiêu thụ ít bộ nhớ hơn [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/vi/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |

### Ghi chú

Nguồn là tham số được truyền vào constructor [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). Trong ví dụ dưới đây, nguồn là tệp "pres.pptx":

Đối với ví dụ này, nguồn (tệp "pres.pptx") sẽ bị khóa trong suốt vòng đời của thể hiện [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation), tức là không thể bị thay đổi hoặc xóa bởi quy trình khác.

### Xem thêm
* lớp [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)